# github-test

这是 DSH 环境接入 GitHub 的**连通性验证仓库**，由代理自动生成。

## 验证内容

- [x] SSH 密钥认证（ed25519，指纹 SHA256:sfk3AUrQkkjrXFvVsOO2R/UXl+cnCkePziZhUQn4pSE）
- [x] git clone（公开仓库，3.9s）
- [x] git push（本仓库，已验证，提交 f8ffeaf）

## 环境说明

本机 Git 为 D 盘便携版 MinGit 2.56.0，认证走 Windows 原生 ssh.exe
（Git 自带的 MSYS 版 ssh/sh 因 DSH 沙箱禁止命名管道而不可用）。

