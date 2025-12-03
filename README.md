# 🖼️ Gemini Vision — Invoice Understanding App

A Streamlit application that uses **Google Gemini Vision (gemini-pro-vision)** to analyze invoices and answer user queries about the uploaded image.  
This project demonstrates how to combine **image understanding** with **natural-language prompting** to extract insights from invoice documents.

---

## 🚀 Features

- Upload invoice images (JPG, PNG, JPEG)  
- View the uploaded image directly in the app  
- Ask any question about the invoice (amount, vendor, items, dates, etc.)  
- Uses **Gemini Vision** for multimodal image + text understanding  
- Clean and interactive **Streamlit UI**

---

## 🛠️ Tech Stack Overview

- **Model:** Google Gemini Pro Vision  
- **Framework:** Streamlit  
- **Image Handling:** PIL  
- **Environment:** python-dotenv for API key loading  
- **Multimodal Input:** Text + Image processed together  

---

## 📦 Project Setup (High-Level)

1. Install project dependencies  
2. Create a `.env` file to store your **GOOGLE_API_KEY**  
3. Run the Streamlit app  
4. Upload an invoice image  
5. Enter your question and get AI-powered responses  

---

## 📂 Folder Structure

- **app.py** — Main application file  
- **.env** — API key file  
- **requirements.txt** — Python dependencies  

---

## 🧠 How the App Works

- Loads your Google API key using dotenv  
- Configures the Gemini client for image processing  
- Accepts an uploaded invoice image  
- Converts the image into the correct input format for Gemini  
- Sends both the image and your question to the model  
- Returns a highly detailed, context-aware response based on the invoice  

---

## 📸 Use Cases

- Invoice detail extraction  
- Vendor name or invoice number identification  
- Total amount or tax calculation queries  
- Detecting due dates or payment terms  
- Understanding itemized breakdowns

---

## 🔮 Future Enhancements

- Add OCR fallback for low-quality images  
- Add PDF invoice support  
- Structured JSON output for integration with tools  
- Multi-invoice comparison features  
- Downloadable invoice summary reports  

---

## ⭐ Support This Project

If you find this useful, consider starring the repository or contributing with improvements!

