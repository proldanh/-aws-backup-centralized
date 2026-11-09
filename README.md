Đồ án Điện toán đám mây: Hệ thống sao lưu và phục hồi tự động trên AWS
Sinh viên: Lư Nhật Trường - MSSV: 22110257 (nhóm 1 SV)
Môn học: Điện toán đám mây
Môi trường: AWS Academy Learner Lab, Region us-east-1
Mô tả

Hệ thống sao lưu và phục hồi tự động cho một web app nhỏ. Web app chạy trên EC2, dữ liệu chính lưu ở RDS MySQL, log/session lưu ở DynamoDB, file dùng chung lưu ở EFS. Tất cả được mã hóa bằng KMS và sao lưu định kỳ bằng AWS Backup.

Dịch vụ AWS sử dụng

AWS Backup, EC2, RDS, DynamoDB, EFS, KMS (cùng VPC, Security Group, S3, CloudWatch). Dùng LabRole/LabInstanceProfile.

Cấu trúc thư mục
Week-1/ đến Week-4/: sản phẩm theo từng tuần, mỗi tuần gồm screenshots/ (ảnh minh chứng), architecture/ (sơ đồ), report/ (báo cáo tuần), worklog/ (nhật ký công việc)
src/: mã nguồn web app và script
final-report/: báo cáo cuối kỳ, sơ đồ kiến trúc cuối, báo cáo chi phí
demo/: video demo
Ghi chú về việc dùng AI

Em dùng Claude (Anthropic) để tham khảo, hướng dẫn cấu hình và gỡ lỗi. Mọi tài nguyên được em tự triển khai và chạy trên AWS Learner Lab, và em giải thích được các cấu hình.
