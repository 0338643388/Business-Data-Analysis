# Phân Tích Kinh Doanh 2024

## Tổng Quan
Dự án này phân tích hiệu suất kinh doanh năm 2024 của một công ty chuyên về điện thoại, máy tính và phụ kiện. Phân tích được thực hiện dựa trên một tập dữ liệu Excel toàn diện gồm 6 sheet (Khách hàng, Sản phẩm, Nhân viên, Dữ liệu bán hàng, Chi nhánh, KPI). Mục tiêu của dự án là khai thác những insight ẩn chứa và đề xuất các chiến lược tăng trưởng đột phá cho năm 2025.

> **“Liệu con số 1.034 tỷ đồng doanh thu và 345 tỷ đồng lợi nhuận năm 2024 đã phản ánh trọn vẹn bức tranh kinh doanh của công ty, hay vẫn còn những ‘góc khuất’ chưa được khám phá – nơi chúng ta có thể tìm thấy cơ hội bứt phá mới?”**

## Mục Lục
- Tóm tắt Dữ Liệu
- Phân Tích Xu Hướng Theo Thời Gian
- Phân Tích Nhóm Sản Phẩm
- Hiệu Suất Chi Nhánh
- Phân Cụm Khách Hàng
- Insight & Đề Xuất Chiến Lược
- License

## Tóm tắt Dữ Liệu
- **Doanh thu tổng cộng:** 1.034 tỷ đồng
- **Lợi nhuận tổng cộng:** 345 tỷ đồng (Biên lợi nhuận: 33,33%)
- **Sản phẩm bán ra:** 55.270
- **Chi phí kinh doanh:** 689 tỷ đồng
- **Vấn đề dữ liệu:** Có 190 đơn hàng với doanh thu và giá vốn bằng 0, chủ yếu thuộc mảng Phụ kiện (60%), Phần mềm (24,21%) và Dịch vụ (15,79%). Có thể đây là các đơn hàng khuyến mãi/tặng kèm hoặc lỗi nhập liệu.
- **Chỉnh sửa dữ liệu:** Một số sản phẩm bị gắn nhãn sai nhóm sản phẩm đã được chuyển đổi về đúng danh mục nhằm đảm bảo tính chính xác.

## Phân Tích Xu Hướng Theo Thời Gian
- **Xu hướng theo quý:** 
  - Quý 2 có doanh thu cao nhất, sau đó giảm dần vào Quý 3 và Quý 4.
  - Số lượng bán (doanh số) cao nhất ở Quý 1 và giảm dần qua các quý.
- **Giải thích ban đầu:** Có thể do nhu cầu thị trường tăng mạnh sau Tết Nguyên Đán, sau đó giảm dần theo thời gian.
- **Phân tích theo tháng:** 
  - Doanh thu hàng tháng tương đối ổn định, với điểm nhấn nhẹ từ tháng 3 đến tháng 5.
  - Số lượng bán ra biến động rõ rệt vào đầu năm (nhu cầu sắm mới sau Tết) và cuối năm (doanh nghiệp “thắt hầu bao” vì ưu tiên ngân sách cho mục đích khác).

## Phân Tích Nhóm Sản Phẩm
- Công ty kinh doanh 4 dòng sản phẩm: **Phần mềm, Phụ kiện, Máy tính, Dịch vụ**.
- **Phân bổ doanh thu:**
  - Phần mềm: 53,43%
  - Phụ kiện: 26,35%
  - Máy tính: 14,95%
  - Dịch vụ: Phần còn lại

## Hiệu Suất Chi Nhánh
- **Phân bố theo vùng:** Công ty có 3 chi nhánh với doanh thu khá cân bằng, trong đó chi nhánh TP. HCM có doanh thu nhỉnh hơn một chút.
- **KPI hàng tháng:**
  - **Đà Nẵng:** Doanh thu thấp nhất nhưng đạt KPI 6/12 tháng (cao nhất).
  - **TP. HCM:** Đạt KPI 5/12 tháng.
  - **Hà Nội:** Đạt KPI 4/12 tháng.
