# 茉莉白月光：像素横版大冒险 (一键部署包)

本压缩包已将单文件游戏重命名为标准入口文件 `index.html`，并内置了各大免费静态托管平台的配置文件。

## 方式一：10 秒免命令拖拽发布（推荐）
1. **Netlify Drop**：打开 https://app.netlify.com/drop ，直接将本压缩包（或解压后的文件夹）拖入网页虚线框，即可立即生成可公开访问的 `https://xxx.netlify.app` 链接。
2. **Cloudflare Pages**：登录 https://dash.cloudflare.com ，进入 **Workers & Pages -> Create -> Pages -> Upload assets**，上传本压缩包即可生成全球加速的 `https://xxx.pages.dev` 链接。

## 方式二：GitHub Pages 自动部署
1. 将解压后的全部文件上传到你的 GitHub 仓库（已内置 `.github/workflows/deploy.yml`）。
2. 在仓库 **Settings -> Pages -> Build and deployment** 中将 **Source** 设为 **GitHub Actions**，即可自动发布为 `https://<你的用户名>.github.io/<仓库名>/`。
