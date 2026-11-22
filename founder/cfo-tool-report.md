> Bản gốc do công cụ `unit_economics.py` của founder-cfo xuất ra, chạy trên `founder/numbers.json`. Đơn vị tiền là **đồng**. Công cụ in sẵn ký hiệu $, tôi đã bỏ ký hiệu đó; ngoài ra không sửa con số nào.

# Unit economics: Tiệm giặt sấy + rèm trọn gói, Tân Phú (152 Tân Kỳ Tân Quý, 10 triệu/tháng). Đơn vị tiền: đồng

Every number below comes from the input file. Nothing is looked up or guessed.

## One kg

| line | per kg |
| --- | ---: |
| Price | 14,545.00 |
| Điện máy giặt + máy sấy (ước tính 0,55 kWh/kg × ~3.400đ/kWh) | -1,900.00 |
| Nước + phí thoát nước (ước tính 5,8 L/kg × 29,3đ/L) | -170.00 |
| Nước giặt, nước xả, tẩy (ước tính) | -1,000.00 |
| Túi nilon, tem (ước tính) | -350.00 |
| Xăng giao nhận và đi tháo lắp rèm (ước tính) | -450.00 |
| Dự phòng bồi thường, giặt lại (~1% giá) | -150.00 |
| **Contribution** (what each kg leaves to pay the fixed costs) | **10,525.00** (72%) |

## The margin that matters

Fixed costs: 26,566,650 a month (Thuê mặt bằng (tin 152 Tân Kỳ Tân Quý) 10,000,000, Nhân viên toàn thời gian 7,500,000, BHXH chủ đóng 21,5% trên lương tối thiểu Vùng I 5.310.000đ 1,141,650, Bán thời gian giao nhận/rèm 5 giờ × 30 ngày × 25.500đ 3,825,000, Điện chiếu sáng, quạt, wifi, camera (ước tính) 700,000, Bảo trì máy 1,000,000, Marketing duy trì (ước tính) 1,500,000, Phần mềm, điện thoại (ước tính) 200,000, Phí rác, an ninh khu phố (ước tính) 200,000, Chi phí khác (ước tính) 500,000).

- **Break-even: 85 kgs a day.** Below that you lose money every month.
- **Profit margin at your plan** (110 a day): **17%** of every sale, after every cost.
- Capacity: 160 a day.

## Year 1, month by month

| month | kgs a day | revenue | profit | cumulative (after 207,720,000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 30 | 13,090,500 | -17,094,150 | -224,814,150 |
| 2 | 40 | 17,454,000 | -13,936,650 | -238,750,800 |
| 3 | 50 | 21,817,500 | -10,779,150 | -249,529,950 |
| 4 | 60 | 26,181,000 | -7,621,650 | -257,151,600 |
| 5 | 70 | 30,544,500 | -4,464,150 | -261,615,750 |
| 6 | 78 | 34,035,300 | -1,938,150 | -263,553,900 |
| 7 | 85 | 37,089,750 | 272,100 | -263,281,800 |
| 8 | 92 | 40,144,200 | 2,482,350 | -260,799,450 |
| 9 | 98 | 42,762,300 | 4,376,850 | -256,422,600 |
| 10 | 103 | 44,944,050 | 5,955,600 | -250,467,000 |
| 11 | 107 | 46,689,450 | 7,218,600 | -243,248,400 |
| 12 | 110 | 47,998,500 | 8,165,850 | -235,082,550 |

- **Year 1 operating profit: -27,362,550** on 402,751,050 of revenue.
- After the 207,720,000 startup spend: -235,082,550.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **263,553,900**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 17% | 85 | -27,362,550 |
| Price -10% | 8% | 98 | -67,637,655 |
| Volume -20% | 3% | 85 | -85,650,000 |
| Unit costs +15% | 13% | 90 | -44,059,620 |

## Red flags

- Year 1 loses money on operations (-27,362,550).
- The startup spend is not earned back within year 1.
