# 🧠 AI-Powered X-Ray Baggage Screening System

This project explores how artificial intelligence can enhance airport security by improving X-ray baggage screening. It compares the performance of three object detection models—YOLOv2, Faster R-CNN, and CNN+SVM—on both real and synthetically augmented X-ray images. The goal is to detect threats such as knives, guns, scissors, wrenches, and liquids with high accuracy and speed.

## 🚀 Features
- Real-time object detection with YOLOv2
- Performance comparison between YOLOv2, Faster R-CNN, and CNN+SVM
- Use of synthetic data via PNG overlay to overcome data scarcity
- High detection accuracy (YOLOv2 achieved 99.5% mAP)
- GDPR-compliant approach using public and generated datasets

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- OpenCV
- NumPy & Matplotlib

## 📂 Project Structure
```
├── models/                 # Model scripts and saved weights
├── data/                   # Real and synthetic X-ray images
├── notebooks/              # Jupyter notebooks for experiments
├── results/                # Output images, metrics, and visualizations
├── utils/                  # Helper functions and scripts
├── README.md
└── requirements.txt
```

## 📊 Results Summary
- **YOLOv2**: 99.5% mAP, 100% recall, 20ms/image inference
- **CNN+SVM**: 60% accuracy on binary classification (harmful vs safe)
- **Faster R-CNN**: 55% accuracy, slower inference, struggles with clutter

## 🧪 Dataset
- Public datasets used: **GDXray** and **SIXray**
- Synthetic images generated using PNG overlays of hazardous items
- Augmentation includes rotation, scaling, and contrast adjustments to simulate real-world baggage conditions

## ▶️ Getting Started
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/ai-xray-baggage-screening.git
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Train or run inference using the scripts in `models/` or `notebooks/`.

## 📌 Key Insights
- YOLOv2 is best suited for real-time airport deployment due to its speed and accuracy.
- Synthetic data can effectively supplement training where real X-ray data is limited.
- AI can reduce manual workload, cut false positives, and improve passenger screening time.

## 📜 License
This project is developed for academic and non-commercial research use only.

## 🙌 Acknowledgments
This work was submitted as part of the MSc Data Science program at Cardiff Metropolitan University. Special thanks to all academic mentors and contributors who supported the project.

## 📫 Contact
**Deepak Arumugam Vivekanandan**  
📧 deep199907@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/deepakv1e7d6/)
