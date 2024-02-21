# BÀI TẬP
Đánh giá mô hình huấn luyện trên tập dữ liệu *churn_modeling.csv* dự đoán khách hàng rời bỏ dịch vụ.

Chia tập dữ liệu train/test với *test_size = 0.2* và *random_state = 42*.

Sử dụng 3 mô hình để huấn luyện và dự đoán:
- Mô hinh 1: luôn luôn dự đoán là 0
- Mô hình 2: Logistic regression
- Mô hình 3: KNN

Các thông số tính toán:
- Accuracy
- Confusion matrix
- Precision, recall, f1
- AUC, ROC (nếu có)