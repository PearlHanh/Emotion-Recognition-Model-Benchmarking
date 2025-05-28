1. Mô tả dự án
   Nhận diện cảm xúc khuôn mặt là một bài toán quan trọng trong lĩnh vực thị giác máy tính (computer vision) và tương tác người – máy.
   Mục tiêu là phân loại chính xác cảm xúc của con người thông qua biểu cảm khuôn mặt trên ảnh.
   Dự án này được thực hiện nhằm so sánh và đánh giá hiệu quả của các mô hình học máy và học sâu (deep learning) khi áp dụng vào bài toán này.
   Các mô hình được triển khai bao gồm:
   - K-Nearest Neighbors (KNN): Phương pháp học dựa trên ví dụ (instance-based), phân loại ảnh dựa trên số lượng hàng xóm gần nhất trong không gian đặc trưng.
   - Decision Tree: Mô hình dạng cây, hoạt động bằng cách chia nhỏ không gian đặc trưng dựa trên các ngưỡng để đưa ra quyết định.
   - Logistic Regression: Mô hình tuyến tính được dùng như một baseline cho bài toán phân loại cảm xúc đa lớp.
   - Support Vector Machine (SVM): Mô hình phân loại mạnh mẽ với khả năng tìm siêu phẳng tối ưu để phân tách các cảm xúc, hỗ trợ kernel phi tuyến.
   - Convolutional Neural Network (CNN): Mạng nơ-ron tích chập, mô hình học sâu nổi bật trong xử lý ảnh. CNN tự động học các đặc trưng không gian
    từ ảnh đầu vào và thường đạt hiệu suất cao.
2. Mục tiêu của dự án
   So sánh hiệu quả của các mô hình truyền thống và học sâu, đánh giá qua độ chính xác(Accuracy).
