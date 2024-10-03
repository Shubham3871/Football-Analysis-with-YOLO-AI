# Football Analysis with YOLO AI

A deep learning project for real-time football detection using YOLOv8l model trained on a custom Roboflow dataset.

## 🎯 Project Overview

1 month ago I saw this awesome match between Manchester City and Manchester United and then decided why not to convert it into a project. This inspired me to create a football detection system that can automatically track and detect footballs in match footage.

This project implements a football detection system using the YOLOv8 large model. It can detect footballs in images and videos with high accuracy, making it suitable for sports analysis, game tracking, and related applications.

## 🚀 Features

- Real-time football detection
- Built with YOLOv8l architecture
- Trained on custom Roboflow football dataset
- Supports both image and video inference
- Easy-to-use inference pipeline

## 📹 Demo Video
Check out the demo video of the football detection system [here](training-vid-ai.mp4).


## 📋 Prerequisites

- Python 3.8+
- PyTorch
- Ultralytics
- CUDA (optional, for GPU acceleration)

```bash
pip install -r requirements.txt
```

## 💻 Installation

1. Clone the repository:
```bash
git clone https://github.com/Shubham3871/Football-Analysis-with-YOLO-AI.git
cd Football-Analysis-with-YOLO-AI
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Download the trained weights (if not training from scratch):
```bash
# Add instructions for downloading weights
```

## 🎓 Training

1. Prepare your dataset using Roboflow
2. Configure the training parameters in `config.yaml`
3. Run the training script:
```python
python train.py
```

## 🎮 Usage

### For Image Detection:
```python
from ultralytics import YOLO

# Load the model
model = YOLO('path/to/weights.pt')

# Perform detection
results = model('path/to/image.jpg')
```

### For Video Detection:
```python
from ultralytics import YOLO

# Load the model
model = YOLO('path/to/weights.pt')

# Perform detection
results = model('path/to/video.mp4')
```

## 📊 Model Performance

- mAP50: [Add your metric]
- mAP50-95: [Add your metric]
- Inference Speed: [Add speed]

## 📁 Project Structure

```
Football-Analysis-with-YOLO-AI/
├── data/
│   ├── train/
│   ├── val/
│   └── test/
├── models/
│   └── weights/
├── config/
│   └── config.yaml
├── src/
│   ├── train.py
│   └── detect.py
├── requirements.txt
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Ultralytics for YOLOv8
- Roboflow for dataset management
- [Add other acknowledgments]

## 📧 Contact

Shubham - shubhamgaikwad9054@gmail.com

Project Link: [https://github.com/Shubham3871/Football-Analysis-with-YOLO-AI](https://github.com/Shubham3871/Football-Analysis-with-YOLO-AI)
