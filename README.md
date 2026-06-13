# AI-Powered Intrusion Detection System

## Overview

The AI-Powered Intrusion Detection System (IDS) is a Machine Learning-based cybersecurity project designed to detect malicious network traffic and classify potential attacks using the NSL-KDD dataset.

The system trains a Random Forest model on network traffic data and exposes prediction capabilities through a FastAPI backend. A simple web interface enables users to test network traffic samples and receive intrusion detection results in real time.

---

## Features

- Intrusion detection using Machine Learning
- Random Forest classification model
- FastAPI REST API backend
- NSL-KDD dataset integration
- Real-time traffic prediction
- Web-based user interface
- JSON-based API testing support

---

## Technologies Used

- Python
- FastAPI
- Scikit-learn
- Pandas
- NumPy
- Joblib
- HTML
- CSS
- JavaScript

---

## Project Structure

```text
AI-Intrusion-Detection-System/
│
├── BACKEND/
│   ├── main.py
│   ├── train.py
│   └── sample.json
│
├── DATASET/
│   └── nsl-kdd.csv
│
├── index.html
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Dataset

This project uses the NSL-KDD dataset, a widely used benchmark dataset for intrusion detection research and machine learning-based cybersecurity applications.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/Swasti30-coding/AI-Intrusion-Detection-System.git
cd AI-Intrusion-Detection-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Train the Model

```bash
python BACKEND/train.py
```

This command trains the Random Forest model and generates the model file required for prediction.

---

## Run the API Server

```bash
uvicorn BACKEND.main:app --reload
```

The API will start locally and can be accessed through FastAPI endpoints.

---

## Usage

1. Train the model using `train.py`.
2. Start the FastAPI server.
3. Open `index.html` in your browser.
4. Enter network traffic feature values.
5. Receive predictions indicating normal or malicious traffic.

---

## Future Enhancements

- Real-time packet capture integration
- Deep Learning-based attack detection
- Interactive analytics dashboard
- SIEM integration
- Cloud deployment support
- Threat intelligence integration

---

## Learning Outcomes

- Machine Learning for Cybersecurity
- Network Intrusion Detection
- API Development with FastAPI
- Data Preprocessing and Feature Engineering
- Model Training and Deployment

---

## Author

**Swastisikha Pradhan**  
B.Tech CSE (Cyber Security)  
ITER, SOA University

GitHub: https://github.com/Swasti30-coding

---

## License

This project is licensed under the MIT License.

See the LICENSE file for details.