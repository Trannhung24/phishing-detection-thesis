# phishing-detection-thesis
# Phishing Detection Thesis 🎓

Đồ án tốt nghiệp: Xây dựng hệ thống phát hiện website giả mạo (phishing) dựa trên Machine Learning.

## 🎯 Mục tiêu
- Phân loại URL: **phishing** hoặc **benign** bằng ML (Random Forest).
- Xây dựng API (FastAPI) để nhập URL và trả kết quả.
- Làm giao diện web demo.
- Viết báo cáo + slides + deploy demo.

## 📂 Cấu trúc repo
- `data/`: dữ liệu (raw, processed, external)
- `notebooks/`: EDA + training
- `src/`: code chính (API, features)
- `models/`: model đã train
- `frontend/`: giao diện
- `reports/`: báo cáo, hình vẽ

## ⚡ Cách chạy
```bash
python -m venv venv
source venv/bin/activate    # Linux/Mac
venv\Scripts\activate       # Windows
pip install -r requirements.txt
