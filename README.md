# nmxlas
#lab4
Yêu cầu thư viện
pip install numpy pillow matplotlib opencv-python scipy scikit-image
Cách chạy chương trình
Sau khi chạy, nhập số từ 10 đến 12 để chọn bài tương ứng:
10: LangBiang (Shift + Otsu)
11: Hồ Xuân Hương (Rotate + Adaptive Thresholding)
12: Quảng trường Lâm Viên (Coordinate Mapping + Binary Closing)
Chi tiết chức năng
1. LangBiang (Shift + Otsu Thresholding)
Ảnh được chuyển sang xám, dịch phải 100px
Phân ngưỡng bằng phương pháp Otsu
Lưu ảnh kết quả là lang_biang.jpg
2. Hồ Xuân Hương (Rotate + Adaptive Thresholding)
Xoay ảnh 45 độ
Áp dụng phân ngưỡng cục bộ threshold_local với offset = 60
Lưu ảnh kết quả là ho_xuan_huong.jpg
3. Quảng trường Lâm Viên (Coordinate Mapping + Binary Closing)
Áp dụng Binary Closing bằng structuring element
Lưu ảnh kết quả là quan_truong_lam_vien.jpg


