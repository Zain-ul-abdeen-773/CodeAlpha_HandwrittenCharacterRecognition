# CodeAlpha_HandwrittenCharacterRecognition
# 🧠 Handwritten Character Recognition Web App  
**CodeAlpha Internship Task 3 — Machine Learning**

A Flask-based deep learning web application that recognizes handwritten characters (A-Z, a-z, 0–9) using a Convolutional Neural Network (CNN) trained on the EMNIST dataset. The app allows users to draw or upload an image of a handwritten character and receive instant predictions with visual feedback.

---

## 📌 Features

✅ Real-time character recognition  
✅ Web interface with drawing canvas & image upload  
✅ EMNIST dataset support (digits + characters)  
✅ Prediction confidence with bar chart  
✅ Built using Flask, TensorFlow, and OpenCV  
✅ Clean UI with responsive design  

---

## 🗂️ Project Structure

```
CodeAlpha_HandwrittenCharacterRecognition/
│
├── static/             # CSS files
│   └── style.css
│
├── templates/          # HTML templates
│   ├── index.html
│   └── result.html
│
├── model/              # Saved trained CNN model
│   └── emnist_cnn_model.h5
│
├── app.py              # Main Flask application
├── utils.py            # Image preprocessing functions
├── requirements.txt    # Required packages
└── README.md           # Project overview
```


---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Bootstrap, JavaScript (Canvas API)  
- **Backend**: Python, Flask  
- **ML/DL**: TensorFlow/Keras, NumPy, OpenCV  
- **Dataset**: [EMNIST Dataset](https://www.nist.gov/itl/products-and-services/emnist-dataset)  

---

## 📊 Model Info

- **Model Type**: Custom CNN (3 conv layers + dense)
- **Input Shape**: 28x28 grayscale
- **Accuracy**: ~95% on EMNIST test set
- **Training Time**: ~20 mins on GPU

---

## 🧪 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/Zain-ul-abdeen-773/CodeAlpha_HandwrittenCharacterRecognition.git
cd CodeAlpha_HandwrittenCharacterRecognition

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
```

## 🤝 Acknowledgements
Special thanks to CodeAlpha for providing this hands-on opportunity to build and deploy real-world ML applications.

## 📬 Contact
If you liked this project, connect with me on:

LinkedIn: http://www.linkedin.com/in/zain-ul-abdeen-48aa72318

GitHub: https://github.com/Zain-ul-abdeen-773

