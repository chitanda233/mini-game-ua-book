# GitHub Pages 发布说明

本仓库已经包含静态阅读站点和 GitHub Pages Actions 工作流。

## 推荐仓库名

`mini-game-ua-book`

## 第一次发布

1. 在 GitHub 新建 **Public** 仓库 `mini-game-ua-book`。
2. 将本仓库全部文件推送到默认分支（`main` 或 `master` 均可，工作流已兼容）。
3. 进入仓库 **Settings → Pages**。
4. 在 **Build and deployment → Source** 选择 **GitHub Actions**。
5. 进入 Actions，等待 `Deploy static book to GitHub Pages` 成功。
6. Pages 页面会显示最终访问地址，通常为：`https://<用户名>.github.io/mini-game-ua-book/`。

官方文档说明，使用自定义 GitHub Actions 发布前，需要先在仓库 Pages 设置中把发布源切换到 GitHub Actions。
