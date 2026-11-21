# Nguồn của từng con số trong `numbers.json`

Tra cứu ngày 21/11/2026. Có 3 loại nguồn:

- **Nguồn:** giá hoặc số liệu công khai, có link.
- **Ước tính:** suy luận của tôi, có ghi cách tính. Cần thay bằng báo giá hoặc số đo thật.
- **Người dùng:** do anh/chị cung cấp.

## Giá bán (bình quân 14.545đ/kg)

| Dòng | Giá trị | Loại | Ghi chú / nguồn |
| --- | --- | --- | --- |
| Giặt sấy xếp | 12.000đ/kg | Ước tính | Khu sinh viên/công nhân 8.000–12.000đ ([Thanh Niên 2023](https://thanhnien.vn/co-mot-dich-vu-cang-mua-cang-dong-khach-185231006180055959.htm)); Giặt Sấy Thông Minh 8–10k ([bảng giá](https://giatsaythongminh.vn/bang-gia)); Tik Tak 15k + ship ([giá](https://giatsaytiktak247.com/giat-say-quan-ao)); Giặt Ơi 30k + ship 40k ([giá](https://giatoi.vn/khu-vuc/tan-phu/)) |
| Rèm trọn gói | 400.000đ cho mỗi việc khoảng 10 kg (≈40.000đ/kg) | Ước tính | Gói tải nhỏ đã gồm tháo lắp: Vua Vệ Sinh 300k, BeeClean 350k, BestClean 399–449k, Ngôi Nhà Xanh 500k, mức phổ biến 590–600k; trên ngưỡng 35–40k/kg (`competitors.md`). Khối lượng một bộ rèm: không có nguồn |
| Tỷ lệ trộn | 100 kg giặt + 10 kg rèm mỗi ngày | Ước tính | Giá bình quân = (100 × 12.000 + 10 × 40.000) / 110 = 14.545đ |

## Chi phí trực tiếp mỗi kg (4.020đ)

| Dòng | Giá trị | Loại | Cách tính / nguồn |
| --- | --- | --- | --- |
| Điện | 1.900đ | Ước tính | Khoảng 0,55 kWh/kg (máy sấy 4,8 kW, giả định 10 kg mỗi mẻ 50 phút ≈ 0,4–0,5 kWh/kg; máy giặt khoảng 0,5 kWh mỗi mẻ 12 kg) × khoảng 3.400đ/kWh. Giá kinh doanh giờ bình thường 3.089đ chưa VAT ([SGGP](https://www.sggp.org.vn/chi-tiet-gia-ban-le-dien-ap-dung-tu-ngay-1-11-2026-post880092.html)), làm tròn lên cho VAT. Công suất máy sấy: [meta.vn](https://meta.vn/may-say-thuong-mai-cua-truoc-speed-queen-les17awf3022-p112097) |
| Nước | 170đ | Ước tính | Máy LG 17 kg dùng 70,1 L mỗi mẻ ([meta.vn](https://meta.vn/may-giat-cong-nghiep-lg-cwt29mdqrs-p119795)). Giả định 12 kg mỗi mẻ → 5,8 L/kg. Giá nước kinh doanh 21.300đ/m³ + 5% VAT + phí thoát nước 30% ≈ 29.300đ/m³ ([SGGP](https://www.sggp.org.vn/don-gia-nuoc-sinh-hoat-ho-gia-dinh-tinh-theo-dinh-muc-post787873.html), giá 2025) |
| Hóa chất | 1.000đ | Ước tính | Nước giặt Hando 35.500đ/L ([handomart](https://www.handomart.com/collections/nuoc-giat-xa-tay-quan-ao)). Khoảng 15 mL nước giặt và 10 mL nước xả mỗi kg ≈ 850đ, cộng tẩy thỉnh thoảng. Một đại lý ghi hóa chất chiếm 10–15% doanh thu ([worldwash, 2021](http://worldwash.vn/mo-tiem-giat-la-can-bao-nhieu-von-chi-phi-mo-tiem-giat-la.html)) |
| Túi, tem | 350đ | Ước tính | Túi PE khoảng 45.000đ/kg túi, 20–40 túi/kg ([chiaki](https://chiaki.vn/tui-nilon-den-tui-xop-pe-2-quai-1-kg)) → khoảng 1.500đ/túi, mỗi túi khoảng 5 kg đồ |
| Xăng giao nhận | 450đ | Ước tính | Xăng E10 RON95 19.840đ/L ([Báo Văn Hóa](https://baovanhoa.vn/gia-xang-dau-hom-nay-13-11-2026-ap-dung-muc-dieu-chinh-tu-chieu-12-11.html)); Wave Alpha 1,72 L/100 km → khoảng 341đ/km, cộng hao mòn xe → khoảng 650đ/km. Giả định 50% số kg được giao nhận, mỗi đơn khoảng 6 km cả đi lấy và đi trả, đơn khoảng 5 kg; việc rèm 2 chuyến khoảng 6 km mỗi chuyến |
| Dự phòng bồi thường | 150đ | Ước tính | Khoảng 1% giá bán, cho giặt lại và bồi thường (xem rủi ro 1–3 trong `ops.md`) |

## Chi phí cố định mỗi tháng (26,57 triệu)

| Dòng | Giá trị | Loại | Nguồn |
| --- | --- | --- | --- |
| Thuê mặt bằng | 10.000.000đ | Nguồn + người dùng | Tin 152 Tân Kỳ Tân Quý, 4×12 m, 10 tr, cọc 10 tr ([nhatot](https://www.nhatot.com/135681901.htm)). Anh/chị đặt trần dưới 13 tr, cọc 1–2 tháng, trả trước 1 tháng |
| Nhân viên toàn thời gian | 7.500.000đ | Nguồn | Khoảng 6,5–9 tr; Tân Phú có tin tới 12 tr ([vieclamtot](https://www.vieclamtot.com/tags/nhan-vien-giat-ui-tphcm), [jobsgo](https://jobsgo.vn/viec-lam/nhan-vien-giat-say-xep-lao-dong-pho-thong-25570805006.html)) |
| BHXH chủ đóng | 1.141.650đ | Nguồn + ước tính | 21,5% ([luatvietnam](https://luatvietnam.vn/bao-hiem/ty-le-dong-bhxh-cua-doanh-nghiep-va-nguoi-lao-dong-563-100379-article.html)) × lương tối thiểu Vùng I 5.310.000đ ([Nghị định 293/2025](https://hatinh.gov.vn/vi/bai-viet/tang-luong-toi-thieu-vung-tu-112026)). Mức đóng thật: hỏi kế toán |
| Bán thời gian | 3.825.000đ | Nguồn | 5 giờ × 30 ngày × 25.500đ/giờ, đúng mức tối thiểu theo giờ Vùng I 2026 |
| Điện chiếu sáng, quạt, wifi, camera | 700.000đ | Ước tính | |
| Bảo trì máy | 1.000.000đ | Nguồn | 1–2 tr/tháng ([sapo](https://www.sapo.vn/blog/mo-tiem-giat-la-tu-a-den-z-can-bao-nhieu-von)) |
| Marketing duy trì | 1.500.000đ | Ước tính | Quảng cáo Zalo/Facebook, tờ rơi |
| Phần mềm, điện thoại | 200.000đ | Ước tính | |
| Phí rác, an ninh | 200.000đ | Ước tính | |
| Khác | 500.000đ | Ước tính | |
| **Lương chủ tiệm** | **0đ** | – | **Chưa tính.** Lợi nhuận trong `cfo.md` là thu nhập của chủ |

## Đầu tư ban đầu (207,72 triệu)

| Dòng | Giá trị | Loại | Nguồn |
| --- | --- | --- | --- |
| Cọc mặt bằng 1 tháng | 10.000.000đ | Nguồn | tin 152 Tân Kỳ Tân Quý (tiền tháng đầu đã tính vào chi phí tháng 1) |
| Máy giặt LG 17 kg | 43.990.000đ | Nguồn | [meta.vn](https://meta.vn/may-giat-cho-tiem-giat-lg-opl-cwt29mdors-asspevn-p125494) |
| Máy giặt LG 13 kg | 30.950.000đ | Nguồn | [meta.vn](https://meta.vn/may-giat-cong-nghiep-lg-cwg27mdqrs-assqeml-p119011) |
| 2 máy sấy Speed Queen 15 kg | 36.900.000đ | Nguồn | 2 × 18.450.000đ ([meta.vn](https://meta.vn/may-say-thuong-mai-cua-truoc-speed-queen-les17awf3022-p112097)) |
| Đi điện nước, nâng công suất điện | 15.000.000đ | Ước tính | Khoảng 13–35 tr theo một bài tổng hợp chi phí ([Hòa Phát](https://maygiathoaphat.vn/chi-phi-mo-cua-hang-tiem-giat-say-tu-dong-la-bao-nhieu-dieu-kien/)). Cần báo giá thợ điện tại mặt bằng |
| Ống thoát khí, thông gió | 5.000.000đ | Nguồn | 5–15 tr (cùng nguồn) |
| Sửa sang, quầy | 15.000.000đ | Nguồn | 10–30 tr (cùng nguồn) |
| Dụng cụ rèm | 7.020.000đ | Nguồn | bàn ủi hơi đứng Philips 2,49 tr, bàn ủi treo Silver Star 1,29 tr, thang rút Nakata 1,85 tr, thang chữ A 1,39 tr (link trong `ops.md`) |
| Kệ, giá phơi rèm, bàn xếp | 6.000.000đ | Ước tính | cần báo giá |
| Cân, bình chữa cháy, camera | 3.860.000đ | Nguồn | cân 1,33 tr; 2 bình × 265k; camera khoảng 2 tr (link trong `ops.md`) |
| Bảng hiệu | 5.000.000đ | Ước tính | cần báo giá |
| Hóa chất, túi ban đầu | 3.000.000đ | Ước tính | |
| Túi lưới, đồng phục, túi giao | 2.000.000đ | Ước tính | |
| Giấy tờ, kiểm định cân | 1.000.000đ | Ước tính | |
| Marketing khai trương | 8.000.000đ | Nguồn | 5–15 tr ([Hòa Phát](https://maygiathoaphat.vn/chi-phi-mo-cua-hang-tiem-giat-say-tu-dong-la-bao-nhieu-dieu-kien/)) |
| Dự phòng | 15.000.000đ | Ước tính | Một nguồn khuyên dự phòng 10–15% ([sapo](https://www.sapo.vn/blog/mo-tiem-giat-la-tu-a-den-z-can-bao-nhieu-von)); ở đây khoảng 7% |

## Lượng khách

| Dòng | Giá trị | Loại | Cách tính / nguồn |
| --- | --- | --- | --- |
| Kế hoạch | 110 kg/ngày | Ước tính | Khoảng 30 khách × 3,3 kg + 1 việc rèm. Tiệm lâu năm ở khu sinh viên: khoảng 30 khách ngày thường, 60–80 ngày cao điểm ([Thanh Niên 2023](https://thanhnien.vn/co-mot-dich-vu-cang-mua-cang-dong-khach-185231006180055959.htm)); 50–60 khách/ngày ([Tiền Phong 2023](https://tienphong.vn/dich-vu-hai-ra-tien-cang-mua-cang-dat-khach-o-tphcm-post1574993.tpo)) |
| Tăng dần năm 1 | 30 → 110 kg/ngày | Ước tính | Chưa có khảo sát khách và chưa có thử nghiệm thật. Đây là giả định dễ sai nhất |
| Công suất | 160 kg/ngày | Ước tính | 2 máy sấy × khoảng 10 kg mỗi mẻ 50–60 phút × 14 giờ × 60% thời gian chạy |

## Phương án sang tiệm (`numbers-option-sang-tiem.json`)

- Giá sang 120 tr đã gồm cọc 12 tr; thuê 7 tr/tháng; kèm 6 máy giặt LG, 5 máy sấy, bàn ủi hơi, máy giặt giày ([nhatot 135697634](https://www.nhatot.com/135697634.htm)).
- Bảo trì máy cũ 2 tr/tháng và thợ kiểm tra 5 tr là **ước tính**.
- Mức tăng khách giữ như phương án thuê mới, tức chưa tính khách cũ có sẵn. Có thể thực tế nhanh hơn, nhưng chưa có số liệu.
