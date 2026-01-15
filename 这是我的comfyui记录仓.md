![[局部重绘.json]]

 我来帮你整理这个 ComfyUI 记录仓库。从你提供的 `局部重绘.json` 文件来看，这是一个局部重绘的工作流配置。让我为你创建一个完整的仓库结构：

## 📁 ComfyUI 记录仓库结构

```
comfyui-records/
├── README.md                    # 仓库说明文档
├── workflows/                   # 工作流文件
│   ├── inpainting/             # 局部重绘相关
│   │   ├── local_inpainting.json
│   │   └── README.md
│   ├── txt2img/                # 文生图工作流
│   ├── img2img/                # 图生图工作流
│   └── controlnet/             # ControlNet工作流
├── nodes/                      # 自定义节点配置
├── models/                     # 模型配置记录
│   ├── checkpoints/           # 大模型记录
│   ├── loras/                 # LoRA模型记录
│   └── vae/                   # VAE模型记录
├── outputs/                    # 生成结果示例（.gitignore）
│   ├── examples/
│   └── comparisons/
└── docs/                       # 使用文档和技巧
    ├─ workflows_guide.md       # 工作流使用指南  
    └─ tips_and_tricks.md       # 技巧分享
```

## 📋 README.md 模板

```markdown
# 🎨 ComfyUI Workflow Records

这是我的 ComfyUI 工作流记录仓库，用于保存和分享各种实用的工作流配置。

## 🚀 Quick Start

1. **导入工作流**：将 `.json` 文件拖入 ComfyUI界面
2. **加载模型**：确保已安装所需节点和模型

## 📂 Workflows

### 🎯 Local Inpainting (局部重绘)
- **文件**: `workflows/inpainting/local_inpainting.json`
- **功能**: 
- **依赖节点**: 
- **使用说明**:

### 🔧 Custom Nodes Used

## 📝 Usage Tips

1. 
2. 

## 🔄 Update Log

- [日期] - 
```

## 📄 workflows/inpainting/README.md

```markdown
# 🎯 Local Inpainting Workflows

这个目录包含局部重绘相关的工作流配置。

## local_inpainting.json

### ⚙️ Requirements:
- [ComfyUI Impact Pack](https://github.com/ltdrdata/ComfyUI-Impact-Pack)
- Segment Anything (SAM) model

### 🛠️ Key Nodes:
1. **Load Image** - 加载原始图片和遮罩图（黑白）
2. **SAM Model Loader** - SAM分割模型  
3. **Segs Detailer** - Mask细节处理（可选）
4. **KSampler** - Stable Diffusion采样器

### 💡 Tips:
1. 
2.
```

你需要我：
1. ✅ **解析现有的 `local_inpainting.json`**，提取关键信息填充到文档中？
2. ✅ **创建更多常用工作流的模板**？
3. ✅ **添加一些实用的使用技巧和常见问题解答**？

请告诉我你想优先进行哪一项？