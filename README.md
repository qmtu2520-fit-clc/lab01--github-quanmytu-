# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Prerequisites
- Python 3.10+
- Git

---

## Setup && Run

Mở **PowerShell** và chạy lần lượt các bước sau:

### 1. Clone repository
```powershell
git clone https://github.com/qmtu2520-fit-clc/lab01-qmtu2520-fit-clc.git
cd lab01-lab01-qmtu2520-fit-clc
```

### 2. Thiết lập môi trường ảo (Virtual Environment)
```powershell
# Cấp quyền chạy script trên PowerShell (nếu cần)
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser -Force

# Tạo môi trường ảo (ưu tiên dùng lệnh py trên Windows)
py -m venv .venv

# Kích hoạt môi trường ảo
.\.venv\Scripts\Activate.ps1
```

### 3. Cài đặt thư viện phụ thuộc
```powershell
pip install -r requirements.txt
pip install -e .
```

### 4. Kiểm tra môi trường và chạy ứng dụng
```powershell
# Kiểm tra môi trường hệ thống
python scripts/check_env.py

# Chạy thử trợ lý
python -m assistant "where is the IT helpdesk?"
```

## Test

&#x09;pytest -q

## Project structure

## Troubleshooting
Lỗi không kích hoạt được .venv (Script execution is disabled):
Chạy lệnh sau rồi thử kích hoạt lại:
```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```
Lệnh python không nhận nhưng máy đã cài Python:
Dùng lệnh py thay cho python khi tạo venv hoặc chạy script:
```powershell
py -m venv .venv
```
