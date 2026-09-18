# 抬头有喵官方网站

首页、隐私政策、使用与支持三个静态页面。参考 RopeJoy 项目的页面组织和 GitHub Pages 发布方式；无需 npm、构建步骤或第三方字体，无分析脚本。

## 本地预览

在本目录运行 `python3 -m http.server 8765`，打开 http://localhost:8765/ 。

## 发布

将本目录内容（包括隐藏目录 .github）作为独立仓库根目录，例如 `macpet-website`，默认分支使用 main。在仓库 Settings → Pages 中选择 GitHub Actions，运行“发布抬头有喵网站”工作流。

网站仓库：https://github.com/fitygrey/macpet-website 。已配置 GitHub Actions 发布；推送 main 分支会自动部署。请勿将整个宠物工程上传为网站。

正式部署地址：

- 首页：https://fitygrey.github.io/macpet-website/
- 隐私政策：https://fitygrey.github.io/macpet-website/privacy/
- 支持页面：https://fitygrey.github.io/macpet-website/support/

所有内部链接使用相对路径，兼容仓库子路径和独立域名。支持邮箱为 onebooksoftware@outlook.com。政策生效日期当前为 2026-09-18；如正式发布时调整，请同步修改 privacy/index.html。
