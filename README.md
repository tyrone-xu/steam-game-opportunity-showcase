# Steam 游戏机会初筛 Agent · 公开展示页

这是一个不带后端的公开展示页。它只说明 Agent 的输入、工作流、输出与能力边界，不能提交链接或调用任何私有能力。

## 本地查看

直接打开 `index.html`，或在此目录运行：

```powershell
python -m http.server 8080
```

然后访问 `http://localhost:8080`。

## GitHub Pages 发布

1. 在 GitHub 创建同名公开仓库 `steam-game-opportunity-showcase`。
2. 推送 `main` 分支。
3. 在仓库 **Settings → Pages** 中选择 **Deploy from a branch**，分支选 `main`、目录选 `/(root)`。
4. 发布地址为 `https://<GitHub用户名>.github.io/steam-game-opportunity-showcase/`。

发布前请确认仓库中不包含 Hermes 配置、飞书截图原图、账号信息、本地路径、令牌或真实报告。
