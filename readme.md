# 语音转文本工具 (Speech to Text Tool)

这是一个基于 [硅基流动 (SiliconFlow)](https://siliconflow.cn/) `FunAudioLLM/SenseVoiceSmall` 免费模型的纯前端语音转文本工具。它被打包成一个独立的 `HTML` 文件，无需任何后端部署，方便非专业用户下载和使用。

This is a pure front-end Speech-to-Text tool powered by the `FunAudioLLM/SenseVoiceSmall` model from SiliconFlow. It's a single, standalone HTML file that requires no backend setup, making it incredibly easy for non-technical users to download and run.

[English Version](./README_EN.md) | [中文版](./README.md)
![工具界面截图](./screenshots/screenshot.png)  


## ✨ 功能特性 (Features)

* **完全离线使用 (客户端)**: 无需服务器，所有操作都在用户的浏览器中完成。
* **简单易用**: 简洁美观的图形化界面，支持文件点击上传和拖拽上传。
* **隐私安全**: 用户的 API Key 和音频文件直接发送至官方 API，不会经过任何第三方服务器。
* **结果处理**: 转写结果可直接在页面查看、一键复制。
* **历史记录**: 自动将转写历史保存在浏览器本地存储中，方便回顾。
* **免费模型**: 使用硅基流动提供的 `FunAudioLLM/SenseVoiceSmall` 免费模型。

## 🚀 如何使用 (How to Use)

1.  **下载文件**:
    * 访问此 GitHub 页面的 [Releases](https://github.com/your-username/your-repo-name/releases) (建议创建一个 Release)。
    * 或者直接下载仓库中的 `speech-to-text.html` 文件。

2.  **获取 API Key**:
    * 访问 [硅基流动 (SiliconFlow) 官网](https://siliconflow.cn/) 并注册/登录。
    * 在您的账户设置中找到并复制您的 API Key。

3.  **运行工具**:
    * 用您的浏览器（推荐 Chrome, Firefox, Edge）打开下载的 `speech-to-text.html` 文件。
    * 在页面顶部的输入框中粘贴您的 API Key 并点击“保存”。
    * 点击或拖拽您的音频文件 (`.mp3`, `.wav`, `.m4a` 等) 到上传区域。
    * 稍等片刻，转写结果便会显示出来。

## 🛠️ 技术栈 (Tech Stack)

* **HTML**: 页面结构
* **CSS**: 页面样式 (无任何框架)
* **JavaScript**: 业务逻辑、API 调用 (`fetch`) 和本地存储 (`localStorage`)

## 🤝 贡献 (Contributing)

欢迎各种形式的贡献！如果您有任何想法、建议或发现 Bug，请随时提交 [Issues](https://github.com/your-username/your-repo-name/issues)。

如果您想改进代码，请：

1.  Fork 本仓库
2.  创建一个新的分支 (`git checkout -b feature/AmazingFeature`)
3.  提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4.  将分支推送到远程 (`git push origin feature/AmazingFeature`)
5.  创建一个 Pull Request

## 📄 开源许可 (License)

本项目采用 [MIT License](LICENSE) 开源许可。
