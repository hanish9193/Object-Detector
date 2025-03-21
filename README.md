# 🚀 YOLOv5 Object Detector

An advanced **object detection** system built using the **YOLOv5** model. This project can identify and classify objects in images and videos with high accuracy and real-time performance.

## 📷 Features

- 🟢 **Pre-trained YOLOv5 Model** for fast and accurate detection
- 📊 Supports detection in **images**, **videos**, and **live streams**
- 🧰 **Customizable** for training on new datasets
- 📈 Outputs detection results with **bounding boxes** and **confidence scores**
- 🏎️ **Optimized for speed** and works on both **CPU** and **GPU**

## 📂 Project Structure

```
├── data/              # Dataset and input files
├── models/            # YOLOv5 model configuration
├── runs/              # Output folder for detections
├── detect.py          # Main detection script
├── train.py           # Model training script
└── README.md          # Project documentation
```

## 🔧 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/hanish9193/Object-Detector.git
cd Object-Detector
```

2. **Set up a virtual environment (optional but recommended):**

```bash
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate     # For Windows
```

3. **Install required packages:**

```bash
pip install -r requirements.txt
```

## ▶️ Usage

### 1. Run Object Detection on Images

```bash
python detect.py --source path/to/image.jpg --weights yolov5s.pt
```

### 2. Run Object Detection on Videos

```bash
python detect.py --source path/to/video.mp4 --weights yolov5s.pt
```

### 3. Real-Time Detection (Webcam)

```bash
python detect.py --source 0 --weights yolov5s.pt
```

## 📊 Training Your Own Model

1. Prepare your dataset following the YOLO format.
2. Use the `train.py` script:

```bash
python train.py --data custom_dataset.yaml --epochs 50 --weights yolov5s.pt
```

## 📜 Requirements

- Python 3.8+
- PyTorch
- OpenCV
- YOLOv5

## 📌 Example Output

![Detection Output](./output/Screenshot%202025-03-21%20220032.png)


## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the **AGPL-3.0 License**.

## 📬 Contact

If you have any questions or issues, reach out via [GitHub Issues](https://github.com/hanish9193/Object-Detector/issues).

