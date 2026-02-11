# ☯️ 无极工具箱

## Wuji Toolbox

---

**一句话 / One Sentence:**
让ComfyUI工作流变得极简，你只需要一个节点。
Make ComfyUI workflow minimal, you only need one node.

---

## 这是什么？/ What is this?

### 中文
这是一个ComfyUI插件，安装后你只需要使用"☯️无极加载器"一个节点，就能完成原本需要10+个节点才能完成的工作。
**全程官方API直连，稳定可靠，与ComfyUI同步更新。**
核心优势：

🎯 极简操作 - 一个节点替代10+节点
⚡ 性能优化 - 内置FP8/FP4/注意力优化
🎨 风格预设 - 100+风格一键应用
🔧 稳定可靠 - 官方API直连，永不掉线

### English
This is a ComfyUI plugin. After installation, you only need to use the "☯️Wuji Loader" node to complete work that originally required 10+ nodes.
**Direct official API connection, stable and reliable, synchronized with ComfyUI updates.**
Key Advantages:

🎯 Minimal Operation - One node replaces 10+ nodes
⚡ Performance Optimization - Built-in FP8/FP4/Attention optimization
🎨 Style Presets - 100+ styles with one click
🔧 Stable & Reliable - Official API connection, never offline

---

## 核心卖点 / Core Selling Points

### 1. 极简操作 / Minimal Operation
一个节点替代10+节点 / One node replaces 10+ nodes

| 其他插件 / Other Plugins | 无极工具箱 / Wuji Toolbox |
|---|---|
| Checkpoint加载器 + CLIP加载器 + VAE加载器 + LoRA加载器x5 | ☯️无极加载器 (1个节点) |
| 模型优化节点 + 采样算法节点 + CFG节点 | ☯️无极优化器 (1个节点) |
| KSampler + VAEDecode | ☯️无极采样器 (1个节点) |
| LoadImage + ImageScale + BEN2抠图 | ☯️无极图像加载器 (1个节点) |
| CLIPTextEncode + 风格选择器 | ☯️无极编辑器 (1个节点) |

**你 / You:** 拖入☯️无极加载器 → 选择模型 → 完成！

**AI:** 收到！正在加载UNet + CLIP + VAE + LoRA...完成！

---

### 2. 全流程简化 / Full Process Simplification
从复杂到极简 / From complex to minimal

**传统工作流 / Traditional Workflow:**
需求 → 拖入10+节点 → 逐个配置 → 连接线路 → 测试调试 → 完成
(繁琐复杂 / Complex)

**VS**

**无极工具箱 / Wuji Toolbox:**
拖入节点 → 选择模型 → 一键生成 → 完成！
(极简高效 / Minimal & Efficient)

---

### 3. 性能优化 / Performance Optimization
内置多种优化，开箱即用 / Built-in optimizations, ready to use

#### 精度优化 / Precision Optimization
- FP4 / INT4 / FP8 Fast / FP8 / FP16 / BF16
- 自动检测显卡支持，智能选择最优精度

#### 采样算法 / Sampling Algorithms
- Flux / Flux2 / SD3 / AuraFlow / HunyuanVideo / Wan / LTXV / Cosmos / Lumina2
- 一键切换，自动配置最佳参数

#### CFG优化 / CFG Optimization
- RescaleCFG / CFGZeroStar / CFGNorm
- 提升图像质量和稳定性

#### 注意力优化 / Attention Optimization
- SageAttention / Torch.compile
- 加速推理，降低显存占用

---

## 节点清单 / Node List

