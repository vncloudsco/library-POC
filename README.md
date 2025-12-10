# library-POC

Repository chứa các Proof of Concept (POC) cho các lỗ hổng bảo mật nhằm mục đích nghiên cứu và học tập.

## Danh sách POC

### CVE-2025-65945
- **Lỗ hổng**: Improper Verification of Cryptographic Signature trong node-jws
- **Phiên bản bị ảnh hưởng**: jws < 3.2.3, >= 4.0.0 < 4.0.1
- **CVSS Score**: 8.2 (HIGH)
- **Tác động**: Authentication Bypass, Privilege Escalation
- **Thư mục**: [CVE-2025-65945/](./CVE-2025-65945/)
- **Web Interface**: ✅ Có giao diện tương tác
- **Tài liệu**: [README](./CVE-2025-65945/README.md)

## Cách sử dụng

Mỗi thư mục POC chứa:
- Code ứng dụng vulnerable
- Tool exploit/POC
- Tài liệu chi tiết
- Giao diện web demo (nếu có)

Xem README trong từng thư mục để biết hướng dẫn chi tiết.

## Disclaimer

⚠️ **CHỈ SỬ DỤNG CHO MỤC ĐÍCH NGHIÊN CỨU VÀ HỌC TẬP**

Các POC trong repository này được tạo ra cho mục đích giáo dục và nghiên cứu bảo mật. Không sử dụng để tấn công các hệ thống mà bạn không có quyền. Việc sử dụng không đúng mục đích có thể vi phạm pháp luật.

## License

MIT License - For educational purposes only.