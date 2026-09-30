# Báo cáo mô tả Dataset S&P 500

## 1. Giới thiệu Dataset

Dataset được sử dụng là dữ liệu lịch sử của chỉ số S&P 500, được thu thập thông qua Yahoo Finance với mã ^GSPC. Dữ liệu có tần suất hàng ngày (Daily) và được sử dụng làm nguồn dữ liệu thị trường chính cho nghiên cứu về khả năng dự báo lợi suất cổ phiếu.

Dataset bao gồm các thông tin về giá và khối lượng giao dịch của S&P 500 theo từng ngày giao dịch.

## 2. Nguồn dữ liệu

* **Nguồn:** Yahoo Finance
* **Mã dữ liệu:** ^GSPC
* **Tần suất:** Daily
* **Định dạng:** CSV
* **Thời gian:** từ thời điểm sớm nhất có sẵn trong nguồn dữ liệu đến thời điểm thu thập.

## 3. Các thuộc tính của Dataset

| Thuộc tính | Mô tả |
| :--- | :--- |
| Date | Ngày giao dịch của S&P 500 |
| Open | Giá mở cửa trong ngày |
| High | Mức giá cao nhất trong ngày |
| Low | Mức giá thấp nhất trong ngày |
| Close | Giá đóng cửa trong ngày |
| Adj Close | Giá đóng cửa đã điều chỉnh |
| Volume | Khối lượng giao dịch được cung cấp bởi Yahoo Finance |

Các thuộc tính giá (Open, High, Low, Close, Adj Close) được sử dụng để mô tả diễn biến của chỉ số theo thời gian. Volume được giữ lại trong dataset để phục vụ các phân tích bổ sung nếu cần.

## 4. Kiểm tra dữ liệu cơ bản

Dataset được kiểm tra các vấn đề cơ bản gồm:

* Số lượng bản ghi và số lượng thuộc tính.
* Khoảng thời gian của dữ liệu.
* Kiểu dữ liệu của từng thuộc tính.
* Giá trị thiếu (missing values).
* Bản ghi trùng lặp theo Date.
* Các giá trị bất thường trong các trường dữ liệu giá.

Đối với Volume, một số quan sát thuộc các giai đoạn lịch sử rất xa có thể có giá trị bằng 0 hoặc không khả dụng. Các giá trị này không được mặc định xem là khối lượng giao dịch thực tế bằng 0 mà sẽ được xem xét riêng trong bước xử lý dữ liệu nếu Volume được sử dụng trong phân tích.

## 5. Kết luận

Dataset S&P 500 cung cấp dữ liệu lịch sử theo ngày với các thông tin Date, OHLC, Adjusted Close và Volume, đáp ứng yêu cầu dữ liệu thị trường cho nghiên cứu. Dataset sẽ được sử dụng làm cơ sở để thực hiện các bước xử lý dữ liệu và xây dựng bài toán dự báo trong các giai đoạn tiếp theo.
