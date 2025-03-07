# Hướng dẫn cài đặt chi tiết
*Trước hết bạn cần cài đặt mạch ESP32 vào trong Arduino IDE để có thể lập trình được cho Ebot*
Link hướng dẫn: https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/
- Sau khi cài đặt xong bạn cần thực hiện các bước được đánh số theo thứ tự sau đây:
![Screenshot 2025-03-02 215440](https://github.com/user-attachments/assets/0681a363-cfe9-46e2-9f1a-47cea80627e5)
- Tiếp theo các bạn cần chọn cổng ví dụ như ở đây của mình là COM1:
![doc-esp32-board-detected-in-port-com-en](https://github.com/user-attachments/assets/9eb0c564-8ad1-414e-a9e1-b3a9f35deadc)
*Nếu như máy tính của các bạn không nhận COM(cổng cắm) tham khảo link hướng dẫn cài đặt driver CH340: https://electropeak.com/learn/how-to-install-ch340-driver/*
- Để mở file bạn cần vào mục File > Open

![Screenshot 2025-03-02 221016](https://github.com/user-attachments/assets/5ca4abe6-7665-4b15-8180-204c9c170319)

- Tiếp theo vào folder bạn vừa tải xuống và giải nén chọn file ESP32_AP.ino (ví dụ như ở đây mình đang lưu ở mục Downloads) rồi bấm Open

![image](https://github.com/user-attachments/assets/0d9837bf-0db3-4015-9990-6cc81faab696)
- Cuối cùng chỉ cần chọn bấm nạp code là xong.

![Screenshot 2025-03-02 221332](https://github.com/user-attachments/assets/a5081c76-aee7-4449-9952-6393bb49894d)

- Cuối cùng ta kết nối với Ebot để có thể điều khiển

Trên Desktop bạn chỉ cần chọn đúng SSID được config sẵn trong code được nạp vào Ebot và nhập mật khẩu như bình thường là được (Ví dụ SSID ở đây là ROBOT_AP)

![image](https://github.com/user-attachments/assets/724e0ba7-c34a-4d7d-b7fe-24acb8ce2d68)

Tương tự như trên Modbile cũng tương tự:

![z6374930877265_5adcd2a9db23f511eac3f6841777cb7f](https://github.com/user-attachments/assets/ad8b9afb-67f9-4e2a-b6aa-30d89bf66a63)

# <ins> LƯU Ý </ins>
- Để có thể điều khiển được Ebot cần đảm bảo việc kết nối thông qua wifi một cách liền mạch điều này có thể sẽ hơi bất tiện cho việc sử dụng internet để tra cứu, tìm kiếm thông tin, ...
