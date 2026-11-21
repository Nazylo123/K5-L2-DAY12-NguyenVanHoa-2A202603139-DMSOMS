# Tự đánh giá — Nguyễn Văn Hoa · G02

## 1. Tự rà soát 4 cảnh

| Ảnh | Đối tượng | Loại lỗi | Ghi chú | Đã sửa? |
|---|---|---|---|---|
| `S01_ir.png` | `infant_seat` | Chưa xác nhận | Hai bản khác `facing`: `rear` và `front`. Kiểm hướng lắp theo xe (§4.8). | |
| `S03_rgb.png` | `object` | Chưa xác nhận | Checker có hai box chỉ ghép được ở phía bạn review hoặc không đạt ngưỡng IoU. Kiểm lại trên ảnh (§4.4, §4.8). | |
| `D03.png` | `person` | Chưa xác nhận | `seatbelt` khác nhau: `worn_correct` và `unknown`. Kiểm phần dây nhìn thấy (§4.7). | |
| `D04.png` | `face`, `face13` | Chưa xác nhận | Hai mắt được gán `closed` trong bản của mình, `unknown` trong bản đối chiếu. Checker cũng báo cờ che ở cả bốn điểm mỗi mắt (§4.5–4.6). | |

## 2. Lỗi mình lặp lại nhiều nhất hôm nay

Kết quả tự kiểm bản cuối: 22 ảnh, 0 lỗi, 6 cảnh báo về trạng thái mắt và cờ che khuất.

- Lỗi đã xác nhận khi xem lại: …
- Vì sao mình mắc: …
- Lần sau tránh bằng cách: …

## 3. Ghi chú về disagreement_log

Script so sánh 22 ảnh chung và ghi 63 dòng khác biệt (55 dòng DMS, 8 dòng OMS). Đây là số dòng khác biệt, không phải số lỗi đã xác nhận.

- Một dòng bạn review đúng và mình sai: …
- Mình học được gì từ dòng đó: …
