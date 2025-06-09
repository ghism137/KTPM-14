# 🧠 Chinese Chess Online 

Một ứng dụng cờ tướng chơi online 2 người sử dụng Python. Backend sử dụng Flask (Python) kết hợp JWT để xác thực và bảo mật phiên đăng nhập người dùng.

---

## 📦 Mục lục

- [Giới thiệu](#giới-thiệu)
- [Giới thiệu thành viên](#giới-thiệu-thành-viên)
- [Mô tả trò chơi](#mô-tả-trò-chơi)
- [Tính năng](#tính-năng)
- [Cách chơi](#cách-chơi)
- [Câu hỏi thường gặp](#câu-hỏi-thường-gặp)
- [Đóng góp](#đóng-góp)
- [Giấy phép](#giấy-phép)


---

## 🚀 Giới thiệu

Dự án giúp bạn chơi cờ tướng với bạn bè qua mạng LAN hoặc internet. Giao diện sử dụng Pygame đơn giản và trực quan, xử lý thời gian thực.

---

## 🧑‍💻 Giới thiệu thành viên

Dự án được thực hiện bởi các thành viên:
- Phạm Đức Hưng (Mã sinh viên: 22010479)
- Phạm Hoài Nam (Mã sinh viên: 22010183)
- Trần Thái Hưng (Mã sinh viên: 23010693)

---

## Mô tả trò chơi

Cờ tướng là một trò chơi chiến thuật dành cho hai người chơi, phổ biến ở các nước Đông Á như Trung Quốc và Việt Nam. Mỗi người chơi sẽ điều khiển một tập hợp quân cờ, mục tiêu là chiếu bí tướng (vua) của đối phương. Trò chơi diễn ra trên bàn cờ 9x10, chia thành hai bên đối xứng, với các loại quân cờ như tướng, sĩ, tượng, xe, pháo, mã và tốt.

Trong phiên bản online của trò chơi:
- Người chơi có thể đăng nhập, tìm trận đấu hoặc mời bạn bè tham gia.
- Sau khi kết nối thành công, hệ thống sẽ thiết lập bàn cờ ban đầu và luân phiên truyền nước đi giữa hai phía.
- Ván cờ sẽ kết thúc khi có người bị chiếu bí, hoặc sẽ trở nên hòa nếu cả 2 bên không thể kết thúc ván cờ.

---

## ✅ Tính năng

- Tạo phòng kết nối 2 người chơi qua mạng.
- Hiển thị bàn cờ, quân cờ, nước đi hợp lệ.
- Xử lý quân cờ:
    - Quản lý lượt đi (đỏ-đen).
    - Kiểm tra chiếu tướng (check) và chiếu bí (game over).
- Thông báo thời gian thực: Khi đối phương đi nước, client sẽ nhận và cập nhật ngay.

---

## 🕹️ Cách chơi
Tuân thủ theo luật chơi cờ tướng truyền thống.

---
## Cài đặt
 Backend:
```bash
python api.py
```

 Frontend:
```bash
cd fe
npm i
npm run dev
```

---

## ❓ Câu hỏi thường gặp

**1. Làm sao để kết nối hai máy tính chơi với nhau?**  
Đảm bảo cả hai máy cùng mạng LAN hoặc biết địa chỉ IP của máy chủ. Máy client nhập IP của server khi được yêu cầu.

**2. Gặp lỗi khi khơi động chương trình (lỗi cài đặt) ?**  
Kiểm tra lại phiên bản Python, cài đặt đúng thư viện trong requirements.txt và đảm bảo firewall không chặn cổng.

**3. Có thể chơi trên nhiều hệ điều hành không?**  
Có, dự án hỗ trợ Windows, macOS và Linux.

---

## 🤝 Đóng góp

Chào mừng mọi đóng góp từ cộng đồng!

- Fork repository và tạo branch mới cho tính năng hoặc sửa lỗi.
- Gửi pull request kèm mô tả chi tiết thay đổi.
- Vui lòng tuân thủ phong cách code và quy tắc đặt tên của dự án.
- Nếu có ý tưởng hoặc phát hiện lỗi, hãy tạo issue để mọi người cùng thảo luận.

---

## 📜 Giấy phép

Dự án được phát hành theo giấy phép MIT. Bạn có thể tự do sử dụng, chỉnh sửa và phân phối lại mã nguồn với điều kiện giữ nguyên thông tin bản quyền ban đầu.

---
