# 🌍 Azure Language Translation API Integration 🚀

This project integrates the **Azure Language Translation API** to enable real-time translation of text into multiple languages. It provides API endpoints to fetch supported languages and translate text dynamically.

## 🔥 Features
- Fetch a list of supported languages
- Translate text into any supported language
- Simple API structure with JSON-based requests
- Fast and reliable translation using Azure services

---

## 🚀 API Endpoints

### **1️⃣ Get Supported Languages**
**Endpoint:**  
```plaintext
GET https://translate-language-azure.vercel.app/languages

Response Example:

json
Copy
Edit
{
  "languages": {
    "en": { "name": "English", "nativeName": "English" },
    "bn": { "name": "Bengali", "nativeName": "বাংলা" },
    "fr": { "name": "French", "nativeName": "Français" }
  }
}


2️⃣ Translate Text
Endpoint:

plaintext
Copy
Edit
POST https://translate-language-azure.vercel.app/translate
Request Body:

json
Copy
Edit
{
  "text": "Hello, how are you?",
  "dest_lang": "es"
}


Response Example:

json
Copy
Edit
{
  "translated_text": "Hola, ¿cómo estás?"
}


🎯 Use Case Scenarios
🌍 Multi-language Customer Support – Automatically translate customer queries.
📖 Content Localization – Translate blogs, product descriptions, and UI dynamically.
📚 Education & Research – Provide global access to historical texts in different languages.
