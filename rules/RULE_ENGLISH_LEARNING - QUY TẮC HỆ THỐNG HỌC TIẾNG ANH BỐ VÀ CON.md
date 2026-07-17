# RULE_ENGLISH_LEARNING

Phiên bản: 01.000

---

# QUY TẮC HỆ THỐNG HỌC TIẾNG ANH BỐ VÀ CON

---

# 1. MỤC ĐÍCH

Tài liệu này quy định các nguyên tắc bắt buộc khi thiết kế và vận hành hệ thống học tiếng Anh dành cho bố và con.

Tài liệu này không chứa:

* Nội dung bài học cụ thể.
* Danh sách từ vựng.
* Danh sách câu.
* Chủ đề học.
* Lộ trình cố định.
* Phương pháp chưa được nghiên cứu.
* Kết luận chuyên môn chưa được kiểm chứng.

Các nội dung trên phải được tạo từ:

* Hồ sơ người học.
* Mục tiêu học.
* Dữ liệu đời sống.
* Gói kết quả nghiên cứu.
* Tiến độ học thực tế.

---

# 2. PHẠM VI HIỆN TẠI

Hệ thống hiện phục vụ:

* Bố.
* Con.
* Hai bố con học tiếng Anh cùng nhau.
* Bắt đầu từ con số 0.
* Ưu tiên nghe và nói.
* Học thông qua đời sống thực tế.

Trong giai đoạn hiện tại, chưa phát triển sâu:

* Đọc.
* Viết.
* Ngữ pháp hệ thống.
* Học thuật.
* Thi cử.
* Chứng chỉ.
* Nhiều ngôn ngữ.
* Tự động hóa toàn bộ.

Không tự mở rộng phạm vi khi chưa có quyết định được xác nhận.

---

# 3. MỤC TIÊU HỆ THỐNG

Mục tiêu dài hạn là giúp hai bố con có thể giao tiếp với nhau bằng tiếng Anh trong đời sống thực tế.

Mục tiêu của bố:

* Học tiếng Anh từ con số 0.
* Nghe đúng.
* Hiểu đúng.
* Phát âm đủ chính xác.
* Ghi nhớ được.
* Nói được trong ngữ cảnh.
* Có khả năng hướng dẫn lại cho con.
* Học song hành theo tiến độ thực tế của con.

Mục tiêu của con:

* Tiếp xúc tiếng Anh phù hợp.
* Gắn ngôn ngữ với đời sống.
* Nghe và nhận diện.
* Hiểu trong ngữ cảnh.
* Phản ứng tự nhiên.
* Bắt chước khi sẵn sàng.
* Dần chủ động giao tiếp với bố.

---

# 4. NGUYÊN TẮC MỘT BƯỚC MỘT

Chỉ thiết kế và triển khai thành phần cần cho giai đoạn hiện tại.

Ưu tiên:

Đơn giản

↓

Dễ vận hành

↓

Dễ ghi nhận

↓

Dễ điều chỉnh

Không tạo thêm:

* Mô-đun.
* Quy trình.
* Tệp.
* Bộ nhớ.
* GPT.
* Tự động hóa.
* Công cụ.

nếu chưa tạo giá trị vận hành thực tế.

Không thiết kế quá xa chỉ để phục vụ khả năng mở rộng lý thuyết.

---

# 5. NGUYÊN TẮC PHÂN TÁCH TRÁCH NHIỆM

Hệ thống phải phân biệt rõ các tầng sau:

## 5.1. Kiến trúc

Kiến trúc chịu trách nhiệm:

* Xác định thành phần.
* Xác định luồng dữ liệu.
* Xác định đầu vào và đầu ra.
* Xác định ranh giới trách nhiệm.
* Xác định điều kiện xử lý.

Kiến trúc không quyết định nội dung học cụ thể.

## 5.2. Nghiên cứu

Nghiên cứu chịu trách nhiệm:

* Tìm kiếm dữ liệu.
* Kiểm chứng nguồn.
* Đánh giá phương pháp.
* Xác định nội dung phù hợp.
* Xác định cách đánh giá.
* Xác định rủi ro và giới hạn.
* Đóng gói kết quả nghiên cứu.

Nghiên cứu không tự thay đổi kiến trúc.

## 5.3. Bộ tạo lộ trình

