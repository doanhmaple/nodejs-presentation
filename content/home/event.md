+++
weight = 40
+++

{{% section %}}

#### Event trong Node.js

[Node.js](https://nodejs.org) hỗ trợ các sự kiện trong các ứng dụng rất hoàn hảo.<br>
Mỗi hành động trong máy tính được gọi là 1 sự kiện (event).

Ví dụ: Khi bạn đọc một tập tin trên ổ cứng, thì có nghĩa là bạn<br>
phải thực hiện 2 hành động **"mở tập tin"** và **"đóng tập tin"**<br>
sau khi đọc xong. Như vậy chúng ta sẽ có 2 sự kiện **mở & đóng**

---

Thực thi ví dụ trên

![Event-ex](/images/event-ex.png)

---

[Node.js](https://nodejs.org) cung cấp lớp **EventEmitter**, nó là lớp trung tâm<br>
trong [Node.js](https://nodejs.org) để hỗ trợ định nghĩa ra một sự kiện,<br>
đăng ký các **Listener** (đối tượng lắng nghe) sự kiện<br>
này và phát ra (emit) sự kiện.

Ví dụ: Tạo event riêng với EventEmitter

---

Thực thi ví dụ trên

![Event-ex](/images/event-ex2.png)

{{% /section %}}