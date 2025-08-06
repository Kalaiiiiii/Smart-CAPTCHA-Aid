🧠 Smart-CAPTCHA-Aid
Development of an AI-Based OCR Tool for Reading CAPTCHA Challenges Aloud to Visually Impaired Users

📖 Introduction
CAPTCHAs are widely used as a security mechanism to differentiate between humans and automated bots on websites. However, these visual challenges present a significant accessibility barrier for visually impaired users.
**Smart-CAPTCHA-Aid** is a machine learning-based solution that solves text-based CAPTCHAs and reads them aloud, promoting digital inclusion and accessibility.

---

## 🎯 Objective

To build a Convolutional Neural Network (CNN)-based Optical Character Recognition (OCR) system that can:

* Identify and decode text from CAPTCHA images.
* Convert the recognized text into speech using TTS.
* Be used in accessibility tools such as screen readers.

---

## 🚧 Problem Statement

* CAPTCHAs are inherently visual and exclude visually impaired users.
* Existing audio CAPTCHAs are limited, unclear, or not universally available.
* There's a lack of inclusive design in current CAPTCHA systems.

---

## 💡 Proposed Solution

Smart-CAPTCHA-Aid provides an AI/ML-based assistive tool that:

* Takes a CAPTCHA image as input.
* Uses a trained CNN model to predict the alphanumeric string.
* Converts the result into spoken output using a text-to-speech engine.
* Can be used alongside screen readers for enhanced accessibility.

---

## 🔧 Tech Stack

| Category             | Tools / Libraries            |
| -------------------- | ---------------------------- |
| Language             | Python 3.11                  |
| ML/DL Framework      | TensorFlow, Keras            |
| Image Processing     | OpenCV                       |
| Visualization        | Matplotlib                   |
| Data Handling        | NumPy, scikit-learn          |
| Text-to-Speech       | gTTS (Google Text-to-Speech) |
| Interface (Optional) | Gradio                       |
| Platform             | Google Colab                 |

---

## 📂 Project Structure

```
Smart-CAPTCHA-Aid/
├── notebook.ipynb              # Full development notebook
├── captcha_model.h5            # Trained CNN model
├── archive.zip                 # Dataset of CAPTCHA images (with samples/)
├── app.py                      # Optional Gradio interface for deployment
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

---

## ⚙️ How to Use

### ✅ Using Google Colab

1. Upload the files: `notebook.ipynb`, `archive.zip`, etc.
2. Unzip the dataset: `archive.zip` (contains `samples/` folder with images).
3. Run the notebook:

   * Preprocess data
   * Train or load the CNN model
   * Predict on sample CAPTCHA images
   * Convert text output to speech using `gTTS`

### ✅ Optional: Launch Gradio Web Interface

```python
gr.Interface(fn=predict_captcha, inputs="image", outputs="text").launch()
```

---

## 🧪 Sample Output

| Input CAPTCHA                 | Predicted Text | Spoken Output    |
| ----------------------------- | -------------- | ---------------- |
| ![captcha](images/sample.png) | `A9B7C`        | 🔊 *"A 9 B 7 C"* |

> *Note: Replace the image and output as per your results.*

---

## 🌍 SDG Alignment

### 🎯 UN Sustainable Development Goal 10: **Reduced Inequalities**

This project addresses digital inequality by enabling visually impaired users to independently solve CAPTCHAs, improving access to essential online services.

---

## 📈 Future Scope

* Support for more distorted and complex CAPTCHA types.
* Integration with browser extensions and assistive tools.
* Support for audio CAPTCHA and handwriting CAPTCHA.
* Mobile app version for real-time use.

---

## 📄 License

This project is licensed under the **MIT License**.
Feel free to use, modify, and distribute with attribution.

---

## 👤 Author

**Aleena K.**
*Electronics & Communication Engineering Student*
[GitHub](https://github.com/yourusername) • [LinkedIn](https://linkedin.com/in/yourprofile)
*(Add your actual links here)*

---

Let me know if you'd like:

* A `requirements.txt` generated
* `app.py` for Gradio/Hugging Face deployment
* Help making a GitHub repo structure or zip

Want me to prepare this in markdown file format for you?
