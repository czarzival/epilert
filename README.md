# Epilert

Epilert is a smart system designed to help detect and monitor epileptic seizures.
It uses AI models to analyze EMG signals and send alerts in real time.

---

## 🔍 Features

* Detects seizures from EMG data using a CNN model
* Provides real-time alerts and tracking
* Visualizes EEG activity and reports
* Works with wearable EMG sensors
* Simple interface for doctors and patients

---

## ⚙️ Tech Stack

* **Python (PyTorch, OpenCV, Pandas)** — for model training and analysis
* **React JS / Tailwind CSS** — for frontend interface
* **Firebase** — for authentication and data storage
* **Flask / FastAPI** — for backend APIs

---

## 🚀 Setup

1. Clone the repo

   ```bash
   git clone https://github.com/czarzival/epilert.git
   cd epilert
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Run the app

   ```bash
   python app.py
   ```

4. (Optional) Start the React frontend

   ```bash
   cd client
   npm install
   npm start
   ```

---

## 📊 Model Overview

The CNN model classifies EMG signal patterns as **seizure** or **normal**.
It uses convolutional layers, batch normalization, and dropout for stable training.
Predictions are stored and displayed on the dashboard.

---

## 📷 Screenshots

 ![Screenshot_2025-03-26_11-42-01](https://github.com/user-attachments/assets/e868bf2e-fc3b-4794-8187-de07dae595b3)
 ![Screenshot_2025-03-26_11-42-53](https://github.com/user-attachments/assets/16845e30-5b0f-4c4e-8a93-8792d2048dec)
![Screenshot_2025-03-26_11-42-32](https://github.com/user-attachments/assets/2452fd8a-c9e7-4922-8265-1e53d8dc074c)
