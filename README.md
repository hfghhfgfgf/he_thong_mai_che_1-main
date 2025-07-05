Đây là file dự án làm về hệ thống mái che thông mình được điều khiển tự động qua ESP32 hoặc thủ công qua web server 

Các linh kiện sử dụng:
1	ESP32	1
2	Cảm biến ánh sáng (Light Sensor)	1
3	Cảm biến mưa (Rain Sensor)	1
4	Động cơ DC 3–6V	1
5	Driver L298N	1
6	Nguồn cấp cho ESP32 và động cơ	1
7	Dây nối và breadboard	
8	Máy chủ chạy Web Server Flask (Laptop)	1
9	Thẻ nhớ 	1



Cách làm:
Upload code lên Esp32 trong file sketch_apr25a và chạy bằng flask

![image](https://github.com/user-attachments/assets/c28e053b-1e35-48af-a707-c48e3d9748d7)

sau đó điều khiển đóng mở rèm che tùy ý ở trên web 
nếu muốn tự động chỉ cần cho chút nước vào cảm biến hoặc che ánh sáng thì mái che sẽ tự động đóng lại

