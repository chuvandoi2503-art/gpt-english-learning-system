# RESEARCH_PACKAGE_STANDARD

Phiên bản: 01.000

---

# CHUẨN GÓI KẾT QUẢ NGHIÊN CỨU

## GPT HỌC TIẾNG ANH BỐ VÀ CON

---

# 1. MỤC ĐÍCH

Tài liệu này quy định cấu trúc chuẩn của gói kết quả nghiên cứu trong hệ thống học tiếng Anh bố và con.

Gói kết quả nghiên cứu được sử dụng để:

* Tiếp nhận kết quả từ GPT Nghiên cứu.
* Kiểm tra kết quả nghiên cứu trước khi áp dụng.
* Chuẩn hóa tri thức đầu vào cho GPT Học tiếng Anh.
* Làm cơ sở tạo lộ trình gần.
* Làm cơ sở tạo kế hoạch tháng.
* Làm cơ sở tạo kế hoạch tuần.
* Làm cơ sở thiết kế hoạt động học.
* Làm cơ sở đánh giá tiến độ.
* Ghi rõ điều kiện áp dụng.
* Ghi rõ rủi ro và giới hạn.
* Giảm việc GPT tự suy đoán từ tài liệu nghiên cứu rời rạc.

Tài liệu này không chứa:

* Yêu cầu nghiên cứu.
* Hồ sơ người học.
* Lộ trình hoàn chỉnh.
* Kế hoạch tháng hoàn chỉnh.
* Kế hoạch tuần hoàn chỉnh.
* Bài học hoàn chỉnh.
* Nhật ký học.
* Quyết định áp dụng cuối cùng.

---

# 2. VAI TRÒ CỦA GÓI KẾT QUẢ NGHIÊN CỨU

Gói kết quả nghiên cứu là cầu nối giữa:

```text
Yêu cầu nghiên cứu

↓

GPT Nghiên cứu

↓

Gói kết quả nghiên cứu

↓

GPT Học tiếng Anh

↓

Lộ trình hoặc kế hoạch học
```

Gói kết quả nghiên cứu phải chuyển kết quả nghiên cứu thành dữ liệu có cấu trúc.

Gói này không chỉ là:

* Bài viết tổng hợp.
* Danh sách đường dẫn.
* Ghi chú rời rạc.
* Bản sao tài liệu nguồn.
* Ý kiến chung chung.
* Kết luận thiếu điều kiện áp dụng.

Gói phải đủ rõ để hệ thống biết:

* Kết luận nào có thể sử dụng.
* Kết luận nào chưa đủ cơ sở.
* Áp dụng cho ai.
* Áp dụng trong điều kiện nào.
* Không nên áp dụng khi nào.
* Dữ liệu nào dùng cho lộ trình.
* Dữ liệu nào dùng cho kế hoạch tuần.
* Dữ liệu nào dùng cho đánh giá.

---

# 3. NGUYÊN TẮC CHUNG

## 3.1. Một gói phải gắn với một yêu cầu nghiên cứu

Mỗi gói kết quả phải tham chiếu tới:

* Mã yêu cầu nghiên cứu.
* Phiên bản yêu cầu nghiên cứu.
* Câu hỏi nghiên cứu chính.
* Quyết định cần hỗ trợ.

Không tạo gói kết quả không có yêu cầu nghiên cứu gốc, trừ khi đó là gói nghiên cứu nền đã được xác định rõ phạm vi.

---

## 3.2. Không mặc định kết quả nghiên cứu luôn đúng

Gói kết quả phải phân biệt:

* Bằng chứng mạnh.
* Bằng chứng trung bình.
* Bằng chứng yếu.
* Kinh nghiệm thực tế.
* Nhận định chuyên gia.
* Khoảng trống chưa đủ dữ liệu.

Không được trình bày mọi kết luận với cùng mức độ chắc chắn.

---

## 3.3. Phải tách dữ liệu nguồn và kết luận

Gói nghiên cứu phải phân biệt rõ:

* Nguồn nói gì.
* GPT Nghiên cứu tổng hợp gì.
* Kết luận nào được suy ra.
* Khuyến nghị nào được đề xuất.
* Điều nào vẫn chưa chắc chắn.

Không trộn nội dung nguồn với nhận định của GPT.

---

## 3.4. Phải gắn với trường hợp thực tế

Kết quả nghiên cứu phải được đối chiếu với:

* Hồ sơ bố.
* Hồ sơ con.
* Hồ sơ nhóm học.
* Mục tiêu hiện tại.
* Điều kiện học.
* Sở thích của con.
* Dữ liệu đời sống.
* Tiến độ thực tế nếu đã có.

