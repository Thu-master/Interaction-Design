# School Timetable Interface – PACT Analysis

## PACT Analysis

- **People**
  - Students (10–22 tuổi)
    - Needs: xem lịch học, đổi tiết, nhắc nhở
    - Skills: digital native, quen mobile app
  - Teachers
    - Needs: quản lý tiết dạy, lịch thay đổi
    - Skills: trung bình - khá (mobile/web)
  - Admin (School staff)
    - Needs: tạo/sửa thời khóa biểu, phân bổ phòng
    - Skills: sử dụng PC, quản lý hệ thống

- **Activities**
  - Students
    - Xem lịch theo ngày/tuần/tháng
    - Nhận thông báo thay đổi lịch
    - Tìm kiếm môn/giáo viên
  - Teachers
    - Kiểm tra lịch dạy
    - Nhận thông báo thay đổi tiết
    - Quản lý lớp được phân công
  - Admin
    - Tạo thời khóa biểu
    - Phân bổ phòng, giáo viên
    - Xuất báo cáo

- **Contexts**
  - Mobile app (students dùng nhiều)
  - Web app (admin, teacher)
  - Online (sync real-time)
  - Offline (cache lịch học gần nhất)

- **Technologies**
  - Web app (React/Angular + NestJS backend)
  - Mobile (Flutter/React Native)
  - Notifications (push/email/SMS)
  - Database (PostgreSQL/Firebase)

---

## Research – 3 Similar Apps

### 1. Google Calendar
- **Data**: events, tasks, reminders
- **Display**: timeline, calendar views, color-coded
- **Interaction**: tap, drag & drop, search, filter
- **Strengths**: trực quan, realtime sync
- **Weaknesses**: không tối ưu riêng cho trường học

### 2. MyStudyLife
- **Data**: class schedule, exams, assignments
- **Display**: timetable view, task list, notifications
- **Interaction**: scroll, filter by subject, reminders
- **Strengths**: thiết kế riêng cho học sinh/sinh viên
- **Weaknesses**: UI hơi cũ, chưa trực quan như dashboard hiện đại

### 3. Class Timetable (Mobile app)
- **Data**: courses, teachers, room, time slots
- **Display**: weekly grid, color-coded subjects
- **Interaction**: swipe, tap-to-edit, minimal setup
- **Strengths**: đơn giản, nhẹ, dễ dùng
- **Weaknesses**: thiếu tính năng quản trị (admin/teacher)
