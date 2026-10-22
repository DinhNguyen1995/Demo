# Hứng Táo IQode: 10 đề bài, một game

Một game hứng táo duy nhất. Từ bài 1 đến bài 10, mỗi bài thêm một thành phần mới (biến, nhân vật, luật) và dạy một kiến thức mới. Bài sau giữ nguyên mọi thứ của bài trước, nên độ khó tăng dần và trẻ thấy game của mình lớn lên.

Mỗi bài trẻ làm vai kỹ sư nhí và chạy trọn một vòng đời phát triển theo IQode Method.

## 1. Vòng đời lặp ở mọi bài

| Bước IQode | Việc của kỹ sư nhí | Tương ứng vòng đời phần mềm |
|---|---|---|
| Real Problem | Nghe một vấn đề thật của "khách hàng" (bác nông dân, bạn Nam...) | Thu thập yêu cầu |
| Analyze | Tách vấn đề: có nhân vật nào, biến nào, luật nào, thắng thua ra sao | Phân tích |
| Design | Vẽ phiếu thiết kế, viết luật NẾU... THÌ..., chọn các con số | Thiết kế |
| Build | Chạy game với thiết kế của mình, hoàn thành nhiệm vụ của bài | Lập trình |
| Reflect | Đọc kết quả, trả lời câu hỏi nhìn lại, quay lại Design sửa một số | Kiểm thử và cải tiến |

Quy tắc:
- Không bỏ bước. Chưa đạt ở Build thì quay về Design, không quay về đầu bài.
- Mỗi lần chỉ sửa một con số, rồi chạy lại để thấy số đó tác động gì.
- Trẻ phải đoán trước kết quả rồi mới bấm chạy.

## 2. Lộ trình 10 bài

| Bài | Tên | Thành phần mới | Kiến thức mới | Thông số trẻ tự thiết kế |
|---|---|---|---|---|
| 1 | Giỏ và táo | Nhân vật Giỏ, Táo | Nhân vật và sự kiện chạm | Tốc độ rơi |
| 2 | Đếm điểm | Biến `diem` | Biến | Điểm mỗi táo, điểm để thắng |
| 3 | Táo sâu | Táo sâu, biến `tim` | NẾU... THÌ... | Số tim, tim mất khi dính sâu |
| 4 | Táo vàng | Táo vàng | Nhiều nhánh điều kiện | Điểm táo vàng, tần suất |
| 5 | Đua với đồng hồ | Đồng hồ đếm ngược | Vòng lặp có điều kiện dừng | Thời gian |
| 6 | Càng giỏi càng nhanh | Tốc độ phụ thuộc điểm | Biến tính từ biến khác (công thức) | Mốc điểm, mức tăng tốc |
| 7 | Gió thổi | Gió ngẫu nhiên | Số ngẫu nhiên, dự đoán | Sức gió, bật/tắt đường báo |
| 8 | Chú sóc tham ăn | Nhân vật Sóc tự chạy | Nhiều nhân vật, mỗi nhân vật một luật | Tốc độ sóc, số táo sóc được ăn |
| 9 | Nam châm | Kỹ năng nam châm, hồi chiêu | Gói việc thành khối có tên (hàm) | Thời gian hút, thời gian hồi |
| 10 | Kỹ sư chỉnh game | Bảng tham số cả game | Tham số hóa và kiểm thử | Sáu thông số chính |

## 3. Chi tiết từng bài

Mỗi bài theo cùng khuôn: Real Problem, Analyze, Design, Build, Reflect. Lời hỏi dưới đây là câu giáo viên đọc nguyên văn hoặc nói lại theo cách của mình.

### Bài 1: Giỏ và táo
- **Real Problem:** Bác nông dân có cây táo. Táo chín rụng xuống đất là dập hết. Bác cần một chiếc giỏ hứng táo.
- **Analyze:** "Có những nhân vật nào? Mỗi nhân vật làm được gì? Chuyện gì xảy ra khi giỏ chạm táo?"
- **Design:** Vẽ giỏ và táo lên phiếu. Chọn tốc độ rơi.
- **Build:** Hứng 5 quả táo.
- **Reflect:** "Táo rơi nhanh hay chậm so với tay em? Em đổi số nào để vừa sức?"
- **Dấu hiệu đạt:** Trẻ nói được câu "khi giỏ chạm táo thì táo biến mất".

