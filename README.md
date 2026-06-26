# PuRF-MLTTA

**Official implementation of our ECCV 2026 paper: “Towards Purified Multi-Label Test-Time Adaptation of Vision-Language Models.”**

## 📌 News 

- **[2026.06]** Our paper has been accepted to **ECCV 2026**! 🎉 
- **[Coming Soon]** Code, pretrained/cache configurations, and evaluation scripts will be released soon.

## 🧠 Overview 

Vision-Language Models (VLMs) have shown strong zero-shot recognition ability, but adapting them to **multi-label test-time scenarios** remains challenging. Existing cache-based test-time adaptation methods mainly rely on global image representations, which can entangle multiple co-occurring objects and introduce biased cache calibration. We propose **PuRF**, a **PuRiFication-driven cache-based framework** for multi-label test-time adaptation. PuRF improves multi-label recognition by purifying both regional evidence and cache representations. 

## 🔥 Highlights 
- 🌍 **Multi-Label Test-Time Adaptation** We study the practical setting where each test image may contain multiple object labels under distribution shifts.
- 🔍 **Region Purification** PuRF identifies reliable and informative regions via multi-granularity consistency, enabling fine-grained multi-label recognition.
- 🧩 **Cache Purification** PuRF builds discriminative class-specific region prototypes and improves cache calibration for multi-label scenarios.
- ⏳ **Temporal Refreshing** PuRF mitigates cache saturation and maintains long-term adaptability under streaming test data.
- 🚀 **Strong Performance** PuRF achieves state-of-the-art results across multiple multi-label benchmarks and diverse VLM backbones. 
