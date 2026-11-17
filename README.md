# LAB1 – KHAI THÁC DỮ LIỆU

- **Họ và tên:** TRẦN TRUNG THÔNG
- **MSSV:** 6451071075
- **Repository GitHub:** `6451071075_Lab1`
- **Tài liệu gốc:** `Tàu liệu LAB1.pdf`, Bài thực hành số 1, trang 1–30 (theo số trang trên trình đọc PDF).

## Phạm vi của bộ file hiện có

8 file `.ipynb` tương ứng **8 câu lập trình Titanic tại mục IV.2, trang 15–27**. Mỗi file có ô `print()` họ tên và MSSV, phần nạp dữ liệu và câu hỏi riêng. Các file được cung cấp dưới dạng mã nguồn để bạn chạy, xem và ghi nhận xét; **chưa kèm kết quả chạy hay ảnh chụp**.

| File | Nội dung |
| --- | --- |
| `6451071075_LAB1_Bai1.ipynb` | Nhập dữ liệu và thống kê các thuộc tính |
| `6451071075_LAB1_Bai2.ipynb` | 5 thuộc tính có nhiều giá trị thiếu nhất |
| `6451071075_LAB1_Bai3.ipynb` | Khảo sát tuổi, giới tính và khả năng sống sót |
| `6451071075_LAB1_Bai4.ipynb` | Khảo sát cảng lên tàu, hạng vé, giới tính và khả năng sống sót |
| `6451071075_LAB1_Bai5.ipynb` | Số người thân đi cùng và khả năng sống sót |
| `6451071075_LAB1_Bai6.ipynb` | Tiền xử lý dữ liệu thiếu và loại bỏ thuộc tính không cần |
| `6451071075_LAB1_Bai7.ipynb` | Biến đổi các thuộc tính theo đề bài |
| `6451071075_LAB1_Bai8.ipynb` | Tạo thuộc tính age_class và fare_per_person |

**Chưa bao gồm trong 8 file này:** 6 yêu cầu cơ bản (mục IV.1, trang 13–15), bài Bank Marketing (mục V, trang 28–29), 2 bài tập thêm (mục VI, trang 29–30). Các phần này thuộc LAB1 nhưng không nằm trong nhóm 8 câu IV.2; cần tách thêm file nếu giảng viên yêu cầu nộp toàn bộ. Không tự suy đoán số bài `<X>` cho các mục khác.

## Hướng dẫn chạy, lưu và chụp hình

1. Giải nén thư mục, chọn file bài muốn làm, vào https://colab.research.google.com/ > **Tải sổ tay lên (Upload notebook)** và mở file đó.
2. Trong **Tệp (Files)** bên trái Colab, nhấn **Tải tệp lên (Upload)** để thêm `titanic.csv` của giảng viên. File không có sẵn chỉ vì nó xuất hiện trong máy hoặc GitHub.
3. Nhấn **Chạy tất cả (Run all)** hoặc chạy lần lượt từ trên xuống. Xác nhận ô đầu tiên in ra đúng họ tên và MSSV; kiểm tra không có lỗi.
4. Đọc và ghi **nhận xét cụ thể** vào phần cuối notebook theo số liệu/biểu đồ của bài. Chụp màn hình từng kết quả. **Hình phải có thanh taskbar Windows** ở phía dưới, không crop mất taskbar. Nên chụp bằng `Win + PrtScn` (toàn màn hình) và lưu trong `anh_ket_qua/` với tên `Bai1_01.png`, `Bai1_02.png`, ...
5. Trong Colab chọn **Tệp > Tải xuống > Tải xuống .ipynb** (File > Download > Download .ipynb) để tải lại notebook có kết quả chạy về máy. Nếu download thay đổi tên do trùng, đổi lại chính xác theo tên trong bảng phía trên.
6. Kiểm tra lại số lượng **8 file `.ipynb`**, có `print()` tên và MSSV, code và kết quả đã chạy, ảnh chụp có taskbar. Sau đó tải toàn bộ các file nộp lên một repository duy nhất.

## Đưa lên GitHub (dùng giao diện web)

1. Đăng nhập GitHub tại https://github.com/ và nhấn nút `+` > **New repository**.
2. Điền **Repository name** là `6451071075_Lab1` (chính xác chữ hoa/chữ thường); chọn **Public** nếu giảng viên phải truy cập mà không có quyền riêng. Nếu yêu cầu riêng tư, chọn **Private** và cấp quyền thích hợp.
3. Nhấn **Create repository**.
4. Vào repository, nhấn **Add file > Upload files** hoặc kéo-thả các file `.ipynb`, `README.md` và ảnh trong `anh_ket_qua/`. **Không upload file `.zip` thay cho các notebook riêng**.
5. Điền commit message, ví dụ `Add LAB1 Titanic notebooks and screenshots`, nhấn **Commit changes**.
6. Mở thử từng file `.ipynb` trên GitHub để chắc chắn tên file, ô code, kết quả và hình đều hiển thị; sao chép link repository để nộp thầy.

**Không tự động đăng GitHub:** Bộ này được chuẩn bị trên máy; bạn cần tự tạo repository/upload từ tài khoản GitHub của mình.
