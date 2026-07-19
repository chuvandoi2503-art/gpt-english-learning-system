# MEMORY_INDEX

Phiên bản: 01.000

---

# REPOSITORY

Owner:

chuvandoi2503-art

Runtime Repository:

gpt-english-learning-system

Core Repository:

gpt-system-core

---

# MỤC ĐÍCH

Memory Index là bản đồ Runtime của GPT ENGLISH LEARNING SYSTEM.

GPT phải đọc tệp này trước khi truy cập Runtime Repository.

Memory Index dùng để:

- Định vị Core.
- Định vị Runtime.
- Định vị Memory.
- Xác định Load Strategy.

Không tự suy đoán path.

Không sử dụng bộ nhớ hội thoại làm nguồn chân lý.

---

# CORE REPOSITORY

## 00 - HIẾN PHÁP GPT

Repository:

gpt-system-core

Path:

CORE/00 - HIẾN PHÁP GPT.md

---

## 01 - QUY TẮC VẬN HÀNH

Path:

CORE/01 - QUY TẮC VẬN HÀNH.md

---

## 02 - TIÊU CHUẨN PHÂN TÁCH TRÁCH NHIỆM

Path:

CORE/02 - TIÊU CHUẨN PHÂN TÁCH TRÁCH NHIỆM.md

---

## 05 - NGUYÊN TẮC KIẾN TRÚC

Path:

CORE/05 - NGUYÊN TẮC KIẾN TRÚC.md

---

# RUNTIME RULE

## RULE_ENGLISH

Repository:

gpt-english-learning-system

Path:

rules/RULE_ENGLISH.md

---

# KNOWLEDGE

## KN_02_ENGLISH

Repository:

gpt-english-learning-system

Path:

knowledge/KN_02_ENGLISH.md

Trạng thái:

LOAD_ON_DEMAND

---

# SYSTEM

## BUSINESS_SPEC_ENGLISH

Path:

SYSTEM/BUSINESS_SPEC_ENGLISH.md

## LEARNER_PROFILE_STANDARD

Path:

SYSTEM/LEARNER_PROFILE_STANDARD.md

## LEARNING_PLAN_STANDARD

Path:

SYSTEM/LEARNING_PLAN_STANDARD.md

---

# DATA

## LEARNER_PROFILE_CURRENT

Path:

data/LEARNER_PROFILE_CURRENT.md

---

## CURRENT_MONTH

Path:

learning/CURRENT_MONTH.md

---

## CURRENT_WEEK

Path:

learning/CURRENT_WEEK.md

---

# WORKING MEMORY

## WM_03A_ENGLISH

Path:

memory/WM_03A_ENGLISH.md

Trạng thái:

CHƯA KHỞI TẠO

---

## WM_04_1_ENGLISH

Path:

memory/WM_04_1_ENGLISH.md

Trạng thái:

CHƯA KHỞI TẠO

---

# LONG TERM MEMORY

## LM_03B_ENGLISH_CURRENT

Path:

memory/LM_03B_ENGLISH_CURRENT.md

Trạng thái:

CHƯA KHỞI TẠO

---

# HISTORY

## WEEKLY_SUMMARY

Path:

history/WEEKLY_SUMMARY.md

---

## LESSONS_LEARNED

Path:

history/LESSONS_LEARNED.md

---

# KHỞI TẠO PHIÊN MẶC ĐỊNH

## BƯỚC 1

Đọc:

- CORE/00
- CORE/01
- CORE/02
- CORE/05

---

## BƯỚC 2

Đọc Runtime:

- RULE_ENGLISH
- LEARNER_PROFILE_CURRENT
- CURRENT_MONTH
- CURRENT_WEEK

---

# LOAD ON DEMAND

- KN_02_ENGLISH
- BUSINESS_SPEC_ENGLISH
- LEARNING_PLAN_STANDARD
- WEEKLY_SUMMARY
- LESSONS_LEARNED
- WM_03A_ENGLISH
- WM_04_1_ENGLISH
- LM_03B_ENGLISH_CURRENT

---

# LOAD STRATEGY

AUTO LOAD:

- CORE/00
- CORE/01
- CORE/02
- CORE/05

SESSION LOAD:

- RULE_ENGLISH
- LEARNER_PROFILE_CURRENT
- CURRENT_MONTH
- CURRENT_WEEK

LOAD ON DEMAND:

- KNOWLEDGE
- SYSTEM
- MEMORY
- HISTORY

---

# TRẠNG THÁI SAU KHỞI TẠO

GPT phải biết:

- Hai bố con hiện đang ở trạng thái nào.
- Đang học tháng nào.
- Đang học tuần nào.
- Có công việc nào đang dở không.
- Hệ thống đã bắt đầu vận hành hay chưa.

---

# NGUYÊN TẮC CUỐI CÙNG

Memory Index là bản đồ Runtime của GPT ENGLISH LEARNING SYSTEM.

GPT không được nạp toàn bộ Repository khi khởi tạo phiên.

Chỉ nạp tối thiểu để bắt đầu vận hành.

Mọi quyết định kiến trúc phải tuân thủ:

- Thực tế > Lý thuyết.
- Vận hành được > Kiến trúc đẹp.
- Học cùng con > Tiến độ lý tưởng.
- Một bước một.
- Nếu tuần này chưa dùng thì chưa xây.
