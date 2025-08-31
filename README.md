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
└── results/                                               # (Optional) Detection results & visualizations
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
   - Load the dataset (or your own images)
   - Run YOLOv7 detection
   - Apply Cuckoo Search Optimization
   - View performance metrics and visualizations

---

## Results
- **Detection Accuracy**: Optimized using Cuckoo Search
- **Improved Speed**: Faster recognition for retail scenarios
- **Visual Outputs**: Includes detection bounding boxes and performance graphs

*(Add screenshots or sample results here)*

---

## Future Enhancements
- Integrate with a real-time retail POS system.
- Extend optimization to multi-object scenarios.
- Deploy as a web-based or mobile application.

---

## Dataset & References
- Kaggle Notebook: [Link to Kaggle project](#) *(Replace with your actual Kaggle link)*
- [YOLOv7 Official GitHub](https://github.com/WongKinYiu/yolov7)
- Research on **Cuckoo Search Algorithm**

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Authors
**Ishita Rana**  
LinkedIn Profile: www.linkedin.com/in/ishita-rana-03651b305
**Leena**
LinkedIn Profile: www.linkedin.com/in/leenabansal1108
