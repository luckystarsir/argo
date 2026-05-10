# ArgoSBX 自用版

这是基于原项目整理的自用版本，已移除 README、网页和脚本输出中的推广/频道/打赏类内容。

## 保留功能

- 一键 SSH 脚本与现有协议变量逻辑
- Xray / Sing-box / Cloudflared 相关部署逻辑
- Argo 临时/固定隧道相关逻辑
- Web 命令生成器 `index.html`
- SAP / Docker / GitHub Actions 相关脚本

## 注意

- 为保持原功能，脚本中仍保留必要的远程下载地址，例如 GitHub Release、Cloudflare cloudflared、Cloud Foundry CLI、Docker 镜像等。
- 如需完全私有化，请把脚本中的远程地址替换为你自己的仓库、镜像或对象存储地址。
- 运行前建议在一次性 VPS 或容器中测试。
