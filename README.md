# Windows-Server-2022-ADDS-DHCP-Failover-Lab
Triển khai hệ thống Windows Server 2022 trong môi trường on-premises, mô phỏng hạ tầng CNTT của một doanh nghiệp nhỏ và vừa
# Mục Tiêu 
- Triển khai môi trường Windows Server 2022
- Triển khai Active Directory với Domain Controllers
- Cấu hình DNS tích hợp với Active Directory
- Triển khai DHCP Failover cho tính dự phòng hiệu năng cao
- Thực hành quản lí users, groups, và permissions
- Thực hành cấu hình, quản lí các Group Policy Object (GPO)
- Triển khai server dự phòng với Windows Server 2022 Core
# Công nghệ sử dụng
- Windows Server 2022 (GUI & Server Core)
- Active Directory Domain Services (AD DS)
- DNS (AD-integrated)
- DHCP và DHCP Failover (Load Balance)
- NTFS & Share Permissions
- Group Policy Object (GPO)
# Triển khai thực tế
## Active Directory
- Domain name: "ctv.local"
- 2 Domain Controllers cho sự dự phòng
- Forest & Domain Functional Level: Windows Server 2022
## DNS
- DNS tích hợp Active Directory
## DHCP & Failover
- DHCP scope: "192.168.10.50 – 192.168.10.200"
- Failover mode: Load Balance
- Thực hiện gán địa chỉ IP khi máy chủ chính ngừng hoạt động
## Server Core (DC02)
- Cấu hình máy chủ dự phòng Domain Controller
- Quản lí từ xa với RSAT
- Giảm bề mặt tấn công và giảm chi phí tài nguyên hệ thống
## Quản lí người dùng và quyền
- Organizational Units (OU), Group, User
- Home Folder cho các users
- Share và NTFS

## Hướng phát triển trong tương lai
- DFS Namespace & Replication
- Backup & Disaster Recovery
- WSUS deployment
- Hybrid Active Directory (Azure AD)

## Người làm dự án
- Chu Trọng Việt
Sinh viên năm cuối - Trường Đại Học Xây Dựng Hà Nội
