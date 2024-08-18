# Detect và Predict Ảnh, Video bằng YOLOv8
Giới thiệu
Dự án này được thực hiện trong khuôn khổ môn học, với mục tiêu sử dụng YOLOv8 để phát hiện các vật thể trong ảnh và video. YOLOv8 là một phiên bản tiên tiến của mô hình YOLO, nổi tiếng về khả năng nhận diện đối tượng thời gian thực. Trong dự án này, tôi đã sử dụng thư viện Ultralytics, triển khai bước đầu là phát hiện đối tượng trên ảnh và video, sau đó đào tạo mô hình với dữ liệu riêng được tạo và tải lên Roboflow. Quá trình này được thực hiện trên Google Colab.
### Nội dung
- Cài đặt
- Sử dụng
- Đào tạo với dữ liệu riêng
- Tham khảo
### Cài đặt
Để chạy dự án này, bạn cần cài đặt các gói cần thiết.
1. `pip install ultralytics`
2. `pip install roboflow`
### Sử dụng
Sau khi cài đặt, bạn có thể bắt đầu phát hiện đối tượng trong ảnh và video:

Detect trên ảnh và video:
### Đào tạo với Dữ liệu riêng
Tôi đã tạo và tải lên bộ dữ liệu riêng trên Roboflow để đào tạo mô hình. Sau khi tải xuống bộ dữ liệu đã chú thích, tôi tiến hành đào tạo lại mô hình YOLOv8 trên Google Colab
