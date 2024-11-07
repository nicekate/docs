# Gradio 使用手册

Gradio 是一个快速、简单的 Python 库，用于为机器学习模型和数据科学项目构建交互式 Web 界面。

## 主要特性

- 快速创建机器学习演示
- 支持多种输入和输出类型
- 简单的界面定制
- 轻松分享和嵌入模型
- 与 Hugging Face 生态系统深度集成

### 安装

使用 pip 安装 Gradio：

```bash
pip install gradio
```

### 快速示例

```python
import gradio as gr

def greet(name):
    return f"Hello, {name}!"

demo = gr.Interface(
    fn=greet, 
    inputs="text", 
    outputs="text"
)

demo.launch()
```

### 文档开发

如果您想本地预览文档：

1. 安装 Mintlify CLI
```bash
npm i -g mintlify
```

2. 在文档根目录运行
```bash
mintlify dev
```

### 项目资源

- [官方文档](https://gradio.app/docs)
- [GitHub 仓库](https://github.com/gradio-app/gradio)
- [Hugging Face 主页](https://huggingface.co/spaces/gradio)

### 贡献

欢迎提交 Issues 和 Pull Requests！
