# Tài chính: tiệm giặt sấy + rèm trọn gói, Tân Phú

Mọi con số dưới đây đều do công cụ `unit_economics.py` (founder-cfo) tính từ `founder/numbers.json`. Bản gốc của công cụ: `founder/cfo-tool-report.md`. Nguồn của từng dữ liệu đầu vào: `founder/cfo-sources.md`. Chỗ ghi *(tính tay)* là phép tính của tôi từ kết quả của công cụ. Đơn vị: đồng; "tr" = triệu đồng.

**Đây không phải tư vấn tài chính, thuế hay pháp lý.** Trước khi chi tiền, nhờ kế toán xem lại cách đăng ký, lương, bảo hiểm xã hội và thuế.

## Ghi chú của CFO

### Kết luận nhanh
Với các giả định hiện tại (giặt 12.000đ/kg, mỗi ngày 1 việc rèm 400.000đ, thuê 10 triệu), tiệm **có lãi khi đã chạy ổn định**:
- Kế hoạch là 110 kg/ngày, khoảng 3.300 kg/tháng. Ở mức đó tiệm lãi khoảng **8,2 triệu/tháng**.
- **Đây là thu nhập của chính chủ tiệm** (người làm ca chiều tối mỗi ngày), chưa trừ lương cho chủ.

Có 2 vấn đề:
1. **Tiền cần có là 263,6 triệu, vượt ngân sách 250 triệu.** Gồm 207,7 triệu đầu tư ban đầu, cộng khoản lỗ dồn của 6 tháng đầu.
2. **Chỉ giặt theo kg thì lỗ.** Không có mảng rèm, hòa vốn phải đạt 111 kg giặt/ngày, cao hơn kế hoạch 100 kg. **Mảng rèm là thứ làm tiệm có lãi.**

Muốn vừa ngân sách thì phải dùng ít nhất 1–2 cách ở mục "Cách cải thiện" bên dưới.

### Biên lợi nhuận
- Giá bình quân **14.545đ/kg**, là giá trộn giữa giặt và rèm theo tỷ lệ kế hoạch: 100 kg giặt × 12.000đ + 10 kg rèm × 40.000đ, chia cho 110 kg.
- Chi phí trực tiếp **4.020đ/kg**: điện, nước, hóa chất, túi, xăng, dự phòng.
- **Mỗi kg để lại 10.525đ (72%)** để trả chi phí cố định.
- Chi phí cố định **26,57 triệu/tháng**. Lớn nhất là nhân sự (12,47 tr) và tiền thuê (10 tr).
- **Hòa vốn: 85 kg/ngày.**
- **Biên lợi nhuận ở mức kế hoạch: 17%.**

### Năm đầu, từng tháng (giả định khách tăng dần)

| Tháng | kg/ngày | Doanh thu | Lãi/lỗ | Lũy kế (sau 207,7 tr đầu tư) |
| --- | ---: | ---: | ---: | ---: |
| 1 | 30 | 13,09 tr | −17,09 tr | −224,81 tr |
| 2 | 40 | 17,45 tr | −13,94 tr | −238,75 tr |
| 3 | 50 | 21,82 tr | −10,78 tr | −249,53 tr |
| 4 | 60 | 26,18 tr | −7,62 tr | −257,15 tr |
| 5 | 70 | 30,54 tr | −4,46 tr | −261,62 tr |
| 6 | 78 | 34,04 tr | −1,94 tr | **−263,55 tr** (đáy) |
| 7 | 85 | 37,09 tr | +0,27 tr | −263,28 tr |
| 8 | 92 | 40,14 tr | +2,48 tr | −260,80 tr |
| 9 | 98 | 42,76 tr | +4,38 tr | −256,42 tr |
| 10 | 103 | 44,94 tr | +5,96 tr | −250,47 tr |
| 11 | 107 | 46,69 tr | +7,22 tr | −243,25 tr |
| 12 | 110 | 48,00 tr | +8,17 tr | −235,08 tr |

