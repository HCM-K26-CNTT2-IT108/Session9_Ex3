# Bài 3: Onboarding lập trình viên mới

## Hướng dẫn cài đặt và bắt đầu với VS Code

Tài liệu này hướng dẫn cài Visual Studio Code (VS Code), mở thư mục dự án và chạy thử một chương trình Python. Phần chữ thường dùng để giải thích; tên biến và lệnh ngắn được trình bày bằng `inline code`; các lệnh Terminal và chương trình dài nằm trong khối code riêng.

## Báo cáo phân tích Input/Output

- **Input:** Văn bản Markdown thô gồm tiêu đề, đoạn giải thích, ký hiệu định dạng, bảng, danh sách công việc và các khối code.
- **Output:** StackEdit chuyển văn bản Markdown thành giao diện dễ đọc, có định dạng tiêu đề, bảng, checklist và code block. StackEdit là trình soạn thảo Markdown; VS Code là trình soạn thảo mã nguồn dùng để tạo và chạy chương trình.

## Cài đặt VS Code

1. Tải bộ cài VS Code từ [trang chủ Visual Studio Code](https://code.visualstudio.com/).
2. Mở bộ cài vừa tải và làm theo hướng dẫn trên màn hình. Trên Windows, có thể giữ các lựa chọn mặc định.
3. Mở VS Code sau khi cài xong.
4. Chọn **File > Open Folder** để mở thư mục làm việc.
5. Tạo file `hello.py`, nhập đoạn Python bên dưới và lưu lại.
6. Mở Terminal trong VS Code bằng **Terminal > New Terminal**, sau đó chạy lệnh phù hợp với máy:

```bash
python hello.py
```

Nếu lệnh `python` không hoạt động trên Windows, thử `py hello.py`. Cần cài Python riêng nếu máy chưa có trình thông dịch Python. Trong ví dụ, `name` là tên biến ngắn dùng để lưu tên người dùng.

## Chương trình Python mẫu

```python
# Lưu tên người dùng vào biến name
name = input("Nhập tên của bạn: ")

# In lời chào ra Terminal
print(f"Xin chào, {name}!")
```

## So sánh StackEdit và VS Code

| Tiêu chí | StackEdit | VS Code |
| --- | --- | --- |
| Mục đích chính | Viết và xem trước tài liệu Markdown | Soạn thảo mã nguồn và quản lý dự án |
| Điểm mạnh | Xem ngay cách Markdown được render; tiện soạn tài liệu | Hỗ trợ nhiều ngôn ngữ, tiện mở Terminal và chạy code |
| Phù hợp khi | Cần viết hướng dẫn, ghi chú hoặc README | Cần phát triển, sửa và chạy chương trình |
| Bắt đầu sử dụng | Mở trình soạn thảo StackEdit trên web | Cài ứng dụng VS Code trên máy tính |

## Checklist tiến độ cài đặt

- [ ] Tải và cài đặt VS Code.
- [ ] Mở thư mục làm việc trong VS Code.
- [ ] Tạo và lưu file `hello.py`.
- [ ] Mở Terminal tích hợp.
- [ ] Chạy `python hello.py` hoặc `py hello.py`.
- [ ] Xác nhận Terminal hiển thị lời chào.

## Escape ký tự Markdown

Dùng dấu gạch chéo ngược `\` trước ký tự đặc biệt để hiển thị nguyên dạng thay vì định dạng Markdown. Ví dụ: `\*` hiển thị \* và `\#` hiển thị \#.