### Bài 2: Đếm điểm
- **Real Problem:** Bác muốn biết hôm nay hứng được bao nhiêu để so với hôm qua.
- **Analyze:** "Cần nhớ một con số. Nó bắt đầu từ mấy? Khi nào nó tăng?"
- **Design:** Đặt tên biến `diem`, bắt đầu bằng 0. Viết: khi hứng táo đỏ thì `diem` tăng ___.
- **Build:** Đạt đủ điểm đã đặt.
- **Reflect:** "Biến `diem` bắt đầu từ mấy? Mỗi lần hứng, nó đổi thế nào?"
- **Dấu hiệu đạt:** Trẻ phân biệt được tên biến và giá trị của biến.

### Bài 3: Táo sâu
- **Real Problem:** Có táo bị sâu. Hứng phải thì cả giỏ hỏng dần.
- **Analyze:** "Làm sao biết táo nào sâu? Hứng phải thì chuyện gì xảy ra? Cần thêm biến nào?"
- **Design:** NẾU giỏ chạm táo sâu THÌ `tim` giảm ___. NẾU `tim` bằng 0 THÌ thua.
- **Build:** Đạt điểm mà còn tim.
- **Reflect:** "Luật của em chạy đúng chưa? Có trường hợp nào em quên?"
- **Dấu hiệu đạt:** Trẻ tự viết được một luật NẾU... THÌ... có điều kiện và kết quả rõ.

### Bài 4: Táo vàng
- **Real Problem:** Thỉnh thoảng có táo vàng, quý hơn táo thường.
- **Analyze:** "Bây giờ có 3 loại táo. Mỗi loại xử lý khác nhau. Viết đủ 3 nhánh."
- **Design:** NẾU sâu THÌ trừ tim. HOẶC NẾU vàng THÌ cộng ___ điểm. CÒN LẠI thì cộng điểm thường.
- **Build:** Đạt điểm, thử chiến thuật chạy theo táo vàng.
- **Reflect:** "Có đáng chạy xa để lấy táo vàng không? Em tính thế nào?"
- **Dấu hiệu đạt:** Trẻ viết được đủ nhánh và không để trùng hay hở nhánh nào.

### Bài 5: Đua với đồng hồ
- **Real Problem:** Chợ sắp đóng cửa, bác chỉ còn ít phút.
- **Analyze:** "Thời gian là một biến giảm dần. Game kết thúc khi nào? Có mấy cách thắng, mấy cách thua?"
- **Design:** Đặt thời gian. Viết: lặp lại cho đến khi hết giờ HOẶC đủ điểm.
- **Build:** Đủ điểm trước khi hết giờ.
- **Reflect:** "Em chọn bao nhiêu giây? Vì sao đủ để thắng mà không quá dễ?"
- **Dấu hiệu đạt:** Trẻ liệt kê được cả điều kiện thắng và điều kiện thua.

### Bài 6: Càng giỏi càng nhanh
- **Real Problem:** Chơi mãi một tốc độ thì chán. Bác muốn game khó dần khi người chơi giỏi lên.
- **Analyze:** "Tốc độ rơi có liên quan gì đến điểm? Viết công thức."
- **Design:** Tốc độ = tốc độ gốc + (điểm chia mốc) nhân mức tăng. Chọn mốc và mức tăng.
- **Build:** Chơi và để ý lúc nào bắt đầu khó chịu.
- **Reflect:** "Con số nào làm game thành bất công?"
- **Dấu hiệu đạt:** Trẻ giải thích được vì sao tốc độ đổi khi điểm đổi.

