# Note on LLaVA (2023)

> Visual Instruction Tuning  
> Liu et al., NeurIPS 2023  
> Link: <https://arxiv.org/abs/2304.08485>

---

## 1. Quick Metadata

- **Status**: Reading
- **Read date**: 04/25/2026
- **Track**: Multimodal
- **Stage**: 2 Generative model
- **Priority**: High
- **Revisit?**: No

---

## 2. One-Sentence Summary

- **Core idea**:
  - Hint: say how LLaVA turns a pretrained visual encoder + LLM into a chat-style multimodal assistant.

---

## 3. Problem and Main Idea

- **What problem are they solving?**
  - Hint: what was still missing after CLIP/Flamingo-style models?
- **What is the main idea?**
  - Hint: focus on visual instruction tuning and conversational multimodal behavior.
- **Why does it matter?**
  - Hint: connect it to the shift toward general-purpose MLLMs.

---

## 4. Method Overview

### 4.1 Pipeline

- **Vision encoder**:
- **Projection / connector**:
- **Language model**:
- Hint: identify what maps visual features into the LLM token space.

### 4.2 Training

- **Stage 1**:
- **Stage 2**:
- Hint: separate feature alignment from instruction tuning.

### 4.3 Data

- **Data source**:
- **Supervision type**:
- Hint: note the role of GPT-generated instruction-following data.

### 4.4 Inference / use

- Hint: describe the input-output format in one line.

---

## 5. Key Technical Points

- **How image features enter the LLM**:
- **Why a simple projector is enough**:
- **What visual instruction tuning adds**:
- **What is efficient about this setup**:
- Hint: keep this section focused on the design choices that make LLaVA practical.

---

## 6. Results

- **Main empirical claim**:
- **What is impressive?**:
- **What still looks weak?**:
- Hint: capture the headline result, then one strength and one weakness.

---

## 7. My Take

- **Why this paper matters, what its main limit is, and what it suggests next**:
- Hint: answer this as one compact paragraph.

---

## 8. Paper-to-Paper Connections

- **Compared with CLIP**:
- **Compared with Flamingo**:
- **Compared with BLIP-2**:
- Hint: focus on alignment vs generation vs instruction tuning.

---

## 9. Reading Log Entry Draft

- **Read on**: YYYY-MM-DD
- **One-line contribution**:
- **Main limitation**:
- **Connection to my interests**:
- **Rating**: ⭐⭐⭐⭐⭐

---

## 10. Terms / Follow-up

- **Terms to review**:
- **Follow-up papers**:
  - [ ] CLIP
  - [ ] Flamingo
  - [ ] BLIP-2
  - [ ] MiniGPT-4
  - [ ] Qwen-VL

[Back to main page](../../README.md)
