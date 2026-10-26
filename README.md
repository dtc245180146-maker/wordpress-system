# Hệ Thống Triển Khai & Quản Trị Website CMS WordPress

Đề tài 3 - Môn: Triển khai và Quản trị Hệ thống Phần mềm

## Kiến trúc hệ thống
- **Web App**: WordPress
- **Database**: MySQL 8.0 & phpMyAdmin
- **Reverse Proxy**: Nginx (Hỗ trợ HTTPS SSL tự ký & Security Headers)
- **Monitoring**: Prometheus + Grafana + cAdvisor + Node Exporter
- **Logging**: Loki + Promtail + LogQL
- **Hardening**: Network Isolation, Environment Variables, Least Privilege, Non-root

## Hướng dẫn cài đặt & khởi chạy
```bash
docker-compose up -d
