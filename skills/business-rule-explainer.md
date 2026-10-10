# Skill: Business Rule Explainer / Trợ lý tóm tắt quy tắc nghiệp vụ

## Description / Mô tả
This skill is designed to analyze source code or system logic and extract pure business rules, domain constraints, and functional workflows in clear, non-technical language suitable for Product Owners, Business Analysts, and developers.

> Kỹ năng được thiết kế để phân tích mã nguồn hoặc logic hệ thống, từ đó chắt lọc ra các quy tắc nghiệp vụ cốt lõi, ràng buộc miền (domain constraints) và luồng công việc bằng ngôn ngữ rõ ràng, dễ hiểu cho cả người làm kinh doanh lẫn kỹ thuật.

## Instructions / Quy tắc thực hiện
When a user asks to summarize, explain, or extract business rules from a code snippet or logic flow, strictly follow these rules:

> Khi người dùng yêu cầu tóm tắt, giải thích hoặc trích xuất quy tắc nghiệp vụ từ một đoạn code hoặc luồng logic, hãy tuân thủ tuyệt đối các quy tắc sau:

1. ***Focus on Business Value, Not Syntax / Tập trung vào giá trị nghiệp vụ, bỏ qua cú pháp***:
   - Do not explain technical loops or variables. Focus entirely on *what* the system permits, restricts, calculates, or triggers for the end-user/business.
   - **Không giải thích vòng lặp hay biến kỹ thuật. Chỉ tập trung vào việc hệ thống cho phép, hạn chế, tính toán hoặc kích hoạt điều gì cho người dùng/doanh nghiệp.**

2. ***Structure by Business Dimensions / Cấu trúc theo các chiều nghiệp vụ***:
   - ***Core Business Objective / Mục tiêu nghiệp vụ***: What problem this logic solves (e.g., applying discount tiers, validating user eligibility). / **Mục đích chính của đoạn logic này là gì.**
   - ***Conditions & Constraints / Điều kiện & Ràng buộc***: Who qualifies, what limits apply, or what validation rules must be satisfied (if-else translated into business policies). / **Các điều kiện tiên quyết và giới hạn áp dụng.**
   - ***Actions & Outcomes / Hành động & Kết quả***: What happens next when conditions are met or failed (e.g., status changes, fees charged, notifications sent). / **Kết quả đầu ra hoặc thay đổi trạng thái sau khi xử lý.**

3. ***Tone and Style / Văn phong***:
   - Clear, professional, concise, and structured (use bullet points or business requirement formats like Given-When-Then where appropriate).
   - **Rõ ràng, chuyên nghiệp, ngắn gọn và có cấu trúc (ưu tiên dùng danh sách hoặc định dạng điều kiện nghiệp vụ).**