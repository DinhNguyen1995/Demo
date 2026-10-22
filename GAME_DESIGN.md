# Hứng Táo IQode: 10 cấp độ tư duy

Game hứng táo cho học sinh tiểu học và đầu cấp 2. Mỗi cấp dạy một kỹ năng tư duy máy tính. Mỗi lần lên cấp, các em chạy lại trọn một vòng đời phát triển phần mềm, giống kỹ sư thật.

Lưu ý giả định: tôi hiểu khung IQode Method là 5 bước Real, Analyze, Design, Build, Reflect. Nếu khung của anh/chị khác, chỉ cần đổi tên 5 bước trong bảng dưới, phần còn lại giữ nguyên.

## 1. Vòng đời lặp ở mọi cấp

| Bước IQode | Vòng đời kỹ sư | Trẻ làm gì | Trong game |
|---|---|---|---|
| Real | Thu thập yêu cầu | Tìm ra vấn đề thật của người chơi | Thẻ tình huống |
| Analyze | Phân tích | Chia nhỏ vấn đề, đặt câu hỏi | Thẻ phân tích |
| Design | Thiết kế | Viết luật, vẽ sơ đồ, đặt biến | Thẻ thiết kế (cấp 9, 10 có tương tác) |
| Build | Lập trình | Chơi và chạy luật vừa thiết kế | Màn chơi |
| Reflect | Kiểm thử và cải tiến | Đọc kết quả, chọn 1 thứ sửa ở vòng sau | Thẻ nhìn lại |

Quy tắc cho giáo viên:
- Không bỏ bước. Trẻ thua ở Build thì quay về Design, không quay về đầu.
- Mỗi cấp sau dùng lại luật của cấp trước, chỉ thêm một khái niệm mới.
- Từ cấp 6 trở đi, trẻ tự nêu vấn đề ở Real, giáo viên chỉ hỏi.

## 2. Mười cấp độ

| Cấp | Tên | Tư duy | Vấn đề thật (Real) | Khái niệm mới trong màn |
|---|---|---|---|---|
| 1 | Hứng được táo | Quan sát, tuần tự | Táo rơi dập hết | Giỏ trái/phải, chạm thì ghi điểm |
| 2 | Táo sâu xuất hiện | Sự kiện, điều kiện | Hứng nhầm táo hỏng | NẾU đỏ THÌ +1, NẾU sâu THÌ -1 tim |
| 3 | Điểm và tim | Biến | Không biết đang thắng hay thua | Biến diem, tim; táo vàng +3 |
| 4 | Nhịp táo rơi | Vòng lặp, quy luật | Đứng sai chỗ | Táo rơi theo mẫu lặp 4 bước |
| 5 | Giỏ đổi màu | Phân loại, điều kiện kép | Hứng sai màu bị trừ | Màu giỏ khớp màu táo mới được điểm |
| 6 | Gió thổi | Dự đoán | Táo trôi lệch, hụt | Đường dự đoán điểm rơi |
| 7 | Hai cây, hai việc | Phân rã bài toán | Màn rối, quá nhiều luật | Ghép nhiều luật đã kiểm tra riêng |
| 8 | Năng lượng giỏ | Thuật toán, tối ưu | Chạy nhiều, giỏ hết sức | Di chuyển tốn năng lượng, phải chọn táo |
| 9 | Tìm lỗi | Gỡ lỗi | Giỏ chạy ngược chiều tay | Chọn giả thuyết, sửa, kiểm tra lại |
| 10 | Em thiết kế màn chơi | Hệ thống, sáng tạo | Bạn thấy màn quá dễ hoặc quá khó | Trẻ chỉnh tốc độ, tỷ lệ sâu, gió, mục tiêu |

## 3. Cách vận hành trong lớp (45 phút/cấp)

| Bước | Thời gian | Câu hỏi mẫu cho giáo viên |
|---|---|---|
| Real | 5 phút | "Nếu em là người chơi, em đang bực chỗ nào?" |
| Analyze | 8 phút | "Chia vấn đề này ra thành mấy phần nhỏ?" |
| Design | 10 phút | "Em viết luật ra giấy trước. Luật nào nghe chưa rõ?" |
| Build | 15 phút | "Chạy thử. Điều gì xảy ra khác với em đoán?" |
| Reflect | 7 phút | "Lần sau em sửa một thứ thôi, em sửa gì?" |

## 4. Đánh giá

Không chấm theo điểm game. Chấm theo 3 dấu hiệu:
1. Trẻ nói được luật của mình bằng câu "nếu... thì...".
2. Trẻ đoán trước kết quả rồi so với kết quả thật.
3. Ở Reflect, trẻ chọn đúng một thứ sửa và nêu lý do.

## 5. Điểm cần kiểm chứng

- Độ khó 10 cấp là ước lượng của tôi, chưa thử với trẻ thật. Cần chơi thử với 5 đến 8 em và chỉnh `cfg` trong `index.html`.
- Cấp 8 dùng thanh năng lượng, trên điện thoại có thể khó. Nên thử riêng trên màn cảm ứng.
- Độ tuổi phù hợp chưa xác định. Cấp 1 đến 5 hợp với lớp 2 đến 4, cấp 6 đến 10 hợp với lớp 4 đến 7 (giả định).

## 6. Bản chơi thử

Mở `index.html` bằng trình duyệt. Kéo chuột hoặc ngón tay để di chuyển giỏ, phím mũi tên cũng dùng được. Cấp 5 và 7: chạm vùng phía trên màn hoặc bấm phím cách để đổi màu giỏ. Thông số từng cấp nằm trong mảng `L` ở đầu phần script.
