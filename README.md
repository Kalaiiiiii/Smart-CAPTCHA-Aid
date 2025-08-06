## 🧠 Smart-CAPTCHA-Aid
Development of an AI-Based OCR Tool for Reading CAPTCHA Challenges Aloud to Visually Impaired Users

## 📖 Introduction
CAPTCHAs are widely used as a security mechanism to differentiate between humans and automated bots on websites. However, these visual challenges present a significant accessibility barrier for visually impaired users.
**Smart-CAPTCHA-Aid** is a machine learning-based solution that solves text-based CAPTCHAs and reads them aloud, promoting digital inclusion and accessibility.

## 🎯 Objective
To build a Convolutional Neural Network (CNN)-based Optical Character Recognition (OCR) system that can:
* Identify and decode text from CAPTCHA images.
* Convert the recognized text into speech using TTS.
* Be used in accessibility tools such as screen readers.

## 🚧 Problem Statement
* CAPTCHAs are inherently visual and exclude visually impaired users.
* Existing audio CAPTCHAs are limited, unclear, or not universally available.
* There's a lack of inclusive design in current CAPTCHA systems.

## 💡 Proposed Solution
Smart-CAPTCHA-Aid provides an AI/ML-based assistive tool that:
* Takes a CAPTCHA image as input.
* Uses a trained CNN model to predict the alphanumeric string.
* Converts the result into spoken output using a text-to-speech engine.
* Can be used alongside screen readers for enhanced accessibility.

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

## 🌍 SDG Alignment
### 🎯 UN Sustainable Development Goal 10: **Reduced Inequalities**
This project addresses digital inequality by enabling visually impaired users to independently solve CAPTCHAs, improving access to essential online services.

## 📈 Future Scope
* Support for more distorted and complex CAPTCHA types.
* Integration with browser extensions and assistive tools.
* Support for audio CAPTCHA and handwriting CAPTCHA.
* Mobile app version for real-time use.

## 📄 License
Feel free to use, modify, and distribute with attribution.

