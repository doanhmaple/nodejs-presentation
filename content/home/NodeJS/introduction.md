+++
weight = 20
+++

## GIỚI THIỆU NODEJS

---

### NODEJS LÀ GÌ?

[Node.js](https://nodejs.org) là Runtime Environment để thực thi code Javascript.<br>
Về bản chất, Node là chương trình C++ được nhúng trong<br>
Chrome v8 engine, engine JavaScript tốc độ chạy cực nhanh.<br>
Node.js thường được sử dụng để xây dựng ứng dụng nhanh và<br>
mở rộng. Là lựa chọn hoàn hảo để xây dựng RESTFul Services.

---

Node.js là single-threaded (đơn luồng). Có nghĩa là ứng dụng<br>
sử dụng Node.js sẽ chạy đơn luồng để chạy tất cả client.

Mặc định ứng dụng Node.js là asynchronous (bất đồng bộ)<br>hoặc non-blocking. Điều này có nghĩa là khi ứng dụng liên quan đến toán tử I/O (Ví dụ: truy cập file hoặc network), thread (luồng)<br>
sẽ không phải chờ (hoặc chặn). Nó sẽ được giải phóng để<br>phục vụ các client khác.

---

### Node dùng để làm gì?

NodeJS có thể xử lý cùng lúc hàng ngàn kết nối.<br>
Bên cạnh các lợi ích về tốc độ thực thi và khả năng mở rộng.

NodeJS là công nghệ mới và sẽ phát triển mạnh hơn<br>
trong tương lai với ưu điểm về các ứng dụng Realtime.

---

Ý tưởng chính của Node.js là sử dụng non-blocking, hướng sự<br>
vào ra của dữ liệu thông qua các tác vụ realtime (thời gian thực) một cách nhanh chóng. 

Nếu như các ứng dụng web truyền thống, các yêu cầu (request) tạo ra một luồng xử lý yêu cầu mới và chiếm RAM của hệ thống thì việc tài nguyên của hệ thống sẽ được sử dụng không hiệu quả. Chính vì lẽ đó, giải pháp mà Node.js đưa ra là sử dụng luồng đơn (Single-Threaded), kết hợp với non-blocking I/O để thực thi các request, cho phép hỗ trợ đồng thời hàng chục ngàn kết nối.

---

### Cài đặt NodeJS

Việc cài đặt [NodeJS](https://nodejs.org) khá đơn giản, bạn chỉ cần<br> 
vào trang chủ của [NodeJS](https://nodejs.org) là có thể tải về và cài đặt,...

[NodeJS](#) muốn chạy được sẽ cần một công cụ quản lý thư viện<br>
lập trình cho nó, thư viện đó là **NPM (Node Package Manager)**.<br>
Khi cài đặt NodeJS, NPM cũng sẽ được cài đặt theo

---

Để kiểm tra xem việc cài đặt đã thành công hay chưa, bạn mở **Termnial** hoặc **Command Prompt (CMD)** và gõ các lệnh sau:

Lệnh **node -v** để kiếm tra phiên bản của NodeJS

```markdown
 C:\User\PC> node -v
 v14.4.0
```

Lệnh **npm -v** để kiểm tra phiên bản của npm

```markdown
 C:\User\PC> npm -v
 v6.14.8 
```