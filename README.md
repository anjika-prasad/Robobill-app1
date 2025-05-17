

# 🤖 Robobill — AI Invoice Assistant

**Robobill** is a smart, Gemini-powered chatbot that analyzes invoice images and answers user queries about them. Upload your invoice, ask questions like “What’s the total amount?” or “List the purchased items,” and Robobill will provide clear, point-wise responses — all with a friendly, branded tone.

## 🚀 Features

* 📄 Upload invoice images (JPG, JPEG, PNG)
* 💬 Ask natural language questions about the invoice
* 🧠 Powered by Google Gemini 1.5 Flash (multi-modal LLM)
* 🤖 Context-aware and friendly chatbot responses
* 🌐 Built with Streamlit for an interactive web experience

## 🛠️ Tech Stack

* **Frontend/UI:** Streamlit
* **Backend:** Python
* **AI Model:** Google Gemini 1.5 Flash
* **Image Handling:** Pillow (PIL)

## 📸 How It Works

1. Upload an invoice image.
2. Type a question like “Summarize the invoice” or “What’s the due date?”
3. Click **"Let’s Go!"**
4. Robobill analyzes the image and gives an insightful answer in natural language.

## 📦 Installation

```bash
git clone https://github.com/anjika-prasad/Robobill-app.git
cd Robobill-app
pip install -r requirements.txt
streamlit run app.py
```

> ⚠️ Don’t forget to add your Gemini API key in `app.py`.

## 🔐 API Configuration

```python
genai.configure(api_key="YOUR_GEMINI_API_KEY")
```

## 🧠 Prompt Design

The app uses a carefully crafted system prompt to ensure:

* Friendly greeting
* Point-wise invoice breakdown
* Uniform formatting
* A branded sign-off

## 📢 Made With ❤️

Made in India by [Anjika Prasad](https://github.com/anjika-prasad)
Powered by my brain 🧠


