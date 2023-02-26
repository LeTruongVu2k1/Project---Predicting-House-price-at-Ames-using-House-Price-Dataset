# Project---Predicting-House-price-at-Ames-using-House-Price-Dataset

Sử dụng tập dataset từ một cuộc thi trên [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview/description).
Đây là tập dữ liệu chứa tới 79 đặc trưng mô tả (hầu hết) mọi khía cạnh của một ngôi nhà dân dụng, từ đó chúng ta sẽ dự đoán giá cuối cùng của mỗi ngôi nhà ở Ames. 

Các bước thực hiện trong Project:

1. Tìm hiểu về tập dữ liệu thông qua các phân tích về dữ liệu bị thiếu, phân bố của dữ liệu đầu ra và độ tương quan giữa các đặc trưng.
2. Xử lý các dữ liệu bị thiếu.
3. Chuyển các biến hạng mục dưới sạng số sang biến hạng mục, bổ sung thêm biến mới.
4. Mã hoá biến hạng mục sử dụng mã hóa số nguyên.
5. Mã hóa các biến hạng mục còn lại sử dụng mã hóa one-hot.
6. Co dãn và chuẩn hóa các đặc trưng dạng số.
7. Sử dụng mô hình Lasso, phương pháp loại thuộc tính và thêm thuộc tính bằng đệ quy để lựa chọn thuộc tính cho bài toán.
8. Sử dụng các mô hình cơ sở để lựa chọn ra mô hình phù hợp nhất.
9. Tìm kiếm ra các bộ tham số tối ưu cho mô hình phù hợp nhất.
10. Cải tiến các bước từ 2-6 để có một mô hình có độ chính xác cao hơn.
11. Chạy dự đoán trên tập test, sau đó submit kết quả lên Kaggle.
