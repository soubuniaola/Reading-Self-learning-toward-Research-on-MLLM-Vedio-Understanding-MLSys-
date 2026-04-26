# ML Reading Path — Toward Multimodal & Video Understanding

> A structured reading log tracking my learning journey toward research in multimodal learning, video understanding, and ML systems efficiency.  
> Started: 04/18/2026 | Target Lab: PALM Lab, Brown University

---

## Repository Structure

```shell
.
├── README.md                   # This file — master index and progress tracker
├── notes/
│   ├── multimodal/             # Paper notes: vision-language alignment
│   ├── video/                  # Paper notes: video understanding
│   └── mlsys/                  # Paper notes: ML systems & efficiency
├── reproductions/              # Code for any partial/full reproductions
└── writing/                    # Open problem notes, technical memos
```

---

## Progress Overview

| Track | Papers Planned | Papers Read | Status |
|---|---|---|---|
| Track 1 — Multimodal Foundations | 8 | 0 | 🚀 In Progress |
| Track 2 — Video Understanding | 8 | 0 | 🚀 In Progress|
| Track 3 — ML Systems | 6 | 0 | 🔜 Not started |
| PALM Lab Papers | 6+ | 0 | 🔜 Not started |

---

## Track 1 — Multimodal Foundations

### Stage 1 — Vision-Language Alignment

