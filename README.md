# 🪙 Coin Detection API

A Flask-based REST API that uses a YOLOv8 deep learning model to detect Indian coins (₹1, ₹2, ₹5, ₹10, ₹20) in uploaded images. The API returns the count and total value of detected coins.

---

## 📦 Features

- Upload an image and get detected coin names
- Returns total value of coins in Indian Rupees
- Uses YOLOv8 via `ultralytics` for object detection
- Supports RESTful API integration

---

## 🛠️ Requirements

### Python Packages

Install dependencies via `pip`:

```bash
pip install -r requirements.txt
