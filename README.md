# Mô tả dự án
- Nghiên cứu và triển khai bài toán image segmentation trong thị giác máy tính nhằm phân đoạn vùng tổn thương trên ảnh y tế.
- Thực hiện data exploration và kiểm tra chất lượng dữ liệu: phát hiện nhãn sai, kiểm tra trùng lặp giữa tập train/test, phân tích phân phối dữ liệu.
- Thiết kế data preprocessing pipeline cho dữ liệu ảnh và mask phục vụ huấn luyện mô hình deep learning.
- Huấn luyện các mô hình CNN-based segmentation gồm U-Net và FCN-ResNet34 bằng Python.
- Theo dõi quá trình huấn luyện thông qua training history (loss, accuracy) và trực quan hóa kết quả mô hình.
- Đánh giá hiệu suất mô hình bằng các chỉ số IoU, Dice Score, Pixel Accuracy trên tập test.
- So sánh hiệu quả giữa các kiến trúc deep learning để lựa chọn mô hình tối ưu cho bài toán phân đoạn ảnh.
- Trực quan hóa kết quả dự đoán và phân tích khả năng nhận diện vùng tổn thương của mô hình.

   Click vào đây để xem code:
UNET: https://github.com/lethilan14062004/Du-An/blob/main/UNET.ipynb
FCNRESNET: https://github.com/lethilan14062004/Du-An/blob/main/FCN_RESNET34.ipynb
Click vào đây để xem báo cáo:
