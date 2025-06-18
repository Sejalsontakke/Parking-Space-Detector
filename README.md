# Smart-Parking-Space-Detector 🚗📸

## Overview

In urban areas, inefficient monitoring of parking spaces leads to traffic congestion, fuel wastage, and user frustration. Traditional systems often rely on manual supervision or expensive hardware-based infrastructure. This project presents a **low-cost, AI-based solution** that utilizes **Convolutional Neural Networks (CNNs)** to automatically detect and classify parking space images as **Occupied** or **Empty** using visual data.

The system is integrated into a **web application** to provide real-time parking status updates, aiming to support **smart city infrastructure** with scalable and accessible technology.

---

## 🔍 Features

- Detects parking space occupancy from camera images using CNN
- Real-time prediction using a lightweight web application
- Scalable and cost-effective for urban deployment
- No hardware dependency (camera-only setup)
- User-friendly interface for monitoring available parking slots

---

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- Streamlit (for the web interface)
- NumPy & Matplotlib (for data handling and visualization)

---

## 📂 Dataset

The dataset contains images of parking slots labeled as either `Empty` or `Occupied`. It is structured as follows:

Dataset/
│
├── train/
│ ├── empty/
│ └── occupied/
│
├── test/
│ ├── empty/
│ └── occupied/


> 📌 **Note**: The dataset will be provided separately and must be placed in the `Dataset/` directory before running the model.

---

## 🚀 How to Run the Project

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/smart-parking-utilization-system.git
cd smart-parking-utilization-system
2. **Install Dependencies
pip install -r requirements.txt

3. Place the dataset
Place the provided dataset inside the Dataset/ folder in the specified format.

4.Train the CNN model
python train_model.py

5.Run the web application
streamlit run app.py

 Future Enhancements
Integration with real-time CCTV feeds

GPS mapping of available parking slots

Deployment on edge devices for in-ground smart sensors

Notification system for drivers

🤝 Contributions
Contributions, suggestions, and improvements are welcome! Feel free to fork the repo and submit a pull request.


---

Let me know if you'd like to include any screenshots, model architecture diagram, or dataset source info in the README as well!



