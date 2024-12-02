# README

# **ContrastiveBert_Stock_Sentiment_Analysis**

Ứng dụng mô hình BERT và kỹ thuật Contrastive Learning để giải quyết bài toán Stock Sentiment Analysis. Mục tiêu đặt ra là phân tích cảm xúc từ các bình luận về thị trường chứng khoán dựa trên 2 nhãn bullish (~positive), bearish (~negative) và 12 nhãn cảm xúc ambiguous, amusement, anger, anxiety, belief, confusion, depression, disgust, excitement, optimism, panic, surprise. Trong đó, mô hình đạt độ chính xác trung bình 79.4% với dự đoán 2 nhãn và 40% với dự đoán 12 nhãn trên tập dữ liệu StockEmotions.

Dataset: https://github.com/adlnlp/StockEmotions

Repo này cung cấp mã nguồn các mô hình cùng với tập dữ liệu cần thiết để tái tạo kết quả và áp dụng vào các ứng dụng phân tích cảm xúc từ các bình luận về thị trường chứng khoán thực tế.

## **Dependencies and Installation**

```bash
git clone https://github.com/bangils37/ContrastiveBert_Stock_Sentiment_Analysis
cd ContrastiveBert_Stock_Sentiment_Analysis
```

### 1. Cài đặt Python

Đảm bảo rằng bạn đã cài đặt **Python 3.8** trở lên (Đề xuất [Anaconda](https://www.anaconda.com/download/#linux) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)). Bạn có thể kiểm tra phiên bản hiện tại bằng lệnh:

```bash
python --version
```

### 2. Thiết lập môi trường ảo (khuyến nghị)

Tạo môi trường ảo để quản lý các gói cài đặt:

```bash
python -m venv venv
source venv/bin/activate  # Trên macOS/Linux
venv\Scripts\activate     # Trên Windows
```

### 3. Cài đặt các thư viện

Chạy lệnh sau để cài đặt tất cả các thư viện cần thiết:

```bash
pip install -r requirements.txt
```

## Run

Để chạy mã trong tệp **`.ipynb`**, bạn có thể sử dụng **Jupyter Notebook**. Nếu bạn chưa cài đặt Jupyter Notebook, bạn có thể cài đặt nó bằng lệnh:

```bash
pip install notebook
```

Sau đó, bạn có thể chạy Jupyter Notebook bằng cách sử dụng lệnh:

```bash
jupyter notebook
```

Sau khi Jupyter Notebook đã mở, bạn có thể tìm tệp **`.ipynb`** muốn chạy và mở nó. Bạn chỉ cần nhấn **Shift + Enter** để chạy từng ô mã trong notebook.
