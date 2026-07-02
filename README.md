# obs-git-sync 发布仓库

Obsidian 插件 Git Sync 的内部发布通道，仅含构建产物，桌面 / Android / iOS 通用。

## 安装（BRAT，推荐）

1. Obsidian 社区商店安装并启用 BRAT（Beta Reviewers Auto-update Tester）
2. BRAT 设置 → `Add beta plugin` → 填 `tap4fun/obs-git-sync`
3. 设置 → 第三方插件 → 启用 Git Sync；之后 BRAT 自动检查更新

## 手动安装

从 Releases 下载 `main.js`、`manifest.json` 与 `styles.css`，放入
`<vault>/.obsidian/plugins/obs-git-sync/`，重启 Obsidian 后启用。

<!--
截图：把图片文件放到 assets/screenshots/ 目录下，用相对路径引用即可，例如：
![设置界面](screenshots/settings.png)
下次 pnpm release 会自动把 screenshots/ 目录同步到 rel 仓库。
-->
