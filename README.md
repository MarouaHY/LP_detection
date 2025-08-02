# 🚗 License Plate Detection and Recognition

This project is part of my final graduation thesis focused on building an **intelligent airport parking system**. The system integrates deep learning models for:

- License plate detection (YOLOv11, YOLOv12)
- Character recognition (CNN, EasyOCR, PaddleOCR)
- Parking space detection

---

## 📂 Repository Structure

| File/Folder                       | Description |
|----------------------------------|-------------|
| `YOLO11.ipynb`                   | YOLOv11 implementation for license plate detection |
| `YOLO12.ipynb`                   | YOLOv12 implementation for improved plate detection |
| `cnn_for_char_recognition.ipynb` | CNN model for license plate character recognition |
| `combined_models.ipynb`          | End-to-end model combining detection + recognition |
| `paddleocr_cer_wer.ipynb`        | PaddleOCR with CER/WER evaluation |
| `LP_detection_recognition.ipynb` | Complete license plate pipeline |
| `graphics_.ipynb`                | Visualizations and plotting metrics |
| `parking_spot.ipynb`             | Detect empty/occupied parking spaces |
| `train_yolo_parking_spot.ipynb`  | Training YOLO model for parking spot detection |
| `YOLO11--result/`                | Detection results using YOLOv11 |
| `models/yolo11m/`                | Custom-trained YOLOv11m weights and configuration |
| `README.md`                      | Project description (you’re reading it!) |

---

## 🧠 Models Used

| Task | Model | Notes |
|------|-------|-------|
| License Plate Detection | YOLOv11, YOLOv12 | Trained on custom dataset |
| Character Recognition | CNN, PaddleOCR, EasyOCR | Compared accuracy & CER/WER |
| Parking Spot Detection | YOLOv11 variant | For managing real-time parking |

---

## 🎯 Objectives

- Detect vehicle license plates in real-time from images or video.
- Recognize plate characters using OCR techniques.
- Detect available parking spots using object detection.

---

## 🚀 Technologies

- Python
- YOLOv11 & YOLOv12 (Ultralytics-based)
- OpenCV
- PaddleOCR / EasyOCR
- Google Colab
- Matplotlib / Seaborn (for graphics)

---

## 🧪 Example Output

- Bounding boxes around detected license plates
- Recognized text from plate (with confidence scores)
- Parking spot status (available/occupied)
- CER/WER charts for OCR evaluation

---

## 📈 Evaluation Metrics

- **Detection Accuracy**
- **OCR Accuracy**
- **Character Error Rate (CER)**
- **Word Error Rate (WER)**

---

## 📝 How to Run

> **Note:** This repo is based on Jupyter notebooks trained and tested in Google Colab. You can open and run any notebook directly in Colab.

1. Clone the repo
2. Upload it to Google Colab
3. Run individual notebooks for:
   - Plate Detection (`YOLO11.ipynb`)
   - Character Recognition (`cnn_for_char_recognition.ipynb`)
   - Parking Detection (`parking_spot.ipynb`)

---
