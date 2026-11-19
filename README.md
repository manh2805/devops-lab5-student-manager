# Student Manager

Ứng dụng quản lý sinh viên — DevOps Lab 5

**Version 1.0.0** — Phát triển bởi Nhóm A & Nhóm B

## Tính năng
- Quản lý thông tin sinh viên (Student Model)
- Thêm sinh viên mới (add_student)
- Tìm kiếm sinh viên theo tên hoặc mã (search_student)

## Cài đặt & Chạy

```bash
git clone https://github.com/manh2805/devops-lab5-student-manager.git
cd devops-lab5-student-manager
python src/main.py
```

## Quy trình Git Flow đã áp dụng
- `main` — production, `develop` — tích hợp
- `feature/add-student` (PR #1), `feature/search-student` (PR #2) → merge vào `develop` qua Pull Request + Code Review
- `feature/update-readme-b` (PR #3), `feature/update-readme-a` (PR #4) → tạo & giải quyết merge conflict
- `develop` → `main`

## Công nghệ
- Python 3.x
- Git & GitHub (Git Flow)

## Tác giả
- Đặng Đức Mạnh — DTC235180119 (đóng vai Dev A & Dev B)
- DevOps Course, Bài 5
