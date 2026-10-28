## Khái Niệm và Nâng Cao Chất Lượng Dân Số

Chất lượng dân số không chỉ đánh giá ở khía cạnh nhân trắc học (chiều cao, cân nặng, sức chịu đựng dẻo dai...) mà còn thể hiện qua đời sống tinh thần, mối quan hệ giữa con người trong xã hội, sự bình đẳng về cơ hội (lựa chọn việc làm, giáo dục, phúc lợi, hôn nhân...), sự tự do cá nhân và môi trường để phát huy khả năng sáng tạo.

Để nâng cao CLDS toàn diện, cần đảm bảo 5 khía cạnh cốt lõi [3]:
1. Thể chất và sức khỏe: Phát triển chiều cao, cân nặng theo tuổi; chăm sóc sức khỏe; đáp ứng nhu cầu dinh dưỡng và hòa hợp với môi trường tự nhiên, xã hội.
2. Trí tuệ và trình độ chuyên môn: Tỷ lệ biết chữ, tỷ lệ đi học, số năm theo học, bằng cấp và trình độ chuyên môn kỹ thuật phục vụ nghề nghiệp.
3. Tinh thần và đời sống văn hóa: Tỷ lệ hộ dân đạt chuẩn văn hóa, khả năng tiếp cận thư viện, tivi, điện thoại, internet và sự gắn kết cộng đồng.
4. Đặc trưng nhân khẩu học: Kiểm soát tỷ suất sinh, tỷ số giới tính khi sinh, tỷ lệ dân số thành thị.
5. Đời sống vật chất và dịch vụ xã hội cơ bản: Thu nhập bình quân đầu người, giảm tỷ lệ nghèo, tiếp cận nước sạch và hố xí hợp vệ sinh.

Mục tiêu Chiến lược Dân số Việt Nam đến năm 2030 (Mục tiêu 4)

* Tỷ lệ cặp nam/nữ thanh niên được tư vấn, khám sức khỏe trước khi kết hôn đạt 90%.
* Giảm 50% số cặp tảo hôn và 60% số cặp hôn nhân cận huyết thống.
* 70% phụ nữ mang thai được tầm soát ít nhất 4 loại bệnh tật bẩm sinh phổ biến; 90% trẻ sơ sinh được tầm soát ít nhất 5 bệnh bẩm sinh phổ biến.
* Tuổi thọ bình quân đạt 75 tuổi (thời gian sống khỏe mạnh đạt tối thiểu 68 năm).
* Chiều cao trung bình thanh niên 18 tuổi: Nam đạt 168,5 cm, Nữ đạt 157,5 cm.
* Chỉ số Phát triển Con người (HDI) nằm trong nhóm 4 nước hàng đầu khu vực Đông Nam Á.

---

## Các Chỉ Số Đánh Giá Chất Lượng Dân Số

Tài liệu bài giảng đi sâu vào 4 chỉ số chuẩn quốc tế do UNDP khởi xướng [5]:

| STT | Chữ viết tắt | Tiếng Anh | Tiếng Việt |
| :--- | :--- | :--- | :--- |
| 1 | HDI | Human Development Index | Chỉ số phát triển con người |
| 2 | IHDI | Inequality-adjusted Human Development Index | Chỉ số phát triển con người hiệu chỉnh bất bình đẳng |
| 3 | GDI | Gender Development Index | Chỉ số phát triển giới |
| 4 | MPI | Multidimensional Poverty Index | Chỉ số nghèo đa chiều |

---

## Chỉ Số Phát Triển Con Người (HDI)

### Ba chiều cạnh đánh giá
HDI được biên soạn từ năm 1990 (công bố trong Báo cáo HDR 1991) nhằm đánh giá tổng hợp mức độ phát triển con người dựa trên 3 trụ cột [5, 6]:
* Sức khỏe: Đo bằng Tuổi thọ trung bình khi sinh (Life Expectancy - LE).
* Giáo dục: Kết hợp giữa Số năm đi học trung bình của người từ 25 tuổi trở lên (Mean Years of Schooling - MYS) và Số năm đi học kỳ vọng của trẻ em trong độ tuổi đi học (Expected Years of Schooling - EYS).
* Mức sống: Đo bằng Tổng thu nhập quốc dân bình quân đầu người (GNI per capita) tính theo Sức mua tương đương (PPP \$).

### Phương pháp tính HDI
* Giai đoạn 1990 – 2010: Tính theo trung bình cộng giản đơn 3 chỉ số thành phần [6]:
  `HDI = \fracI_sức khỏe + I_giáo dục + I_thu nhập3`
* Từ năm 2010 đến nay: Tính theo trung bình nhân (trung bình hình học) 3 chỉ số thành phần đã chuẩn hóa [6, 7]:
  `HDI = \sqrtLEI · EI · II`

### Quy trình chuẩn hóa các chỉ số thành phần
Công thức chuẩn hóa tổng quát [7]:
`I_i = \fracX_i^thực - X_i^\minX_i^\max - X_i^\min`

