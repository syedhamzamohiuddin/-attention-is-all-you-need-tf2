# 🧠 Transformer: Attention Is All You Need — A Faithful TensorFlow Implementation

This repository contains a **from-scratch, TensorFlow 2 implementation** of the Transformer architecture described in the paper [*Attention Is All You Need* (Vaswani et al., 2017)](https://arxiv.org/abs/1706.03762).  
  
It replicates the architecture and training pipeline in detail — including **three-way weight tying**, **causal masking**, and **original Moses tokenization** — and is trained on the **WMT14 English–German** machine translation task.

---

## 📌 Links

- 📘 **Kaggle Notebook**:  
  [Transformer — Attention Is All You Need (Detailed)](https://www.kaggle.com/code/hamzamohiuddin/transformer-attention-is-all-you-need-detailed)  
  > 📌 Written as a tutorial for those implementing the paper — includes detailed commentary, diagrams, and code explanations with references to paper sections.

- ✍️ **Medium Article**:  
  [Implementing Attention Is All You Need — Lessons from Recreating the Transformer](https://medium.com/p/bada14b0023a)

---

## 🚀 Key Features

- ✅ **TensorFlow 2 implementation** of *Attention Is All You Need* — no shortcuts or black boxes  
- ✅ **Trained on WMT14 English–German** using official scripts and preprocessed corpus  
- ✅ **Faithful preprocessing**: Moses tokenization + BPE (like the original paper)  
- ✅ **Accurate causal masking**, validated across attention, logits, and loss layers  
- ✅ **Three-way weight tying**: encoder embeddings, decoder embeddings, and output projection **share weights**  
  ⚠️ *Often skipped in popular implementations — this repo preserves it as per the original paper*  
- ✅ **Complete training pipeline**: learning rate schedule, loss masking, label smoothing  
- ✅ **Visual explanations**: inline diagrams for masking, attention, positional encoding, and more  
- ✅ **End-to-end tested**: outputs verified at every stage — embeddings → attention → logits  
- ✅ **Educational structure**: built to teach paper implementation, not just replicate results

---

## 📷 Visuals from the Notebook

<p align="center">
  <img src="https://storage.googleapis.com/kaggle-media/transformer_diagram.png" alt="Transformer Diagram" width="600"/>
  <br>
  <i>Detailed diagrams and tensor flows included to explain architecture components</i>
</p>

---

## 📄 What’s Inside

This repo links to the full implementation and tutorial-style notebook:

| Component | Status |
|----------|--------|
| Encoder & Decoder Blocks | ✅ Fully implemented |
| Multi-Head Attention | ✅ Custom with masking support |
| Positional Encoding | ✅ Reimplemented with visualization |
| Embedding Layer | ✅ With shared weights (tied) |
| Training Schedule | ✅ Custom LR + label smoothing |
| Masking Logic | ✅ Causal & padding masks validated |
| Dataset Preprocessing | ✅ WMT14 + Moses/BPE |
| TensorFlow Code | ✅ Native TF2 without shortcuts |

---

## 📚 Learning Outcomes

This project was created to:
- 🧠 **Understand every detail of the Transformer paper**
- 🧪 **Answer real questions** about masking, autoregression, positional encoding, etc.
- 🎯 **Train the full model** from scratch using open WMT14 data
- 🛠️ **Recreate core components** without depending on libraries like HuggingFace or T2T
- ✅ **Validate implementation correctness** at every stage

---

## 🧪 Why This Implementation Stands Out

- Most open-source Transformer repos skip key aspects like:
  - 🔁 **Three-way weight tying**
  - 🧱 **Faithful masking logic**
  - 🧹 **Real preprocessing from WMT14 scripts**
- This implementation takes the paper **literally and rigorously**, as a learning and engineering challenge
- Ideal for:
  - Engineers studying transformers deeply
  - Students learning paper-to-code skills
  - Researchers verifying correctness of model components

---

## 🧠 Author

**Hamza Mohiuddin**  
Deep Learning Engineer — Computer Vision, Real-Time Systems, and Edge AI  
📍 *Always learning, always building*  
[LinkedIn](https://www.linkedin.com/in/hamzamohiuddin) • [Kaggle](https://www.kaggle.com/hamzamohiuddin) • [Medium](https://medium.com/@hamzamohiuddin)

---

## 📜 License

Released under the **MIT License** — free for personal and commercial use with attribution.

---

## 🔍 GitHub Topics

