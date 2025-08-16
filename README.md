# 📘 EduGenius AI – Smart Concept Explainer  

EduGenius AI is an **AI-powered learning assistant** that helps students and professionals **understand, summarize, and explain complex concepts**. It supports multiple output formats including **PDFs, presentations, and audio explanations**, making learning more interactive and accessible.  

---

## 🚀 Features  
- 📄 **PDF Support** – Upload documents and extract key concepts.  
- 🤖 **AI-Powered Explanations** – Uses **Google Gemini API** to simplify topics.  
- 🎤 **Text-to-Speech (TTS)** – Converts AI-generated explanations into audio for hands-free learning.  
- 📊 **Presentation Generator** – Automatically creates PowerPoint slides from key ideas.  
- 🎨 **Streamlit Web App** – Simple and elegant interface with custom styling.  
- 📚 **Multi-format Learning** – Download explanations as PDFs, listen as audio, or view as slides.  

---

## 🛠️ Tech Stack  
- **Python 3.9+**  
- **Streamlit** – for web app interface  
- **Google Gemini API** – AI-powered content generation  
- **PyMuPDF (fitz)** – PDF text extraction  
- **python-pptx** – PowerPoint generation  
- **gTTS / Pydub** – Text-to-Speech  
- **FPDF** – PDF export  

---

## 📦 Installation  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/edugenius-ai.git
   cd edugenius-ai
   ```

2. **Create virtual environment (recommended)**  
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**  
   - Get an API key from Google AI Studio.  
   - Create a `.env` file in the project root:  

   ```ini
   GEMINI_API_KEY=your_api_key_here
   ```

---

## ▶️ Usage  
Run the Streamlit app:  

```bash
streamlit run app.py
```

- Upload a PDF file or enter a concept manually.  
- Choose output format (Text, PDF, PPT, Audio).  
- Get simplified explanations instantly.  

---

## 📂 Project Structure  
```bash
📦 EduGenius AI
 ┣ 📜 app.py                # Main application
 ┣ 📜 requirements.txt      # Dependencies
 ┣ 📜 README.md             # Documentation
 ┣ 📜 NotoSans-Bold.ttf     # Fonts
 ┣ 📜 NotoSans-Regular.ttf  # Fonts
 ┗ 📜 NotoSans-Regular.pkl  # Saved model/config
```

---

## 🖼️ Screenshots  
(Add images of the app interface here – e.g., file upload, AI response, generated PPT.)  

---

## ✨ Future Improvements  
- 🌐 Multi-language support  
- 🧑‍🏫 Interactive quiz generation  
- 📱 Mobile-friendly deployment  

---

## 🤝 Contributing  
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.  

---

## 📜 License  
This project is licensed under the MIT License.  
