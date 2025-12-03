# 🛍️ Clothing Sales Chat (Gradio)

**clothing_sales_chat_gradio** is an AI-powered Gradio chat assistant designed for a clothing store.
It interacts naturally with customers and gently encourages them to explore items on sale — especially hats (60% off!) and other discounted products (50% off).

Built using **Python**, **OpenAI GPT-4.1 Mini**, and **Gradio**, and deployed on **Hugging Face Spaces**.

---

## 🚀 Live Demo

Experience the app here:
👉 **[https://huggingface.co/spaces/vinaykahar978/clothing_sales_chat_gradio](https://huggingface.co/spaces/vinaykahar978/clothing_sales_chat_gradio)**

---

## 📦 GitHub Repository

Source code:
👉 **[https://github.com/vinaykahar978/clothing_sales_chat_gradio.git](https://github.com/vinaykahar978/clothing_sales_chat_gradio.git)**

---

## ✨ Features

* Interactive chat assistant built with **Gradio ChatInterface**
* AI agent that:

  * Encourages customers to explore items on sale
  * Promotes hats (60% off)
  * Reminds users when an item (ex: shoes) is not on sale
  * Redirects customers if they ask for unavailable items (like belts)
* Smooth streaming responses
* Clean and simple UI

---

## 🛠️ Tech Stack

* **Python**
* **Gradio**
* **OpenAI GPT-4.1 Mini**
* **dotenv** (local environment variables)

---

## 📁 Project Structure

```
.
├── app.py               # Main Gradio application
├── requirements.txt     # Python dependencies
├── runtime.txt          # Python runtime for Hugging Face
├── .gitignore           # Hidden files / folders
└── README.md            # Project documentation
```

---

## ⚙️ Setup (Local Development)

### 1️⃣ Clone the repository

```bash
git clone https://github.com/vinaykahar978/clothing_sales_chat_gradio.git
cd clothing_sales_chat_gradio
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Create a `.env` file

(Do NOT commit this file)

```
OPENAI_API_KEY=your_openai_key_here
```

### 4️⃣ Run the app

```bash
python app.py
```

Then open:
👉 `http://localhost:7860`

---

## 🌐 Deploying to Hugging Face Spaces

The project is already deployed:
🔗 **[https://huggingface.co/spaces/vinaykahar978/clothing_sales_chat_gradio](https://huggingface.co/spaces/vinaykahar978/clothing_sales_chat_gradio)**

To deploy your own:

1. Create a new **Gradio / Python Space**
2. Upload your project files (or push via git)
3. Add your secrets:

   * `OPENAI_API_KEY`
4. Hugging Face automatically builds & launches the app

---

## 🔒 Security Notes

* Never commit `.env` or API keys
* Always use Hugging Face **Secrets** for deployment
* Do not hard-code sensitive data in `app.py`

---

## 💡 Future Improvements

* Add product images & pricing
* Add a recommendation engine based on customer queries
* Add support for exporting chat transcripts
* Add multi-product catalog navigation

