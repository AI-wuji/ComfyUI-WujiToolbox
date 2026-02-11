# ☯️ 无极工具箱 / Wuji Toolbox

**一句话 / One Sentence:**
让ComfyUI工作流变得极简，你只需要一个节点。
Make ComfyUI workflow minimal, you only need one node.

---

## 简介 / Introduction

☯️无极工具箱是一个ComfyUI插件，旨在简化AI绘图工作流程。通过官方API直连，将原本需要多个节点才能完成的操作整合为单一节点，大幅降低使用门槛，提升工作效率。

Wuji Toolbox is a ComfyUI plugin designed to simplify AI image generation workflows. By directly connecting to official APIs, it consolidates operations that originally required multiple nodes into single nodes, significantly lowering the barrier to entry and improving work efficiency.

**核心特点 / Key Features:**
- 🎯 **极简操作** - 一个节点替代10+节点
- ⚡ **性能优化** - 内置FP8/FP4/注意力优化
- 🎨 **风格预设** - 100+风格一键应用
- 🔧 **稳定可靠** - 官方API直连，永不掉线

---

## 节点介绍 / Node Introduction

### 核心节点 / Core Nodes

#### ☯️无极加载器 / Wuji Loader
一站式模型加载器，同时支持：
- UNet模型加载
- Checkpoint模型加载
- CLIP模型加载（支持双CLIP）
- VAE模型加载
- 视觉模型加载
- ControlNet模型加载
- LoRA模型加载（支持5个LoRA同时加载）

#### ☯️无极优化器 / Wuji Optimizer
综合模型优化节点，支持：
- **精度优化**: FP4/INT4/FP8 Fast/FP8/FP16/BF16
- **采样算法**: Flux/SD3/AuraFlow/HunyuanVideo/Wan/LTXV/Cosmos/Lumina2等
- **CFG优化**: RescaleCFG/CFGZeroStar/CFGNorm
- **注意力优化**: SageAttention/Torch.compile

#### ☯️无极采样器 / Wuji Sampler
采样解码一体化节点：
- 直接调用官方KSamplerAdvanced
- 自动VAEDecode解码
- 输出潜空间和图像

#### ☯️无极图像加载器 / Wuji Image Loader
图像处理综合节点：
- 加载输入图像
- 百万像素比例缩放（保持宽高比）
- BEN2智能抠图（需安装ComfyUI-Easy-Use）

#### ☯️无极编辑器 / Wuji Editor
提示词编辑编码节点：
- 正向/负向提示词输入
- 风格预设选择（流派/媒介/摄影/动漫/游戏）
- CLIP编码输出
- 自动生成空Latent

### 辅助节点 / Utility Nodes

#### ☯️无极风格选择器 / Wuji Style Selector
独立风格选择节点，输出风格文本供其他节点使用。

#### ☯️无极风格编辑器 / Wuji Style Editor
带CLIP编码的风格编辑器，直接输出CONDITIONING。

#### ☯️无极畅联 / Wuji Smooth Link
全局无线连接节点，支持任意类型数据连接。

#### ☯️无极清理器 / Wuji Cleaner
显存和内存清理工具：
- 基础清理：垃圾回收+显存释放
- 极限清理：卸载所有模型+深度清理

### 高级节点 / Advanced Nodes

#### ☯️无极LLM润词器 / Wuji LLM Expander
AI提示词扩写工具：
- 支持在线模型（GLM-4V/Gemini/GPT）
- 支持本地Qwen模型
- 支持图像/视频输入参考
- 多种扩写预设

*⚠️ 需要配置API Key或下载本地模型*

#### ☯️无极放大器 / Wuji Upscaler
图像视频放大工具：
- 基于SeedVR2引擎
- 支持RTX 40/50系列优化
- 多种颜色校正算法

*⚠️ 需要下载模型文件*

---

## 使用流程 / Workflow

```
Step 1: 下载插件
↓
Step 2: 安装到ComfyUI/custom_nodes/
↓
Step 3: 启动ComfyUI
↓
Step 4: 拖入☯️无极加载器 → 选择模型 → 连接☯️无极采样器 → 生成！
```

---

## 下载 / Download

[🚀 立即下载 / Download Now](https://drive.uc.cn/s/ca4a9cc1df7b4)

**文件大小 / File Size:** 1.4 MB  
**版本 / Version:** v2.11

---

## 支持我们 / Support Us

如果这个工具帮助到了您，欢迎赞赏支持！

![微信赞赏码](https://github.com/AI-wuji/ComfyUI-WujiToolbox/blob/master/%E8%B5%9E%E8%B5%8F%E7%A0%81.jpg?raw=true)

---

## 许可证 / License

MIT License - 免费使用，欢迎传播
