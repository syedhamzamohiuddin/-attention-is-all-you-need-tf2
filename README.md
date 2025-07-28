# Transformer From Scratch — Attention Is All You Need (TensorFlow 2)

> 📓 **Full implementation notebook is available on Kaggle:**  
> 👉 [Transformer — Attention Is All You Need (Detailed TF2 Implementation)](https://www.kaggle.com/code/hamzamohiuddin/transformer-attention-is-all-you-need-detailed)

This project is a faithful, from-scratch TensorFlow 2.x implementation of the landmark paper:  
**[Attention Is All You Need (Vaswani et al., 2017)](https://arxiv.org/abs/1706.03762)**

Unlike many simplified tutorials, this project strictly follows the original architecture, training regime, and data preparation — with **no shortcuts**. The entire network is built from scratch, including attention mechanisms, positional encoding, masking logic, and custom training loops.

---

## 🔍 Why This Implementation Stands Out

- ✅ **Paper-Faithful Design**  
  Directly follows the structure and hyperparameters described in the paper — you're encouraged to keep the paper open while exploring the notebook.

- ✅ **Built From Scratch in TensorFlow 2**  
  No high-level Keras abstractions or external libraries (like HuggingFace) are used — everything is implemented manually for clarity and control.

- ✅ **Original WMT14 Data Preprocessing**  
  Sentence pairs are preprocessed using the original [Moses tokenizer](https://github.com/moses-smt/mosesdecoder) and `clean-corpus-n.perl` script — same as the paper.

- ✅ **Accurate and Tested Causal Masking**  
  The masking logic (including padding and look-ahead/causal masks) is implemented and verified rigorously — a common source of bugs in other replications.

- ✅ **End-to-End Pipeline With Evaluation**  
  Includes full training loop with teacher forcing, BLEU score evaluation, and inference with greedy decoding.

- ✅ **Detailed Commentary and Visual Aids**  
  Custom drawings and inline explanations are included to clarify difficult topics like multi-head attention, layer normalization, and masking.

---

## 🧠 What You'll Learn

This project is ideal if you want to:

- Understand how Transformers really work under the hood
- Study or reimplement research papers accurately
- Learn how to write production-level deep learning code in **raw TensorFlow 2.x**
- Train and evaluate sequence-to-sequence models on realistic datasets

---

## 📌 Notebook Highlights

> The entire project lives inside a single Kaggle notebook for ease of study.  
> Every section is annotated and matches the structure of the original paper.

📎 **Notebook**: [Transformer — Attention Is All You Need (Detailed)](https://www.kaggle.com/code/hamzamohiuddin/transformer-attention-is-all-you-need-detailed)

Key Sections:
- Tokenization & Data Preprocessing (Moses)
- Positional Encoding
- Multi-Head Scaled Dot-Product Attention
- Encoder & Decoder Block
- Causal and Padding Mask Implementation
- Custom Training Loop with Loss & Accuracy
- BLEU Score Evaluation
- Greedy Inference

---

## 🛠 Technologies Used

- **TensorFlow 2.x** (no Keras layers used)
- **WMT14 En-De Dataset** (preprocessed using Moses scripts)
- **Python** and **NumPy**
- **BLEU evaluation**

---

## 📜 License

This project is released under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Hamza Mohiuddin**  
Deep Learning Engineer | Paper Implementation Specialist  
📘 [Medium Article](https://medium.com/p/bada14b0023a) | 📊 [Kaggle Profile](https://www.kaggle.com/hamzamohiuddin)

> Feel free to ⭐️ the repo or fork if this project helped you!  
> Pull requests welcome for improvements or extensions.

---
