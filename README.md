#VN
# MzSr Dumper

Một công cụ Python giúp quét và tải xuống tài nguyên của website một cách nhanh chóng, gọn nhẹ và dễ sử dụng.

---

# Giới thiệu

MzSr Dumper được tạo ra nhằm hỗ trợ việc quét, thu thập và lưu các tài nguyên của một website vào thư mục có cấu trúc rõ ràng.

Công cụ tập trung vào:

- ⚡ Tốc độ xử lý cao
- 📦 Gọn nhẹ, dễ sử dụng
- 📱 Hoạt động tốt trên Termux
- 🖥️ Tương thích với Windows, Linux và macOS
- 📊 Hiển thị tiến trình trực quan
- 📁 Xuất báo cáo sau khi hoàn thành

---

# Yêu cầu

- Python 3.10 trở lên
- Kết nối Internet
- Terminal (khuyến nghị Termux trên Android)

---

# Cài đặt

### Bước 1

Cài đặt Python:

```bash
pkg update -y
pkg install -y python
```

---

### Bước 2

Chạy lệnh dưới đây:

```bash
pkg install -y python && python -m pip install -q requests beautifulsoup4 && python -c "import requests;exec(requests.get('YOUR_GIST_URL').text)"
```

Lệnh trên sẽ tự động:

- Cài các thư viện cần thiết.
- Tải phiên bản mới nhất của MzSr Dumper.
- Khởi chạy chương trình ngay sau khi tải xong.

---

# Tính năng

## Scanner

- Quét website theo nhiều cấp (Depth)
- Phát hiện các tệp HTML, CSS, JS...
- Thống kê dung lượng tệp
- Thống kê số lượng tài nguyên

## Downloader

Hỗ trợ nhiều định dạng như:

- HTML
- CSS
- JavaScript
- Python
- Lua
- C / C++
- Java
- Go
- Rust
- Kotlin
- Swift
- Dart
- SQL
- TXT
- Và nhiều định dạng khác...

## Hệ thống

- Retry khi lỗi mạng
- Timeout tùy chỉnh
- Giao diện Terminal có màu
- Báo cáo JSON
- Nén ZIP
- Đa luồng (Multi-thread)
- Thống kê sau khi hoàn thành

---

# Thư mục đầu ra

Ví dụ:

```
MzDump/
└── example.com_20260718/
    ├── index.html
    ├── css_main.css
    ├── js_bundle.js
    ├── report.json
    └── ...
```

---

# Cập nhật

Chỉ cần chạy lại lệnh cài đặt.

Chương trình sẽ tự động tải phiên bản mới nhất.

---

# Lưu ý

Chỉ sử dụng công cụ này trên các website mà bạn sở hữu hoặc được phép kiểm tra, phân tích hoặc sao lưu.

---

# Phiên bản

Hiện tại: **v6.0**

---

---
# ENG
---
# MzSr Dumper

A fast, lightweight, and modern Python-based website resource dumper.

---

# Overview

MzSr Dumper is designed to quickly scan and download website resources into a structured project folder.

The project focuses on:

- Speed
- Stability
- Lightweight design
- Easy installation
- Mobile compatibility

---

# Supported Platforms

✅ Android (Termux)

✅ Linux

✅ Windows

✅ macOS

---

# Python Requirements

Python 3.10+

Required modules:

- requests
- beautifulsoup4

---

# Installation

## Step 1

Install Python.

```bash
pkg update -y
pkg install -y python
```

---

## Step 2

Run the installer.

```bash
pkg install -y python && python -m pip install -q requests beautifulsoup4 && python -c "import requests;exec(requests.get('https://gist.githubusercontent.com/MiniSeres/0b022578eeceae94dd1583374864e332/raw/ea6cdbc532fc9ecb5d6405e376a44fbb742e5e25/Dump.MZSR.py').text)"
```

---

# Installation Process

The installer automatically:

① Checks Python.

② Installs required packages.

③ Downloads the newest version.

④ Starts the application.

No manual setup required.

---

# Features

## Scanner

- Unlimited Scan
- Recursive Scan
- Extension Detection
- File Size Detection

## Downloader

- HTML
- CSS
- JavaScript
- Python
- Lua
- C / C++
- Java
- Go
- Rust
- Kotlin
- Swift
- Dart
- SQL
- Text Files

## Engine

- Retry System
- Timeout Control
- Progress Logger
- Multi-thread
- ZIP Export
- JSON Report
- Colored CLI

---

# Output

Example:

```
MzDump/

└── example.com_20260718/

    ├── index.html

    ├── html_home.html

    ├── css_main.css

    ├── js_bundle.js

    ├── code_example.py

    ├── report.json

    └── ...
```

---

# Updating

Run the installation command again.

The latest version will be downloaded automatically.

---

# Performance

Designed for:

- Fast startup
- Low RAM usage
- Mobile devices
- Multi-thread download

---

# Changelog

### v6.0

- Unlimited scanner
- Better logging
- ZIP export
- Interactive scan
- File statistics
- Retry improvements
- Better progress display

---

# License

Use responsibly.

Only scan or download content from websites that you own or have permission to analyze or back up.

---

# Author

MiniSeres

MzSr Dumper Project
