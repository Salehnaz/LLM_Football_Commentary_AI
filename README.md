# LLM_Football_Commentary_AI


# 🏟️ Mini LLM for Sports Commentary Classification

A small-scale **Transformer-based model** built from scratch in Python using PyTorch.  
Trained to classify live sports commentary into categories like **GOAL**, **PASS**, **FOUL**, etc.  

This project is designed to **demystify how LLMs work** — from tokenization to embeddings to inference — without relying on pre-built APIs.

---

## 🚀 Features
- 📄 **Custom Tokenizer** — converts text into token IDs without external tokenization libraries
- 🧠 **Lightweight Transformer Encoder** — a single-layer encoder to capture contextual meaning
- 📊 **Domain-Specific Training** — 200+ sports commentary samples
- 🔌 **Java-Ready API Integration** — inference results can be served to a Spring Boot backend
- 🏗️ **Fully Reproducible in Google Colab** — train and run without local setup



![be2ad47a-094b-4b8b-970a-d80052d9ac6f](https://github.com/user-attachments/assets/4b9c7251-5da1-406b-a8fd-008be4b52db4)



---

## 📦 Tech Stack
**Languages**  
- Python (ML Core)  
- Java (for backend integration,future/planned)  

**Libraries**  
- PyTorch  
- Scikit-learn  
- Pandas  

**Infrastructure**  
- Google Colab / Google Codelab for training & hosting

---

## 🛠️ Installation & Running
### Clone the repo
```bash
git clone https://github.com/Salehnaz/LLM_Football_Commentary_AI.git
cd LLM_Football_Commentary_AI

###Install dependencies
pip install -r requirements.txt

###Run locally
python LLM_Football_Commentary_AI

```
### Example Predictions

"He smashes it into the net!" → GOAL

"The ball is passed across the field." → PASS

"Great dribble from midfield!" → DRIBBLE

"Misses the chance to equalize." → MISS

"That tackle might be a foul." → FOUL

