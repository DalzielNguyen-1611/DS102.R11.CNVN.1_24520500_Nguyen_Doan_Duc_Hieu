<!-- Header / Banner UIT -->
<p align="center">
  <a href="https://www.uit.edu.vn/" title="Trường Đại học Công nghệ Thông tin - ĐHQG TP.HCM" style="border: none;">
    <img src="https://i.imgur.com/WmMnSRt.png" alt="Trường Đại học Công nghệ Thông tin | University of Information Technology" width="650">
  </a>
</p>

<h1 align="center"><b>HỌC MÁY THỐNG KÊ (STATISTICAL MACHINE LEARNING)</b></h1>

<p align="center">
  <i>Kho lưu trữ toàn bộ mã nguồn, tài liệu và quá trình thực hiện bài tập thực hành môn Học máy thống kê</i>
</p>

<p align="center">
  <a href="https://github.com/DalzielNguyen-1611/DS102.R11.CNVN.1_24520500_Nguyen_Doan_Duc_Hieu"><img src="https://img.shields.io/badge/Course-DS102-0077b6?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Course DS102"></a>
  <img src="https://img.shields.io/badge/Semester-HK1%20(2026--2027)-0096c7?style=for-the-badge&logo=clockify&logoColor=white" alt="Semester">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Version">
  <img src="https://img.shields.io/badge/Jupyter-Lab%20%2F%20Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
</p>

---

## 📌 1. THÔNG TIN HỌC PHẦN

| Thuộc tính | Chi tiết |
| :--- | :--- |
| **Tên môn học** | **Học máy thống kê** *(Statistical Machine Learning)* |
| **Mã môn học** | **DS102** |
| **Lớp học phần** | **DS102.R11.CNVN** |
| **Học kỳ / Năm học** | **Học kì 1 — Năm học 2026 - 2027** |
| **Khoa / Trường** | Khoa Khoa học và Kỹ thuật Thông tin — Trường ĐH Công nghệ Thông tin (UIT - ĐHQG-HCM) |

---

## 👨‍🏫 2. GIẢNG VIÊN HƯỚNG DẪN

* **Giảng viên lý thuyết:** ThS. **Lưu Thanh Sơn**
* **Giảng viên thực hành:** ThS. **Nguyễn Hiếu Nghĩa**

---

## 👨‍🎓 3. THÔNG TIN SINH VIÊN

| Họ và Tên | MSSV | Lớp | GitHub | Email |
| :--- | :---: | :---: | :---: | :---: |
| **Nguyễn Doãn Đức Hiếu** | **24520500** | DS102.R11.CNVN | [@DalzielNguyen-1611](https://github.com/DalzielNguyen-1611) | [24520500@gm.uit.edu.vn](mailto:24520500@gm.uit.edu.vn) |

---

## 🎯 4. MỤC TIÊU CỦA REPOSITORY

Repository này được tạo ra nhằm:
1. **Lưu trữ & theo dõi tiến độ:** Quản lý tập trung mã nguồn, bài làm thực hành (Lab assignments) qua từng tuần học của môn Học máy thống kê.
2. **Thực hành thuật toán:** Áp dụng các mô hình học máy (Hồi quy, Phân lớp, Phân cụm, Học sâu, Giảm chiều dữ liệu, ...) trên các bộ dữ liệu thực tế.
3. **Phân tích dữ liệu & Đánh giá mô hình:** Thực hiện khám phá dữ liệu (EDA), tiền xử lý, huấn luyện mô hình, tinh chỉnh siêu tham số và đánh giá hiệu năng (Accuracy, Precision, Recall, F1-score, ROC-AUC, RMSE, MAE, ...).
4. **Làm tài liệu tham khảo:** Hệ thống hóa kiến thức phục vụ cho các kỳ thi và quá trình nghiên cứu sau này.

---

## 📂 5. TIẾN ĐỘ & CẤU TRÚC BÀI THỰC HÀNH

| Bài tập | Nội dung / Chủ đề chính | Thư mục Lab | Các bài thực hành | Trạng thái |
| :---: | :--- | :---: | :---: | :---: |
| **Lab 01** | **Thuật toán Newton-Raphson & Thu thập dữ liệu S&P 500** | [Lab01/](./Lab01/) | [`1`](./Lab01/1/) &bull; [`2`](./Lab01/2/) | ✅ Hoàn thành |
| **Lab 02** | *Nội dung đang được cập nhật* | [Lab02/](./Lab02/) |  | ⏳ Đang cập nhật |
| **Lab 03** | *Nội dung đang được cập nhật* | [Lab03/](./Lab03/) |  | ⏳ Đang cập nhật |
| **Lab 04** | *Nội dung đang được cập nhật* | [Lab04/](./Lab04/) |  | ⏳ Đang cập nhật |
| **Lab 05** | *Nội dung đang được cập nhật* | [Lab05/](./Lab05/) |  | ⏳ Đang cập nhật |

### 🌳 Cấu trúc thư mục

Mỗi bài tập thực hành được phân tách độc lập trong một thư mục con đánh số thứ tự (`1`, `2`,...):

```text
DS102.R11.CNVN.1_24520500_Nguyen_Doan_Duc_Hieu/
├── Lab01/                                  # Bài thực hành số 1
│   ├── 1/                                  # Bài 1: Thuật toán tối ưu Newton-Raphson
│   │   └── Newton-Raphson.ipynb
│   └── 2/                                  # Bài 2: Thu thập và mô tả dữ liệu S&P 500
│       ├── Crawl.ipynb                     # Script cào dữ liệu qua Selenium & API
│       ├── Report.ipynb                    # Báo cáo mô tả thuộc tính dataset S&P 500
│       ├── sp500_yahoo.csv                 # Dữ liệu định dạng CSV
│       ├── sp500_yahoo.tsv                 # Dữ liệu định dạng TSV
│       └── sp500_yahoo.json                # Dữ liệu định dạng JSON
├── Lab02/                   # Bài thực hành số 2
├── Lab03/                   # Bài thực hành số 3
├── Lab04/                   # Bài thực hành số 4
├── Lab05/                   # Bài thực hành số 5
└── README.md                # Tài liệu giới thiệu học phần & môn học
```

### 📝 Chi tiết nội dung thực hiện Lab 01:
* **Bài 1 — [Lab01/1/](./Lab01/1/):** Cài đặt và thực nghiệm thuật toán tối ưu hóa không ràng buộc **Newton-Raphson** (`Newton-Raphson.ipynb`) trên các hàm số đa biến.
* **Bài 2 — [Lab01/2/](./Lab01/2/):**
  * Thu thập dữ liệu lịch sử hàng ngày của chỉ số chứng khoán **S&P 500 (`^GSPC`)** từ Yahoo Finance (`Crawl.ipynb`) giai đoạn từ 30/12/1927 đến nay (24,803 phiên giao dịch).
  * Xuất và lưu trữ đồng thời ở 3 định dạng: CSV, TSV và JSON.
  * Báo cáo mô tả cấu trúc, ý nghĩa các thuộc tính và kiểm tra tính toàn vẹn của bộ dữ liệu (`Report.ipynb`).
