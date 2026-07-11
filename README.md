# TTS 文字朗读

基于 Web Speech API 的纯前端文字朗读工具，支持中文语音合成。

## 功能

- 输入文字，选择语音，点击播放即可朗读
- 支持中文语音选择（普通话、粤语、国语等）
- 可调节朗读速度（0.5x - 2.0x）
- 长文本自动分段朗读
- 响应式设计，适配手机和桌面浏览器

## 使用方式

直接打开 `index.html` 文件，或部署到任意静态网站托管服务：

- GitHub Pages
- Netlify
- Vercel
- 本地 HTTP 服务器

## 技术栈

- 纯 HTML/CSS/JavaScript，无依赖
- Web Speech API (SpeechSynthesis)
- 单文件应用，易于部署

## 浏览器兼容性

- Chrome/Edge（推荐，语音质量最佳）
- Safari
- Firefox（部分功能可能受限）

## 部署到 GitHub Pages

```bash
# 在仓库设置中启用 Pages
# Settings → Pages → Source: main branch
```

访问 `https://用户名.github.io/tts-reader/` 即可使用。

## 开发

```bash
# 本地预览
python3 -m http.server 8888
# 访问 http://localhost:8888
```

## 许可证

MIT
