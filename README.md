# AI 智能营养师

这是可直接发布到 GitHub Pages / Netlify / Vercel 的静态部署包。

## 本地预览

在当前目录运行：

```bash
python3 -m http.server 8787
```

然后打开：

```text
http://127.0.0.1:8787
```

## 说明

- 已移除 React / Tailwind / Three.js 的远程 CDN 依赖
- Gemini / Firebase / 媒体权限 已做本地演示兜底
- 适合公开展示交互，不依赖后端服务
- AI 生成结果目前为演示数据，不是真实在线模型输出

## GitHub Pages 发布

最简单做法：

1. 新建一个 GitHub 仓库
2. 把本目录全部文件上传到仓库根目录
3. 在 GitHub 仓库设置里开启 Pages
4. Source 选 `Deploy from a branch`
5. Branch 选 `main`，目录选 `/ (root)`
6. 保存后等待 GitHub 生成公网地址
