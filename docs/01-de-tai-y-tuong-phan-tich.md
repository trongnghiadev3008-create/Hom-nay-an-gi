# Hôm nay ăn gì? – Chọn đề tài, ý tưởng, nghiên cứu và phân tích



## Nhóm: X 
## Thành viên nhóm

| STT | Họ và tên | MSSV | Vai trò |
|---|---|---|---|
| 1 | Lương Trọng Nghĩa | [087206014598] | [Nhóm trưởng] |
| 2 | Trần Cao Thịnh | [066206014460] | [Thành viên] |
| 3 | Trần Quốc Kha | [074206003186] | [Thành viên] |

## 1. Chọn đề tài

**Tên ứng dụng:** Hôm nay ăn gì?

**Mô tả ngắn:** Ứng dụng di động giúp người dùng quyết định nhanh bữa ăn trong vòng khoảng 20 phút bằng cách "quay" ngẫu nhiên một món phù hợp với tiêu chí của mình (bữa ăn, ngân sách, nguyên liệu sẵn có), sau đó dẫn đến quán hoặc nền tảng giao đồ ăn để đặt món.

**Lý do chọn đề tài:**

- Đây là câu hỏi quen thuộc mỗi ngày của sinh viên, dân văn phòng và các gia đình nhỏ: "Trưa nay ăn gì?". Việc phải nghĩ và chọn lặp lại nhiều lần khiến người dùng mệt mỏi (decision fatigue).
- Đề tài gần gũi, dễ khảo sát ngay trong nhóm và lớp, dễ kiểm chứng nhu cầu thật.
- Phạm vi tất cả người dùng
- Có yếu tố giao diện thú vị (hiệu ứng quay, thẻ món ăn) 

## 2. Vấn đề và mục tiêu

### 2.1 Vấn đề cần giải quyết

- Mất nhiều thời gian lướt app giao đồ ăn hoặc bản đồ nhưng vẫn không chọn được món.
- Hay ăn lặp lại một vài món quen thuộc, ngại thử món mới.
- Khó cân đối giữa ngân sách, khẩu vị, nhóm người đi cùng và thời gian.
- Có nguyên liệu trong nhà nhưng không biết nấu hoặc chọn món gì.

### 2.2 Mục tiêu sản phẩm

- Giúp người dùng chốt món trong vài thao tác, mục tiêu dưới 1 phút.
- Gợi ý món phù hợp theo tiêu chí do người dùng đặt ra.
- Lưu lại món yêu thích và lịch sử để lần sau chọn nhanh hơn, tránh lặp.
- Kết nối thẳng sang bản đồ và ứng dụng giao đồ ăn để hoàn tất quyết định.

### 2.3 Mục tiêu học tập của nhóm

- Thực hành quy trình: nghiên cứu → ý tưởng → phân tích → thiết kế giao diện.
- Hoàn thiện bộ thiết kế đầy đủ trên Figma và quản lý toàn bộ tài liệu trên GitHub.

## 3. Đối tượng người dùng

| | Persona 1 | Persona 2 | Persona 3 |
|---|---|---|---|
| **Mô tả** | Sinh viên, 19–22 tuổi | Nhân viên văn phòng, 23–32 tuổi | Người nội trợ / gia đình nhỏ, 28–40 tuổi |
| **Nhu cầu** | Ăn ngon, rẻ, gần trường | Chọn nhanh giờ nghỉ trưa, ngại nghĩ | Nấu gì từ nguyên liệu có sẵn, đa dạng bữa ăn |
| **Nỗi đau** | Ngân sách hạn hẹp, hay ăn lặp | Ít thời gian, mỗi ngày phải quyết định | Cả nhà khó thống nhất món |
| **Tính năng cần** | Lọc theo giá, quay ngẫu nhiên | Quay nhanh, lưu món hay ăn | Chọn theo nguyên liệu, ngân sách mỗi người |

*Ghi chú: các persona trên là giả định ban đầu, nhóm nên đối chiếu lại với kết quả khảo sát ở mục 5.3.*

## 4. Ý tưởng và tính năng

### 4.1 Ý tưởng cốt lõi
Để trả lời cho câu  " ăn gì cũng được  "  
Biến việc chọn món thành một trải nghiệm vui và nhanh


### 4.2 Danh sách màn hình 

| STT | Màn hình | Chức năng chính |
|---|---|---|
| 01 | Splash và Welcome | Giới thiệu ứng dụng, nút "Bắt đầu chọn món", thông điệp "Đừng mất 20 phút để nghĩ món" |
| 02 | Trước khi quay | Màn hình chính với vòng quay, chọn tiêu chí (ăn trưa, dưới 70k, ăn đây...), mục "Trong kho có gì?" để chọn món/nguyên liệu sẵn có |
| 03 | Đang quay | Hiệu ứng quay ngẫu nhiên, trạng thái "Đang quay" |
| 04 | Kết quả quay | Hiển thị món được chọn kèm giá, mô tả; nút "Xem quán", "Lưu món"; liên kết Google Maps, GrabFood, ShopeeFood, chia sẻ; lựa chọn "Không thích món này?" |
| 05 | Sau khi quay | Quay lại trang chính với nút "Thử lại" để quay lần nữa |
| 06 | Khám phá | Chọn loại món (cơm, bún/phở, đồ Tây, healthy, ăn vặt, đồ uống) và ngân sách mỗi người bằng thanh trượt |
| 07 | Món hợp gu | Danh sách khoảng 4 món vừa gu, vừa túi tiền; hiển thị giá, tổng ngân sách ước tính; nút "Xem chi tiết món" |
| 08 | Kết quả / Chi tiết món | Thông tin chi tiết món, nút xem quán, lưu món, các liên kết đặt món |
| 09 | Yêu thích | Danh sách món đã lưu (ví dụ: cơm tấm sườn bì chả) |
| 10 | Lịch sử | Các món đã chọn, đã quay theo từng ngày (hôm nay, hôm qua), trạng thái đã chọn hoặc đã bỏ qua |

