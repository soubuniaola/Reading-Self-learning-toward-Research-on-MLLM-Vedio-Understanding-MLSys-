# ML Reading Path — Toward Multimodal & Video Understanding

> A structured reading log tracking my learning journey toward research in multimodal learning, video understanding, and ML systems efficiency.  
> Started: 04/18/2026 | Target Lab: PALM Lab, Brown University

---

## Repository Structure

```
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
| Learning Transferable Visual Models From Natural Language Supervision (CLIP) | Radford et al. | ICML | 2021 | [Paper](https://arxiv.org/abs/2103.00020) | 📖 Reading  |[Notes](notes/multimodal/CLIP_2021.md) |
| Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision (ALIGN) | Jia et al. | ICML | 2021 | [Paper](https://arxiv.org/abs/2102.05918) | ⬜ Unread | |
| Florence: A New Foundation Model for Computer Vision | Yuan et al. | arXiv | 2021 | [Paper](https://arxiv.org/abs/2111.11432) | ⬜ Unread | |

### Stage 2 — Generative Multimodal Models

| Paper | Authors | Venue | Year | Link | Status | Notes |
|---|---|---|---|---|---|---|
| Flamingo: a Visual Language Model for Few-Shot Learning | Alayrac et al. | NeurIPS | 2022 | [Paper](https://arxiv.org/abs/2204.14198) | ⬜ Unread | |
| Visual Instruction Tuning (LLaVA) | Liu et al. | NeurIPS | 2023 | [Paper](https://arxiv.org/abs/2304.08485) | ⬜ Unread | |

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

### Stage 3 — Video-Language Models & PALM Lab

| Paper | Authors | Venue | Year | Link | Status | Notes |
|---|---|---|---|---|---|---|
| VideoCLIP: Contrastive Pre-training for Zero-shot Video-Text Understanding | Xu et al. | EMNLP | 2021 | [Paper](https://arxiv.org/abs/2109.14084) | ⬜ Unread | |
| InternVideo: General Video Foundation Models via Generative and Discriminative Learning | Wang et al. | arXiv | 2022 | [Paper](https://arxiv.org/abs/2212.03191) | ⬜ Unread | |
| PALM Lab | Chen Sun et al. | | | | ⬜ Unread | |

---

## Track 3 — ML Systems & Efficiency

### Hardware Intuition & Profiling

| Resource | Type | Link | Status | Notes |
|---|---|---|---|---|
| Making Deep Learning Go Brrrr From First Principles | Blog | [Horace He](https://horace.io/brrr_intro.html) | ⬜ Unread | Start here |
| PyTorch Profiler Tutorial | Docs | [PyTorch](https://pytorch.org/tutorials/recipes/recipes/profiler_recipe.html) | ⬜ Unread | Hands-on |
| NVIDIA CUDA Programming Guide (Memory Hierarchy section) | Docs | [NVIDIA](https://docs.nvidia.com/cuda/cuda-c-programming-guide/) | ⬜ Unread | Skim for intuition |

### Key MLSys Papers

| Paper | Authors | Venue | Year | Link | Status | Notes |
|---|---|---|---|---|---|---|
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
|---|---|---|---|---|
| [Paper title] | Partial — reproduced [specific component] | [Link to folder] | 🔜 Planned | |

---

## Status Key

| Symbol | Meaning |
|---|---|
| ⬜ Unread | Not yet started |
| 📖 Reading | In progress |
| ✅ Done | Read and logged |
| 🔁 Revisit | Read but needs another pass |
