# 🧠 LLM-Fine-Tuning-Qwen2.5-1.5B-Instruct 

## 1. 📌 Introduction

This project demonstrates the fine-tuning of a **transformer-based Large Language Model (LLM)** using Hugging Face's `transformers` library. The goal is to create a **custom instruction-following model** capable of responding to text prompts in a context-aware manner.

### ✅ Model Used
- **Base Model**: (`Qwen2.5-1.5B-Instruct`)
- **Fine-Tuned Model Name**: `finetuned_model_id = "/gdrive/mydrive/project/model"`

### 🛠️ Technologies Used
- Python
- Hugging Face Transformers
- PyTorch
- Google Colab (for training environment)
- Weights & Biases (wandb) for tracking
- bitsandbytes (for efficient model loading and quantization)

---

## 2. ⚙️ Requirements

Essential libraries:
- `transformers`
- `torch`
- `bitsandbytes`
- `datasets`
- `wandb`
- `faker`
- `pydantic`

---

## 3. 🔗 Model & Dataset

The fine-tuned model and the training dataset can be accessed here:

📦 **[Google Drive Link to Model and Dataset](https://drive.google.com/drive/folders/1n6mVdV2p8ETMAfqEmhBBGBYz5RPfsSAV?usp=drive_link)**  

---



## 4. 📈 What I Gained from This Project

- Learned how to load and preprocess data for transformer models
- Understood how to configure and run the `Trainer` API for fine-tuning
- Gained experience using cloud tools (Colab, Drive, wandb)
- Practiced using quantization for memory-efficient training

---

## 5. 🧾 Conclusion

This project provided practical insights into working with LLMs and customizing them for task-specific applications. The final model can serve as a foundational chatbot, prompt generator, or be further tuned for domain-specific instruction tasks.