Thanh điều hướng dưới cùng gồm 4 mục: **Trang chủ – Khám phá – Yêu thích – Lịch sử**.

### 4.3 Phân nhóm tính năng

**Tính năng chính (MVP):**

- Quay chọn món ngẫu nhiên theo tiêu chí (bữa ăn, ngân sách, kiểu ăn).
- Xem kết quả và chi tiết món.
- Lưu món yêu thích.
- Lưu lịch sử các món đã quay hoặc đã chọn.
- Khám phá món theo loại và ngân sách mỗi người.

**Tính năng mở rộng (phát triển sau):**

- Gợi ý theo nguyên liệu có trong nhà ("Trong kho có gì?").
- Liên kết mở nhanh Google Maps, GrabFood, ShopeeFood.
- Chia sẻ kết quả cho bạn bè, nhóm.
- Gợi ý tránh lặp món so với lịch sử vài ngày gần đây.
- Gợi ý theo vị trí và khung giờ, bình chọn nhóm, tài khoản đăng nhập.

## 5. Nghiên cứu

### 5.1 Nghiên cứu các giải pháp hiện có

Nhóm cần tự rà soát và kiểm chứng lại thông tin dưới đây bằng cách tải và dùng thử từng ứng dụng, sau đó ghi lại nhận xét thực tế.

| Nhóm giải pháp | Ví dụ | Điểm mạnh | Hạn chế so với ý tưởng của nhóm |
|---|---|---|---|
| App giao đồ ăn | GrabFood, ShopeeFood, be, Foody | Dữ liệu quán lớn, đặt món trực tiếp | Danh sách quá dài gây rối, không hỗ trợ "quyết định" nhanh, thiên về mua hàng |
| Bản đồ và đánh giá | Google Maps | Tìm quán gần, có đánh giá | Phải tự lọc và so sánh, mất thời gian |
| Vòng quay ngẫu nhiên | Web hoặc app vòng quay may mắn chọn món | Đơn giản, vui | Thường phải tự nhập danh sách, ít tiêu chí, không có lịch sử hay lưu món |


### 5.2 Phân tích khác biệt

- Tập trung vào giải quyết sự phân vân, không phải bán món.
- Có yếu tố vui và gamification (vòng quay) tạo thói quen mở app mỗi ngày.
- Cá nhân hoá nhẹ bằng tiêu chí, yêu thích và lịch sử.
- Không phụ thuộc một nền tảng: cho phép sang nhiều nơi đặt món.


## 6. Phân tích

### 6.1 Luồng người dùng chính
Thêm vào sau ....

### 6.2 Yêu cầu chức năng

- Chọn và thay đổi tiêu chí lọc (bữa ăn, mức giá, kiểu ăn).
- Quay ngẫu nhiên và hiển thị kết quả có hiệu ứng.
- Quay lại nhiều lần; loại bỏ món người dùng không thích.
- Xem chi tiết món: tên, mô tả, giá.
- Lưu và bỏ lưu món yêu thích.
- Lưu và xem lịch sử theo ngày.
- Điều hướng bằng thanh tab dưới cùng.
- Mở liên kết ngoài (bản đồ, giao đồ ăn).

### 6.3 Yêu cầu phi chức năng

- Giao diện đơn giản, dùng được bằng một tay, thao tác ít bước.
- Phản hồi nhanh, hiệu ứng quay mượt.
- Màu sắc ấm (cam, kem) gợi cảm giác ẩm thực, nhất quán trên mọi màn hình.
- Chữ dễ đọc, nút bấm đủ lớn.
- Dữ liệu yêu thích và lịch sử được lưu cục bộ trên thiết bị (giai đoạn đầu).

### 6.4 Phân tích SWOT

| Điểm mạnh | Điểm yếu |
|---|---|
| Ý tưởng gần gũi, dễ hiểu; giao diện vui; luồng ngắn gọn | Phụ thuộc dữ liệu món và quán; 

| Cơ hội | Thách thức |
|---|---|
| Nhu cầu hằng ngày rất lớn; có thể liên kết với nền tảng giao đồ ăn; mở rộng sang nhóm bạn, gia đình | Dễ bị sao chép; người dùng có thể quay lại dùng thẳng app giao đồ ăn; cần giữ chân bằng giá trị riêng |

### 6.5 Rủi ro và hướng xử lý

| Rủi ro | Hướng xử lý |
|---|---|
| Gợi ý không hợp khẩu vị | Cho phép "Thử lại", loại món không thích, học từ yêu thích và lịch sử |
| Thiếu dữ liệu món và quán | Bắt đầu với danh sách món phổ biến tự xây dựng, mở rộng dần |
| Người dùng chỉ dùng một vài lần | Thêm lịch sử, yêu thích, gợi ý tránh lặp để tạo thói quen |
| Phạm vi quá rộng so với thời gian | Chốt MVP ở mục 4.3, tính năng mở rộng làm sau |

