# Optimized QR Code Recognition in Retail Stores Using YOLOv7 and Cuckoo Search Algorithm

## Project Overview
This project focuses on enhancing **QR code recognition in retail environments** by integrating **YOLOv7** (a state-of-the-art object detection model) with the **Cuckoo Search Optimization algorithm** for improved detection and efficiency. The solution aims to optimize recognition speed and accuracy, making it suitable for real-time applications in retail and inventory management.

---

## Key Features
- **YOLOv7-based QR Code Detection**: Utilized for fast and accurate object detection.
- **Cuckoo Search Optimization**: Applied to fine-tune detection parameters and improve performance.
- **Optimized for Retail Use**: Handles real-world challenges like varying lighting, rotation, and occlusion.
- **Visualization & Analytics**: Includes performance metrics, plots, and detection results.

---

## Tech Stack
- **Language**: Python 3.x
- **Libraries**: 
  - YOLOv7
  - OpenCV (`cv2`)
  - NumPy, Pandas
  - Matplotlib, Seaborn
  - Pillow
  - Pyzbar
  - Weights & Biases (for experiment tracking)
- **Algorithms**:
  - YOLOv7 Object Detection
  - Cuckoo Search Algorithm for optimization

---

## Project Structure
```
├── optimized-qr-code-recognition-in-retail-stores.ipynb  # Main Kaggle notebook
├── requirements.txt                                       # Dependencies
├── README.md                                              # Project documentation
└── results/                                               # Detection results & visualizations
```

---

## Installation & Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/Ishita200420/qr-code-recognition-yolov7-cuckoo.git
   cd qr-code-recognition-yolov7-cuckoo
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook optimized-qr-code-recognition-in-retail-stores.ipynb
   ```
2. Follow the steps in the notebook to:
   - Load the dataset or your own dataset
   - Run YOLOv7 detection
   - Apply Cuckoo Search Optimization
   - View performance metrics and visualizations

---

## Results
- **Detection Accuracy**: Optimized using Cuckoo Search
- **Improved Speed**: Faster recognition for retail scenarios
- **Visual Outputs**: Includes detection bounding boxes and performance graphs

<img width="829" height="330" alt="image" src="https://github.com/user-attachments/assets/bda4aed4-f813-47b8-af41-8ea635d53f39" />

<img width="462" height="208" alt="image" src="https://github.com/user-attachments/assets/73596d53-b2ad-41a8-a704-f47d3aa5083e" />

<img width="1041" height="437" alt="image" src="https://github.com/user-attachments/assets/47b35bfb-2660-42e1-afd2-cab27b2dacb8" />

---

## Future Enhancements
- Integrate with a real-time retail POS system.
- Extend optimization to multi-object scenarios.
- Deploy as a web-based or mobile application.

---

## Dataset & References
- Kaggle Notebook: Link to Kaggle project: (https://www.kaggle.com/code/ishita200420/optimized-qr-code-recognition-in-retail-stores)
- [YOLOv7 Official GitHub](https://github.com/WongKinYiu/yolov7)
- Research on **Cuckoo Search Algorithm**

---

## Authors
- **Ishita Rana: **
  LinkedIn Profile: www.linkedin.com/in/ishita-rana-03651b305
- **Leena: **
  LinkedIn Profile: www.linkedin.com/in/leenabansal1108
