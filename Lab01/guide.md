# Environment Setup

- [Environment Setup](#environment-setup)
  - [1. Fork GitHub Repo](#1-fork-github-repo)
  - [2. Start a Codespace](#2-start-a-codespace)
  - [3. Run minikube](#3-run-minikube)
  - [4. Tun a keep alive for the codespace](#4-tun-a-keep-alive-for-the-codespace)

## 1. Fork GitHub Repo

Go to this repo and fork it to your own GitHub account so you have full control over the CI/CD pipeline.

## 2. Start a Codespace

Start a GitHub Codespace on your forked repo.

## 3. Run minikube

```bash
minikube start --cpus 3 --memory 8g
```

## 4. Tun a keep alive for the codespace

In a new terminal, run the following command to keep the codespace alive.

```bash
while true; do date; sleep 60; done
```