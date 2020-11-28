+++
weight = 30
+++

### Node Runtime?

**NodeJS** là môi trường runtime JavaScript với độ trễ thấp<br>
và thông lượng cao bằng cách thực hiện phương pháp<br>
“non-blocking” để cung cấp các yêu cầu. Nói cách khác,<br>
NodeJS không lãng phí thời gian hoặc tài nguyên khi chờ<br>
các yêu cầu I/O trả về.

---

### Event

[NodeJS]() hỗ trợ các sự kiện trong các ứng dụng rất hoàn hảo.<br>
Mỗi hành động trong máy tính được gọi là 1 sự kiện (event).

Ví dụ: khi bạn đọc một tập tin trên ổ cứng, thì có nghĩa là bạn<br>
phải thực hiện 2 hành động **"mở tập tin"** và **"đóng tập tin"**<br>
sau khi đọc xong. Như vậy chúng ta sẽ có 2 sự kiện **mở & đóng**

---

Thực thi ví dụ trên.

```
const fs = require('fs');

// init thread for read
const rs = rs.createReadStream('C:/test/demo.txt');

// 'Open' event
rs.on('open', function() {
  console.log('File opened!');
})
```

---

Module events cung cấp cho bạn lớp EventEmitter,<br>
nó là một lớp trung tâm trong **NodeJS** hỗ trợ định nghĩa<br>
ra một sự kiện, đăng ký các Listener (Đối tượng lắng nghe)<br>
sự kiện này, và phát ra (emit) sự kiện.
