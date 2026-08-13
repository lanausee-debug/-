# 图灵审图（Tuling Shentu）

一站式智能审图平台静态站点，聚焦轨道交通行业，为设计质量与交付效率双向赋能。

## 目录结构

```
.
├── index.html            # 站点主页
├── hero-bg.jpg           # 首屏背景图
├── logo.png              # 站点 Logo
├── 规范核对.mp4           # 产品演示视频①
├── 设计依据核查.mp4        # 产品演示视频②
└── README.md
```

## 部署

### GitHub Pages

1. 在 GitHub 新建仓库，将本目录内容上传到仓库根目录。
2. 进入仓库 **Settings → Pages**，将 Source 设置为 `main` 分支根目录（`/ (root)`），保存。
3. 稍等片刻即可通过 `https://<用户名>.github.io/<仓库名>/` 访问。

### Cloudflare Pages

1. 登录 Cloudflare 控制台，进入 **Workers & Pages → Create → Pages**。
2. 关联 GitHub 仓库（或选择“直接上传”拖入本目录）。
3. 构建命令留空，输出目录填根目录 `/`，点击部署。

## 说明

- 页面内「进入系统 / 立即试用」等按钮跳转到外部演示地址，部署后如需替换，请编辑 `index.html` 中对应链接。
- 视频文件 `规范核对.mp4`、`设计依据核查.mp4` 均在 10 MB 以下，无需 Git LFS。
