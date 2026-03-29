# Secure Delivery Ordering System (Production Ready)

ระบบสั่งซื้ออาหารและสินค้าเดลิเวอร์รี่ที่มีความปลอดภัยระดับสูง แก้ไขช่องโหว่ความปลอดภัยทั้งหมด ลดปัญหาคอขวดของฐานข้อมูล (N+1 Query) และปรับปรุงระบบสิทธิพิเศษ (Point System) และ UX/UI ให้สมบูรณ์แบบ

## Features
- Secure Authentication & Authorization (Password Hashing, Role-based Access Control)
- Full CSRF Protection on all forms and state-changing actions
- Prevented SQL Injection via Prepared Statements across all queries
- Optimized Database Queries (Eliminated N+1 Query issues using IN clauses and GROUP_CONCAT)
- Secure File Uploads via strict MIME-type mapping and renaming
- Logic-fixed Point System (Points granted only upon order confirmation)
- Dynamic Pagination and Input Validations
- Responsive Design & UTF-8 Compatibility