Không sử dụng kết luận chung cho mọi trường hợp.

---

## 3.5. Chỉ đóng gói dữ liệu có giá trị sử dụng

Không đưa vào gói:

* Thông tin ngoài phạm vi.
* Nội dung không hỗ trợ quyết định.
* Dữ liệu lặp lại không cần thiết.
* Trích dẫn dài không tạo giá trị.
* Danh sách nguồn không được đánh giá.
* Kiến thức không liên quan đến lộ trình hoặc kế hoạch hiện tại.

---

# 4. KHI NÀO TẠO GÓI KẾT QUẢ NGHIÊN CỨU

Tạo gói kết quả khi:

* Yêu cầu nghiên cứu đã được thực hiện.
* Các nguồn chính đã được thu thập.
* Dữ liệu đã được kiểm tra.
* Các kết luận chính đã được tổng hợp.
* Điều kiện áp dụng đã được xác định.
* Rủi ro và giới hạn đã được ghi nhận.
* Đầu ra có thể hỗ trợ quyết định thực tế.

Không tạo gói chính thức khi:

* Chỉ mới có một nguồn yếu.
* Chưa trả lời được câu hỏi chính.
* Chưa đánh giá độ tin cậy.
* Chưa xác định điều kiện áp dụng.
* Chưa biết kết quả sẽ dùng vào đâu.
* Còn mâu thuẫn lớn chưa được trình bày.

---

# 5. PHÂN LOẠI GÓI KẾT QUẢ NGHIÊN CỨU

Mỗi gói phải thuộc ít nhất một loại chính.

## 5.1. Gói nghiên cứu hồ sơ người học

Dùng để làm rõ:

* Trạng thái của bố.
* Trạng thái phát triển liên quan của con.
* Điều kiện học.
* Khả năng tiếp nhận.
* Giới hạn cần tôn trọng.
* Dữ liệu cần theo dõi.

---

## 5.2. Gói nghiên cứu phương pháp học

Dùng để xác định:

* Cách học nghe.
* Cách luyện phát âm.
* Cách ghi nhớ.
* Cách tương tác.
* Cách đưa tiếng Anh vào đời sống.
* Cách giảm áp lực.
* Cách duy trì hứng thú.

---

## 5.3. Gói nghiên cứu lộ trình

Dùng để hỗ trợ:

* Xác định các giai đoạn.
* Xác định thứ tự phát triển năng lực.
* Xác định điều kiện chuyển bước.
* Xây lộ trình ba tháng gần.
* Xây kế hoạch một tháng.
* Tổ chức kế hoạch tuần.

---

## 5.4. Gói nghiên cứu nội dung

Dùng để xác định:

* Loại từ phù hợp.
* Loại câu ngắn phù hợp.
* Loại ngữ cảnh phù hợp.
* Mức độ khó phù hợp.
* Cách mở rộng từ sở thích.
* Nội dung nên ưu tiên.
* Nội dung nên tránh.

Gói này không phải bài học hoàn chỉnh.

---

## 5.5. Gói nghiên cứu đánh giá

Dùng để xác định:

* Cách kiểm tra bố.
* Cách quan sát con.
* Dấu hiệu hiểu.
* Dấu hiệu sẵn sàng.
* Dấu hiệu quá tải.
* Tiêu chí chuyển tiếp.
* Tiêu chí ôn lại.

---

## 5.6. Gói nghiên cứu công cụ

Dùng để đánh giá:

* Ứng dụng.
* Phần mềm.
* Từ điển.
* Nguồn phát âm.
* Nguồn nghe.
* Kênh học.
* Thiết bị hỗ trợ.

---

## 5.7. Gói nghiên cứu vấn đề phát sinh

Dùng khi:

* Bố gặp lỗi kéo dài.
* Con không phản ứng.
* Con mất hứng thú.
* Cách tiếp cận không hiệu quả.
* Kế hoạch quá tải.
* Tiến độ lệch khỏi dự kiến.
* Cần thay đổi phương pháp.

---

# 6. CẤU TRÚC GÓI KẾT QUẢ NGHIÊN CỨU

Một gói đầy đủ gồm:

