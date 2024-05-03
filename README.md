## 🌟 Vi-InternLM2-Xcpmposer多模态越南语大语言模型 🌟

**Vi-InternLM2-Xcpmposer多模态越南语大语言模型**（以下简称Vi-InternLM2-Xcpmposer模型）是一个专门针对越南语进行优化的多模态大语言模型，旨在提升越南语的文本生成、翻译及图文理解性能。本模型集成了高级权重量化（AWQ）算法和高效推理引擎（TurboMind），显著提高处理越南语的准确性和效率。
### 🚀 更新日志（希望平台大佬能给予本项目算力支持到5月底，毕业论文答辩结束）
2024年4月19日把微调好的Vi-InternLM2-7B上传，模型网址如下：https://openxlab.org.cn/models/detail/uuuii/internLM2-Vietnamese/tree/main

2024年5月1日把微调好的Vi-InternLM-Xcomposer2上传，模型网址如下：https://openxlab.org.cn/models/detail/uuuii/internLM-Xcomposer-2-Vietnamese/tree/main

2024年5月3日把微调好的Vi-InternLM2-7B进行应用搭建，搭建好的应用可进行在线使用体验，网址如下（欢迎点赞收藏）：https://openxlab.org.cn/apps/detail/uuuii/internLM2-vi

![0fbbd745ef2b7823130b7d854d92048b](https://github.com/xuhefangyuan/Vi-internlm2-xcomposer/assets/87607843/e3515c1f-57b6-4e6f-93cf-02827e6c3831)

### 🚀 模型特点

- **📈 高效的文本处理能力**：优化后的InternLM模型在越南语文本生成和翻译任务上，相较现有模型展现出更高的性能。
- **🖼️ 多模态输入理解**：模型支持图文混合输入，能有效处理图文相关的复杂查询，提高理解和响应的准确率。
- **🌍 跨语言能力强**：除了越南语，本模型还支持包括中文和英文在内的多语言输入，适用于多语种交互环境。

### 🛠️ 环境需求

- Python 3.7+
- PyTorch 1.8+
- Transformers 4.5.0+

### ⚙️ 安装指南

```
bashCopy code
pip install -r requirements.txt
```

### 🌟 快速启动

以下是使用InternLM模型进行文本生成的示例代码：

```
pythonCopy codefrom internlm import InternLM

model = InternLM(model_name='Vi-InternLM2-Xcpmposer')

text = "越南的首都是哪里？"
response = model.generate(text)
print(response)
```

### 📐 模型架构

Vi-InternLM2-Xcpmposer模型采用的是Transformer架构，具体配置如下：

- **模型大小**：7B 参数
- **层数**：24 层 Transformer
- **隐藏层维度**：1024
- **注意力头数**：16

### 📚 使用案例

1. **文本翻译**： 将越南语翻译成中文或英文，适用于多语种内容创作者和国际会议通讯。
2. **图文内容理解**： 解析图文混合内容，自动生成相关描述，支持新闻、社交媒体等多种应用场景。

### 🤝 贡献

欢迎对Vi-InternLM2-Xcpmposer模型的贡献，您可以通过以下方式帮助我们改进模型：

- 提交Bug报告 🐛
- 提出新功能 💡
- 发送Pull Requests 👥

### ©️ 许可证

本项目采用MIT许可证，详见LICENSE文件。

### 💖 致谢

特此感谢上海人工智能实验室组织的书生浦语实战营学习活动，提供的开发流程及算力支持。
