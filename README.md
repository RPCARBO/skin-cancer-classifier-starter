# Zoogle: Skin Cancer Classifier Flask App

A Flask-based web application that leverages a **TensorFlow Lite** model to classify skin cancer types from uploaded images. The app also integrates **Google GenAI** to provide detailed insights about the classified type, making it a useful tool for medical professionals and researchers.

---

## Features
- **Image Upload & Classification**
  - Upload an image of a skin lesion.
  - Classifies the type of skin cancer using a TensorFlow Lite model.

- **Detailed Analysis**
  - Fetches additional information via Google GenAI:
    - Description  
    - Causes  
    - Risk Factors  
    - Prognosis  
    - Treatments  

- **Interactive UI**
  - Built with **Tailwind CSS** for a clean, responsive design.
  - Includes image preview and structured display of results.

- **Cloud & Local Deployment**
  - Run locally or deploy on cloud platforms (e.g., Render).

---

## Usage
1. **Upload an Image**  
   Navigate to the main page and upload a skin lesion image.

2. **View Results**  
   - See the classified cancer type.  
   - Confidence score.  
   - Detailed information from Google GenAI.

3. **Analyze the Details**  
   Review causes, risk factors, prognosis, and treatment options.

---

## Technologies Used
- **Flask** – Lightweight Python web framework  
- **TensorFlow Lite** – Efficient ML model execution  
- **Google GenAI** – Provides detailed medical insights  
- **Tailwind CSS** – Modern, responsive UI design  
- **Pillow** – Image processing  
- **Pydantic** – Data validation and structuring  

---

## Deployment
- **Local**: Run with Flask development server.  
- **Cloud**: Deploy easily on platforms like Render.  

---

## Note
This project is intended for **educational and research purposes**. It should not replace professional medical diagnosis.