1. Thông tin định danh.
2. Yêu cầu nghiên cứu gốc.
3. Tóm tắt điều hành.
4. Bối cảnh áp dụng.
5. Phương pháp nghiên cứu.
6. Danh sách nguồn.
7. Đánh giá chất lượng nguồn.
8. Kết quả theo từng câu hỏi.
9. Kết luận chính.
10. Khuyến nghị.
11. Điều kiện áp dụng.
12. Điều không nên áp dụng.
13. Rủi ro.
14. Giới hạn.
15. Mức độ tin cậy.
16. Dữ liệu dùng cho hồ sơ.
17. Dữ liệu dùng cho lộ trình.
18. Dữ liệu dùng cho kế hoạch tháng.
19. Dữ liệu dùng cho kế hoạch tuần.
20. Dữ liệu dùng cho bố chuẩn bị.
21. Dữ liệu dùng cho tương tác với con.
22. Dữ liệu dùng cho đánh giá.
23. Khoảng trống còn lại.
24. Ngày cần kiểm tra lại.
25. Trạng thái và xác nhận.

---

# 7. THÔNG TIN ĐỊNH DANH

Mỗi gói phải có:

* Mã gói nghiên cứu.
* Tên gói.
* Loại gói.
* Mã yêu cầu nghiên cứu gốc.
* Phiên bản yêu cầu gốc.
* Ngày bắt đầu nghiên cứu.
* Ngày hoàn thành.
* Người hoặc GPT thực hiện.
* Người kiểm tra.
* Người xác nhận.
* Phiên bản gói.
* Trạng thái.

Mã gói phải duy nhất.

---

# 8. YÊU CẦU NGHIÊN CỨU GỐC

Phần này phải ghi:

* Câu hỏi chính.
* Các câu hỏi phụ.
* Đối tượng áp dụng.
* Quyết định cần hỗ trợ.
* Phạm vi.
* Điều nằm ngoài phạm vi.
* Tiêu chuẩn nguồn.
* Điều kiện hoàn thành.

Không cần sao chép toàn bộ yêu cầu nghiên cứu.

Chỉ cần tóm tắt và tham chiếu đúng phiên bản.

---

# 9. TÓM TẮT ĐIỀU HÀNH

Tóm tắt điều hành phải giúp người dùng hiểu nhanh:

* Nghiên cứu giải quyết vấn đề gì.
* Kết luận quan trọng nhất là gì.
* Khuyến nghị chính là gì.
* Mức độ tin cậy.
* Rủi ro lớn nhất.
* Quyết định nào có thể được hỗ trợ.
* Điều gì chưa được kết luận.

Phần này phải ngắn gọn.

Không thay thế nội dung chi tiết bên dưới.

---

# 10. BỐI CẢNH ÁP DỤNG

Phải ghi rõ kết quả được xem xét trong bối cảnh:

* Bố bắt đầu từ trình độ nào.
* Con ở độ tuổi nào.
* Trọng tâm học hiện tại.
* Mục tiêu hiện tại.
* Điều kiện học thực tế.
* Sở thích liên quan.
* Hạn chế hiện có.
* Dữ liệu thực tế nào đã được dùng.

Nếu bối cảnh thay đổi lớn, phải đánh giá lại khả năng áp dụng.

---

# 11. PHƯƠNG PHÁP NGHIÊN CỨU

Phần này mô tả:

* Cách tìm nguồn.
* Tiêu chí chọn nguồn.
* Tiêu chí loại nguồn.
* Khoảng thời gian xuất bản được xem xét.
* Loại nguồn đã sử dụng.
* Cách đối chiếu nguồn.
* Cách xử lý nguồn mâu thuẫn.
* Cách đánh giá khả năng áp dụng.
* Giới hạn của quá trình nghiên cứu.

Không cần mô tả kỹ thuật tìm kiếm không tạo giá trị kiểm tra.

---

# 12. DANH SÁCH NGUỒN

Mỗi nguồn phải có:

* Mã nguồn.
* Tên tài liệu.
* Tác giả hoặc tổ chức.
* Năm hoặc ngày xuất bản.
* Loại nguồn.
* Đường dẫn hoặc định danh.
* Đối tượng nghiên cứu.
* Nội dung hỗ trợ.
* Giới hạn của nguồn.
* Mức độ tin cậy.

Không chỉ liệt kê đường dẫn.

---

# 13. ĐÁNH GIÁ CHẤT LƯỢNG NGUỒN

Mỗi nguồn có thể được đánh giá:

* Rất cao.
* Cao.
* Trung bình.
* Thấp.
* Chỉ tham khảo.

Việc đánh giá dựa trên:

* Loại nguồn.
* Uy tín của tổ chức.
* Thiết kế nghiên cứu.
* Cỡ mẫu nếu có.
* Độ mới.
* Mức độ liên quan.
* Đối tượng nghiên cứu.
* Khả năng áp dụng.
* Xung đột lợi ích nếu biết.

Không đánh giá nguồn chỉ dựa trên việc nội dung phù hợp với giả thuyết.

