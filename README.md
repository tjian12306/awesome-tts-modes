# Awesome TTS Models [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)  
**最新开源 TTS 模型集合（按更新时间倒序排列）**  
*更新至 2025 年 5 月，持续追踪语音合成前沿技术*  

---

## 📢 简介  
本仓库收集 **2024-2025 年最新开源 TTS 模型**，涵盖语音克隆、多语言支持、情感控制、实时生成等核心功能。每个模型均提供论文、代码仓库、Demo 链接及技术亮点说明，助力开发者快速探索语音合成技术边界。  

**⭐ 点击 Star 追踪更新 | 🔄 Fork 后提交你的模型**  

---

## 🚀 最新模型列表（2024-2025）  

### 2025 年发布  
| 模型名称 | 发布时间 | 开源地址 | 核心特性 |  
|---------|---------|----------|----------|  
| **Muyan-TTS** | 2025-05-13 | [GitHub](https://github.com/MYZY-AI/Muyan-TTS) / [HF](https://huggingface.co/MYZY-AI/Muyan-TTS) | • 极速生成（0.33秒/1秒音频）<br>• 长文本连贯朗读（适配播客/有声书）<br>• 零样本语音克隆 |  
| **Spark-TTS** | 2025-04-21 | [GitHub](https://github.com/mindspore-lab/mindone/tree/master/examples/sparktts) | • 基于 Qwen2.5 架构的高效合成<br>• 零样本跨语言音色克隆<br>• 性别/音高/语速可控生成 |  
| **MegaTTS3** | 2025-04-03 | [HF](https://huggingface.co/ByteDance/MegaTTS3) | • 超轻量化（45M 参数）<br>• 中英文混合朗读<br>• 口音强度控制 |  
| **Zonos-TTS** | 2025-02-11 | [HF](https://huggingface.co/Zyphra/Zonos-v0.1-hybrid) | • 实时语音克隆（免费商用）<br>• 20 万小时英语数据训练<br>• 支持情感控制与 API 部署 |  
| **Kokoro TTS** | 2025-01-18 | [HF](https://huggingface.co/kokoro-tts) | • Apache 2.0 免费商用<br>• 多语言支持（中/英/法/日/韩）<br>• ONNX 轻量化实时部署 |  

### 2024 年发布  
| 模型名称 | 发布时间 | 开源地址 | 核心特性 |  
|---------|---------|----------|----------|  
| **MaskGCT** | 2024-10-31 | [GitHub](https://github.com/open-mmlab/Amphion/tree/main/models/tts/maskgct) | • 10万小时多语言训练<br>• 零样本跨语种生成<br>• 语速/情感/风格控制 |  
| **F5-TTS** | 2024-XX-XX | [GitHub](https://github.com/SJTU-Cambridge-Hikvision/F5-TTS) | • 零样本音色克隆<br>• CUDA/DirectML 多后端支持<br>• 低延迟实时推理 |  

---

## 🌟 技术趋势总结  
1. **轻量化与实时化**：如 MegaTTS3（45M 参数）和 Muyan-TTS（0.33秒/秒音频）突破边缘设备部署瓶颈。  
2. **多模态控制**：Spark-TTS 支持音高/语速调节，MaskGCT 实现跨语言风格迁移。  
3. **商业化友好**：Zonos-TTS 和 Kokoro TTS 采用 Apache 2.0/MIT 协议，降低企业应用门槛。  

---

## 🤝 贡献指南  
1. **提交要求**：  
   - 仅收录 **2024 年后发布**的开源模型  
   - 需包含 **论文/代码/Demo 三要素**  
   - 优先推荐商用友好型（Apache 2.0/MIT 协议）  

2. **流程**：  
   ```markdown  
   | Model | Paper | Code | Demo | Notes |  
   |-------|-------|------|------|-------|  
   | [Your Model] | [arXiv] | [GitHub] | [Demo] | 技术亮点说明 |  
   ```  
   **Fork 后提交 PR**，审核通过后合并。  

---

## 📜 许可证  
本仓库采用 **CC-BY-4.0 协议**，引用内容版权归属原始作者。模型许可证以各项目声明为准。  

---

**⭐ Star | 🔄 Fork | 🚀 探索语音合成未来**  
*让机器发声更有温度，让创造无界！*  

> 注：完整技术细节请参考各模型官方文档。部分项目需手动配置环境（如 CUDA 12），详见引用链接。
