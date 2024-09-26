# ActionsBildSample

## 概要
GitHub Actionsをローカル実行 してみるサンプルプロジェクトです。

## 実行方法

```bash

brew install act
act --version
act version 0.2.67
act --container-architecture linux/amd64
# ls -la /var/run/
# sudo ln -s ~/.docker/run/docker.sock /var/run/docker.sock

# ローカルで実行してみる
act -j build --container-architecture linux/amd64
```