---

# 14. KẾT QUẢ THEO TỪNG CÂU HỎI

Mỗi câu hỏi nghiên cứu phải có phần trả lời riêng.

Cấu trúc:

```text
Câu hỏi:

Kết quả chính:

Bằng chứng hỗ trợ:

Nguồn phản biện hoặc mâu thuẫn:

Mức độ tin cậy:

Điều kiện áp dụng:

Điểm chưa rõ:
```

Không gộp tất cả câu hỏi thành một kết luận chung nếu cần dùng cho các quyết định khác nhau.

---

# 15. KẾT LUẬN CHÍNH

Kết luận chính phải:

* Trả lời trực tiếp câu hỏi nghiên cứu.
* Nêu rõ mức độ chắc chắn.
* Không vượt quá bằng chứng.
* Không biến khuyến nghị thành sự thật tuyệt đối.
* Không bỏ qua ngoại lệ quan trọng.
* Phân biệt kết luận đã xác nhận và kết luận tạm thời.

Có thể phân loại:

* Đã có cơ sở mạnh.
* Có cơ sở tương đối.
* Chỉ là hướng tham khảo.
* Chưa đủ cơ sở kết luận.

---

# 16. KHUYẾN NGHỊ

Khuyến nghị phải:

* Gắn với mục tiêu.
* Gắn với đối tượng.
* Gắn với điều kiện thực tế.
* Có thể thực hiện.
* Có mức ưu tiên.
* Có lý do.
* Có điều kiện dừng hoặc đánh giá lại.

Mỗi khuyến nghị nên có:

* Nội dung.
* Đối tượng.
* Mục đích.
* Điều kiện áp dụng.
* Mức ưu tiên.
* Rủi ro.
* Dữ liệu cần theo dõi.
* Thời điểm đánh giá lại.

---

# 17. ĐIỀU KIỆN ÁP DỤNG

Phải ghi rõ:

* Áp dụng cho ai.
* Áp dụng trong điều kiện nào.
* Áp dụng trong giai đoạn nào.
* Cần dữ liệu đầu vào nào.
* Cần bố đạt điều kiện gì.
* Cần con có trạng thái gì.
* Khi nào phải giảm tải.
* Khi nào phải dừng.
* Khi nào phải nghiên cứu lại.

Không sử dụng khuyến nghị ngoài điều kiện áp dụng.

---

# 18. ĐIỀU KHÔNG NÊN ÁP DỤNG

Gói phải ghi rõ:

* Phương pháp không phù hợp.
* Đối tượng không phù hợp.
* Điều kiện không phù hợp.
* Cách hiểu sai thường gặp.
* Cách triển khai có thể gây áp lực.
* Nội dung chưa đủ bằng chứng.
* Những việc không nên suy ra từ nghiên cứu.

Phần này là bắt buộc với các nghiên cứu liên quan đến trẻ nhỏ.

---

# 19. RỦI RO

Gói phải đánh giá rủi ro như:

* Quá tải.
* Ép con tạo đầu ra.
* Kỳ vọng tiến độ không thực tế.
* Bố phát âm chưa đủ rõ.
* Áp dụng nội dung sai độ tuổi.
* Quá phụ thuộc thiết bị.
* Đánh giá sai từ dữ liệu ít.
* Dùng sở thích làm giới hạn.
* Áp dụng phương pháp ngoài phạm vi.
* Dùng nghiên cứu chung cho trường hợp riêng.

Mỗi rủi ro cần có:

* Mô tả.
* Mức độ.
* Khả năng xảy ra.
* Tác động.
* Dấu hiệu nhận biết.
* Biện pháp giảm thiểu.
* Điều kiện dừng.

---

# 20. GIỚI HẠN

Gói phải nêu rõ:

* Giới hạn của nguồn.
* Giới hạn của phương pháp nghiên cứu.
* Giới hạn về độ tuổi.
* Giới hạn về đối tượng.
* Giới hạn về ngôn ngữ.
* Giới hạn về bối cảnh.
* Giới hạn về khả năng áp dụng.
* Dữ liệu còn thiếu.
* Kết luận chưa thể đưa ra.

Không được che giấu giới hạn để tạo cảm giác chắc chắn.

---

# 21. MỨC ĐỘ TIN CẬY

Mức độ tin cậy của gói có thể là:

* Rất cao.
* Cao.
* Trung bình.
* Thấp.
* Chưa đủ cơ sở.

Mức độ tin cậy phải dựa trên:

* Chất lượng nguồn.
* Số lượng nguồn phù hợp.
* Mức độ thống nhất.
* Độ liên quan.
* Độ mới.
* Khả năng áp dụng cho trường hợp hiện tại.
* Mức độ đầy đủ của dữ liệu thực tế.

Có thể đánh giá riêng từng kết luận.

---

# 22. DỮ LIỆU DÙNG CHO HỒ SƠ

Nếu nghiên cứu làm thay đổi cách hiểu người học, gói phải ghi:

* Trường hồ sơ bị ảnh hưởng.
* Dữ liệu hiện tại.
* Dữ liệu đề xuất.
* Cơ sở.
* Mức độ tin cậy.
* Điều kiện cập nhật.
* Trạng thái đề xuất.

Gói nghiên cứu không tự sửa hồ sơ.

Chỉ tạo đề xuất cập nhật.

---

# 23. DỮ LIỆU DÙNG CHO LỘ TRÌNH

Phần này phải cung cấp dữ liệu như:

* Năng lực cần phát triển.
* Thứ tự phát triển.
* Điều kiện bắt đầu.
* Điều kiện chuyển bước.
* Dấu hiệu sẵn sàng.
* Dấu hiệu quá tải.
* Mức độ linh hoạt.
* Mốc thời gian dự kiến nếu có cơ sở.
* Nội dung cần ưu tiên.
* Nội dung chưa nên triển khai.
* Cách cập nhật theo dữ liệu tuần.

Không bắt buộc tạo lộ trình hoàn chỉnh.

---

# 24. DỮ LIỆU DÙNG CHO KẾ HOẠCH THÁNG

Phần này có thể gồm:

* Mục tiêu tháng phù hợp.
* Nhóm năng lực cần ưu tiên.
* Loại ngữ cảnh nên sử dụng.
* Cách tổ chức mức độ khó.
* Cách phân bổ nội dung.
* Điều kiện điều chỉnh.
* Dấu hiệu cần kéo dài.
* Dấu hiệu có thể tiến nhanh.
* Cách liên kết với sở thích của con.

Số lượng cụ thể chỉ được đề xuất khi có đủ cơ sở.

---

# 25. DỮ LIỆU DÙNG CHO KẾ HOẠCH TUẦN

Phần này phải trả lời được:

* Tuần này nên ưu tiên năng lực nào.
* Loại nội dung nào phù hợp.
* Mức độ khó nào phù hợp.
* Cách chọn số lượng.
* Cách chọn ngữ cảnh.
* Cách dùng sở thích làm điểm vào.
* Bố cần chuẩn bị gì.
* Con nên được tiếp cận theo cách nào.
* Dữ liệu nào cần ghi nhận.
* Điều kiện hoàn thành.
* Điều kiện kéo dài.
* Điều kiện mở rộng.
* Điều kiện chuyển tiếp.

Không nhất thiết phải đưa ra nội dung bài học cụ thể nếu yêu cầu nghiên cứu không yêu cầu.

---

# 26. DỮ LIỆU DÙNG CHO BỐ CHUẨN BỊ

Phải làm rõ nếu có liên quan:

* Bố cần nghe nguồn nào.
* Bố cần luyện năng lực gì.
* Tiêu chí phát âm đủ sẵn sàng.
* Cách kiểm tra nghe.
* Cách kiểm tra ghi nhớ.
* Cách luyện nói trong ngữ cảnh.
* Lỗi cần theo dõi.
* Khi nào chưa nên làm mẫu cho con.

---

# 27. DỮ LIỆU DÙNG CHO TƯƠNG TÁC VỚI CON

Phải làm rõ:

* Cách tiếp cận phù hợp.
* Cách tạo chú ý.
* Cách dùng vật thật.
* Cách dùng sở thích.
* Cách lặp lại.
* Cách phản hồi.
* Dấu hiệu nên dừng.
* Dấu hiệu con đang hiểu.
* Dấu hiệu con đang quá tải.
* Điều không nên làm.

---

# 28. DỮ LIỆU DÙNG CHO ĐÁNH GIÁ

## 28.1. Với bố

Gói cần xác định:

* Năng lực cần kiểm tra.
* Cách kiểm tra.
* Tiêu chí đạt.
* Lỗi cần theo dõi.
* Thời điểm kiểm tra.
* Cách ôn lại.
* Điều kiện sẵn sàng.

## 28.2. Với con

Gói cần xác định:

* Dấu hiệu cần quan sát.
* Ngữ cảnh quan sát.
* Mức độ lặp lại cần thiết.
* Điều có thể kết luận.
* Điều chưa được kết luận.
* Dấu hiệu giảm tải.
* Dấu hiệu cần tham khảo chuyên gia.

---

