# LEARNING_PLAN_STANDARD

Phiên bản: 01.000

---

# CHUẨN KẾ HOẠCH HỌC

## MỤC ĐÍCH

Tệp này quy định cấu trúc tối thiểu của:

* Kế hoạch tháng hiện tại.
* Kế hoạch tuần hiện tại.
* Tổng kết tuần.

GPT sử dụng chuẩn này để:

* Sinh kế hoạch học.
* Kiểm tra tính hợp lệ.
* Điều chỉnh tiến độ.
* Cập nhật hồ sơ người học.

Tệp này không lưu dữ liệu thực tế.

---

# 1. CURRENT_MONTH

Mỗi kế hoạch tháng phải có:

```yaml id="ff90b7"
month:
    objective:
    focus:
    contexts:
    father_focus:
    child_focus:
    expected_progress:
    review_condition:
```

## Giải thích

* `objective`: Mục tiêu của tháng.
* `focus`: Trọng tâm năng lực.
* `contexts`: Các ngữ cảnh dự kiến.
* `father_focus`: Phần bố cần phát triển.
* `child_focus`: Phần con cần tiếp cận.
* `expected_progress`: Tiến độ mong đợi.
* `review_condition`: Điều kiện rà soát.

---

# 2. CURRENT_WEEK

Mỗi kế hoạch tuần phải có:

```yaml id="35oz9r"
week:
    vocabulary:
    short_sentences:
    activities:
    father_homework:
    observation_points:
    completion_condition:
```

## Giải thích

* `vocabulary`: Nhóm từ của tuần.
* `short_sentences`: Câu ngắn ưu tiên.
* `activities`: Hoạt động cùng con.
* `father_homework`: Bài tập của bố.
* `observation_points`: Điều cần quan sát.
* `completion_condition`: Điều kiện hoàn thành.

---

# 3. WEEKLY_SUMMARY

Mỗi tổng kết tuần phải có:

```yaml id="lyr5sx"
summary:
    successes:
    failures:
    lessons_learned:
    profile_changes:
    next_actions:
```

## Giải thích

* `successes`: Điều hiệu quả.
* `failures`: Điều không hiệu quả.
* `lessons_learned`: Bài học rút ra.
* `profile_changes`: Điều cần cập nhật hồ sơ.
* `next_actions`: Hướng xử lý tuần tiếp theo.

---

# 4. LUỒNG VẬN HÀNH

```text id="fxhz1e"
LEARNER_PROFILE_CURRENT

↓

CURRENT_MONTH

↓

CURRENT_WEEK

↓

WEEKLY_SUMMARY

↓

Cập nhật PROFILE nếu cần

↓

Lặp lại
```

---

# 5. QUY TẮC

* Không tạo kế hoạch vượt quá một tháng chi tiết.
* Không tạo kế hoạch tuần nếu thiếu hồ sơ.
* Không ép hoàn thành đúng thời gian.
* Có thể kéo dài hoặc rút ngắn tuần học.
* Ưu tiên nghe và nói trước.
* Ưu tiên sở thích hiện tại của con.
* Bố luôn học trước một bước ngắn.
* Chỉ cập nhật hồ sơ khi có dữ liệu được xác nhận.

---

# 6. KIỂM TRA TÍNH HỢP LỆ

Một kế hoạch hợp lệ khi:

* Có mục tiêu rõ ràng.
* Có trọng tâm học.
* Có hoạt động thực tế.
* Có điều kiện hoàn thành.
* Có điều cần quan sát.
* Có tổng kết sau khi kết thúc.

Nếu thiếu một trong các thành phần trên:

```text id="4ekttd"
CHỜ BỔ SUNG
```

---

# 7. NGUYÊN TẮC CUỐI CÙNG

GPT chỉ cần nhớ:

```text id="2sh9kt"
PROFILE

↓

MONTH

↓

WEEK

↓

SUMMARY

↓

PROFILE
```

Đây là vòng lặp vận hành duy nhất của hệ thống học tiếng Anh bố và con.
