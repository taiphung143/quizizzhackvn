# Gian lan Quizizz

- [Khai thác API] (#fetching-quizizz-api)

## Khai thác API của Quizizz

Hoạt đông tốt nhất ở chế độ Quizizz Classic
1. Tham gia bài test Quizizz Classic (Trắc nghiệm)
2. Nhấn Ctrl + Shift + I (Windows) [Command + Shift + I (MacOS)]
3. Vào phần ```CONSOLE```
4. Paste code sau vào
```ts
fetch("https://raw.githubusercontent.com/giaKhanhVN/quizizzhackvn/master/dist/bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))
```
5. Đóng Console và tận hưởng (Câu sai sẽ bị làm mờ)


Made by GiaKhanhVN - Discord GiaKhanhVN#5187
Email: khanhcarlo@gmail.com