# 29. KHOẢNG TRỐNG CÒN LẠI

Mỗi gói phải ghi:

* Điều chưa biết.
* Điều chưa đủ dữ liệu.
* Điều chưa tìm được nguồn mạnh.
* Điều còn tranh luận.
* Câu hỏi cần nghiên cứu tiếp.
* Dữ liệu thực tế cần thu thập thêm.
* Quyết định chưa thể hỗ trợ.

Không được trình bày gói như đã giải quyết toàn bộ vấn đề nếu vẫn còn khoảng trống.

---

# 30. NGÀY CẦN KIỂM TRA LẠI

Gói phải có:

* Ngày tạo.
* Ngày đánh giá lại dự kiến.
* Điều kiện kích hoạt đánh giá lại sớm.
* Nguồn có thể thay đổi.
* Kết luận có thể lỗi thời.

Phải đánh giá lại sớm khi:

* Hồ sơ người học thay đổi.
* Mục tiêu thay đổi.
* Kết quả thực tế trái với khuyến nghị.
* Có nghiên cứu mới tốt hơn.
* Xuất hiện rủi ro mới.

---

# 31. TRẠNG THÁI GÓI KẾT QUẢ NGHIÊN CỨU

Gói có thể có các trạng thái:

* Bản nháp.
* Chờ bổ sung nguồn.
* Chờ kiểm tra.
* Cần nghiên cứu thêm.
* Chờ xác nhận.
* Đã xác nhận.
* Đang áp dụng.
* Cần đánh giá lại.
* Hết hiệu lực.
* Bị thay thế.
* Lưu trữ.

Chỉ gói đã xác nhận hoặc đang áp dụng mới được dùng làm đầu vào chính thức.

---

# 32. QUY TẮC PHIÊN BẢN

Mỗi gói phải có phiên bản.

Khi cập nhật:

* Ghi rõ nội dung thay đổi.
* Ghi lý do.
* Ghi nguồn mới.
* Ghi kết luận bị ảnh hưởng.
* Ghi người kiểm tra.
* Ghi người xác nhận.
* Liên kết phiên bản trước.

Nếu câu hỏi nghiên cứu thay đổi bản chất:

Phải tạo gói mới gắn với yêu cầu nghiên cứu mới.

---

# 33. MẪU GÓI KẾT QUẢ NGHIÊN CỨU