- **Phân tích chi tiết:**
  - **TP. HCM:** 
    - Doanh thu theo nhóm ngành: Dịch vụ (18 tỷ), Máy tính (52 tỷ), Phần mềm (190 tỷ), Phụ kiện (92 tỷ).
    - Phần mềm là mảng chủ lực, cho thấy khách hàng tại HCM ưa chuộng các gói phần mềm cao cấp hoặc dài hạn.
    - Kinh doanh thuận lợi tập trung vào nửa cuối năm.
  - **Hà Nội:** 
    - Máy tính có doanh thu và số lượng bán cao nhất, gợi ý nên đẩy mạnh bán máy tính.
    - Biên lợi nhuận ổn định vào đầu năm, tạo cơ hội tăng cường các chương trình khuyến mãi.
  - **Đà Nẵng:** 
    - Phụ kiện là mảng có doanh thu cao nhất, mặc dù số lượng bán không nhiều bằng HCM, nhưng khoảng cách không quá lớn.
    - Thời điểm mạnh từ tháng 4 đến tháng 6, phù hợp với chiến dịch marketing.
- **Xu hướng cuối năm:** Doanh thu giảm ở cả ba chi nhánh do doanh nghiệp hạn chế mua sắm; đề xuất tung chương trình khuyến mãi để kích cầu.

## Phân Cụm Khách Hàng
- **Cluster 1 (66,11%) – Khách hàng trung thành:**
  - Mua hàng thường xuyên, đạt số đơn hàng ổn định (~6.500 đơn).
  - Chủ yếu mua phần mềm; mặc dù doanh thu không cao nhất nhưng đảm bảo tính liên tục.
  - **Chiến lược:** Duy trì chất lượng sản phẩm và khuyến khích bán kèm thông minh để biến họ thành kênh marketing truyền miệng.
- **Cluster 2 (7,12%) – Khách hàng “mùa vụ”:**
  - Số lượng đơn hàng thấp (~800 đơn), nhưng doanh thu có tháng vượt cả nhóm VIP (ví dụ: tháng 8).
  - Chủ yếu mua phụ kiện.
  - **Chiến lược:** Tận dụng các khuyến mãi theo mùa để tăng nhanh lợi nhuận.
- **Cluster 3 (26,72%) – Nhóm VIP:**
  - Đóng góp doanh thu cao nhất, chủ yếu từ phần mềm.
  - Mua không thường xuyên nhưng mỗi lần đặt hàng có giá trị lớn (ví dụ: tháng 9 với doanh thu ~43 tỷ đồng).
  - **Chiến lược:** Cung cấp dịch vụ đẳng cấp và ưu đãi độc quyền; áp dụng chiến lược cá nhân hóa trong các tháng thấp điểm.

## Insight & Đề Xuất Chiến Lược
- **Tối ưu danh mục sản phẩm:** Mở rộng dòng phụ kiện tiềm năng, điều chỉnh chiến lược giá phần mềm, và chú trọng phát triển máy tính cùng dịch vụ nhằm tăng biên lợi nhuận.
- **Đẩy mạnh bán chéo:** Khuyến khích khách hàng mua combo (ví dụ: Phần mềm + Phụ kiện, Máy tính + Phụ kiện) để thúc đẩy doanh thu và tạo thói quen mua sắm trọn gói.
- **Chiến lược riêng cho từng chi nhánh:**
  - **TP. HCM:** Tăng cường marketing vào nửa cuối năm.
  - **Hà Nội:** Triển khai các chương trình ưu đãi vào đầu năm.
  - **Đà Nẵng:** Tập trung các chiến dịch marketing từ tháng 4 đến tháng 6 và tung khuyến mãi cuối năm.
- **Chăm sóc khách hàng theo phân khúc:** 
  - Trung thành: Giữ chân qua chất lượng và bán kèm.
  - Mùa vụ: Tận dụng các chương trình khuyến mãi ngắn hạn.
  - VIP: Đảm bảo dịch vụ cao cấp và ưu đãi cá nhân hóa.

Trả lời cho câu hỏi mở đầu, con số 1.034 tỷ doanh thu và 345 tỷ lợi nhuận năm 2024 rất ấn tượng, nhưng ẩn chứa nhiều góc khuất về mùa vụ, hiệu suất chi nhánh, danh mục sản phẩm và hành vi khách hàng. Nếu công ty khai thác triệt để các insight này, năm 2025 hứa hẹn sẽ là bước nhảy vọt trên con đường phát triển.

## License
This project is licensed under the MIT License.
