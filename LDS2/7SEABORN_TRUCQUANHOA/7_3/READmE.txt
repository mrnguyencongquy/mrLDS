Diamond - Nghịch lý Simpson
Vinh Tran
•
Jan 24
Nghịch lý Simpson hay hiệu ứng Yule–Simpson, là một nghịch lý trong xác suất và thống kê, trong đó một xu hướng xuất hiện trong dữ liệu sẽ bị đảo ngược khi được phân tích dưới góc nhìn khác.

Dựa trên dữ liệu đính kèm hãy hoàn tất file Jupyter để phát hiện nghịch lý Simpson khi phân tích giá kim cương bằng các công cụ trực quan hóa dữ liệu:
1. Đọc dữ liệu diamonds.csv, đưa vào biến diamonds
2. Vẽ biểu đồ bar so sánh giá của kim cương theo color, cut và clarity. Bạn nhận xét gì về biểu đồ vừa tạo?
3. Bây giờ hãy thử phân tích thuộc tính 'carat' theo 'color' và 'clarity' qua biểu đồ catplot - bar plot.
4. Vẽ biểu đồ bar so sánh 'carat' của kim cương theo color, cut và clarity.
5. Hãy chia carat ra làm 5 khoảng giá trị, tạo cột diamonds['carat_category'] chứa khoảng giá trị tương ứng (gợi ý: dùng pd.qcut).
6. Phân tích chi tiết hơn thuộc tính 'price' theo 'clarity', 'carat_category', 'color' qua biểu đồ catplot - point plot
7. Kết luận