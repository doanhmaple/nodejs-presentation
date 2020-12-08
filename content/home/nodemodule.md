+++
weight = 50
+++

{{% section %}}

#### Node Module

![NPM](/images/npm.png)

---

[Node Module](https://nodejs.org/api/modules.html) là tập hợp các thư viện trong **JavaScript.**<br>
Nó cung cấp các hàm để bạn có thể đưa vào một ứng dụng.

Bạn có thể tạo module của riêng mình và sử dụng nó với<br>
nhiều ứng dụng khác nhau. [Node.js](https://nodejs.org) có 1 bộ *Built-in Module*,<br>
bạn có thể sử dụng luôn mà không cần cài đặt thêm gì nữa...

---

#### Cách sử dụng module

- Sử dụng **`require()`** với tên module cần gọi

```
// Ví dụ
const http = require('http');
```

-	Module trên là **module http**, là một module được xây dựng<br>
sẵn trên Node, bạn cũng có thể cài đặt và sử dụng module<br>
bên thứ 3 trên trang [npmjs.com](https://www.npmjs.com)

```
// Ví dụ
npm install express
  const express = require(‘express’);
```

{{% /section %}}