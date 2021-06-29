Canada
Vinh Tran
•
Jan 30
Dựa trên file dữ liệu đính kèm (Canada.xlsx) chứa thông tin nhập cư vào Canada của các nước từ năm 1980 đến năm 2013 và file bản đồ world_countries.json để thực hiện các yêu cầu:

Phần 1 - Map:
1. Hiển thị bản đồ thế giới
2. Tạo bản đồ với center là Canada (location=[56.130, -106.35]) và zoom level (zoom_start=4)
3. Tạo Stamen Toner Map với center là Canada, và zoom level là 4
4. Tạo Stamen Terrain Map với center là Canada, và zoom level là 4
5. Tạo Stamen Watercolor Map với center là Canada, và zoom level 4

Phần 2 - Choropleth Map:
1. Đọc dữ liệu Canada.xlsx và lưu vào df_can, tìm hiểu về dữ liệu với: describe, head, shape, columns
2. Làm sạch dữ liệu:
• Bỏ đi những cột không cần thiết như 'AREA', 'REG', 'DEV', 'Type', 'Coverage'
• Đổi tên một số cột như sau: 'OdName' => 'Country', 'AreaName' => 'Continent', 'RegName' => 'Region'
• Đổi tất cả tên các cột sang kiểu string
• Thêm cột Total chứa tổng lượng nhập cư qua các năm
3. Xem thông tin dữ liệu lúc này:
Hiển thị 5 dòng dữ liệu đầu của df_can sau khi làm sạch dữ liệu
Cho biết kích thước của df_can sau khi làm sạch dữ liệu
4. Tạo world map, với center [0, 0] là latitude và longitude, zoom level là 2, sử dụng tiles là OpenStreetMap
5. Tạo choropleth map sử dụng total nhập cư của từng quốc gia vào Canada từ năm 1980 đến năm 2013