# osfun.org

面向 AI 时代的操作系统研究与开源实践。从 Linux 出发，探索智能体如何与计算机共同工作。

基于 airdb.team 的 Astro 静态构建方式创建，页面内容与视觉独立。

## 本地运行

```sh
pnpm install --frozen-lockfile
pnpm dev
pnpm build
```

首页位于 `src/pages/index.astro`，样式位于 `src/styles/global.css`。图片为 AI 生成概念图，经 Astro 输出响应式 WebP。参与入口暂使用 info@airdb.com。

## 发布

已准备 GitHub Pages 工作流（每次重跑使用独立产物名称）。创建对应仓库后，在 Settings → Pages 中选择 GitHub Actions，并配置自定义域名 osfun.org。目前未创建远端仓库或修改 DNS。
