# CMPA-SLU: A Benchmark for Chinese Mobile Personal Assistant Spoken Language Understanding

## 📖 Introduction

**CMPA-SLU** is a high-quality Chinese Spoken Language Understanding (SLU) benchmark collected from real-world mobile personal assistant applications. To address the limitations of existing outdated benchmarks, CMPA-SLU provides a larger scale with **50 domains, 247 intents, and 74 slot types**. It covers emerging mobile functionalities (e.g., "Turn Off Video AI Subtitles") and reflects native Chinese user behaviors. 

**CMPA-SLU** 是一个从真实手机个人助手应用场景中收集的高质量中文口语理解（SLU）基准数据集。针对现有中文基准数据陈旧、领域覆盖受限的问题，本数据集涵盖了 **50 个领域、247 个意图和 74 种槽位类型**。它不仅包含了最新的移动端功能（如“关闭视频AI字幕”），还真实反映了中国手机用户的使用习惯与长尾分布特征。

## ✨ Key Features & Innovations

1. **Real-world Scenarios (真实场景)**: Collected from recent real-world mobile applications with rigorous anonymization and manual annotation.
2. **Partial Category Setting (部分类别设定)**: To simulate practical deployment, we introduce a Partial Category setting. Candidate labels are dynamically filtered using a BGE-based retrieval strategy, reducing computational overhead and improving accuracy.
3. **Intent-Slot Schema Mapping (IS-Map, 意图-槽位映射策略)**: We adopt a label mapping strategy for joint intent and slot prediction within a single generation process, eliminating multi-turn dialogue overhead and yielding better performance.
4. **Other Intent (其他意图)**: Explicitly includes casual/non-task-oriented expressions (e.g., "Never mind"), better reflecting real-world complexity.

## 📊 Dataset Statistics

- **Total Samples**: 7,820 (Train: 4,685 | Validation: 1,550 | Test: 1,585)
- **Domains**: 50
- **Intents**: 247
- **Slot Types**: 74
- **Distribution**: Exhibits a pronounced long-tail distribution, simulating real user requests.

| Dataset | Domain | Intent | Slot |
| :--- | :---: | :---: | :---: |
| CAIS | 11 | 4 | 24 |
| SMP2019 | 29 | 23 | 59 |
| SMP2020 | 45 | 59 | 80 |
| MASSIVE-ZH | 18 | 60 | 55 |
| **CMPA-SLU (Ours)** | **50** | **247** | **74** |


## 📝 Citation

If you find our work useful in your research, please cite:

Coming soon.
