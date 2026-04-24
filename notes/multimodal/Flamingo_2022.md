# Note on Flamingo (2022)

> Flamingo: a Visual Language Model for Few-Shot Learning  
> Alayrac et al., NeurIPS 2022  
> Link: https://arxiv.org/abs/2204.14198

---

## 1. Quick Metadata

- **Status**: 📖 Reading
- **Read date**: 2026-04-24
- **Track**: Multimodal
- **Stage**: 2 Generative Multimodal Model
- **Priority**: High 
- **Revisit?**: No

---

## 2. One-Sentence Summary

- **Core idea**:
Flamingo, a VLM, uses pre-trained visual encoder with ***Perceiver Resampler*** to generate the fixed length visual token (image, video), conflating it with language token through *GATED ATTEN-DENSE* which interleaved in pre-trained frozen LM block and ultimately generate visual-informed texts.

***From source text:*** *Flamingo models have this capability--they are viasually-conditioned autoregressive text generation modles able to ingest a sequence of text tokens interleaved with images and/or videos, and produce text as output.*
---

## 3. Problem Setting

- **What problem are they solving?**
  1. Limited use cases (e.g. classification)
  2. Lack the ability to generate language
  3. Previous low-data regimes condition hindered performance gains from visually-conditioned language model.
  4. Bridge the gap of few-shot inferencing ability between prompts in text and visual elements.
- **Why does this problem matter?**
  
- **What was the common approach before this paper?**
  
- **What limitation of prior work are they targeting?**
  

---

## 4. Main Contributions

1. Able to accept arbitrarily interleaved visual data and text as input and generate text in open-edned manner
2. Novel archietecture
3. Multi-objective training and optimization strategy on a mixture of visual and language datasets (M3W: interleaved image and text dataset; Image/Video-text pairs)
4. Few-shot task adaptation capability 


---

## 5. Method Overview

### 5.1 High-level pipeline
- Visual Encoder: Normalization-Free ResNet (NSNet, F6 model)
- Perceiver Resampler: Similar to Perceiver and DETR (Learn a predefined number of latent input queries which are fed to a Transformer and corss-attend to the visual features)
- LM block: Transformer decoder (frozen text-only LM blocks)
- GATED XATTN-DENSE layer: using tanh gating after cross-attn and ffw.

### 5.2 Training objective
- Multiple-object training: minimizing the weighted sum of per-dataset expected negative log-likelihoods of text, given the visual inputs.

### 5.3 Dataset / data mixture
- **Dataset scale**:
- **Data source**:
- **Supervision type**:
- Hint: check whether the paper mixes image-text and video-text data.

### 5.4 Model architecture
- **Vision encoder**:
- **Adapter / resampler**:
- **Language model**:
- **Cross-attention / fusion mechanism**:
- Hint: note which parts are frozen and which parts are trainable.

### 5.5 Inference / few-shot use
- 
- Hint: pay attention to how prompts are formatted with images and text demonstrations.

---

## 6. Key Technical Details

- **How visual tokens are compressed**:
  - Hint: why not feed all patch tokens directly?
- **How image features enter the LM**:
  - Hint: where are cross-attention layers inserted?
- **Training efficiency choice**:
  - Hint: what is gained by freezing large pretrained modules?
- **Prompting / in-context learning setup**:
  - Hint: how does Flamingo perform few-shot transfer without task-specific fine-tuning?
- **Video handling**:
  - Hint: how are frames represented and fused?

---

## 7. Results

### 7.1 Main empirical results
- 
- Hint: record both the broad claim and 2-3 benchmark highlights.

### 7.2 What is impressive?
- 
- Hint: look for where few-shot performance is unusually strong.

### 7.3 What are the weak spots?
- 
- Hint: note cases where it still trails specialist models or seems expensive.

---

## 8. My Understanding

### 8.1 Intuition in plain words
- 
- Hint: try explaining it as “a frozen LM learns when to look at visual memory.”

### 8.2 Why Flamingo mattered historically
- 
- Hint: place it between contrastive vision-language models and later chat-style MLLMs.

### 8.3 What unlocked later MLLMs?
- 
- Hint: think about frozen-backbone adaptation and multimodal prompting.

---

## 9. Relation to My Interests

### 9.1 Connection to multimodal learning
- 

### 9.2 Connection to video understanding
- 
- Hint: note whether the paper treats video as sampled visual sequences and what that implies.

### 9.3 Connection to ML systems / efficiency
- 
- Hint: focus on frozen modules, trainable bridges, and compute tradeoffs.

---

## 10. Limits and Open Questions

- **What did they not do?**
- **What assumptions seem strong?**
- **What breaks in harder settings?**
- **What would I try next?**
- Hint: grounding, hallucination, long context, data scale, and adaptation cost are good angles.

---

## 11. Paper-to-Paper Connections

- **Compared with CLIP**:
- **Compared with Florence**:
- **Compared with BLIP-2 / LLaVA**:
- **Compared with video-language models**:
- Hint: ask what changes when the goal shifts from alignment to generation.

---

## 12. Memorable Takeaways

1. 
2. 
3. 

- Hint: keep these to ideas you would still remember a month later.

---

## 13. Reading Log Entry Draft

- **Read on**: YYYY-MM-DD
- **One-line contribution**: 
- **What did they not do?**: 
- **Connection to my interests**: 
- **Rating**: ⭐⭐⭐⭐⭐

---

## 14. Terms / Concepts to Review

- 
- Hint: collect exact module names and training terms here.

---

## 15. Follow-up Papers

- [ ] CLIP
- [ ] Florence
- [ ] BLIP-2
- [ ] LLaVA
- [ ] VideoCLIP

[Back to main page](../../README.md)