Bảng giá trị biên cố định do UNDP quy định [7]:
* Sức khỏe (LEI): `LEI = (LE - 20)/(85 - 20)` (với min = 20 năm, max = 85 năm).
* Giáo dục (EI): Là trung bình cộng của 2 chỉ số thành phần [7]:
  * `MYSI = MYS/15` (min = 0, max = 15 năm).
  * `EYSI = EYS/18` (min = 0, max = 18 năm).
  * `EI = (MYSI + EYSI)/2`.
* Thu nhập (II): Dùng hàm logarithm tự nhiên để phản ánh quy luật giảm dần của lợi ích thu nhập [7]:
  `II = (\ln(GNI/ng) - \ln(100))/(\ln(75.000) - \ln(100))` (với min = 100 USD PPP, max = 75.000 USD PPP).

### Phân nhóm xếp hạng HDI
HDI nhận giá trị từ 0 đến 1 (0 = không có phát triển nhân văn; 1 = phát triển lý tưởng) và chia làm 4 nhóm [7]:
* Nhóm 1 (Mức rất cao): `HDI ≥ 0,800`.
* Nhóm 2 (Mức cao): `0,700 ≤ HDI < 0,800`.
* Nhóm 3 (Mức trung bình): `0,550 ≤ HDI < 0,700`.
* Nhóm 4 (Mức thấp): `HDI < 0,550`.

*Thực trạng Việt Nam*: Năm 2022, HDI của Việt Nam đạt 0,726 (xếp hạng 107/193 quốc gia), tiếp tục nằm trong nhóm các quốc gia có HDI Cao.

---

## Chỉ Số Phát Triển Con Người Hiệu Chỉnh Bất Bình Đẳng (IHDI)

* Ý nghĩa: HDI đo lường thành tựu trung bình, còn IHDI đo lường mức độ phát triển con người thực tế khi có tính đến sự bất bình đẳng trong phân phối 3 thành phần (sức khỏe, giáo dục, thu nhập).
* Phương pháp: Áp dụng phương pháp hàm phúc lợi xã hội của Atkinson (1970) sử dụng dữ liệu khảo sát hộ gia đình và bảng sống.
* 3 bước tính IHDI [13]:
  1. Ước tính mức độ bất bình đẳng trong từng khía cạnh.
  2. Điều chỉnh các chỉ số đã chuẩn hóa theo hệ số bất bình đẳng.
  3. Tính trung bình nhân 3 chỉ số đã hiệu chỉnh để ra IHDI.
* Nguyên lý: Do luôn tồn tại bất bình đẳng nên `IHDI ≤ HDI`. Khoảng chênh lệch giữa HDI và IHDI đại diện cho mức tổn thất phát triển con người do bất bình đẳng (ở quy mô toàn cầu, mức tổn thất này trung bình khoảng 20%).

---

## Chỉ Số Phát Triển Giới (GDI)

* Khái niệm & Công thức: GDI đo lường sự chênh lệch về phát triển con người giữa hai giới Nam và Nữ [12]:
  `GDI = HDI_f/HDI_m`
  *(Trong đó `HDI_f` là HDI của Nữ, `HDI_m` là HDI của Nam)*.
* Khung chuẩn hóa riêng theo giới:
  * Tuổi thọ trung bình: Nữ [22,5 – 87,5 năm]; Nam [17,5 – 82,5 năm] (do sinh học nữ có tuổi thọ cao hơn nam).
  * Giáo dục & Thu nhập: Áp dụng cùng ngưỡng tối thiểu/tối đa với HDI.
* Phân nhóm mức độ bình đẳng giới dựa trên độ lệch tuyệt đối `100 · |GDI - 1|` [12]:
  * Nhóm 1 (Độ lệch < 2,5%): Mức độ bình đẳng giới Cao.
  * Nhóm 2 (2,5% – 5%): Trung bình cao.
  * Nhóm 3 (5% – 7,5%): Trung bình.
  * Nhóm 4 (7,5% – 10%): Trung bình thấp.
  * Nhóm 5 (> 10%): Thấp.

*Thực trạng Việt Nam*: Năm 2018, GDI của Việt Nam đạt 1,003 (với `HDI_f = 0,693` và `HDI_m = 0,692`), xếp vào Nhóm 1 (bình đẳng giới cao).

---

## Chỉ Số Nghèo Đa Chiều (MPI)

Khái niệm: Thay vì chỉ dùng nghèo thu nhập, MPI đo lường các thiếu hụt chồng chéo mà cá nhân/hộ gia đình phải đối mặt ở 3 chiều cạnh [12, 16]:
  1. Sức khỏe: Dinh dưỡng, Tử vong trẻ em.
  2. Giáo dục: Số năm đi học, Tỷ lệ trẻ em đi học.
  3. Tiêu chuẩn sống: Nhiên liệu nấu ăn, Hố xí/Vệ sinh, Nước sạch, Điện, Nhà ở, Tài sản.
* Chuyển đổi chính sách tại Việt Nam: Từ sau năm 2015, Việt Nam đã chính thức chuyển sang áp dụng đo lường chuẩn nghèo đa chiều. Tỷ lệ hộ nghèo theo cách tiếp cận này đã giảm mạnh từ hơn 58% (năm 1993) xuống dưới 3% vào năm 2020