| 节点 / Node | 功能 / Function | 状态 / Status |
|---|---|---|
| ☯️无极加载器 / Wuji Loader | 一站式模型加载 | ✅ 稳定 |
| ☯️无极优化器 / Wuji Optimizer | 精度+采样+CFG优化 | ✅ 稳定 |
| ☯️无极采样器 / Wuji Sampler | 采样+解码一体化 | ✅ 稳定 |
| ☯️无极图像加载器 / Wuji Image Loader | 加载+缩放+BEN2抠图 | ✅ 稳定 |
| ☯️无极编辑器 / Wuji Editor | 提示词+风格+编码 | ✅ 稳定 |
| ☯️无极风格选择器 / Wuji Style Selector | 独立风格选择 | ✅ 稳定 |
| ☯️无极风格编辑器 / Wuji Style Editor | 风格+CLIP编码 | ✅ 稳定 |
| ☯️无极畅联 / Wuji Smooth Link | 全局无线连接 | ✅ 稳定 |
| ☯️无极清理器 / Wuji Cleaner | 显存内存清理 | ✅ 稳定 |
| ☯️无极LLM润词器 / Wuji LLM Expander | AI提示词扩写 | ⚠️ 需API Key |
| ☯️无极放大器 / Wuji Upscaler | 图像视频放大 | ⚠️ 需模型文件 |

---

## 适合谁用？/ Who is it for?

| 人群 / Audience | 效果 / Effect |
|---|---|
| ComfyUI新手 / Beginners | 降低门槛，快速上手专业工作流 |
| 效率追求者 / Efficiency Seekers | 一个节点完成复杂操作，效率提升5倍 |
| 稳定性要求者 / Stability Seekers | 官方API直连，告别第三方节点失效 |
| 多模型用户 / Multi-Model Users | 一站式加载，告别繁琐配置 |

---

## 怎么用？/ How to use?

### 4步开始 / 4 Steps to Start

```
Step 1          Step 2          Step 3          Step 4
下载            安装            启动            使用
(10秒)          (30秒)          (5秒)           (全自动)
```

### 详细步骤 / Detailed Steps

#### 中文：
```
# 1. 下载
下载: https://drive.uc.cn/s/ca4a9cc1df7b4

# 2. 安装
解压 → 放入 ComfyUI/custom_nodes/ → 完成

# 3. 启动
启动ComfyUI，在节点列表中找到"☯️无极工具箱"

# 4. 使用
拖入☯️无极加载器 → 选择模型 → 连接☯️无极采样器 → 生成！
```

#### English:
```
# 1. Download
Download: https://drive.uc.cn/s/ca4a9cc1df7b4

# 2. Install
Extract → Put in ComfyUI/custom_nodes/ → Done

# 3. Start
Launch ComfyUI, find "☯️Wuji Toolbox" in node list

# 4. Use
Drag ☯️Wuji Loader → Select model → Connect ☯️Wuji Sampler → Generate!
```

---

## 效果对比 / Results Comparison

| 工作流 / Workflow | 传统方式 / Traditional | 无极工具箱 / Wuji Toolbox | 提升 / Improvement |
|---|---|---|---|
| Flux基础工作流 | 8个节点 | 3个节点 | 2.7倍简化 |
| SD3完整工作流 | 12个节点 | 4个节点 | 3倍简化 |
| 多LoRA加载 | 6个LoRA加载器 | 1个无极加载器 | 6倍简化 |
| 风格化生成 | 手动输入风格词 | 一键选择 | 10倍效率 |

---

## 下载 / Download

### UC网盘 / UC Drive

[🚀 立即下载 / Download Now](https://drive.uc.cn/s/ca4a9cc1df7b4)

**文件 / File:** 1.4 MB | **版本 / Version:** v2.11

---

## 支持我们 / Support Us

### 中文
如果这个工具帮助到了您，欢迎赞赏支持，您的支持是我持续改进的动力！

### English
If this tool helps you, welcome to support us. Your support is my motivation for continuous improvement!

### 微信赞赏码 / WeChat Support
> "您的支持是我最大的动力"
> "Your support is my greatest motivation"

![微信赞赏码](https://github.com/AI-wuji/ComfyUI-WujiToolbox/blob/master/%E8%B5%9E%E8%B5%8F%E7%A0%81.jpg?raw=true)

---

## 许可证 / License

MIT License - 免费使用，欢迎传播 / Free to use, welcome to share

---

<p align="center">
  <b>☯️ 无极工具箱 - 让ComfyUI变得简单</b><br>
  <b>Wuji Toolbox - Make ComfyUI Simple</b>
</p>

<p align="center">
  官方API直连 · 极简操作 · 稳定可靠<br>
  Official API · Minimal Operation · Stable & Reliable
</p>
