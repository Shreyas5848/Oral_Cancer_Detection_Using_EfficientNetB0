# 🦷 Oral Cancer Detection Using Deep Learning

A web-based deep learning application for early detection of **oral cancer** using image classification. This tool allows users to upload oral cavity images and instantly receive predictions — **Benign** or **Malignant** — using a trained deep learning model. It aims to support cancer awareness, preliminary screening, and early intervention.

> ⚠️ **Disclaimer:** This is not a diagnostic tool. It is intended for educational and research purposes only. Always consult medical professionals for clinical advice.

---

## 🚀 Features

- Upload oral cavity images via an intuitive UI.
- Predicts "Benign" or "Malignant" using a CNN / **EfficientNetB0** model.
- Lightweight Flask backend with real-time inference.
- Preprocessing and training notebooks included.
- Uses class weighting to address data imbalance.
- Includes demo images for UI (from Unsplash and Pexels).
- Gives accuracy of **98%.**

---

## 🧠 Tech Stack

| Component   | Technology             |
|-------------|------------------------|
| Frontend    | Streamlit  |
| Backend     | Python     |
| Model       | TensorFlow, Keras (EfficientNetB0) |
| Deployment  | Localhost / (Optional: Render, Streamlit, Hugging Face Spaces) |
| Dataset     | Curated dataset of oral lesion images |

---

Install Dependencies
Make sure you have Python 3.8+ and pip installed.
pip install -r requirements.txt



📊 Model Training

The model is trained using a CNN and/or EfficientNetB0.
Class weights are used to address class imbalance.
You can retrain using the train_model.ipynb notebook with your own dataset.

🧪 Future Enhancements

Add user authentication and upload history.
Improve dataset diversity and quality.
Include heatmaps or Grad-CAM for model interpretability.
Deploy on cloud (Render, Hugging Face Spaces, or Streamlit Cloud).