Bộ tạo lộ trình chịu trách nhiệm chuyển gói kết quả nghiên cứu thành lộ trình có cấu trúc.

Bộ tạo lộ trình không tự nghiên cứu.

## 5.4. Bộ tạo đơn vị học

Bộ tạo đơn vị học chịu trách nhiệm chuyển một phần lộ trình thành hoạt động học có thể thực hiện.

Bộ tạo đơn vị học không tự thay đổi mục tiêu hoặc lộ trình.

## 5.5. Bộ ghi nhận

Bộ ghi nhận chỉ lưu những gì đã xảy ra.

Bộ ghi nhận không tự suy diễn hoặc đánh giá.

## 5.6. Bộ đánh giá

Bộ đánh giá phân tích dữ liệu và đề xuất hướng xử lý.

Bộ đánh giá không tự áp dụng thay đổi.

Người dùng là người quyết định cuối cùng.

---

# 6. NGUYÊN TẮC NGHIÊN CỨU TRƯỚC KHI TẠO NỘI DUNG

Không tạo lộ trình hoặc đơn vị học thực tế khi chưa có đủ:

* Hồ sơ người học.
* Mục tiêu học.
* Khoảng trống cần nghiên cứu.
* Gói kết quả nghiên cứu phù hợp.
* Nguồn đủ tin cậy.
* Điều kiện áp dụng rõ ràng.

Nếu thiếu dữ liệu:

Xác định khoảng trống

↓

Tạo yêu cầu nghiên cứu

↓

Nghiên cứu

↓

Đóng gói kết quả

↓

Xác nhận

Không tự điền nội dung bằng suy đoán.

---

# 7. NGUYÊN TẮC CON QUYẾT ĐỊNH TỐC ĐỘ

Lộ trình được tổ chức theo tiến độ thực tế của con.

Bố học đầy đủ hơn nhưng không chạy trước con quá xa.

Tốc độ học phải dựa trên:

* Tuổi.
* Giai đoạn phát triển.
* Khả năng chú ý.
* Khả năng tiếp nhận.
* Mức độ hứng thú.
* Phản ứng thực tế.
* Điều kiện sinh hoạt.
* Kết quả nghiên cứu.
* Dữ liệu tiến độ.

Không tăng độ khó chỉ vì đã hết một khoảng thời gian trên lịch.

---

# 8. NGUYÊN TẮC BỐ HỌC TRƯỚC MỘT BƯỚC NGẮN

Trước khi sử dụng nội dung với con, bố phải:

* Nghe được mẫu đúng.
* Hiểu đúng nghĩa.
* Phát âm đủ rõ.
* Biết ngữ cảnh sử dụng.
* Nói được nội dung cần dùng.
* Đạt điều kiện chuẩn bị của đơn vị học.

Bố không cần học trước quá nhiều.

Khoảng học trước do lộ trình và gói kết quả nghiên cứu xác định.

Không viết cứng khoảng thời gian nếu chưa có cơ sở.

---

# 9. NGUYÊN TẮC PHÁT ÂM CỦA BỐ

Bố không sử dụng một từ hoặc câu làm mẫu cho con khi:

* Chưa có nguồn phát âm đủ tin cậy.
* Chưa nghe rõ.
* Chưa xác định được cách phát âm.
* Chưa luyện đủ để nói ổn định.
* Chưa hiểu cách dùng trong ngữ cảnh.

Nếu chưa đạt điều kiện:

* Gắn trạng thái chưa sẵn sàng.
* Tiếp tục luyện.
* Chưa đưa vào phần tương tác với con.

Mục tiêu không phải tạo giọng hoàn hảo.

Mục tiêu là tạo mẫu âm đủ đúng, rõ và ổn định.

---

# 10. NGUYÊN TẮC ƯU TIÊN NGHE VÀ NÓI

Thứ tự ưu tiên hiện tại:

Nghe

↓

Nhận diện

↓

Hiểu

↓

Phản ứng

↓

Bắt chước

↓

Nói

Đọc và viết trong giai đoạn hiện tại chỉ hỗ trợ bố:

* Nhận diện mặt chữ.
* Ghi nhớ từ.
* Làm bài tập củng cố.
* Ghi chú lỗi.
* Theo dõi tiến độ.

Không biến đọc và viết thành trục học chính.

---

# 11. NGUYÊN TẮC KHÔNG ÉP CON TẠO ĐẦU RA

Con không bắt buộc phải:

* Nói ngay.
* Lặp lại ngay.
* Trả lời ngay.
* Phát âm tròn chữ.
* Ngồi học theo tiết dài.
* Hoàn thành số lượng cố định.
* Làm bài kiểm tra như người lớn.

Các phản ứng hợp lệ gồm:

* Chú ý.
* Quan sát.
* Nhìn.
* Chỉ.
* Cầm.
* Đưa.
* Thực hiện hành động.
* Phát âm một phần.
* Im lặng nhưng có biểu hiện hiểu.
* Chủ động sử dụng vào thời điểm khác.

Không kết luận con không học được chỉ vì chưa nói.

---

# 12. NGUYÊN TẮC HIỂU TRƯỚC KHI NÓI

Với con, tiến trình mặc định là:

Tiếp xúc

↓

Chú ý

↓

Nhận diện

↓

Hiểu

↓

Phản ứng

↓

Bắt chước

↓

Chủ động sử dụng

Không bỏ qua các bước đầu để ép con nói.

Không lấy khả năng nói làm chỉ số duy nhất của tiến độ.

---

# 13. NGUYÊN TẮC ĐỜI SỐNG THẬT

Đời sống thật là môi trường học chính.

Nội dung học phải ưu tiên gắn với:

* Người thật.
* Đồ vật thật.
* Hoạt động thật.
* Địa điểm thật.
* Sự kiện thật.
* Thói quen thật.
* Tình huống giao tiếp thật.

Dữ liệu đời sống là đầu vào, không phải bài học hoàn chỉnh.

Luồng bắt buộc:

Dữ liệu đời sống

↓

Nghiên cứu

↓

Lộ trình

↓

Đơn vị học

↓

Thực hành

Không tự chuyển dữ liệu đời sống thành bài học khi chưa qua xử lý phù hợp.

---

# 14. NGUYÊN TẮC MỘT NGỮ CẢNH, HAI MỨC HỌC

Bố và con có thể học từ cùng một ngữ cảnh.

Mức học của bố có thể gồm:

* Nghe.
* Hiểu.
* Phát âm.
* Ghi nhớ.
* Nói.
* Thực hành.
* Tự kiểm tra.
* Hướng dẫn lại.

Mức học của con có thể gồm:

* Tiếp xúc.
* Chú ý.
* Nhận diện.
* Hiểu.
* Phản ứng.
* Bắt chước.
* Chủ động sử dụng.

Không dùng cùng một bài tập hoặc tiêu chí đánh giá cho bố và con.

---

# 15. NGUYÊN TẮC TÁCH TIẾN ĐỘ BỐ VÀ CON

Mỗi đơn vị học phải ghi riêng:

## Tiến độ của bố

* Đã chuẩn bị hay chưa.
* Nghe được hay chưa.
* Phát âm đạt hay chưa.
* Ghi nhớ được hay chưa.
* Sử dụng được hay chưa.
* Còn lỗi gì.

## Tiến độ của con

* Đã tiếp xúc hay chưa.
* Có chú ý hay không.
* Có nhận diện hay không.
* Có hiểu hay không.
* Có phản ứng hay không.
* Có bắt chước hay không.
* Có chủ động sử dụng hay không.

Không gộp tiến độ của hai người thành một điểm số chung.

---

# 16. NGUYÊN TẮC ĐƠN VỊ HỌC

Một đơn vị học chỉ hợp lệ khi có tối thiểu:

* Mã đơn vị học.
* Người học.
* Mục tiêu.
* Ngữ cảnh.
* Dữ liệu ngôn ngữ.
* Phần chuẩn bị của bố.
* Phần tương tác với con.
* Cách thực hành.
* Dữ liệu cần ghi nhận.
* Điều kiện hoàn thành.
* Điều kiện ôn lại.
* Nguồn nghiên cứu.

Nếu thiếu thành phần bắt buộc:

Không phát hành đơn vị học.

---

# 17. NGUYÊN TẮC BÀI TẬP CỦA BỐ

Bố phải có bài tập phù hợp để:

* Kiểm tra nghe.
* Kiểm tra phát âm.
* Kiểm tra ghi nhớ.
* Kiểm tra nói.
* Kiểm tra sử dụng trong ngữ cảnh.
* Phát hiện lỗi.
* Ôn lại.

Bài tập phải phục vụ khả năng sử dụng tiếng Anh thật với con.

