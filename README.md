# LAB02-AGILE-SCRUM-JIRA-GITHUB
Lab 02 – Phân tích yêu cầu &amp; Thiết kế Use Case (Hotel Booking System)
### 🏨 Hệ thống Quản lý Khách sạn (Hotel Management System)
### 📖 Giới thiệu

Dự án Hệ thống Quản lý Khách sạn mô phỏng quy trình hoạt động cơ bản của một khách sạn hiện đại, bao gồm các chức năng đặt phòng, check-in, check-out, và quản lý thông tin khách hàng.
Mục tiêu là giúp sinh viên hiểu rõ cách phân tích – thiết kế hệ thống hướng đối tượng (OOAD) thông qua việc xây dựng Use Case Diagram, Sequence Diagram, Class Diagram và Package Diagram.

### ⚙️ Chức năng chính
1. Đặt phòng online

Khách hàng xem danh sách phòng trống.

Chọn phòng và ngày nhận/trả.

Nhập thông tin cá nhân.

Xác nhận đặt phòng.

2. Check-in / Check-out

Nhân viên xác thực thông tin khách hàng khi đến.

Cập nhật trạng thái phòng từ “Trống” → “Đang sử dụng”.

Khi khách rời đi, hệ thống tính hóa đơn và cập nhật lại trạng thái phòng.

3. Quản lý phòng & khách hàng

Quản lý danh sách phòng, loại phòng, giá phòng.

Quản lý thông tin khách hàng và lịch sử đặt phòng.

### 🧩 Thành phần hệ thống
Thành phần	Mô tả
User (Khách hàng)	Người dùng cuối, thực hiện đặt phòng online.
Receptionist (Lễ tân)	Quản lý check-in/out và xác nhận thông tin khách hàng.
System (Hệ thống)	Lưu trữ, xử lý, và phản hồi dữ liệu đặt phòng.
Database	Lưu thông tin khách hàng, phòng, giao dịch, hóa đơn.
### 🪄 Các biểu đồ UML
### 🧍 Use Case Diagram

Mô tả các chức năng chính và mối quan hệ giữa Khách hàng, Lễ tân, và Hệ thống.

### 🔄 Sequence Diagram

Đặt phòng online – Mô tả trình tự giao tiếp giữa Khách hàng, Giao diện, Bộ xử lý đặt phòng và CSDL.

Check-in / Check-out – Mô tả quá trình nhận và trả phòng, cập nhật trạng thái, và in hóa đơn.

### 🛠️ Công cụ sử dụng

draw.io / PlantUML – Vẽ sơ đồ UML.

Visual Studio Code – Soạn thảo mã và tài liệu.

GitHub / GitLab – Lưu trữ mã nguồn và tài liệu.
