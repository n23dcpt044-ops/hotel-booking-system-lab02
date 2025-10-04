# hotel-booking-system-lab02
gioi thieu ve du an
# 🏨 LAB 02: HỆ THỐNG QUẢN LÝ ĐẶT PHÒNG KHÁCH SẠN (HOTEL BOOKING SYSTEM)

Dự án này là một bài thực hành về Phân tích Yêu cầu, Thiết kế Hệ thống và Ứng dụng quy trình Agile-Scrum sử dụng UML, ERD, Jira và GitHub.

## 🎯 1. MỤC TIÊU DỰ ÁN

Mục tiêu chính của hệ thống là cung cấp một nền tảng quản lý đặt phòng toàn diện, bao gồm cả trải nghiệm đặt phòng trực tuyến cho Khách hàng và nghiệp vụ quản lý nội bộ cho Lễ tân, Quản lý và Buồng phòng.

## 🛠️ 2. PHÂN TÍCH VÀ THIẾT KẾ (UML & ERD)

### 2.1. Các Tác nhân (Actors) Chính

| Tác nhân | Vai trò |
| :--- | :--- |
| **Guest** | Tìm kiếm, Đặt phòng, Thanh toán online. |
| **Receptionist** | Check-in, Check-out, Quản lý đặt phòng tại quầy. |
| **Manager** | Quản lý giá, phòng, và xem báo cáo doanh thu. |
| **Housekeeping** | Cập nhật trạng thái dọn dẹp phòng. |
| **Payment Gateway** | Xử lý giao dịch thanh toán trực tuyến. |

### 2.2. Các Artefact Thiết kế

Dưới đây là các tài liệu thiết kế cốt lõi của hệ thống:

| Tài liệu | Mô tả | Liên kết File |
| :--- | :--- | :--- |
| **Use Case Diagram** | Thể hiện phạm vi và chức năng chính của hệ thống. | [Link to Use_Case_Diagram.png/drawio](Use_Case_Diagram.png) |
| **Sequence Diagram (Online Booking)** | Mô tả luồng tương tác khi Khách hàng đặt và thanh toán online. | [Link to Online_Booking_Sequence.png/drawio](Online_Booking_Sequence.png) |
| **Sequence Diagram (Check-in/out)** | Mô tả luồng nghiệp vụ Lễ tân khi nhận/trả phòng. | [Link to Checkin_Checkout_Sequence.png/drawio](Checkin_Checkout_Sequence.png) |
| **Entity Relationship Diagram (ERD)** | Thiết kế cơ sở dữ liệu với 6 bảng chính (Guest, Room, Reservation, v.v.) và các mối quan hệ 1-N. | [Link to ERD.png/drawio](ERD.png) |

## ⚙️ 3. TRIỂN KHAI QUY TRÌNH AGILE-SCRUM

Dự án được quản lý theo mô hình **Scrum** trên nền tảng **Jira** và đồng bộ với **GitHub**.

### 3.1. Product Backlog (Các User Story chính)

Các yêu cầu được định nghĩa theo định dạng: *As a [role], I want [function], so that [benefit].*

1.  **Tìm phòng:** As a Guest, I want to search and view available rooms, so that I can find the perfect room for my trip.
2.  **Đặt phòng & Thanh toán:** As a Guest, I want to book a room and pay online, so that my room is secured immediately.
3.  **Check-in:** As a Receptionist, I want to check guests in quickly, so that the arrival process is smooth and efficient.
4.  **Check-out:** As a Receptionist, I want to total charges and perform check-out, so that I can collect full payment.
5.  **Quản lý Giá:** As a Manager, I want to manage room types and pricing, so that I can adjust the pricing strategy flexibly.
6.  **Báo cáo:** As a Manager, I want to view revenue reports, so that I can monitor financial performance.
7.  **Buồng phòng:** As Housekeeping, I want to receive a list of rooms needing cleaning, so that I can prioritize my work.

### 3.2. Kế hoạch Sprint (4 Sprints)

| Sprint | Mục tiêu chính |
| :--- | :--- |
| **Sprint 1** | **Nền tảng & Tìm kiếm:** Auth, Tìm phòng, Xem chi tiết. |
| **Sprint 2** | **Đặt phòng:** Đặt phòng & giữ chỗ, Quản lý đặt phòng cơ bản. |
| **Sprint 3** | **Nghiệp vụ cốt lõi:** Thanh toán & Check-in/out. |
| **Sprint 4** | **Phân hệ Quản lý:** Báo cáo, Housekeeping, Tối ưu & Release. |

### 3.3. Đồng bộ hóa Jira ↔ GitHub

Quá trình phát triển được theo dõi bằng cách sử dụng **Smart Commit** để tự động cập nhật trạng thái Task và ghi lại thời gian làm việc trong Jira.

* **Cú pháp ví dụ:** `SCRUM-5 #time 30m #comment Updated design document. #review`