Không tạo bài tập chỉ để hoàn thành hình thức.

---

# 18. NGUYÊN TẮC ĐÁNH GIÁ CON

Không kiểm tra con theo cách:

* Hỏi dồn.
* Bắt nhắc lại.
* Chấm điểm.
* So sánh với trẻ khác.
* Ép trả lời.
* Kết luận từ một lần quan sát.

Việc đánh giá con phải dựa trên:

* Quan sát tự nhiên.
* Phản ứng trong ngữ cảnh.
* Hành động.
* Mức độ hiểu.
* Mức độ chủ động.
* Dữ liệu lặp lại theo thời gian.

---

# 19. NGUYÊN TẮC GHI NHẬT KÝ

Nhật ký phải phân biệt:

* Sự kiện.
* Quan sát.
* Minh chứng.
* Nhận định tạm thời.
* Câu hỏi cần nghiên cứu.

Nhật ký không được tự thêm:

* Chẩn đoán.
* Phán xét.
* So sánh.
* Kết luận chưa đủ cơ sở.
* Nội dung không thực sự xảy ra.

Nếu thông tin chưa được xác nhận, phải ghi rõ trạng thái.

---

# 20. NGUYÊN TẮC ĐÁNH GIÁ TIẾN ĐỘ

Đánh giá tiến độ phải dựa trên nhiều nguồn:

* Mục tiêu.
* Lộ trình.
* Nhật ký học.
* Bài tập của bố.
* Quan sát con.
* Minh chứng.
* Dữ liệu qua thời gian.

Không đánh giá chỉ dựa trên:

* Số lượng từ.
* Số ngày học.
* Một lần ghi âm.
* Một lần con không phản ứng.
* Cảm giác chủ quan.

Mọi kết luận quan trọng phải nêu:

* Cơ sở.
* Mức độ tin cậy.
* Điều kiện áp dụng.
* Rủi ro sai lệch.

---

# 21. NGUYÊN TẮC ĐIỀU CHỈNH

Hệ thống được phép đề xuất:

* Giữ nguyên.
* Ôn lại.
* Giảm tải.
* Tăng độ khó.
* Đổi ngữ cảnh.
* Đổi hoạt động.
* Tạm dừng.
* Chuyển giai đoạn.
* Nghiên cứu lại.

Hệ thống không tự áp dụng thay đổi khi chưa có xác nhận của người dùng.

Không ghi đè lộ trình cũ.

Mọi thay đổi phải có:

* Nội dung thay đổi.
* Lý do.
* Dữ liệu làm cơ sở.
* Người xác nhận.
* Phiên bản mới.

---

# 22. NGUYÊN TẮC NGHIÊN CỨU LẠI

Phải tạo yêu cầu nghiên cứu mới khi:

* Thiếu dữ liệu để quyết định.
* Kết quả thực tế khác khuyến nghị cũ.
* Phương pháp không tạo hiệu quả.
* Bố gặp lỗi kéo dài.
* Con có thay đổi rõ.
* Mục tiêu thay đổi.
* Gói nghiên cứu đã cũ.
* Xuất hiện rủi ro mới.

Không áp dụng máy móc một kết quả nghiên cứu đã không còn phù hợp.

---

# 23. NGUYÊN TẮC NGUỒN CHÂN LÝ

Mỗi loại dữ liệu phải có một nguồn chân lý riêng:

* Hồ sơ người học là nguồn chân lý về người học.
* Mục tiêu là nguồn chân lý về hướng học.
* Gói kết quả nghiên cứu là nguồn chân lý về tri thức đã kiểm chứng.
* Lộ trình là nguồn chân lý về kế hoạch đang áp dụng.
* Đơn vị học là nguồn chân lý về hoạt động cần thực hiện.
* Nhật ký là nguồn chân lý về điều đã xảy ra.
* Đánh giá tiến độ là nguồn chân lý về trạng thái đã phân tích.

GPT không phải nguồn chân lý.

GPT là bộ xử lý và hỗ trợ người dùng.

---

# 24. NGUYÊN TẮC QUẢN LÝ PHIÊN BẢN

Các dữ liệu sau phải có phiên bản:

* Hồ sơ người học.
* Mục tiêu.
* Gói kết quả nghiên cứu.
* Lộ trình.
* Đơn vị học.
* Đánh giá tiến độ.

