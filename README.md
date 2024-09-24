# Môi trường phát triển 
Ngôn ngữ Python là một ngôn ngữ lập trình thông dịch, tức là mã nguồn của chương trình không cần phải được biên dịch thành mã máy trước khi chạy. 
Thay vào đó, mã nguồn Python được dịch và thực thi tại thời điểm chạy bởi trình thông dịch Python. Python là một ngôn ngữ lập trình đa mục đích và có cú pháp đơn giản, dễ đọc, dễ học.
# Thư viện và Framework
## OpenCV
OpenCV là một thư viện mã nguồn mở được sử dụng để xử lý ảnh và video, phân tích các hình ảnh theo thời gian thực. 
Nó cung cấp các công cụ mạnh mẽ để xử lý và phân tích hình ảnh từ những tác vụ cơ bản như lọc ảnh, phát hiện cạnh, chuyển đổi hình ảnh, đến các tác vụ phức tạp hơn như nhận dạng đối tượng, theo dõi chuyển động và phân đoạn ảnh.
- Các tính năng chính:
  - Xử lý ảnh: Lọc ảnh, chuyển đổi màu sắc, phát hiện cạnh, phát hiện đối tượng.
  - Phân tích video: Phát hiện và theo dõi chuyển động, tách nền.
  - Nhận dạng hình ảnh: Nhận diện khuôn mặt, mắt, và các bộ phận cơ thể.
  - Hỗ trợ đa nền tảng: Có thể chạy trên nhiều hệ điều hành như Windows, Linux, macOS và các nền tảng di động.
- Ứng dụng thực tế:
  - Nhận diện khuôn mặt trong ảnh và video.
  - Phân tích chuyển động và xử lý video trong thời gian thực.
  - Phát triển hệ thống điều khiển robot dựa trên xử lý hình ảnh.
- Cài đặt:
  ```cmd
  pip install opencv-python
  ```
## MediaPipe
MediaPipe là một framework mã nguồn mở của Google dùng để xử lý video và xử lý các tín hiệu đa phương tiện khác, cung cấp các giải pháp đã được tối ưu hóa cho các ứng dụng liên quan đến máy học như nhận diện khuôn mặt, theo dõi bàn tay, 
và phân tích chuyển động của cơ thể.

- Các tính năng chính:
  - Nhận diện bàn tay và cơ thể: MediaPipe cung cấp các giải pháp nhận diện và theo dõi chuyển động của bàn tay, cơ thể, và mặt.
  - Nhận diện khuôn mặt: Cung cấp các giải pháp phát hiện và theo dõi khuôn mặt theo thời gian thực.
  - Xử lý tín hiệu thời gian thực: Dễ dàng tích hợp với các hệ thống video và các ứng dụng xử lý thời gian thực.
- Ứng dụng thực tế:
  - Theo dõi cử chỉ bàn tay cho các ứng dụng điều khiển không chạm.
  - Nhận diện khuôn mặt để phục vụ cho các hệ thống bảo mật.
  - Phân tích chuyển động cơ thể cho các ứng dụng thể thao hoặc y tế.
- Cài đặt
  ```cmd
  pip install mediapipe
  ```
## PyAutoGUI
PyAutoGUI là một thư viện Python đơn giản để tự động hóa giao diện người dùng. 
Nó cho phép lập trình viên điều khiển chuột và bàn phím một cách tự động, giúp thực hiện các tác vụ như di chuyển chuột, nhấp chuột, nhập văn bản, chụp màn hình và tự động hóa các hoạt động khác.
- Cài đặt
  ```cmd
  pip install pyautogui
  ```
