# Phân quyền và menu động:
- Phân quyền cho từng menu link, mỗi link ứng với một folder (giả sử ![modules](./images/modules.PNG))
- Trong mỗi folder có các config, view cho từng phần hoặc view dùng chung, i18n cho translate,...
- Khi vào link menu load view tương ứng với quyền (có thể đặt tên file html dạng base_view.html và base_view_<role>.html)

# Config
- Tham khảo hình ![config](./images/config.PNG), với all.js là các config chung cho toàn bộ các mtr run (development, prod,...), khi run project thì run 'npm run ' + <env_name> thì sẽ đọc file cấu hình tương ứng
- Cấu hình các strategies để login (folder strategies), các phương thúc login khác nhau đổi tên file để apply

# Theme
- Xây dựng folder components chứa các view component dùng chung