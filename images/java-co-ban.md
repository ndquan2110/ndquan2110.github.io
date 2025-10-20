+++
title = "Java: Kiến thức cơ bản và môi trường phát triển"
date = "2025-10-17T09:00:00+07:00"
draft = false
categories = ["Java"]
tags = ["java", "cơ bản"]
description = "Tìm hiểu về môi trường phát triển Java, cấu trúc chương trình cơ bản và cách biên dịch, chạy chương trình Java đầu tiên."
featured_image = "/images/java-intro.jpg"
+++

# ☕ Java: Kiến thức cơ bản và môi trường phát triển

**Java** là một trong những ngôn ngữ lập trình phổ biến và mạnh mẽ nhất hiện nay, được sử dụng rộng rãi trong phát triển ứng dụng web, di động và doanh nghiệp.  
Bài viết này sẽ giúp bạn làm quen với **môi trường phát triển Java**, hiểu **cấu trúc cơ bản** của một chương trình và biết cách **chạy chương trình đầu tiên** của mình.

---

## 🧩 1. Môi trường phát triển Java

Để lập trình Java, bạn cần chuẩn bị:

### 🔹 **1. JDK (Java Development Kit)**
JDK là bộ công cụ cần thiết để biên dịch và chạy các chương trình Java.  
Bạn có thể tải về tại:  
👉 [https://www.oracle.com/java/technologies/javase-downloads.html](https://www.oracle.com/java/technologies/javase-downloads.html)

Sau khi cài đặt, kiểm tra bằng lệnh:

```bash
java -version
javac -version
```

Nếu cả hai lệnh đều hoạt động, nghĩa là bạn đã cài đặt thành công ✅

---

### 🔹 **2. IDE (Môi trường lập trình tích hợp)**

Bạn có thể viết Java bằng **trình soạn thảo** như VS Code, Notepad++,…  
Tuy nhiên, dùng **IDE chuyên dụng** sẽ tiện hơn. Một số IDE phổ biến:

- 🧠 **IntelliJ IDEA** (được khuyên dùng)
- 💼 **Eclipse**
- 💻 **NetBeans**
- ✨ **VS Code** (với extension Java)

---

## 🧱 2. Cấu trúc cơ bản của chương trình Java

Một chương trình Java thường bao gồm:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Xin chào, Java!");
    }
}
```

### Giải thích:
- `public class HelloWorld`: khai báo lớp có tên là *HelloWorld* (tên file phải trùng với tên lớp).
- `public static void main(String[] args)`: phương thức chính — nơi chương trình bắt đầu chạy.
- `System.out.println(...)`: in ra màn hình một dòng văn bản.

---

## ⚙️ 3. Cách biên dịch và chạy chương trình

Sau khi lưu file trên với tên `HelloWorld.java`, bạn có thể chạy bằng **dòng lệnh**:

```bash
javac HelloWorld.java
java HelloWorld
```

Kết quả sẽ là:

```
Xin chào, Java!
```

---

## 🚀 4. Kết luận

Bạn đã vừa tạo và chạy thành công **chương trình Java đầu tiên** 🎉  
Trong các bài viết tiếp theo, mình sẽ hướng dẫn:

- Biến, kiểu dữ liệu và toán tử trong Java  
- Cấu trúc điều khiển (if, for, while)  
- Lập trình hướng đối tượng (OOP)  

---

**Tác giả:** Nguyễn Đình Quân  
📅 *Đăng ngày: 17/10/2025*  
💬 *Nếu bạn thấy bài viết hữu ích, hãy để lại bình luận hoặc chia sẻ nhé!*