- Doanh thu năm 1: **402,75 tr**. Lỗ vận hành năm 1: **−27,36 tr**.
- **Tiền cần có trước khi tiệm tự nuôi được: 263,55 tr.**
- **Thu hồi vốn:** không trong năm 1. Nếu từ tháng 13 giữ được mức kế hoạch, cần khoảng **41 tháng** (gần 3,5 năm) *(tính tay)*. Tiền cọc 10 tr sẽ được hoàn lại khi trả mặt bằng.
- Mức tăng khách từ 30 lên 110 kg/ngày là **ước tính**: chưa có khảo sát khách và chưa có thử nghiệm thật. Đây là con số dễ sai nhất.

### Con số phải theo dõi sát nhất
Giá giặt/kg và lượng khách. Theo bảng tình huống của công cụ:

| Tình huống | Biên lợi nhuận | Hòa vốn/ngày | Lãi năm 1 |
| --- | ---: | ---: | ---: |
| Kế hoạch | 17% | 85 kg | −27,36 tr |
| Giá giảm 10% | 8% | 98 kg | −67,64 tr |
| Khách ít hơn 20% | 3% | 85 kg | −85,65 tr |
| Chi phí trực tiếp tăng 15% | 13% | 90 kg | −44,06 tr |

**Đừng đua giá với tiệm 8.000–10.000đ/kg.** Giặt 10.000đ/kg thì biên lợi nhuận chỉ còn 5%, hòa vốn 102 kg/ngày, cần 289,3 tr tiền mặt.

### Tiền mặt
Cần **263,6 tr**, so với ngân sách 250 tr, tức **thiếu khoảng 13,6 tr**. Con số này đã gồm 15 tr dự phòng phát sinh. Không nên cắt khoản dự phòng.

### Cách cải thiện (đều đã chạy qua công cụ, trừ chỗ ghi "tính tay")

| # | Cách | Biên LN | Hòa vốn/ngày | Lãi năm 1 | Tiền cần có | Thu hồi vốn |
| --- | --- | ---: | ---: | ---: | ---: | ---: |
| 0 | Kế hoạch gốc | 17% | 85 kg | −27,4 tr | 263,6 tr | ~tháng 41 |
| 1 | **Giá giặt 13.500đ/kg** (thay 12.000đ) | 24% | 75 kg | **+10,4 tr** | 251,4 tr | ~tháng 28 |
| 2 | Giá giặt 15.000đ/kg | 30% | 67 kg | +48,2 tr | 242,4 tr | ~tháng 22 |
| 3 | **Gấp đôi việc rèm** (2 việc/ngày, 120 kg/ngày) | 32% | 70 kg | +63,2 tr | 239,5 tr | ~tháng 20 |
| 4 | **Hoãn tuyển nhân viên toàn thời gian 3 tháng đầu** (chủ + người bán thời gian tự làm; tiết kiệm 3 × 8,64 tr = 25,9 tr) | 17% | 85 kg | ~−1,4 tr *(tính tay)* | **~237,6 tr** *(tính tay)* | ~tháng 38 *(tính tay)* |
| 5 | Cách 1 + cách 4 | 24% | 75 kg | ~+36,3 tr *(tính tay)* | **~225,5 tr** *(tính tay)* | ~tháng 26 *(tính tay)* |
| 6 | **Sang tiệm Vườn Lài** (120 tr gồm cọc; thuê 7 tr; bảo trì máy cũ 2 tr/tháng) | 21% | 78 kg | −3,4 tr | **220,3 tr** | ~tháng 30 |

Cách đọc bảng:
- **Cách 1** chỉ cần khách chấp nhận giá giặt **13.500đ/kg đã gồm giao nhận miễn phí trong 3 km**.
  - So sánh: Giặt Ơi thu 30.000đ/kg cộng 40.000đ tiền ship, Tik Tak thu 15.000đ/kg cộng 30.000đ ship.
  - So với các app thì vẫn rẻ. Nhưng mức này cao hơn tiệm gần nhà (khoảng 8–12k), nên phải thử với khách thật trước khi chốt.
