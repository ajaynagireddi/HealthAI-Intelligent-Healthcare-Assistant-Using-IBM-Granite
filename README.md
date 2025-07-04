# HealthAI-Intelligent-Healthcare-Assistant-Using-IBM-Granite
# 🏥 HealthAI - A Generative AI Medical Assistant

**HealthAI** is an AI-powered healthcare assistant built using **IBM’s Granite LLM** (`granite-3.3-2b-instruct`) via Hugging Face. It provides **disease prediction from symptoms** and **home remedies for common illnesses** — all with a focus on natural guidance, friendly tone, and responsible AI use.

> 🔬 This project is part of an academic submission by **Dy Abhiswar** under [Your Institution/Teacher Name].

---

## 🌟 Features

✅ **Symptoms Identifier**  
Users input symptoms, and HealthAI predicts a likely disease using a fine-tuned language model prompt.

✅ **Home Remedies Recommender**  
Users input a disease name and receive safe, natural, and home-based remedies.

✅ **Conversational Interface**  
Runs with an interactive web interface using Gradio in Google Colab — no installation required.

✅ **Powered by IBM Granite LLM**  
Harnesses `granite-3.3-2b-instruct` for accurate, language-informed health guidance.

---

## 🛠️ Technologies Used

- `Python 3.10+`
- [`transformers`](https://huggingface.co/docs/transformers/) by Hugging Face  
- `Gradio` for user interface  
- `Google Colab` for quick deployment  
- `IBM Granite 3.3 2B Instruct` model

---

## 🚀 Getting Started

> 🔗 **Run on Google Colab**  
Open the project in [Google Colab](https://colab.research.google.com/) and run all cells.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/healthai.git
cd healthai
2️⃣ Run in Google Colab
Open healthai.ipynb on Google Colab:

Click Runtime > Run All

Interact with the UI

🧪 How to Use
🩺 Symptoms Identifier
Input: “sore throat, body ache, mild fever”

Output: “These symptoms may indicate a common cold or flu. Stay hydrated and rest. Consult a doctor if symptoms persist.”

🌿 Home Remedies
Input: “migraine”

Output: “Try applying peppermint oil to your temples, rest in a dark room, and stay hydrated.”