| Paper | Authors | Venue | Year | Link | Status | Notes |
|---|---|---|---|---|---|---|
| Learning Transferable Visual Models From Natural Language Supervision (CLIP) | Radford et al. | ICML | 2021 | [Paper](https://arxiv.org/abs/2103.00020) | ✅ Done  |[Notes](notes/multimodal/CLIP_2021.md) |
| Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision (ALIGN) | Jia et al. | ICML | 2021 | [Paper](https://arxiv.org/abs/2102.05918) | ✅ Done | |
| Florence: A New Foundation Model for Computer Vision | Yuan et al. | arXiv | 2021 | [Paper](https://arxiv.org/abs/2111.11432) | ✅ Done | [Notes](notes/multimodal/Florence_2021.md)

### Stage 2 — Generative Multimodal Models

| Paper | Authors | Venue | Year | Link | Status | Notes |
|---|---|---|---|---|---|---|
| Flamingo: a Visual Language Model for Few-Shot Learning | Alayrac et al. | NeurIPS | 2022 | [Paper](https://arxiv.org/abs/2204.14198) | ✅ Done | [Notes](notes/multimodal/Flamingo_2022.md)|
| Visual Instruction Tuning (LLaVA) | Liu et al. | NeurIPS | 2023 | [Paper](https://arxiv.org/abs/2304.08485) | 📖 Reading | [Note](notes/multimodal/LLaVA_2023.md) |
| BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models | Li et al. | ICML | 2023 | [Paper](https://arxiv.org/abs/2301.12597) | ⬜ Unread | |
| InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning | Dai et al. | NeurIPS | 2023 | [Paper](https://arxiv.org/abs/2305.06500) | ⬜ Unread | |
| MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models | Zhu et al. | ICLR | 2024 | [Paper](https://arxiv.org/abs/2304.10592) | ⬜ Unread | |
| mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality | Ye et al. | arXiv | 2023 | [Paper](https://arxiv.org/abs/2304.14178) | ⬜ Unread | |
| ShareGPT4V: Improving Large Multi-modal Models with Better Captions | Chen et al. | arXiv | 2023 | [Paper](https://arxiv.org/abs/2311.12793) | ⬜ Unread | |
| Improved Baselines with Visual Instruction Tuning (LLaVA-1.5) | Liu et al. | CVPR | 2024 | [Paper](https://arxiv.org/abs/2310.03744) | ⬜ Unread | |
| LLaVA-NeXT: Improved reasoning, OCR, and world knowledge | Liu et al. | arXiv | 2024 | [Paper](https://arxiv.org/abs/2401.01325) | ⬜ Unread | |
| Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLMs | Tong et al. | NeurIPS | 2024 | [Paper](https://arxiv.org/abs/2406.16860) | ⬜ Unread | |
| PaliGemma: A versatile 3B VLM for transfer | Beyer et al. | arXiv | 2024 | [Paper](https://arxiv.org/abs/2407.07726) | ⬜ Unread | |
| InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks | Chen et al. | CVPR | 2024 | [Paper](https://arxiv.org/abs/2312.14238) | ⬜ Unread | |
| Qwen-VL: A Versatile Vision-Language Model's Understanding, Localization, Text Reading, and Beyond | Bai et al. | arXiv | 2023 | [Paper](https://arxiv.org/abs/2308.12966) | ⬜ Unread | |
| Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution | Wang et al. | arXiv | 2024 | [Paper](https://arxiv.org/abs/2409.12191) | ⬜ Unread | |
| CogVLM: Visual Expert for Pretrained Language Models | Wang et al. | NeurIPS | 2024 | [Paper](https://arxiv.org/abs/2311.03079) | ⬜ Unread | |
| MM1: Methods, Analysis and Insights from Multimodal LLM Pre-training | McKinzie et al. | arXiv | 2024 | [Paper](https://arxiv.org/abs/2403.09611) | ⬜ Unread | |
| Idefics2: What matters when building vision-language models? | Laurençon et al. | arXiv | 2024 | [Paper](https://arxiv.org/abs/2405.02246) | ⬜ Unread | |

### Stage 3 — PALM Lab: Multimodal Papers

| Paper | Authors | Venue | Year | Link | Status | Notes |
|---|---|---|---|---|---|---|
| [Add Chen Sun paper] | Chen Sun et al. | | | | ⬜ Unread | |
| [Add Chen Sun paper] | Chen Sun et al. | | | | ⬜ Unread | |

---

## Track 2 — Video Understanding

### Stage 1 — Temporal Modeling: CNN Era

| Paper | Authors | Venue | Year | Link | Status | Notes |
|---|---|---|---|---|---|---|
| Two-Stream Convolutional Networks for Action Recognition in Videos | Simonyan & Zisserman | NeurIPS | 2014 | [Paper](https://arxiv.org/abs/1406.2199) | 📖 Reading | |
| Temporal Segment Networks (TSN) | Wang et al. | ECCV | 2016 | [Paper](https://arxiv.org/abs/1608.00859) | 📖 Reading | |
| SlowFast Networks for Video Recognition | Feichtenhofer et al. | ICCV | 2019 | [Paper](https://arxiv.org/abs/1812.03982) | 📖 Reading | |

### Stage 2 — Transformer-Based Video Models

| Paper | Authors | Venue | Year | Link | Status | Notes |
|---|---|---|---|---|---|---|
| ViViT: A Video Vision Transformer | Arnab et al. | ICCV | 2021 | [Paper](https://arxiv.org/abs/2103.15691) | ⬜ Unread | |
| Video Swin Transformer | Liu et al. | CVPR | 2022 | [Paper](https://arxiv.org/abs/2106.13230) | ⬜ Unread | |
| VideoMAE: Masked Autoencoders are Data-Efficient Learners for Self-Supervised Video Pre-Training | Tong et al. | NeurIPS | 2022 | [Paper](https://arxiv.org/abs/2203.12602) | ⬜ Unread | |
| VideoMAE V2: Scaling Video Masked Autoencoders with Dual Masking | Wang et al. | CVPR | 2023 | [Paper](https://arxiv.org/abs/2303.16727) | ⬜ Unread | Priority |
| Hiera: A Hierarchical Vision Transformer without the Bells-and-Whistles | Ryali et al. | ICML | 2023 | [Paper](https://arxiv.org/abs/2306.00989) | ⬜ Unread | |
| VideoMamba: State Space Model for Efficient Video Understanding | Li et al. | ECCV | 2024 | [Paper](https://arxiv.org/abs/2403.06977) | ⬜ Unread | |
| UnmaskedTeacher: Towards Training-Efficient Video Foundation Models | Li et al. | ICCV | 2023 | [Paper](https://arxiv.org/abs/2310.10558) | ⬜ Unread | |

### Stage 3 — Video-Language Models & PALM Lab

| Paper | Authors | Venue | Year | Link | Status | Notes |
|---|---|---|---|---|---|---|
| VideoCLIP: Contrastive Pre-training for Zero-shot Video-Text Understanding | Xu et al. | EMNLP | 2021 | [Paper](https://arxiv.org/abs/2109.14084) | ⬜ Unread | |
| InternVideo: General Video Foundation Models via Generative and Discriminative Learning | Wang et al. | arXiv | 2022 | [Paper](https://arxiv.org/abs/2212.03191) | ⬜ Unread | |
| PALM Lab | Chen Sun et al. | | | | ⬜ Unread | |
| Video-ChatGPT: Towards Detailed Video Understanding via Large Vision and Language Models | Maaz et al. | ACL | 2024 | [Paper](https://arxiv.org/abs/2306.05424) | ⬜ Unread | |
| VideoChat: Chat-Centric Video Understanding | Li et al. | arXiv | 2023 | [Paper](https://arxiv.org/abs/2305.06355) | ⬜ Unread | |
| MVBench: A Comprehensive Multi-modal Video Understanding Benchmark (VideoChat2) | Li et al. | CVPR | 2024 | [Paper](https://arxiv.org/abs/2311.17005) | ⬜ Unread | |
| Video-LLaVA: Learning United Visual Representation by Alignment Before Projection | Lin et al. | EMNLP | 2024 | [Paper](https://arxiv.org/abs/2311.10122) | ⬜ Unread | |
| LLaMA-VID: An Image is Worth 2 Tokens in Large Language Models | Li et al. | ECCV | 2024 | [Paper](https://arxiv.org/abs/2311.17043) | ⬜ Unread | |
| TimeChat: A Time-sensitive Multimodal Large Language Model for Long Video Understanding | Ren et al. | CVPR | 2024 | [Paper](https://arxiv.org/abs/2312.02051) | ⬜ Unread | |
| MovieChat: From Dense Token to Sparse Memory for Long Video Understanding | Song et al. | CVPR | 2024 | [Paper](https://arxiv.org/abs/2402.12079) | ⬜ Unread | |
| PLLaVA: Parameter-free LLaVA Extension from Images to Videos for Video Dense Captioning | Xu et al. | arXiv | 2024 | [Paper](https://arxiv.org/abs/2404.16994) | ⬜ Unread | |
| LongVA: Long Context Transfer from Language to Vision | Zhang et al. | arXiv | 2024 | [Paper](https://arxiv.org/abs/2406.16852) | ⬜ Unread | |
| InternVideo2: Scaling Foundation Models for Multimodal Video Understanding | Wang et al. | ECCV | 2024 | [Paper](https://arxiv.org/abs/2403.15377) | ⬜ Unread | |
| VindLU: A Recipe for Effective Video-and-Language Pretraining | Cheng et al. | CVPR | 2023 | [Paper](https://arxiv.org/abs/2212.05743) | ⬜ Unread | |

---

## Track 3 — ML Systems & Efficiency

### Hardware Intuition & Profiling

| Resource | Type | Link | Status | Notes |
| --- | --- | --- | --- | --- |
| Making Deep Learning Go Brrrr From First Principles | Blog | [Horace He](https://horace.io/brrr_intro.html) | ⬜ Unread | Start here |
| PyTorch Profiler Tutorial | Docs | [PyTorch](https://pytorch.org/tutorials/recipes/recipes/profiler_recipe.html) | ⬜ Unread | Hands-on |
| NVIDIA CUDA Programming Guide (Memory Hierarchy section) | Docs | [NVIDIA](https://docs.nvidia.com/cuda/cuda-c-programming-guide/) | ⬜ Unread | Skim for intuition |

### Key MLSys Papers

| Paper | Authors | Venue | Year | Link | Status | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness | Dao et al. | NeurIPS | 2022 | [Paper](https://arxiv.org/abs/2205.14135) | ⬜ Unread | Essential |
| FlashAttention-2 | Dao | ICLR | 2024 | [Paper](https://arxiv.org/abs/2307.08691) | ⬜ Unread | |
| Efficient Transformers: A Survey | Tay et al. | ACM Computing Surveys | 2022 | [Paper](https://arxiv.org/abs/2009.06732) | ⬜ Unread | Design space overview |
| Efficient Large Scale Language Modeling with Mixtures of Experts | Artetxe et al. | EMNLP | 2021 | [Paper](https://arxiv.org/abs/2112.10684) | ⬜ Unread | |
| Efficient Memory Management for Large Language Model Serving with PagedAttention (vLLM) | Kwon et al. | SOSP | 2023 | [Paper](https://arxiv.org/abs/2309.06180) | ⬜ Unread | Inference serving |

---

## Reading Log

> Reverse chronological — most recent entries at the top.

### [Month YYYY]

#### [Paper Title]

- **Read on**: YYYY-MM-DD  
- **One-line contribution**: What is the single core insight of this paper?  
- **What did they not do?**: The most important question — where does this paper leave off?  
- **Connection to my interests**: How does this connect to multimodal / video / efficiency?  
- **Rating**: ⭐⭐⭐⭐⭐  

---

## Open Problems & Ideas

> Running notes on questions that emerge from reading. For personal reflection and research inspriation.

- 🟧 **[Problem title]**: Brief description of the open question and which papers surfaced it.

---

## Reproductions

| Paper | Scope | Code | Status | Notes |
| --- | --- | --- | --- | --- |
| [Paper title] | Partial — reproduced [specific component] | [Link to folder] | 🔜 Planned | |

---

## Status Key

| Symbol | Meaning |
| --- | --- |
| ⬜ Unread | Not yet started |
| 📖 Reading | In progress |
| ✅ Done | Read and logged |
| 🔁 Revisit | Read but needs another pass |