```md
# GÓI KẾT QUẢ NGHIÊN CỨU

## 1. THÔNG TIN CHUNG

- Mã gói:
- Tên gói:
- Loại gói:
- Mã yêu cầu nghiên cứu:
- Phiên bản yêu cầu:
- Ngày bắt đầu:
- Ngày hoàn thành:
- Người thực hiện:
- Người kiểm tra:
- Người xác nhận:
- Phiên bản:
- Trạng thái:

---

## 2. YÊU CẦU NGHIÊN CỨU GỐC

- Câu hỏi chính:
- Câu hỏi phụ:
- Đối tượng:
- Quyết định cần hỗ trợ:
- Phạm vi:
- Ngoài phạm vi:

---

## 3. TÓM TẮT ĐIỀU HÀNH

- Vấn đề:
- Kết luận quan trọng nhất:
- Khuyến nghị chính:
- Mức độ tin cậy:
- Rủi ro chính:
- Điều chưa thể kết luận:

---

## 4. BỐI CẢNH ÁP DỤNG

- Hồ sơ bố liên quan:
- Hồ sơ con liên quan:
- Mục tiêu:
- Điều kiện học:
- Sở thích liên quan:
- Dữ liệu thực tế đã sử dụng:
- Giới hạn bối cảnh:

---

## 5. PHƯƠNG PHÁP NGHIÊN CỨU

- Cách tìm nguồn:
- Tiêu chí chọn:
- Tiêu chí loại:
- Khoảng thời gian:
- Cách đối chiếu:
- Cách xử lý mâu thuẫn:
- Giới hạn:

---

## 6. NGUỒN

| Mã | Nguồn | Loại | Nội dung hỗ trợ | Giới hạn | Độ tin cậy |
|---|---|---|---|---|---|
| | | | | | |

---

## 7. KẾT QUẢ THEO CÂU HỎI

### Câu hỏi 1

- Kết quả:
- Bằng chứng:
- Nguồn mâu thuẫn:
- Mức độ tin cậy:
- Điều kiện áp dụng:
- Điểm chưa rõ:

### Câu hỏi 2

- Kết quả:
- Bằng chứng:
- Nguồn mâu thuẫn:
- Mức độ tin cậy:
- Điều kiện áp dụng:
- Điểm chưa rõ:

---

## 8. KẾT LUẬN CHÍNH

1.
2.
3.

---

## 9. KHUYẾN NGHỊ

### Khuyến nghị 1

- Nội dung:
- Đối tượng:
- Mục đích:
- Điều kiện áp dụng:
- Mức ưu tiên:
- Rủi ro:
- Dữ liệu cần theo dõi:
- Thời điểm đánh giá lại:

---

## 10. ĐIỀU KHÔNG NÊN ÁP DỤNG

-
-
-

---

## 11. RỦI RO

| Rủi ro | Mức độ | Dấu hiệu | Biện pháp giảm thiểu | Điều kiện dừng |
|---|---|---|---|---|
| | | | | |

---

## 12. GIỚI HẠN

-
-
-

---

## 13. MỨC ĐỘ TIN CẬY

- Mức độ tổng thể:
- Cơ sở:
- Kết luận có độ tin cậy cao:
- Kết luận có độ tin cậy trung bình:
- Kết luận chưa đủ cơ sở:

---

## 14. DỮ LIỆU ĐỀ XUẤT CẬP NHẬT HỒ SƠ

- Hồ sơ bị ảnh hưởng:
- Trường dữ liệu:
- Dữ liệu hiện tại:
- Dữ liệu đề xuất:
- Cơ sở:
- Mức độ tin cậy:

---

## 15. DỮ LIỆU CHO LỘ TRÌNH

- Năng lực cần phát triển:
- Thứ tự phát triển:
- Điều kiện bắt đầu:
- Điều kiện chuyển bước:
- Dấu hiệu sẵn sàng:
- Dấu hiệu quá tải:
- Mức độ linh hoạt:
- Nội dung ưu tiên:
- Nội dung chưa nên triển khai:

---

## 16. DỮ LIỆU CHO KẾ HOẠCH THÁNG

- Mục tiêu:
- Nhóm năng lực:
- Loại ngữ cảnh:
- Mức độ khó:
- Cách tổ chức:
- Điều kiện điều chỉnh:

---

## 17. DỮ LIỆU CHO KẾ HOẠCH TUẦN

- Năng lực ưu tiên:
- Loại nội dung:
- Mức độ khó:
- Cách chọn số lượng:
- Ngữ cảnh:
- Cách dùng sở thích:
- Phần bố chuẩn bị:
- Phần tương tác với con:
- Dữ liệu cần ghi:
- Điều kiện hoàn thành:
- Điều kiện kéo dài:
- Điều kiện mở rộng:
- Điều kiện chuyển tiếp:

---

## 18. DỮ LIỆU CHO ĐÁNH GIÁ

### Với bố

- Năng lực:
- Cách kiểm tra:
- Tiêu chí đạt:
- Lỗi cần theo dõi:
- Cách ôn:

### Với con

- Dấu hiệu quan sát:
- Ngữ cảnh:
- Mức độ lặp lại:
- Điều có thể kết luận:
- Điều không được kết luận:
- Dấu hiệu giảm tải:

---

## 19. KHOẢNG TRỐNG CÒN LẠI

-
-
-

---

## 20. KIỂM TRA LẠI

- Ngày cần kiểm tra lại:
- Điều kiện kiểm tra lại sớm:
- Nguồn cần theo dõi:
- Dữ liệu thực tế cần bổ sung:

---

## 21. XÁC NHẬN

- Kết quả kiểm tra:
- Người kiểm tra:
- Người xác nhận:
- Ngày xác nhận:
- Ghi chú:
```

---

# 34. MẪU GÓI RÚT GỌN

Có thể dùng gói rút gọn cho vấn đề nhỏ, ít rủi ro:

```md
# GÓI KẾT QUẢ NGHIÊN CỨU RÚT GỌN

- Mã gói:
- Yêu cầu nghiên cứu:
- Đối tượng:
- Vấn đề:
- Kết luận:
- Khuyến nghị:
- Điều kiện áp dụng:
- Điều không nên áp dụng:
- Rủi ro:
- Giới hạn:
- Mức độ tin cậy:
- Nguồn:
- Dữ liệu cho kế hoạch tuần:
- Dữ liệu cho đánh giá:
- Khoảng trống còn lại:
- Ngày kiểm tra lại:
- Người xác nhận:
```

Không dùng mẫu rút gọn cho:

* Vấn đề phát triển trẻ nhỏ.
* Vấn đề có rủi ro cao.
* Thay đổi lộ trình lớn.
* Kết luận chuyên môn quan trọng.
* Khuyến nghị có thể gây áp lực cho con.
* Quyết định liên quan đến tham khảo chuyên gia.

