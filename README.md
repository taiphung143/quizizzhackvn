# Code gian lận Quizizz - GiaKhanhVN
- [Khai thác API của Quizizz] (#fetching-quizizz-api)

## Khai thác API của Quizizz

Hoạt đông tốt nhất ở chế độ Quizizz Classic
1. Tham gia bài test Quizizz Classic (Trắc nghiệm)
2. Nhấn Ctrl + Shift + I (Windows) [Command + Shift + I (MacOS)]
3. Vào phần ```CONSOLE```
4. Dán code sau vào
```ts
fetch("https://raw.githubusercontent.com/giaKhanhVN/quizizzhackvn/master/dist/bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))
```
5. Đóng ```CONSOLE``` và tận hưởng (Câu sai sẽ bị làm mờ)

![screenshot](/docs/screenshot_1.png)

Made by GiaKhanhVN - Discord GiaKhanhVN#5187
Email: khanhcarlo@gmail.com
