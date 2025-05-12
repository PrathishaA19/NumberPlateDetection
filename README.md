
# 🚗 Automatic License Plate Detection and Recognition

This project detects and recognizes license plates from images and videos using **YOLO-free contour detection** for localization and **EasyOCR** for text recognition. Designed for real-time or batch processing, it runs seamlessly in environments like **Google Colab** or **locally** on your machine.

---

## 📸 Features

* 📷 **Supports both image and video input**
* 🎯 **License plate localization** using OpenCV contour detection (no YOLO needed)
* 🔤 **Text recognition** using EasyOCR
* ⏱️ **Real-time video processing** with optional frame skipping for better performance
* 🧾 **Annotated output** with bounding boxes and overlaid license plate numbers

---

## 🛠️ Tech Stack

* Python 3.x
* OpenCV
* EasyOCR
* NumPy
* imutils
* Google Colab *(optional for cloud execution)*

---

## 🧑‍💻 How to Run

### ✅ Google Colab (Recommended)

1. Open the provided Colab notebook.
2. Upload your **image** or **video** when prompted.
3. The system will display and provide a **download link** for the annotated output.

### 🖥️ Local Setup

1. Ensure **Python 3.x** is installed.
2. Install required dependencies:

```bash
pip install opencv-python easyocr imutils numpy
```

3. *(Optional: for GPU acceleration with EasyOCR)*

```bash
pip install torch torchvision torchaudio
```

4. Run the script:

```bash
python main.py
```

---

## 🧾 Output

* Detected license plates are highlighted with **bounding boxes**.
* **Recognized text** (license number) is overlaid directly on the image or video frame.

---

## 🖼️ Sample Output

```
[✓] Detected Plate: MH12AB1234
[✓] Saved output: annotated_video.mp4
```

> Output is saved as an image or video with license plate annotations.

---

