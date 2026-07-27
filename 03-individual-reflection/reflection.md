# 03 — Individual Reflection (Bài Tự Đánh Giá Cá Nhân)

> **Học viên:** Phạm Trung Hiếu
> **Mã học viên:** 2A202601834
> **Lớp / Khóa học:** AI Product Labs — Day 02  

---

## 1. Vai trò và đóng góp cá nhân trong làm việc nhóm

Trong buổi làm lab nhóm Day 02:

- **Vai trò:** Nhà đầu tư ý tưởng và phát triển giải pháp.
- **Đóng góp chính:**
  - Tham gia đánh giá các bài toán theo pain, workflow, metric và tính khả thi.
  - Góp phần chọn bài toán *“Tóm tắt và trích xuất insight từ Research Paper AI”* vì có bottleneck và baseline thời gian rõ.
  - Phát triển giải pháp theo hướng trích xuất thông tin có cấu trúc thay vì chỉ tóm tắt chung.
  - Cùng nhóm xây dựng Workflow Before / After và xác định bước sinh viên review là human boundary.
  - Phân tích Rule, Workflow và Agent; đề xuất chọn Workflow để giới hạn scope và giảm rủi ro.
  - Góp ý các boundary: không bịa số liệu, phải chỉ rõ trang và nội dung nguồn trong PDF.

---

## 2. AI đã hỗ trợ gì trong quá trình làm bài?

- **Làm rõ bài toán:** AI giúp chuyển pain đọc paper thành bottleneck cụ thể là đọc sâu và trích xuất kiến trúc, dataset, metric.
- **Chuẩn hóa workflow:** AI hỗ trợ chia quy trình thành các bước Current State và Future State rõ ràng.
- **So sánh giải pháp:** AI giúp phân tích sự khác nhau giữa Rule, Workflow và Agent.
- **Xác định rủi ro:** AI gợi ý các rủi ro như hallucination, sai số liệu và mất thông tin kỹ thuật khi tóm tắt.

---

## 3. AI đã sai hoặc hời hợt ở đâu? Tôi đã tự sửa lại thế nào?

- **Điểm AI làm chưa tốt:**
  - Ban đầu AI đề xuất Agent có thể tự tìm, đọc và viết tổng quan nghiên cứu, khiến phạm vi quá lớn.
  - Một số bản tóm tắt quá ngắn, có nguy cơ bỏ mất dataset, metric và thông số thử nghiệm.
  - AI có thể tạo ra thông tin hợp lý về ngôn ngữ nhưng không tồn tại trong PDF.

- **Cách tôi điều chỉnh:**
  - Thu hẹp giải pháp từ Agent xuống Workflow tuyến tính.
  - Yêu cầu đầu ra theo schema cố định: Architecture, Dataset, Metric và Main Contribution.
  - Giữ sinh viên ở bước review và xác minh.
  - Bắt buộc mỗi thông tin phải kèm số trang và đoạn văn nguồn; nội dung không có nguồn phải được đánh dấu cần kiểm tra.

---

## 4. Bài học lớn nhất rút ra sau Day 02 Lab

1. **Problem phải có workflow và metric rõ:** Pain lớn nhưng không đo được thì khó kiểm chứng hiệu quả của giải pháp.
2. **AI không nên thay thế hoàn toàn người đọc:** AI hỗ trợ sàng lọc và trích xuất; sinh viên vẫn phải hiểu và xác minh nội dung.
3. **Workflow phù hợp hơn Agent trong scope hiện tại:** Quy trình tuyến tính dễ kiểm soát, dễ đánh giá và ít rủi ro hơn.
4. **Nguồn gốc thông tin là boundary quan trọng:** Một câu trả lời đúng nhưng không chỉ ra nguồn vẫn chưa đủ tin cậy trong nghiên cứu.

**Nếu làm lại buổi lab này, tôi sẽ thay đổi điều gì:**

Tôi sẽ thử nghiệm sớm trên nhiều loại layout PDF và đo riêng độ chính xác của từng trường thông tin trước khi chốt mục tiêu trên 90%.