- **Cách 3** cần khoảng 60 việc rèm/tháng.
  - Riêng Celadon có hơn 6.600 hộ, và mùa trước Tết là cao điểm giặt rèm.
  - Đây là cách tăng lãi mạnh nhất, nhưng cũng là giả định chưa được kiểm chứng.
- **Cách 4** làm chủ tiệm phải tự đứng khoảng 14 tiếng/ngày trong 3 tháng.
- **Cách 6** đã vừa ngân sách mà không cần đổi gì khác. Đổi lại:
  - Mặt tiền chỉ 3 m, chật cho việc phơi rèm.
  - Máy cũ, chưa rõ tình trạng.
  - Phải biết **vì sao chủ cũ bán**. Vườn Lài đã có ít nhất 2 tiệm giặt khác.

**Đề xuất:** thuê mặt bằng mới, kết hợp **cách 1 và cách 4**, cần khoảng 225 tr. Đẩy mạnh mảng rèm ngay từ đầu, nhắm mùa trước Tết. Phương án sang tiệm chỉ nên chọn nếu thợ kiểm tra máy xác nhận còn tốt và chủ cũ cho xem sổ doanh thu thật.

### Thuế
- Doanh thu năm 1 là 402,75 tr. Ở mức kế hoạch là 576 tr/năm *(tính tay)*. Cả hai đều **dưới 1 tỷ/năm**.
- Theo Nghị định 141/2026, mức này **không nộp VAT và thuế TNCN**, chỉ khai doanh thu thực tế trước 31/01 năm sau.
- Doanh thu trong bảng là trước thuế; ở mức này không phải cộng thêm thuế vào giá. Vượt 1 tỷ thì phải tính lại.

### Điện
- Ở mức kế hoạch, tiệm dùng khoảng 1.815 kWh/tháng cho máy *(tính tay: 110 kg × 0,55 kWh × 30 ngày)*, cộng đèn và quạt. Mức này **sát ngưỡng 2.000 kWh/tháng**; vượt ngưỡng thì bị tính giá điện theo 3 khung giờ (giờ cao điểm đắt hơn 70%).
- Nên ghi số điện mỗi tuần (SOP 6 trong `ops.md`).

### Điều kiện của hội đồng
Chưa chạy `/founder-board`, nên chưa có điều kiện nào để đối chiếu.

## Những giả định quan trọng nhất (cần kiểm chứng)

1. **Giá:**
   - Giặt 12.000đ/kg, giao nhận miễn phí trong 3 km.
   - Rèm 400.000đ cho mỗi việc khoảng 10 kg, đã gồm tháo lắp (dưới 10 kg giá trọn gói 399.000đ; trên 10 kg 35.000đ/kg). Mức này nằm giữa Vua Vệ Sinh 300k / BeeClean 350k và mức phổ biến khoảng 600k.
2. **Lượng khách:**
   - 110 kg/ngày khi ổn định, khoảng 30 khách × 3,3 kg cộng 1 việc rèm.
   - Báo chí ghi tiệm lâu năm ở khu sinh viên có khoảng 30 khách ngày thường, 50–60 khách ngày đông.
   - Số kg mỗi khách là ước tính.
3. **Khối lượng một bộ rèm:** không tìm được nguồn. Nếu một việc rèm trung bình chỉ 5 kg thì doanh thu rèm theo kg vẫn giữ, nhưng số việc phải gấp đôi mới ra cùng số kg.
4. **Chi phí trên mỗi kg** (điện 1.900đ, hóa chất 1.000đ…) là ước tính. Đo thật trong 2 tuần đầu rồi cập nhật `numbers.json` và chạy lại.