Không được:

* Ghi đè âm thầm.
* Xóa lịch sử thay đổi.
* Dùng bản nháp như bản chính thức.
* Thay đổi nội dung đã xác nhận mà không ghi lý do.

---

# 25. NGUYÊN TẮC AN TOÀN VÀ GIỚI HẠN

Hệ thống không thay thế:

* Bác sĩ.
* Chuyên gia phát triển trẻ em.
* Chuyên gia ngôn ngữ trị liệu.
* Giáo viên chuyên môn.
* Chuyên gia phát âm.

Khi xuất hiện vấn đề vượt ngoài phạm vi học tiếng Anh thông thường, hệ thống phải:

* Nêu rõ giới hạn.
* Không tự chẩn đoán.
* Không tạo cảm giác chắc chắn giả.
* Đề xuất tham khảo chuyên gia phù hợp.

---

# 26. NGUYÊN TẮC KHÔNG TỰ ĐỘNG HÓA QUÁ SỚM

Không tự động hóa một quy trình khi:

* Quy trình chưa ổn định.
* Đầu vào chưa chuẩn.
* Đầu ra chưa rõ.
* Tiêu chí kiểm tra chưa đủ.
* Chưa xác định được giá trị thực tế.

Ưu tiên vận hành thủ công hoặc bán thủ công.

Chỉ tự động hóa khi bước đó:

* Đã lặp lại đủ nhiều.
* Có đầu vào ổn định.
* Có đầu ra rõ ràng.
* Có tiêu chí kiểm tra.
* Có cơ chế xử lý lỗi.

---

# 27. NGUYÊN TẮC KHÔNG THIẾT KẾ QUÁ XA

Trong phiên bản hiện tại:

* Chỉ tập trung tiếng Anh.
* Chỉ tập trung nghe và nói.
* Chỉ tập trung bố và con.
* Chỉ xây thành phần cần cho vận hành ban đầu.

Không triển khai trước:

* Ngôn ngữ thứ hai.
* Ngôn ngữ thứ ba.
* Hệ điều hành học tập tổng quát.
* Ứng dụng quy mô lớn.
* Kho dữ liệu phức tạp.
* Hệ thống tự động hóa toàn bộ.

Khả năng mở rộng chỉ được giữ ở cấp nguyên tắc.

---

# 28. LUỒNG VẬN HÀNH BẮT BUỘC

Hồ sơ bố và con

↓

Mục tiêu nghe và nói

↓

Dữ liệu đời sống

↓

Yêu cầu nghiên cứu

↓

Gói kết quả nghiên cứu

↓

Người dùng xác nhận

↓

Tạo lộ trình

↓

Người dùng xác nhận

↓

Tạo đơn vị học

↓

Bố chuẩn bị

↓

Bố và con thực hành

↓

Ghi nhật ký

↓

Đánh giá tiến độ

↓

Đề xuất xử lý

↓

Người dùng quyết định

Không bỏ qua bước nghiên cứu hoặc xác nhận khi dữ liệu chưa đủ.

---

# 29. QUYỀN QUYẾT ĐỊNH CUỐI CÙNG

Hệ thống có trách nhiệm:

* Phân tích.
* Đề xuất.
* Cảnh báo.
* Xác định khoảng trống.
* Đưa ra phương án.

Người dùng quyết định:

* Chấp nhận hay không.
* Học tiếp hay không.
* Ôn lại hay không.
* Thay đổi phương pháp hay không.
* Điều chỉnh lộ trình hay không.
* Khi nào mở rộng hệ thống.

Hệ thống không quyết định thay người dùng.

---

# 30. NGUYÊN TẮC CUỐI CÙNG

Mọi thành phần của hệ thống phải phục vụ mục tiêu:

Giúp bố và con học tiếng Anh cùng nhau theo cách:

* Thực tế.
* Phù hợp.
* Có kiểm chứng.
* Không gây áp lực.
* Có thể ghi nhận.
* Có thể điều chỉnh.
* Gắn với đời sống.
* Dễ duy trì lâu dài.

Khi có nhiều phương án:

Ưu tiên phương án:

* Đơn giản hơn.
* Ít thành phần hơn.
* Gắn với đời sống hơn.
* Dễ vận hành hơn.
* Dễ kiểm tra hơn.
* Dễ sửa hơn.
* Có cơ sở rõ hơn.
