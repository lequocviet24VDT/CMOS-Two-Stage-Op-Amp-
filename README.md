# Thiết kế và mô phỏng Op-Amp CMOS 2 tầng trên LTspice

## 1. Giới thiệu

Đây là dự án cá nhân nhằm nghiên cứu và thiết kế mạch khuếch đại thuật toán CMOS 2 tầng trên phần mềm LTspice.

Mục tiêu của dự án là củng cố kiến thức về thiết kế vi mạch tương tự, nguyên lý hoạt động của MOSFET và các thông số đặc trưng của mạch khuếch đại.

## 2. Thông số thiết kế

| Thông số | Giá trị mục tiêu |
|---|---:|
| Điện áp nguồn (V<sub>DD</sub>) | 1,8 V |
| Độ lợi DC | 50–60 dB |
| Tích độ lợi – băng thông (GBW) | 20 MHz |
| Điện dung tải (C<sub>L</sub>) | 5 pF |

## 3. Cấu trúc mạch

Mạch Op-Amp được thiết kế theo kiến trúc CMOS 2 tầng, bao gồm:

- Tầng đầu vào vi sai và tải chủ động.
- Tầng khuếch đại thứ hai.
- Tụ bù Miller nhằm cải thiện tính ổn định của mạch.

## 4. Mô phỏng và đánh giá

Mạch được mô phỏng trên LTspice để đánh giá các thông số kỹ thuật, bao gồm:

- Độ lợi điện áp DC.
- Tích độ lợi – băng thông (GBW).
- Dự trữ pha (PM).
- Tốc độ đáp ứng sườn (Slew Rate).
- Nhiễu đầu vào quy đổi.
- Công suất tiêu thụ.

Các đồ thị mô phỏng và kết quả đo được sẽ được trình bày trong thư mục `Kết quả mô phỏng/`.

## 5. Công cụ sử dụng

- LTspice.
- Thiết kế mạch tương tự CMOS.
- Phân tích điểm làm việc của MOSFET.
- Mô phỏng AC, quá độ và nhiễu.

## 6. Mục tiêu học tập

Thông qua dự án này, tôi hướng đến việc củng cố kiến thức và phát triển kỹ năng thiết kế, mô phỏng và phân tích hiệu năng mạch vi mạch tương tự.

Đây là dự án học tập cá nhân, phục vụ quá trình tự nghiên cứu và phát triển kỹ năng thiết kế vi mạch.