---

# 35. KIỂM TRA TÍNH HỢP LỆ

Một gói hợp lệ phải có tối thiểu:

* Yêu cầu nghiên cứu gốc.
* Câu hỏi đã được trả lời.
* Nguồn.
* Đánh giá nguồn.
* Kết luận.
* Mức độ tin cậy.
* Điều kiện áp dụng.
* Điều không nên áp dụng.
* Rủi ro.
* Giới hạn.
* Dữ liệu đầu ra phù hợp mục đích.
* Khoảng trống còn lại.
* Ngày kiểm tra lại.
* Người xác nhận.

Nếu thiếu một trong các mục trên:

Gói phải ở trạng thái chờ bổ sung hoặc chờ kiểm tra.

---

# 36. QUY TRÌNH TIẾP NHẬN GÓI NGHIÊN CỨU

Luồng tiếp nhận:

```text
Nhận gói nghiên cứu

↓

Kiểm tra yêu cầu nghiên cứu gốc

↓

Kiểm tra nguồn

↓

Kiểm tra câu trả lời

↓

Kiểm tra điều kiện áp dụng

↓

Kiểm tra rủi ro và giới hạn

↓

Kiểm tra dữ liệu đầu ra

↓

Đánh giá mức độ tin cậy

↓

Trình người dùng xác nhận

↓

Đưa vào sử dụng
```

Không sử dụng trực tiếp chỉ vì gói đã được GPT Nghiên cứu tạo ra.

---

# 37. PHÂN TÁCH VỚI CÁC TỆP KHÁC

## Yêu cầu nghiên cứu

Quy định cần nghiên cứu gì.

## Gói kết quả nghiên cứu

Lưu kết quả đã được tổng hợp và kiểm tra.

## Hồ sơ người học

Lưu trạng thái hiện tại.

## Lộ trình

Sắp xếp hướng phát triển.

## Kế hoạch tuần

Quy định việc sắp thực hiện.

## Nhật ký

Lưu điều đã xảy ra.

## Tổng kết tuần

Tổng hợp kết quả một chu kỳ.

Không trộn các vai trò trên.

---

# 38. NGUYÊN TẮC MỘT BƯỚC MỘT

Phiên bản đầu chỉ cần:

* Một mẫu gói đầy đủ.
* Một mẫu gói rút gọn.
* Một cơ chế kiểm tra hợp lệ.
* Một quy trình tiếp nhận.
* Một cơ chế xác nhận.

Chưa cần:

* Cơ sở dữ liệu nghiên cứu.
* Bảng chấm điểm tự động.
* Hệ thống tự động duyệt nguồn.
* Kho gói nghiên cứu lớn.
* Tự động cập nhật lộ trình.

Chỉ mở rộng sau khi vận hành thực tế.

---

# 39. TIÊU CHÍ HOÀN THÀNH CHUẨN

Chuẩn gói kết quả nghiên cứu được xem là đủ cho phiên bản cơ bản khi:

1. Liên kết được với yêu cầu nghiên cứu.
2. Trả lời được câu hỏi chính.
3. Có nguồn và đánh giá nguồn.
4. Phân biệt bằng chứng và suy luận.
5. Có mức độ tin cậy.
6. Có điều kiện áp dụng.
7. Có điều không nên áp dụng.
8. Có rủi ro.
9. Có giới hạn.
10. Có dữ liệu cho lộ trình hoặc kế hoạch.
11. Có dữ liệu cho đánh giá.
12. Có khoảng trống còn lại.
13. Có ngày kiểm tra lại.
14. Có trạng thái và phiên bản.
15. Có thể được GPT Học tiếng Anh sử dụng mà không phải tự suy đoán lại toàn bộ tài liệu nguồn.

---

# 40. NGUYÊN TẮC CUỐI CÙNG

Gói kết quả nghiên cứu phải:

* Đúng yêu cầu.
* Đúng đối tượng.
* Đúng phạm vi.
* Có nguồn.
* Có kiểm chứng.
* Có điều kiện áp dụng.
* Có giới hạn.
* Có rủi ro.
* Có mức độ tin cậy.
* Có dữ liệu đầu ra rõ ràng.
* Không che giấu khoảng trống.
* Không biến khuyến nghị thành chân lý tuyệt đối.

Mục tiêu cuối cùng:

> Chuyển kết quả nghiên cứu thành một gói tri thức có cấu trúc, đủ tin cậy và đủ rõ để GPT Học tiếng Anh có thể sử dụng trong việc tạo lộ trình, kế hoạch học và đánh giá tiến độ mà không phải tự suy đoán lại từ đầu.
