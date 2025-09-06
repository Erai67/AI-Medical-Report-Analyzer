# AI Medical Report Analyzer

An AI-powered web application that simplifies complex medical reports into easy-to-understand explanations in multiple Indian languages.

---

## The Problem
Medical reports are often filled with technical jargon and complex data that can be confusing and intimidating for the average person. This language barrier can cause anxiety and prevent people, especially in rural areas or those without a medical background, from understanding their own health status and taking the right next steps.  
My own family's difficulty in understanding these reports inspired this project.

---

## The Solution
This tool bridges that gap. By using the power of **Google Gemini AI**, it takes a medical report—either as pasted text or a photo—and provides a simple, clear, and compassionate explanation in the user's chosen language. It's designed to be accessible to everyone, empowering them with the knowledge they need to have more informed conversations with their doctors.

---

## Key Features
- **Dual Input Methods**: Users can either paste text directly or upload a photo of their report.  
- **Multi-Language Support**: The entire interface and the final analysis are available in several major Indian languages.  
- **AI-Powered Analysis**: Leverages Google's powerful AI to "read" and interpret the reports.  
- **Simple Explanations**: Breaks down complex medical terms and explains what they mean in plain language.  
- **Secure**: Your API key is required for analysis but is not stored or saved anywhere.  

---

## How to Use
1. **Get a free API Key**: Visit the [Google AI Studio](https://aistudio.google.com/) website to generate your key.  
2. **Open the Application**: Launch the `medical_report_analyzer.html` file in any web browser.  
3. **Enter Your Key**: Copy the generated key and paste it into the **Google AI API Key** input box at the top of the application.  
4. **Select Language**: Choose your preferred language from the dropdown menu.  
5. **Provide Report**: Either paste the text from your report into the text box **OR** click the upload area to select a photo of your report.  
6. **Analyze**: Click the **Analyze** button and wait for the simplified explanation to appear.  

---

## Technologies Used
- **Frontend**: HTML, Tailwind CSS  
- **Logic**: JavaScript  
- **AI Model**: Google Gemini API  

---

## Disclaimer
This tool provides information for **educational purposes only** and is **not a substitute for professional medical advice, diagnosis, or treatment**.  
Always seek the advice of a qualified physician or other health provider with any questions you may have regarding a medical condition.

---

## Contributing
Contributions are welcome.  
If you have ideas for new features, bug fixes, or additional language support, feel free to open an **issue** or submit a **pull request**.

---

## License
This project is licensed under the **MIT License**.
