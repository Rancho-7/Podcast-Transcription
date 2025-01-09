# Podcast Transcription App

一个基于 Next.js 和 OpenAI Whisper API 的播客转录应用，支持音频文件转录和智能摘要生成。

## 🌟 特性

- 🎯 支持音频文件上传和 URL 输入两种方式
- 🎙️ 支持小宇宙播客链接解析
- 📝 使用 OpenAI Whisper API 进行高质量音频转录
- 📊 AI 驱动的内容摘要生成
- 🎨 现代化的 UI 设计
- 💾 支持转录文本和摘要的下载
- 🎵 内置音频播放器

## 🚀 快速开始

### 前置要求

- Node.js 18+ 
- OpenAI API Key

### 安装

1. 克隆仓库：
```bash
git clone https://github.com/yourusername/podcast-transcription.git
cd podcast-transcription
```

2. 安装依赖：
```bash
npm install
# 或
yarn install
# 或
pnpm install
```

3. 配置环境变量：
创建 `.env.local` 文件并添加以下内容：
```env
NEXT_PUBLIC_OPENAI_API_KEY=your_openai_api_key
```

4. 启动开发服务器：
```bash
npm run dev
# 或
yarn dev
# 或
pnpm dev
```

访问 [http://localhost:3000](http://localhost:3000) 查看应用。

## 🛠️ 技术栈

- **Framework**: [Next.js 14](https://nextjs.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **UI Components**: [shadcn/ui](https://ui.shadcn.com/)
- **API**: [OpenAI Whisper](https://platform.openai.com/docs/guides/speech-to-text)
- **Type Safety**: [TypeScript](https://www.typescriptlang.org/)

## 📝 使用说明

1. **文件上传**：
   - 点击 "File Upload" 标签
   - 选择本地音频文件
   - 点击 "Transcribe" 开始转录

2. **URL 输入**：
   - 点击 "URL Input" 标签
   - 输入播客链接（支持小宇宙播客）
   - 点击 "Transcribe" 开始转录

3. **查看结果**：
   - 转录完成后会显示详细的文本内容
   - 同时生成内容摘要
   - 可以通过下载按钮保存转录文本和摘要

## 🤝 贡献

欢迎提交 Pull Requests 和 Issues！

## 📄 许可证

MIT License - 查看 [LICENSE](LICENSE) 文件了解详情。