### Bài 7: Gió thổi
- **Real Problem:** Hôm nay có gió. Mỗi quả táo trôi một hướng khác nhau.
- **Analyze:** "Gió làm lệch trái hay phải thì không biết trước. Có cách nào đoán điểm rơi?"
- **Design:** Chọn sức gió. Chọn bật hay tắt đường báo điểm rơi.
- **Build:** Thắng trong điều kiện có gió.
- **Reflect:** "Đường báo điểm rơi giúp em hay làm game dễ quá? Nên bật hay tắt?"
- **Dấu hiệu đạt:** Trẻ nói được "ngẫu nhiên" nghĩa là không đoán chắc được, chỉ đoán được khoảng.

### Bài 8: Chú sóc tham ăn
- **Real Problem:** Táo rơi xuống đất bị sóc nhặt ăn. Bác phải hứng nhanh hơn sóc.
- **Analyze:** "Sóc có luật gì? Sóc đi đâu? Khi nào sóc thắng? Luật của sóc và của giỏ ghép nhau thế nào?"
- **Design:** Chọn tốc độ sóc và số táo sóc được ăn trước khi em thua.
- **Build:** Đạt điểm trước khi sóc ăn đủ táo.
- **Reflect:** "Sóc quá nhanh hay quá chậm? Em sửa con số nào?"
- **Dấu hiệu đạt:** Trẻ viết riêng luật cho từng nhân vật và chỉ ra chỗ hai luật va chạm nhau.

### Bài 9: Nam châm
- **Real Problem:** Bác muốn một dụng cụ hút táo về giỏ, nhưng không được dùng mãi.
- **Analyze:** "Nam châm là chuỗi việc: bật, hút, tắt, chờ hồi. Đặt cho nó một cái tên để gọi lại."
- **Design:** Chọn thời gian hút và thời gian hồi. Khi chơi bấm nút Nam châm hoặc phím N.
- **Build:** Dùng nam châm đúng lúc để thắng.
- **Reflect:** "Em dùng nam châm lúc nào là lợi nhất? Vì sao cần hồi chiêu?"
- **Dấu hiệu đạt:** Trẻ nói được lợi ích của việc gói nhiều bước thành một khối có tên.

### Bài 10: Kỹ sư chỉnh game
- **Real Problem:** Bạn Nam nói game quá khó. Bạn Lan nói quá dễ. Em làm một bản vừa cho cả hai.
- **Analyze:** "Con số nào làm game khó nhất? Đoán trước rồi mới đổi. Mỗi lần chỉ đổi một số."
- **Design:** Chỉnh bảng tham số, ghi dự đoán trước khi chạy.
- **Build:** Chơi thử bản của em và thắng ở lần chơi thứ hai.
- **Reflect:** "Số nào đổi có tác dụng lớn nhất? Dự đoán của em đúng mấy lần?"
- **Dấu hiệu đạt:** Trẻ có bảng ghi: số đổi, dự đoán, kết quả thật.

## 4. Cách chia thời gian mỗi bài (45 phút)

| Bước | Phút |
|---|---|
| Real Problem | 5 |
| Analyze | 8 |
| Design | 10 |
| Build | 15 |
| Reflect | 7 |

## 5. Bản chơi thử

Mở `index.html` bằng trình duyệt. Kéo chuột hoặc ngón tay để di chuyển giỏ, phím mũi tên cũng được. Ở bài 9 và 10, bấm nút Nam châm hoặc phím N.

Bản này mô phỏng bước Design bằng các thanh trượt. Với lớp học thật, nên để trẻ vẽ phiếu thiết kế trên giấy trước rồi mới nhập số vào máy.

## 6. Điểm cần kiểm chứng

- Các giá trị mặc định và khoảng điều chỉnh chưa thử với trẻ thật. Cần cho 5 đến 8 em chơi và chỉnh bảng `F`, `P` trong `index.html`.
- Độ tuổi phù hợp chưa xác định. Giả định: bài 1 đến 5 cho lớp 2 đến 4, bài 6 đến 10 cho lớp 4 đến 7.
- Nếu muốn trẻ tự lập trình thay vì chỉnh thông số, có thể dựng lại từng bài bằng Scratch. Bảng ở mục 2 dùng được nguyên làm danh sách khối lệnh cần dạy.
