<h1 align="center">
  <strong>PageTalk - 你的网页 AI 助手 ✨</strong>
</h1>

<p align="center">
  <a href="https://github.com/jeanchristophe13v/PageTalk"> <!-- 如果有仓库链接，请替换 -->
    <img src="magic.png?raw=true" alt="Pagetalk 图标" title="Pagetalk 图标" width="250">
  </a>
</p>

#### [English/英文](README.md)

## PageTalk 3.6.0 🎉

**🌟 划词助手 - 革命性功能：**
PageTalk不再仅仅是个侧栏AI插件！现在你可以选择网页上的任何文本，立即获得：
- **解读** 复杂内容的AI分析
- **翻译** 到你偏好的语言
- **对话** 基于选中文本的上下文聊天
- **自定义** 你自己的选项，配置个性化提示词

只需选择文本 → 选择操作 → 获得即时AI助手。就是这么简单！

**其他更新：**
- **多提供商支持**: 新增了对多个AI提供商的支持，您现在可以自定义添加和管理来自不同平台的模型，包括 **OpenAI, Claude, Gemini, DeepSeek, OpenRouter, 硅基流动, 智谱AI** 等。
- **增强代理支持：** 更新了HTTP和SOCKS5代理功能，提供更好的连接性
- **Bug修复：** 解决了各种小问题，提升稳定性

*备注：如果遇到任何问题，请先尝试删除老版本的 PageTalk、刷新网页、刷新插件或重启浏览器*

---

**划词助手演示**


https://github.com/user-attachments/assets/1315abf6-9773-4e54-bd2f-97ad480946c3


---

## 简介

Pagetalk 是一款浏览器插件，通过集成 Google Gemini API 来增强您的网页浏览体验。轻松总结页面、进行上下文对话，并管理自定义 AI 助手。


## 主要特性

*   **网页交互:** 读取页面内容，提供对话上下文。
*   **上下文聊天:** 与 AI 讨论当前网页内容。
*   **多助手系统:** 创建、自定义、切换并**导入/导出** AI 助手。
*   **图片输入:** 上传或粘贴图片进行讨论。
*   **富文本渲染:** 支持 Markdown、代码高亮、**LaTeX** 公式和 **Mermaid** 图表。
*   **PDF 解析与对话:** 支持网页内 PDF 文件内容提取与对话。
*   **URL 上下文提取:** Gemini-2.0-flash 和 Gemini-2.5-flash-preview-05-20 ( gemini-2.5-flash(-thinking) )支持自动提取网页内容作为上下文。
*   **个性化设置:** 配置 API 密钥、**语言 (中/英)**、**主题 (浅色/深色)**。
*   **聊天导出:** 将对话保存为 Markdown 或纯文本文件。

## 使用示例

### 多标签页交互 & YouTube解析
<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin: 10px 0;">
  <div>
    <img src="https://github.com/user-attachments/assets/23d3b878-52f3-437a-a85a-c7d53f194fe7" alt="输入@选择标签页" width="300" style="border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);"/>
    <p><em>输入@选择已打开的标签页</em></p>
  </div>
  <div>
    <img src="https://github.com/user-attachments/assets/17d27bb0-47a9-4297-a8aa-8d637679a807" alt="选中标签页显示" width="300" style="border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);"/>
    <p><em>选中样式</em></p>
  </div>
  <div>
    <img src="https://github.com/user-attachments/assets/dc001071-2580-414f-a5ce-f127f966e50d" alt="AI总结" width="300" style="border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);"/>
    <p><em>让PageTalk总结你选择的标签页</em></p>
  </div>
  <div>
    <img src="https://github.com/user-attachments/assets/6ed43746-a2c4-4c60-b00a-9a1d49833460" alt="YouTube URL解析" width="300" style="border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);"/>
    <p><em>解析Youtube URL</em></p>
  </div>
</div>

### 核心功能展示
<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin: 10px 0;">
  <div>
    <img src="https://github.com/user-attachments/assets/4aa393e4-659d-433a-9d4c-583217c95158" alt="PageTalk界面" width="300" style="border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);"/>
    <p><em>主界面 & 聊天</em></p>
  </div>
  <div>
    <img src="https://github.com/user-attachments/assets/0dc31cbc-b714-4037-8185-cba15f7e4238" alt="助手管理" width="300" style="border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);"/>
    <p><em>深色模式支持</em></p>
  </div>
  <div>
    <img src="https://github.com/user-attachments/assets/58256468-0ce8-476b-9383-e9dab566dd24" alt="富文本渲染" width="300" style="border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);"/>
    <p><em>Mermaid渲染</em></p>
  </div>
  <div>
    <img src="https://github.com/user-attachments/assets/c23d2919-aa7c-427a-80a8-1b08a5f46a5c" alt="设置面板" width="300" style="border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);"/>
    <p><em>url提取</em></p>
  </div>
</div>


## 安装


**注意:** 需要在开发者模式下以"加载已解压的扩展程序"方式安装。

**获取 API 密钥:** 在使用插件前，请先从 [Google AI Studio](https://aistudio.google.com) 获取您的 Gemini API 密钥。

### 插件安装
1. chrome: https://chromewebstore.google.com/detail/pagetalk-your-gemini-brow/pjmpcpolpfejiacaemgjnjnknlcfcami?authuser=0&hl=zh-CN

2. edge： https://microsoftedge.microsoft.com/addons/detail/pagetalk-your-gemini-br/mpmohgpcggkkbjdamcnmmnkblkmpldmi

3. Firefox: https://addons.mozilla.org/zh-CN/firefox/addon/pagetalk-gemini-assistant/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search

> ⚠️注意：由于一些兼容性问题，PageTalk在Firefox的一些功能（比如@选择标签页对话）并不完整，但仍然可以很好地总结和对话，往后会慢慢支持所有功能。

### 开发者通道

1. **克隆仓库或直接下载 ZIP 并解压**
```
git clone https://github.com/jeanchristophe13v/PageTalk.git
```

2. **加载插件文件夹**
- **Edge:** 地址栏输入 `edge://extensions/` -> 启用"开发者模式" -> 点击"加载解压缩的扩展" -> 选择项目文件夹。
- **Chrome:** 地址栏输入 `chrome://extensions/` -> 启用"开发者模式" -> 点击"加载已解压的扩展程序" -> 选择项目文件夹。

## 使用说明

- **打开:** 点击 Pagetalk 图标或使用快捷键 (默认 `Alt+P`)。
- **设置标签页:** (包含通用、助手、模型子标签页)
    *   **通用:** 切换语言/主题，导出聊天记录。
    *   **助手:** 管理助手，导入/导出配置。
    *   **模型:** 设置 API 密钥，选择默认模型。

## 💗感谢DartNode的支持 ~
[![Powered by DartNode](https://dartnode.com/branding/DN-Open-Source-sm.png)](https://dartnode.com "Powered by DartNode - Free VPS for Open Source")
