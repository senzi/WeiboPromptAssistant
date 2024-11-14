# WeiboPromptAssistant

WeiboPromptAssistant 是一个用于将微博内容转换为 AI 提示词的浏览器插件，方便进行分析、翻译和改写。

## 项目来源

本项目 fork 自 [SomiaWhiteRing/chinese2chinese4weibo](https://github.com/SomiaWhiteRing/chinese2chinese4weibo)，并在其基础上进行了优化。

## 优化内容

1. 增加多 Prompt 配置功能。
2. 新增“一键复制”功能，方便使用。

## 功能特点

- 在每条微博下方添加“中译中”按钮，支持实时翻译。
- 支持自定义 AI 接口设置（默认使用 DeepSeek）。
- 自定义翻译提示词，满足不同需求。

## 安装方法

1. 安装 [Tampermonkey](https://www.tampermonkey.net/) 浏览器扩展。
2. 点击[此处](https://github.com/senzi/WeiboPromptAssistant/raw/master/WeiboPromptAssistant.user.js)安装脚本。
3. 进入微博页面，点击微博下方的“功能设置”按钮，配置以下信息：
   - API 地址
   - API Key
   - 模型名称
   - 翻译提示词

## 使用说明

1. 打开任意微博详情页。
2. 点击“中译中”按钮查看翻译结果。
3. 随时通过“功能设置”按钮调整配置。

## 注意事项

- 需要自备 AI API 密钥。
- 默认配置适用于 DeepSeek API。
- 建议根据个人需求调整提示词以获得最佳翻译效果。

## 开源协议

本项目遵循 MIT License 开源协议。