## Chương 1. Tổng quan về OpenCV và Xử lý ảnh cơ bản

* Giới thiệu thư viện OpenCV và các ứng dụng trong thị giác máy tính.
* Cài đặt và cấu hình môi trường làm việc với OpenCV.
* Đọc, hiển thị và lưu ảnh số.
* Chuyển đổi giữa các không gian màu (RGB, Grayscale, HSV,...).
* Thao tác cơ bản trên ảnh và giá trị điểm ảnh (Pixel Operations).

## Chương 2. Các phép biến đổi ảnh số

* Thay đổi kích thước ảnh (Image Resizing).
* Cắt vùng ảnh quan tâm (Cropping).
* Xoay ảnh (Rotation) và lật ảnh (Flipping).
* Các phép biến đổi hình học nâng cao: Translation, Affine Transformation và Perspective Transformation.

## Chương 3. Kỹ thuật phát hiện biên ảnh

* Phát hiện biên bằng Gradient bậc nhất:

  * Sobel Operator
  * Prewitt Operator
  * Roberts Operator
  * So sánh ưu, nhược điểm của từng phương pháp.
* Phát hiện biên bằng Gradient bậc hai:

  * Laplacian Edge Detection.
* Phát hiện biên tối ưu bằng:

  * Canny Edge Detection.

## Chương 4. Phân vùng và trích xuất thông tin ảnh

* Phân ngưỡng toàn cục (Global Thresholding).
* Phân ngưỡng thích nghi (Adaptive Thresholding).
* Phân vùng dựa trên đặc trưng biên ảnh.
* Phân cụm dữ liệu ảnh bằng thuật toán K-Means.
* Tìm kiếm và đối sánh mẫu trong ảnh (Template Matching).

## Chương 5. Xử lý video và phát hiện đối tượng

* Đọc, hiển thị và ghi dữ liệu video.
* Phát hiện chuyển động trong chuỗi khung hình (Motion Detection).
* Theo dõi đối tượng:

  * MeanShift Tracking
  * CamShift Tracking
  * OpenCV Object Tracking API
* Phát hiện và nhận dạng đối tượng:

  * Haar Cascade Classifier
  * HOG + SVM
  * Deep Learning Object Detection (YOLO, SSD, Faster R-CNN).
* Xây dựng các ứng dụng thị giác máy tính thời gian thực.
