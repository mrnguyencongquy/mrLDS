Dữ liệu được trích xuất từ http://wiki.stat.ucla.edu/socr/index.php/SOCR_Data_MLB_HeightsWeights

Ghi chú: Major League Baseball (MLB) là giải đấu bóng chày chuyên nghiệp. Major League Baseball có tổng cộng 30 đội bóng đến từ nhiều bang khác nhau của Mỹ và Canada (29 đội từ Mỹ và 1 đội từ Canada). MLB luôn được sự quan tâm lớn của hầu hết fan bóng chày trên toàn thế giới, và cũng được xem là giải đấu nổi tiếng và uy tín nhất, tập hợp những cầu thủ có trình độ cao nhất trong bộ môn này. Dữ liệu heights (tính theo inches) và weights (tính theo pounds) là chiều cao và cân nặng của các cầu thủ có tham gia 1 số giải của MLB.

Cho tập tin dữ liệu heights_1.txt, weights_1.txt => hãy chép dữ liệu từ tập tin này vào list là height, weight, và thực hiện các yêu cầu sau:
1. Tạo numpy array arr_height từ list height.
2. Tạo numpy array arr_weight từ list weight.
3. Cho hệ số quy đổi từ inch sang m là 0.0254, tạo arr_height_m dựa trên công thức: arr_height * hệ số quy đổi.
4. Cho hệ số quy đổi từ pound sang kg là 0.453592, tạo arr_weight_kg dựa trên công thức: arr_weight * hệ số quy đổi.
5. Tính BMI của arr_height_m và arr_weight_kg theo công thức BMI = Cân nặng / (Chiều cao * Chiều cao), và lưu vào arr_bmi.
6. Cho biết giá trị cân nặng ở vị trí index = 50 trong arr_weight_kg
7. Tạo arr_height_m_100 gồm các phần tử có vị trí index từ 100 đến 110 (lấy cả index 110) trong arr_height_m
8. Cho biết các cầu thủ bóng chày có bmi < 21 trong arr_bmi
9. Cho biết chiều cao trung bình và cân nặng trung bình của các cầu thủ
10. Cho biết chiều cao và cân nặng lớn nhất của các cầu thủ
11. Cho biết chiều cao và cân nặng nhỏ nhất của các cầu thủ