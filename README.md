
# Fake News Detection System

An advanced Fake News Detection System that uses machine learning to classify news articles as real or fake. The application is built with Flask and deployed on Heroku. The model achieves an accuracy of 92.6% on a balanced dataset, providing a reliable and engaging user interface to make text classification accessible to everyone.

---

## 📋 Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Project Structure](#project-structure)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🌟 Features

- **Real-time News Classification**: Detects whether a news article is real or fake.
- **Engaging Interface**: Dynamic visual feedback, with color-coded stamps for quick identification.
- **Mobile & Desktop Support**: Responsive design tailored for both desktop and mobile experiences.
- **High Accuracy Model**: Powered by an XGBoost model trained with a 95k dataset, achieving a 92.6% accuracy.

---

## 🚀 Installation

### Prerequisites

- Python 3.7 or higher
- Virtual Environment (recommended)
- Flask and other dependencies (specified in `requirements.txt`)

### Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/fake-news-detection.git
   cd fake-news-detection

2.Create a Virtual Environment:
   python3 -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`

3.Install Dependencies:
    pip install -r requirements.txt

4.Run the Application:
 python app.py


 📊 Model Details
--- 
-The application uses an XGBoost model, pre-trained on a dataset with 95,000 samples. Data preprocessing includes:

-Stop word removal, stemming, and lemmatization
-Text tokenization via CountVectorizer

📂 Project Structure-
---
fake-news-detection/
│
├── app.py                  # Flask backend code <br>
├── model_pipeline.pkl      # Pre-trained model pipeline for fast predictions <br>
├── templates/
│   └── index.html          # Main frontend HTML template <br>
├── static/
│   └── style.css           # Custom CSS for styling <br>
├── Procfile                # Heroku configuration <br>
├── requirements.txt        # Python dependencies <br>
├── LICENSE                 # License information <br>
└── README.md               # Project documentation <br>


🌐 Deployment on Heroku-<br>
---
-heroku login <br>
-heroku create fake-news-detection <br>
-git push heroku main <br>
-heroku open <br>


🤝 Contributing <br>
---
Contributions are welcome! Feel free to submit a PR or open an issue for any bug fixes, enhancements, or additional features.<br>

📜 License <br>
---
This project is licensed under the MIT License. See the LICENSE file for details.<br>

📞 Contact  <br>
---
For any questions or feedback, please contact [mfizakhan05@gmail.com].<br>




