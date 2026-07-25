# PHƯƠNG PHÁP LUẬN

# XÁC ĐỊNH CÁC TÍN HIỆU KỸ THUẬT TRÊN FiinTrade®

A person sitting in a chair facing a massive curved wall of small video screens reflecting on a dark, glossy floor.

FiinTrade logo

FiinGroup ENLIGHTEN THE MARKET logo

# Nội dung

**FiinGroup và FiinTrade®** 3

**Phương pháp luận** 4

I Tổng quan phương pháp xác định tín hiệu kỹ thuật 4
1 Bộ chỉ tiêu xác định xu hướng \<trend\> 4
2 Bộ chỉ tiêu xác định kỹ thuật \<indicator signal\> 5
3 Bộ chỉ tiêu xác định tín hiệu nhiễu \<deceptive order\> 8
4 Bộ chỉ tiêu phân tích giá, khối lượng 18
5 Bộ chỉ tiêu phân tích chiến lược TA \<TA strategy\> 21

II Ứng dụng của việc xác định tín hiệu kỹ thuật trên FiinTrade 29

<page_number>2</page_number>

FiinTrade logo FiinGroup ENLIGHTEN THE MARKET logo

# FiinGroup và FiinTrade®

Được thành lập vào năm 2008, Công ty Cổ phần FiinGroup (tiền thân là StoxPlus) tự hào là công ty hàng đầu Việt Nam trong lĩnh vực cung cấp các sản phẩm thông tin đa chiều, chuyên sâu và đáng tin cậy về tình hình tài chính doanh nghiệp, dữ liệu thị trường tức thời, báo cáo phân tích chứng khoán hữu ích, công cụ quản lý đầu tư tối ưu, cùng các sự kiện và tin tức vô cùng quan trọng cho nhà đầu tư cá nhân và các chuyên gia tại Việt Nam.

## Ban lãnh đạo của FiinGroup

Ban lãnh đạo của FiinGroup là các chuyên gia CFA Charteredholder, ACCA, MBA và có bề dầy trên 38 năm kinh nghiệm sâu trong lĩnh vực Đầu tư, Ngân hàng, Phân tích Tài chính và Công nghệ từ Trung tâm Tài chính Luân Đôn, Anh Quốc, Thụy Sỹ, Úc và Đông Nam Á.

## Phần mềm FiinTrade®

Ra mắt vào ngày 10/10/2019, FiinTrade là sản phẩm công nghệ tài chính được nghiên cứu và phát triển bởi FiinGroup nhằm phục vụ các chuyên viên tư vấn, môi giới, nhà giao dịch (traders) và các nhà đầu tư năng động tại thị trường chứng khoán Việt Nam.

FiinTrade được thiết kế là nền tảng thông tin toàn diện, bao gồm dữ liệu giao dịch, dữ liệu cơ bản, các công cụ phân tích dữ liệu và hiển thị đa chiều cũng với các phân tích với hệ thống đánh giá sức khỏe và xếp hạng doanh nghiệp trong từng nhóm ngành. Nền tảng này cũng bước đầu cung cấp các phân tích cơ bản đến chuyên sâu dựa trên số liệu về thị trường và cổ phiếu, một cách độc lập bởi đội ngũ chuyên gia phân tích của FiinGroup.

## Mục đích của tài liệu này

Trong tài liệu này, chúng tôi hân hạnh trình bày với quý khách hàng và các bạn về phương pháp luận xây dựng, đánh giá các chỉ tiêu kỹ thuật đối với các mã chứng khoán niêm yết trên sàn chứng khoán.

Mong muốn của chúng tôi là hỗ trợ các Nhà đầu tư đánh giá nhanh các chỉ tiêu tài chính cơ bản, qua đó tiết kiệm thời gian trong quá trình thu thập dữ liệu và phân tích.

Chúng tôi tin tưởng tài liệu này cũng làm tăng tính minh bạch khi quý vị và các bạn sử dụng thông tin dữ liệu do FiinGroup cung cấp.

<page_number>3</page_number>

FiinTrade logo

FiinGroup logo

# Phương pháp luận

## I Tổng quan phương pháp xác định tín hiệu kỹ thuật

Phân tích **Tín hiệu kỹ thuật** trong đầu tư chứng khoán là phương pháp phân tích, dự báo xu thế giá chứng khoán thông qua việc nghiên cứu các dữ liệu thị trường quá khứ, chủ yếu là giá cả và khối lượng. Đồng thời việc phân tích giá và khối lượng giao dịch trên thị trường chứng khoán Việt Nam giúp nhà đầu tư có thể nhận biết các giao dich bất thường cũng như xác định xu thế ngắn hạn của thị trường chứng khoán.

Nhờ nguồn dữ liệu đầy đủ và chính xác, FiinGroup đã xây dựng các phương pháp xác định tính hiệu kỹ thuật một cách tự động trên hệ thống FiinTrade. Các nhóm chức năng phân tích kỹ thuật trên FiinTrade bao gồm:

**Nhóm 1**: Phân tích xác định xu hướng \<trend\>
**Nhóm 2**: Phân tích xác định kỹ thuật \<Indicator signal\>
**Nhóm 3**: Phân tích xác định tín hiệu nhiễu \<deceptive order\>.
**Nhóm 4**: Phân tích giá và khối lượng \<price-volume analysis\>
**Nhóm 5**: Chiến lược phân tích kỹ thuật \<TA strategy\>.

## 1 Bộ chỉ tiêu xác định xu hướng \<trend\>

### a) Lựa chọn chỉ báo

| STT | Tên tiêu chí | Mô tả | Ý nghĩa và ứng dụng |
| --- | --- | --- | --- |
| 1 | MA(5) | Được tính bằng trung bình cộng của 4 giá đóng cửa tại các kỳ thời gian (1 ngày/1 tuần/1 tháng/ 1 năm) và giá hiện tại | Moving Average (5) chỉ xu hướng giá của cổ phiếu trong ngắn hạn. Dựa vào đường MA cho phép nhà đầu tu dự báo xu hướng giá trong trung và ngắn hạn, từ đó có thể đưa gia quyết định đầu tư. |

### b) Phương pháp xác định xu hướng

| STT | Khung thời gian | Tăng (Bullish) | Trung tính (Neutral) | Giảm (Bearish) |
| --- | --- | --- | --- | --- |
| 1. | 1 ngày | Giá khớp vượt đường MA(5) | Giá khớp bằng đường MA(5) | Giá khớp thấp hơn đường MA(5) |

<page_number>4</page_number>

FiinTrade logo FiinGroup logo

| 2. | 1 tuần | Giá khớp vượt đường MA(5) | Giá khớp bằng đường MA(5) | Giá khớp thấp hơn đường MA(5) |
| --- | --- | --- | --- | --- |
| 3. | 1 tháng | Giá khớp vượt đường MA(5) | Giá khớp bằng đường MA(5) | Giá khớp thấp hơn đường MA(5) |
| 4. | 1 năm | Giá khớp vượt đường MA(5) | Giá khớp bằng đường MA(5) | Giá khớp thấp hơn đường MA(5) |

### c) Hiển thị trên Fiintrade

Kết quả xác định “Trend” được thể hiện tại chức năng **Danh mục** tab **Tổng quan**. Người dùng có thể lựa chọn chỉ tiêu “Trend” theo ngày/ tuần/ tháng/ năm để theo dõi diễn biến xu hướng của cổ phiếu.

Screenshot of FiinTrade interface showing a stock watchlist with Trend indicators

# 2 Bộ chỉ tiêu xác định kỹ thuật \<indicator signal\>

## a) Lựa chọn chỉ báo

| STT | Tên tiêu chí | Mô tả | Ý nghĩa và ứng dụng |
| --- | --- | --- | --- |
| 1 | MA(5) | Được tính bằng trung bình cộng của 4 giá đóng cửa tại các kỳ thời gian (mỗi 15 phút/1 giờ/1 ngày/1 tuần) và giá hiện tại | Moving Average (5) chỉ xu hướng giá của cổ phiếu trong ngắn hạn. Dựa vào đường MA cho phép nhà đầu tư dự báo xu hướng giá trong |

<page_number>5</page_number>

FiinTrade logo

FiinGroup logo

|  |  |  | trung và ngắn hạn, từ đó có thể đưa gia quyết định đầu tư. |
| --- | --- | --- | --- |
| 2 | RSI(14) | RSI = 100-[100/1+RS)] Trong đó: - RS = trung bình tăng/trung bình giảm. - RSI: được tính dựa vào giá đóng cửa 14 kỳ (mỗi 15 phút/1 giờ/1 ngày/1 tuần) gần nhất, nên cũng gọi là đường RSI 14 | Ngoài việc xác định tín hiệu tăng/giảm, ý nghĩa đường RSI còn thể hiện xác ở 2 tiêu chí: - Xác định xu hướng giá tương lai. - Xác định tính phân kỳ, hội tụ của giá |
| 3 | CMF(20) | $$ CMF = \frac{\sum_{t=1}^{20}(CLV_t \times volume_t)}{\sum_{t=1}^{20} volume_t} $$ Trong đó: $$ CLV = \frac{(close - low) - (high - close)}{high - low} $$ Close: giá đóng trong kỳ thời gian Low: giá thấp nhất trong kỳ thời gian High: giá cao nhất trong kỳ thời gian | Chỉ báo cho phép xác định dấu hiệu áp lực mua trong giai đoạn tích lũy hoặc áp lực bán trong giai đoạn phân phối |
| 4 | ROC(9) | ROC = [(giá hiện tại – giá tại 9 kỳ trước) / (giá tại 9 kỳ trước)] X 100 | Nhà phân tích kỹ thuật có thể sử dụng chỉ báo Mức độ biến động (ROC) để xác định xu hướng và xác định các điều kiện quá mua và quá bán của cổ phiếu. |

## b) *Phương pháp đánh giá*

Các chuyên gia của FiinGroup đánh giá các tín hiệu kỹ thuật theo 5 cấp độ bao gồm: 1. Strong Bullish, 2. Bullish, 3. Neutral, 4. Bearish, 5. Strong Bearish. Cách xác định tín hiệu kỹ thuật dựa theo nhóm chỉ báo.

| Tên chỉ báo | Tăng (Bullish) | Trung tính (Neutral) | Giảm (Bearish) |
| --- | --- | --- | --- |
| MA(5) | Giá hiện tại > MA(5) | Giá hiện tại = MA(5) | Giá hiện tại < MA(5) |

<page_number>6</page_number>

FiinTrade logo

FiinGroup logo

| Moving Averages | Xác định theo MA(5) | Xác định theo MA(5) | Xác định theo MA(5) |
| --- | --- | --- | --- |

| Tên chỉ báo | Tăng (Bullish) | Trung tính (Neutral) | Giảm (Bearish) |
| --- | --- | --- | --- |
| RSI(14) | RSI(14) vượt lên đường 30 | Trường hợp còn lại | RSI(14) cắt xuống 70 |
| CMF(20) | CMF(20) > 0 | CMF(20) = 0 | CMF(20) < 0 |
| ROC(9) | ROC(9) vượt lên đường 30 | Trường hợp còn lại | ROC(9) cắt xuống đường 70 |
| Indicators | Trong 3 chỉ báo bên trên nếu số chỉ báo Tăng (Bullish) nhiều hơn số chỉ báo Giảm (Bearish) | Trường hợp còn lại | Trong 3 chỉ báo bên trên nếu số chỉ báo Tăng (Bullish) ít hơn số chỉ báo Giảm (Bearish) |

Việc xác định tín hiệu của nhóm **Tổng hợp (Summary)** dựa vào kết quả cuối cùng của 2 nhóm **TB Động (Moving Averages (A))** và **Chỉ tiêu (Indicators (B))** như sau:

| B \ A | Tăng (Bullish) | Trung tính (Neutral) | Giảm (Bearish) |
| --- | --- | --- | --- |
| Tăng (Bullish) | Strong Bullish | Bullish | Neutral |
| Trung tính (Neutral) | Bullish | Neutral | Bearish |
| Giảm (Bearish) | Neutral | Bearish | Strong Bearish |

### c) Hiển thị kết quả trên FiinTrade

Kết quả tính được thể hiện tại chức năng **Tín hiệu kỹ thuật** tab **chỉ tiêu** trên FiinTrade. Mỗi cổ phiếu được xác định tín hiệu kỹ thuât theo các chu kỳ thời gian (15 phút/1 giờ/1 ngày/1 tuần). Tín hiệu tổng hợp được thể hiện bởi các màu sắc khác nhau theo ý nghĩa của dấu hiệu đó.

<page_number>7</page_number>

FiinTrade logo FiinGroup logo

| MÃ | LOẠI HÌNH | 15 PHÚT | 1 GIỜ | 1 NGÀY | 1 TUẦN |
| --- | --- | --- | --- | --- | --- |
| BID 41.30 0.00 VND - 0.00% | T.B Động | Tăng | Giảm | Giảm | Tăng |
| Chỉ tiêu | Tăng | Tăng | Tăng | Tăng |  |
| Tổng hợp | Tăng mạnh | Trung tính | Trung tính | Tăng mạnh |  |
| BVH 73.60 0.00 VND - 0.00% | T.B Động | Giảm | Giảm | Giảm | Tăng |
| Chỉ tiêu | Tăng | Giảm | Giảm | Giảm |  |
| Tổng hợp | Trung tính | Giảm mạnh | Giảm mạnh | Trung tính |  |
| CTD 73.50 -1.00 VND -1.34% | T.B Động | Giảm | Giảm | Giảm | Giảm |
| Chỉ tiêu | Giảm | Giảm | Giảm | Tăng |  |
| Tổng hợp | Giảm mạnh | Giảm mạnh | Giảm mạnh | Trung tính |  |
| CTG 21.95 -0.35 VND -1.57% | T.B Động | Giảm | Giảm | Giảm | Tăng |
| Chỉ tiêu | Giảm | Giảm | Giảm | Giảm |  |
| Tổng hợp | Giảm mạnh | Giảm mạnh | Giảm mạnh | Trung tính |  |
| DPM 13.70 -0.05 VND -0.36% | T.B Động | Giảm | Giảm | Giảm | Giảm |
| Chỉ tiêu | Giảm | Giảm | Giảm | Tăng |  |
| Tổng hợp | Giảm mạnh | Giảm mạnh | Giảm mạnh | Trung tính |  |
| EIB 18.40 0.00 VND - 0.00% | T.B Động | Tăng | Tăng | Tăng | Tăng |
| Chỉ tiêu | Tăng | Tăng | Tăng | Tăng |  |
| Tổng hợp | Tăng mạnh | Tăng mạnh | Tăng mạnh | Tăng mạnh |  |

# 3 Bộ chỉ tiêu xác định tín hiệu nhiễu \<deceptive order>

Dựa vào dữ liệu giao dịch của các cổ phiếu, Fiingroup đã xây dựng hệ thống tự động thống kê 5 tín hiệu nhiễu thường gặp, bao gồm:

| Tín hiệu | Ý Nghĩa |
| --- | --- |
| Mua trần – bán sàn | Xác định các cổ phiếu có dư mua trần và dư bán sàn với khối lượng lớn |
| Hủy lệnh | Xác định các cổ phiếu có số lượng lệnh bị hủy nhiều trong ngày |
| Đè giá -đẩy giá | Xác định các cổ phiếu đang có xu hướng bị đè giá hoặc đẩy giá |
| Mua – bán chủ động | Xác định các các cổ phiếu có sự chênh lệch lớn về cung cầu giao dịch |
| Chốt phiên | Xác định các cổ phiếu có khối lượng giao dịch lớn vào cuối phiên |

## 3.1 Mua trần bán sàn

### 3.1.1 Định nghĩa

Mua trần là hành động nhà đầu thực hiện giao dịch tại mức giá trần. Trong khi đó, Bán sàn được định nghĩa là hành động nhà đầu tư thực hiện giao dịch tại mức giá sàn.

<page_number>8</page_number>

FiinTrade logo

FiinGroup logo

Tín hiệu **Mua trần (Bán sàn)** là tín hiệu kỹ thuật xảy ra khi mã chứng khoán có khối lượng dư mua trần (hoặc dư bán sàn) lớn đột biến so với khối lượng giao dịch của các phiên trước. Hệ thống FiinTrade hỗ trợ nhà đầu tư thống kê các giao trên toàn thị trường, xác định các cổ phiếu có mua trần (bán sàn) đột biến trong phiên giao dịch.

### 3.1.2 Các chỉ tiêu xác định tín hiệu

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | Giá mua 1 | Là giá mua tốt nhất |
| 2. | Khối lượng đặt mua 1 | Là khối lượng đặt mua tại giá mua tốt nhất |
| 3. | Giá bán 1 | Là giá bán tốt nhất |
| 4. | Khối lượng đặt bán 1 | Là khối lượng chào bán tại giá bán tốt nhất |
| 5. | Giá trần | Là mức giá cao nhất mà nhà đầu tư có thể giao dịch trong phiên giao dịch hiện tại |
| 6. | Giá sàn | Là mức giá thấp nhất mà nhà đầu tư có thể giao dịch trong phiên giao diện hiện tại |
| 7. | K.L TB 10 phiên | Là trung bình khối lượng giao dịch của 10 phiên liên tiếp (không bao gồm phiên giao dịch hiện tại) |

### 3.1.3 Phương pháp xác định tín hiệu

| STT | Tên tín hiệu | Mô tả |
| --- | --- | --- |
| 1. | Mua trần | Bước 1: Xác định khối lượng dư mua trần (K.L dư mua trần) Nếu Giá mua 1 = Giá trần thì khối lượng đặt mua 1 được gọi là K.L dư mua trần. Bước 2: Tính tỷ lệ dư mua trần Tỷ lệ dư mua trần= K.L dư mua trần/ K.L T.B 10 phiên Bước 3: Xác định tín hiệu VD: Nếu tỷ lệ dư mua trần > 0.5 và K.L T.B 10 phiên > 10,000 thì tín hiệu “Mua trần” được xác định. Tỷ lệ dư mua trần và K.L T.B 10 phiên có thể tùy chỉnh dựa vào nhu cầu người dùng. |
| 2. | Bán sàn | Bước 1: Xác định khối lượng dư bán sàn (K.L dư bán sàn) Nếu Giá bán 1 = Giá sàn thì khối lượng đặt bán 1 được gọi là K.L dư bán sàn. |

<page_number>9</page_number>

FiinTrade logo FiinGroup logo

**Bước 2**: Tính tỷ lệ dư bán sàn

Tỷ lệ dư bán sàn = K.L dư bán sàn/ K.L T.B 10 phiên

<u>**Bước 3**</u>: Xác định tín hiệu

VD: Nếu tỷ lệ dư bán sàn > 0.5 và K.L T.B 10 phiên > 10,000 thì tín hiệu "Bán sàn" được xác định.

Tỷ lệ dư bán sàn và K.L T.B 10 phiên có thể tùy chỉnh dựa vào nhu cầu người dùng.

### 3.1.4 Hiển thị trên Fiintrade

Việc xác định mua trần-bán sàn được thể hiện tại chức năng **"Tín hiệu kỹ thuật"** tab **"Tín hiệu nhiễu"** mục **"Mua trần, bán sàn"**. Fiintrade cho phép tùy chỉnh **K.L TB 10 phiên và tỷ lệ mua trần và tỷ lệ bán sàn** để tìm danh sách những cổ phiếu có tín hiệu "Mùa trần/ Bán sàn" phù hợp.

Screenshot of FiinTrade interface showing technical signals for stocks like QCG and AMD

### 3.2 Huỷ lệnh

#### 3.2.1 Định nghĩa

**Hủy lệnh** là việc nhà đầu tư thực hiện hủy các lệnh đã đặt (mua hoặc bán) trên thị trường.

Việc xác định số lượng và khối lượng của lệnh hủy giúp nhà đâu tư nhận biết được phần nào cung cầu giao dịch của cổ phiếu và đặc biệt là có thể dự đoán khả năng làm giá của các cổ phiếu.

Hủy lệnh bao gồm **hủy lệnh mua** và **hủy lệnh bán**. Hệ thống FiinTrade hỗ trợ nhà đầu tư thống kê các giao trên toàn thị trường, xác định các cổ phiếu có hủy lệnh (mua và bán) đột biến trong phiên giao dịch.

<page_number>10</page_number>

FiinTrade logo

FiinGroup ENLIGHTEN THE MARKET logo

## 3.2.2 Các chỉ tiêu xác định tín hiệu

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | Giá mua 1 | Là giá mua tốt nhất |
| 2. | Khối lượng đặt mua 1 | Là khối lượng đặt mua tại giá mua tốt nhất |
| 3. | Giá mua 2 | Là giá mua tốt thứ hai |
| 4. | Khối lượng đặt mua 2 | Là khối lượng đặt mua tại giá mua hai |
| 5. | Giá mua 3 | Là giá mua tốt thứ ba |
| 6. | Khối lượng đặt mua 3 | Là khối lượng đặt mua tại giá mua ba |
| 7. | Giá bán 1 | Là giá bán tốt nhất |
| 8. | Khối lượng đặt bán 1 | Là khối lượng chào bán tại giá bán tốt nhất |
| 9. | Giá bán 2 | Là giá bán tốt thứ hai |
| 10. | Khối lượng đặt bán 2 | Là khối lượng chào bán tại giá bán hai |
| 11. | Giá bán 3 | Là giá bán tốt thứ ba |
| 12. | Khối lượng đặt bán 3 | Là khối lượng chào bán tại giá bán ba |
| 13. | Tổng khối lượng khớp lệnh | Là khối lượng khớp tích lũy từ đầu phiên giao dịch tới thời điểm hiện tại. |
| 14. | K.L TB 10 phiên | Là trung bình khối lượng giao dịch của 10 phiên liên tiếp (không bao gồm phiên giao dịch hiện tại) |

## 3.2.3 Phương pháp xác định tín hiệu

| STT | Tên tín hiệu | Mô tả |
| --- | --- | --- |
| 1. | Hủy lệnh Mua | Bước 1: Xác định trạng thái hủy lệnh mua Tại thời điểm khối lượng đặt mua giảm mà tổng khối lượng khớp lệnh không thay đổi thì một lệnh hủy mua vừa được thực hiện. Khi đó: K.L hủy lệnh mua tại t = K.L đặt mua tại (t-1) – K.L đặt mua tại t. |

<page_number>11</page_number>

FiinTrade logo FiinGroup logo

|  | Tổng K.L hủy lệnh mua được xác định bằng tổng K.L hủy lệnh mua tích lũy từ đầu phiên. Bước 2: Xác định tín hiệu “Hủy lệnh Mua” VD: Nếu K.L TB 10 phiên > 10,000 và Tổng K.L hủy lệnh mua > 0 thì tín hiệu “Hủy lệnh Mua” được xác định. K.L TB 10 phiên có thể tùy chỉnh dựa trên như cầu người dùng. |
| --- | --- |
| 2. Hủy lệnh Bán | Bước 1: Xác định trạng thái hủy lệnh bán Tại thời điểm khối lượng đặt bán giảm mà tổng khối lượng khớp lệnh không thay đổi thì một lệnh hủy bán vừa được thực hiện. Khi đó: K.L hủy lệnh bán tại t = K.L đặt bán tại (t-1) – K.L đặt bán tại t. Tổng K.L hủy lệnh bán được xác định bằng tổng K.L hủy lệnh bán tích lũy từ đầu phiên. Bước 2: Xác định tín hiệu “Hủy lệnh Bán” VD: Nếu K.L TB 10 phiên > 10,000 và Tổng K.L hủy lệnh bán > 0 thì tín hiệu “Hủy lệnh Bán” được xác định. K.L TB 10 phiên có thể tùy chỉnh dựa trên như cầu người dùng. |

## 3.2.4 Hiển thị trên Fiintrade

Việc xác định hủy lệnh được thể hiện tại chức năng “Tín hiệu kỹ thuật” tab “Tín hiệu nhiễu” mục “Hủy lệnh”. Fiintrade cho phép tùy chỉnh K.L TB 10 phiên để tìm danh sách những cổ phiếu có tín hiệu “Mùa trần/ Bán sàn” phù hợp.

FiinTrade interface screenshot

| MÃ | GIÁ | KHỐI LƯỢNG | SỐ LỆNH HỦY | K.L LỆNH HỦY | SỐ LỆNH HỦY (MUA) | K.L LỆNH HỦY (MUA) | SỐ LỆNH HỦY (BÁN) | K.L LỆNH HỦY (BÁN) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| E1VFVN30 | 13.00 | 3,203.82 | 85 | 6,381.83 | 44 | 3,397.08 | 41 | 2,984.75 |
| HPG | 21.70 | 7,501.04 | 156 | 813.87 | 47 | 223.88 | 109 | 589.99 |
| HAI | 3.32 | 15,844.68 | 19 | 763.78 | 3 | 26.38 | 16 | 737.40 |
| ART | 2.60 | 5,071.29 | 2 | 675.40 | 1 | 60.00 | 1 | 615.40 |
| CTG | 24.50 | 10,775.78 | 116 | 589.78 | 48 | 408.20 | 68 | 181.58 |
| PVD | 10.85 | 7,456.74 | 46 | 439.73 | 12 | 87.70 | 34 | 352.03 |
| HKB | 0.70 | 288.72 | 1 | 420.00 | 0 | 0.00 | 1 | 420.00 |
| SSI | 15.50 | 3,294.86 | 95 | 403.48 | 24 | 224.00 | 71 | 179.48 |
| HDB | 25.85 | 2,443.62 | 196 | 379.13 | 161 | 344.25 | 35 | 34.88 |
| VRE | 26.00 | 2,592.86 | 129 | 294.78 | 67 | 157.48 | 62 | 137.30 |
| VNM | 101.00 | 1,700.72 | 203 | 288.22 | 104 | 174.72 | 99 | 113.50 |

Giá: x1000 (VND). Khối lượng: x1000 (CP). Giá trị: x1000000 (VND)

<page_number>12</page_number>

FiinTrade logo

FiinGroup ENLIGHTEN THE MARKET logo

# 3.3 Đè giá – Đẩy giá

## 3.3.1 Định nghĩa

Đè giá và đẩy giá là hành động của nhà đầu tư hoặc một nhóm nhà đầu tư thực hiện nhằm mục đích kiểm soát giá cổ phiếu với các mục đích khác nhau.

**Đè giá (hay đè bán)** xảy ra khi khối lượng đặt bán tại một bước giá lớn đột biến so với khối lượng giao dịch các phiên trước.**Đẩy giá (hay đè mua)** xảy ra khi khối lượng đặt mua tại một bước giá lớn đột biến so với khối lượng giao dịch các phiên trước.

Dựa và việc thống kê giao dịch real – time, hệ thống FiinTrade xác định và thống kê danh sách các cổ phiếu có dấu hiệu đè giá hoặc đẩy giá. Từ đó giúp nhà đầu tư có thêm góc nhìn về hoạt động giao dịch của cổ phiếu

### 3.3.2 Các chỉ tiêu xác định tín hiệu

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | Khối lượng đặt mua 1 | Là khối lượng đặt mua tại giá mua tốt nhất |
| 2. | Khối lượng đặt mua 2 | Là khối lượng đặt mua tại giá mua hai |
| 3. | Khối lượng đặt mua 3 | Là khối lượng đặt mua tại giá mua ba |
| 4. | Khối lượng đặt bán 1 | Là khối lượng chào bán tại giá bán tốt nhất |
| 5. | Khối lượng đặt bán 2 | Là khối lượng chào bán tại giá bán hai |
| 6. | Khối lượng đặt bán 3 | Là khối lượng chào bán tại giá bán ba |
| 7. | K.L TB 10 phiên | Là trung bình khối lượng giao dịch của 10 phiên liên tiếp (không bao gồm phiên giao dịch hiện tại) |

### 3.3.3 Phương pháp xác định tín hiệu

| STT | Tên tín hiệu | Mô tả |
| --- | --- | --- |
| 1. | Đè giá | Bước 1: Xác định trạng thái đè giá Tại một thời điểm, khối lượng đặt bán tại các bước giá lớn đột biến so với K.L TB 10 phiên thì xảy ra trạng thái đè giá. Khi đó, khối lượng đặt bán tại các bước giá được gọi là K.L đè giá Bước 2: Xác định tỷ lệ đè giá Tỷ lệ đè giá = K.L đè giá/ K.L TB 10 phiên. Bước 3: Xác định tín hiệu Đè giá |

<page_number>13</page_number>

FiinTrade logo

FiinGroup logo

|  |  | Nếu tỷ lệ đè giá > 10% và K.L TB 10 phiên >10,000 thì tín hiệu Đè giá được xác định. Tỷ lệ đè giá và K.L TB 10 phiên có thể điều chỉnh dựa trên nhu cầu của người dùng. |
| --- | --- | --- |
| 2. | Đẩy giá | Bước 1: Xác định trạng thái đẩy giá Tại một thời điểm, khối lượng đặt mua tại các bước giá lớn đột biến so với K.L TB 10 phiên thì xảy ra trạng thái đẩy giá. Khi đó, khối lượng đặt mua tại các bước giá được gọi là K.L đẩy giá. Bước 2: Xác định tỷ lệ đẩy giá Tỷ lệ đẩy giá = K.L đẩy giá/ K.L TB 10 phiên. Bước 3: Xác định tín hiệu Đẩy giá Nếu tỷ lệ đẩy giá > 10% và K.L TB 10 phiên >10,000 thì tín hiệu Đẩy giá được xác định. Tỷ lệ đẩy giá và K.L TB 10 phiên có thể điều chỉnh dựa trên nhu cầu của người dùng. |

### 3.3.4 *Hiển thị trên Fiintrade*

Việc xác định đè giá được thể hiện tại chức năng **“Tín hiệu kỹ thuật”** tab **“Tín hiệu nhiễu”** mục **“Đè giá”**. Fiintrade cho phép tùy chỉnh **K.L TB 10 phiên** và **tỷ lệ đè giá (hoặc tỷ lệ đẩy giá)** để tìm danh sách những cổ phiếu có tín hiệu “Đè giá” phù hợp.

| MÃ | GIÁ | K.L T.B 10D | K.L ĐÈ GIÁ (MUA) | MUA VÀO | THỨ HẠNG |
| --- | --- | --- | --- | --- | --- |
| HQC | 1.14 | 5,505.48 | 1,106.28 | 1.14 | 20/124 |
| PVD | 10.80 | 2,688.53 | 309.69 | 10.65 | 3/8 |
| ART | 2.50 | 2,511.31 | 871.60 | 2.40 | 20/39 |
| KLF | 1.50 | 1,469.06 | 756.80 | 1.50 | 28/60 |
| LPB | 7.60 | 4,060.52 | 653.80 | 7.40 | 14/18 |
| BSR | 7.20 | 2,781.41 | 290.80 | 7.10 | 2/3 |
| HUT | 1.90 | 1,134.33 | 440.60 | 1.90 | 13/374 |
| QCG | 6.82 | 754.24 | 473.45 | 6.82 | 15/124 |

Giá: x1000 (VND). Khối lượng: x1000 (CP). Giá trị: x1000000 (VND)

<page_number>14</page_number>

FiinTrade logo

FiinGroup ENLIGHTEN THE MARKET logo

# 3.4 Mua – bán chủ động

## 3.4.1 Định nghĩa

**Lệnh Buy Up (Mua chủ động)** là lệnh do nhà đầu tư thực hiện chủ động mua lên so với giá hiện tại của cổ phiếu. **Lệnh Sell Down (Bán chủ động)** là lệnh do nhà đầu tư thực hiện chủ động bán dưới giá hiện tại của cổ phiếu.

Thống kê khối lượng giao dich theo lệnh BU – SD giúp nhà đầu tư có thể sử dụng để đánh giá tương quan giữa cung và cầu trên giao dịch thực tế, nhận định tương đối về sự vận động của xu hướng dòng tiền. Kết hợp với diễn biến giá, chỉ số BU/SD có thể giúp nhà đầu tư nhận biết được động thái của các nhà đầu tư lớn.

Hệ thống FiinTrade thống kê giao dịch trên toàn thị trường và xác định danh sách các cổ phiếu có tỷ lệ BU/SD đột biến trong phiên

## 3.4.2 Các chỉ tiêu xác định tín hiệu

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | Giá khớp | Là giá khớp lệnh tại thời điểm hiện tại. |
| 2. | K.L khớp | Là khối lượng khớp lệnh tại thời điểm hiện tại. |
| 3. | Giá Mua 1 | Là giá đặt mua tốt nhất. |
| 4. | Giá Bán 1 | Là giá chào bán tốt nhất. |
| 5. | K.L TB 10 phiên | Là trung bình khối lượng giao dịch của 10 phiên liên tiếp (không bao gồm phiên giao dịch hiện tại) |

## 3.4.3 Phương pháp xác định tín hiệu

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | Mua chủ động | Bước 1: Xác định kiểu BU Tại thời điểm khớp lệnh thành công, nếu “Giá khớp > Giá Mua 1” hoặc “Giá khớp = Giá Bán 1” thì giao dịch đó là kiểu BU với khối lượng khớp lệnh đó được gọi là khối lượng khớp BU. Bước 2: Xác định Tổng K.L BU Tổng K.L BU được xác định bằng cách tính tổng khối lượng khớp BU tích lũy từ đầu phiên. Bước 3: Xác định kiểu SD Tại thời điểm khớp lệnh thành công, nếu “Giá khớp < Giá Bán 1” hoặc “Giá khớp = Giá Mua 1” thì giao dịch đó là kiểu SD với khối lượng khớp lệnh đó được gọi là khối lượng khớp SD. |

<page_number>15</page_number>

FiinTrade logo

FiinGroup logo

|  |  | Bước 4: Xác định Tổng Khối Lượng SD Tổng K.L SD được xác định bằng cách tính tổng khối lượng khớp SD tích lũy từ đầu phiên. |
| --- | --- | --- |
|  |  | Bước 5: Tính tỷ lệ BU/SD BU/SD = (Tổng K.L BU)/ (Tổng K.L SD). |
|  |  | Bước 6: Xác định tín hiệu Mua chủ động Nếu BU/SD > 0.3 và K.L T.B 10 phiên > 10.000 thì tín hiệu “Mua chủ động” được xác định. Tỷ lệ BU/SD, K.L T.B 10 phiên có thể hiệu chỉnh tùy vào mục đích người dùng. |
| 2. | Bán chủ động | Bước 1: Xác định kiểu BU Tại thời điểm khớp lệnh thành công, nếu “Giá khớp > Giá Mua 1” hoặc “Giá khớp = Giá Bán 1” thì giao dịch đó là kiểu BU với khối lượng khớp lệnh đó được gọi là khối lượng khớp BU. |
| Bước 2: Xác định Tổng K.L BU Tổng K.L BU được xác định bằng cách tính tổng khối lượng khớp BU tích lũy từ đầu phiên. |  |  |
| Bước 3: Xác định kiểu SD Tại thời điểm khớp lệnh thành công, nếu “Giá khớp < Giá Bán 1” hoặc “Giá khớp = Giá Mua 1” thì giao dịch đó là kiểu SD với khối lượng khớp lệnh đó được gọi là khối lượng khớp SD. |  |  |
| Bước 4: Xác định Tổng Khối Lượng SD Tổng K.L SD được xác định bằng cách tính tổng khối lượng khớp SD tích lũy từ đầu phiên. |  |  |
| Bước 5: Tính tỷ lệ BU/SD BU/SD = (Tổng K.L BU)/ (Tổng K.L SD). |  |  |
| Bước 6: Xác định tín hiệu Bán chủ động Nếu BU/SD < 0.3 và K.L T.B 10 phiên > 10.000 thì tín hiệu “Mua chủ động” được xác định. Tỷ lệ BU/SD, K.L T.B 10 phiên có thể hiệu chỉnh tùy vào mục đích người dùng. |  |  |

### 3.4.4 *Hiển thị trên FiinTrade:*

Việc xác định mua/bán chủ động được thể hiện tại chức năng **“Tín hiệu kỹ thuật”** tab **“Tín hiệu nhiều”** mục **“Mua/bán chủ động”**. Fiintrade cho phép tùy chỉnh **K.L TB 10 phiên** và **tỷ lệ BU/SD** để tìm danh sách những cổ phiếu có tín hiệu “Mua/bán chủ động” phù hợp.

<page_number>16</page_number>

FiinTrade and FiinGroup logos FiinGroup logo

Screenshot of FiinTrade interface showing stock market data

# 3.5 Chốt phiên

## 3.5.1 Định nghĩa

**Chốt phiên** là hoạt động được nhà đầu tư thực hiện giao dịch với khối lượng lớn cổ phiếu vào cuối phiên. Việc xác định giao dịch lớn vào cuối phiên giúp nhà đầu tư biết được các cổ phiếu có dấu hiệu ra tăng thanh khoản. Kết hợp với thông tin biến động giá sẽ là một trong những công cụ hỗ trợ nhà đầu tư trong việc dự đoán xu hướng giá cổ phiếu

Hệ thống FiinTrade thống kê giao dịch trên toàn thị trường và xác định danh sách các cổ phiếu có dấu hiệu giao dịch “ Chốt phiên” đột biến.

### 3.5.2 Các chỉ tiêu xác định tín hiệu

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | Khối lượng khớp | Là khối lượng khớp lệnh tại một thời điểm |
| 2. | Thời gian khớp | Là thời gian xảy ra giao dịch khớp lệnh. |

### 3.5.3 Phương pháp xác định tín hiệu

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | Chốt phiên | Bước 1: Xác định tổng K.L (trước 14h00) Tổng K.L (trước 14h00) = Tổng cộng khối lượng khớp của tất các các giao dịch từ thời điểm 9h00 đến 14h00 Bước 2: Xác định tổng K.L (sau 14h00) Tổng K.L (sau 14h00) = Tổng cộng khối lượng khớp của các giao dịch sau 14h00. |

<page_number>17</page_number>

FiinTrade logo FiinGroup ENLIGHTEN THE MARKET logo

**Bước 3**: Xác định tỷ lệ vượt

Tỷ lệ vượt = Tổng K.L (sau 14h00) / Tỷ lệ K.L (trước 14h00)

<u>**Bước 4**</u>: Xác định tín hiệu **Chốt phiên**

Nếu tỷ lệ vượt > 20% và K.L TB 10 phiên > 10,000 thì tín hiệu **Chốt phiên** được xác định.

Tỷ lệ vượt và K.L TB 10 phiên có thể được điều chỉnh để phù hợp với nhu cầu người dùng.

### 3.5.4 Hiển thị trên Fiintrade

Việc xác định chốt phiên được thể hiện tại chức năng **“Tín hiệu kỹ thuật”** tab **“Tín hiệu nhiễu”** mục **“Chốt phiên”**. Fiintrade cho phép tùy chỉnh **K.L TB 10 phiên** và **tỷ lệ vượt** để tìm danh sách những cổ phiếu có tín hiệu “Chốt phiên” phù hợp.

Screenshot of FiinTrade technical signal interface

# 4 Bộ chỉ tiêu phân tích giá, khối lượng

## 4.1 Định nghĩa

Dựa trên thống kê dữ liệu giao dịch real time và lịch sử về giá khớp, tổng khối lượng giao dịch cuối mỗi ngày và tổng khối lượng ước lượng, FiinGroup đã xây dựng các chỉ tiêu để xác định các tín hiệu kỹ thuật về phân tích giá – khối lượng, bao gồm:

- Khối lượng tăng và giá tăng,

- Khối lượng tăng và giá giảm,

- Giá tăng liên tục trong nhiều phiên,

- Giá giảm liên tục trong nhiều phiên,

<page_number>18</page_number>

FiinTrade logo

FiinGroup ENLIGHTEN THE MARKET logo

- Khối lượng tăng liên tục nhiều phiên

Trong đó, tổng khối lượng ước lượng (T.K.L ước lượng) là tổng khối lượng khớp lệnh dự báo trong phiên giao dịch hiện tại.

## 4.2 Các yếu tố đầu vào cho phân tích giá – khối lượng

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | Giá khớp | Là giá giao dịch khớp lệnh tại thời điểm hiện tại |
| 2. | Tổng khối lượng khớp | Là tổng khối lượng khớp lệnh tại thời điểm hiện tại |
| 3. | Giá EOD | Là giá đóng cửa của mỗi ngày giao dịch (không bao gồm phiên giao dịch hiện tại) |
| 4. | Tổng khối lượng khớp EOD | Là tổng khối lượng khớp lệnh của mỗi ngày giao dịch (không bao gồm phiên giao dịch hiện tại) |

## 4.3 Phương pháp phân tích giá, khối lượng

| STT | Tên tín hiệu | Mô tả |
| --- | --- | --- |
| 1. | Khối lượng tăng và giá tăng | Bước 1: Xác định Tổng khối lượng ước lượng T.K.L ước lượng = Tổng khối lượng khớp * (Tổng thời gian giao dịch)/ (Thời gian đã giao dịch) Trong đó: Tổng thời gian khớp = 4,25 đối với sàn HOSE và 4,5 đối với sàn HNX và UPCOM. Thời gian đã giao dịch là khoảng thời gian tính từ đầu phiên giao dịch đến thời điểm hiện tại. Bước 2: Xác định số phiên khối lượng tăng Đếm số phiên khối lượng tăng liên tục dựa trên Tổng khối lượng EOD của những ngày trước và T.K.L ước lượng của ngày hiện tại. Bước 3: Xác định tín hiệu Khối lượng tăng và giá tăng Nếu số phiên khối lượng tăng liên tục > 3 và Giá khớp > Giá EOD tại đầu chuỗi thì tín hiệu Khối lượng tăng và giá tăng được xác nhận. |

<page_number>

19
</page_number>

FiinTrade logo

FiinGroup ENLIGHTEN THE MARKET logo

| 2. | Khối lượng tăng và giá giảm | Bước 1: Xác định Tổng khối lượng ước lượng T.K.L ước lượng = Tổng khối lượng khớp * (Tổng thời gian giao dịch)/ (Thời gian đã giao dịch) Trong đó: Tổng thời gian khớp = 4,25 đối với sàn HOSE và 4,5 đối với sàn HNX và UPCOM. Thời gian đã giao dịch là khoảng thời gian tính từ đầu phiên giao dịch đến thời điểm hiện tại. Bước 2: Xác định số phiên khối lượng tăng Đếm số phiên khối lượng tăng liên tục dựa trên Tổng khối lượng EOD của những ngày trước và T.K.L ước lượng của ngày hiện tại. Bước 3: Xác định tín hiệu Khối lượng tăng và giá giảm Nếu số phiên khối lượng tăng liên tục > 3 và Giá khớp < Giá EOD tại đầu chuỗi thì tín hiệu Khối lượng tăng và giá giảm được xác nhận. |
| --- | --- | --- |
| 3. | Giá tăng liên tục trong nhiều phiên | Bước 1: Xác định số phiên giá tăng liên tục Đếm số phiên giá tăng liên tục dựa trên giá khớp và giá EOD. Bước 2: Xác định tín hiệu Giá tăng liên tục trong nhiều phiên Nếu số phiên giá tăng liên tục > 3 thì tín hiệu Giá tăng liên tục trong nhiều phiên được xác nhận. |
| 4. | Giá giảm liên tục trong nhiều phiên | Bước 1: Xác định số phiên giá giảm liên tục Đếm số phiên giá giảm liên tục dựa trên giá khớp và giá EOD. Bước 2: Xác định tín hiệu Giá giảm liên tục trong nhiều phiên Nếu số phiên giá giảm liên tục > 3 thì tín hiệu Giá giảm liên tục trong nhiều phiên được xác nhận. |
| 5. | Khối lượng tăng liên tục | Bước 1: Xác định Tổng khối lượng ước lượng T.K.L ước lượng = Tổng khối lượng khớp * (Tổng thời gian giao dịch)/ (Thời gian đã giao dịch) Trong đó: Tổng thời gian khớp = 4,25 đối với sàn HOSE và 4,5 đối với sàn HNX và UPCOM. Thời gian đã giao dịch là khoảng thời gian tính từ đầu phiên giao dịch đến thời điểm hiện tại. |

<page_number>20</page_number>

FiinTrade logo

FiinGroup logo

**<u>Bước 2</u>: Xác định số phiên khối lượng tăng**

Đếm số phiên khối lượng tăng liên tục dựa trên Tổng khối lượng EOD của những ngày trước và T.K.L ước lượng của ngày hiện tại.

**<u>Bước 3</u>: Xác định tín hiệu Khối lượng tăng liên tục**

Nếu số phiên khối lượng tăng liên tục > 3 thì tín hiệu **Khối lượng tăng liên tục** được xác nhận.

## 4.4 Hiển thị trên Fiintrade

Việc phân tích giá và khối lượng được thể hiện tại chức năng **“Tín hiệu kỹ thuật”** tab **“Phân tích Giá – KL”** mục **“Chốt phiên”**. Fiintrade cho phép lựa chọn phương pháp phân tích giá – khối lượng phù hợp với nhu cầu tại droplist.

Screenshot of FiinTrade Technical Signals interface

# 5 Bộ chỉ tiêu phân tích chiến lược TA \<TA strategy>

## 5.1 Tích luỹ

### 5.1.1 Định nghĩa

Tích lũy là chiến lược đầu tư tập trung vào các cổ phiếu có thanh khoản tăng đột biến từ nền tích lũy trong một giai đoạn. Hệ thống FiinTrade hỗ trợ nhà đầu tư thống kê các giao trên toàn thị trường, xác định các cổ phiếu nền tích lũy tính đến thời điểm hiện thời và có đột biến trong phiên giao dịch.

### 5.1.2 Các chỉ tiêu xác định chiến lược

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | Tổng khối lượng khớp | Là tổng khối lượng khớp lệnh hiện tại |

<page_number>21</page_number>

FiinTrade logo

FiinGroup logo

| 2. | %Thay đổi | Là tỷ lệ tăng/giảm giá trong phiên hiện tại |
| --- | --- | --- |
| 3. | K.L TB 10 phiên | Là trung bình khối lượng giao dịch của 10 phiên liên tiếp (không bao gồm phiên giao dịch hiện tại) |

## 5.1.3 Phương pháp xác định chiến lược

| STT | Chiến lược | Mô tả |
| --- | --- | --- |
| 1. | Tích lũy | Bước 1: Xác định tổng khối lượng ước lượng T.K.L ước lượng = Tổng khối lượng khớp * (Tổng thời gian giao dịch)/ (Thời gian đã giao dịch) Trong đó: Tổng thời gian khớp = 4,25 đối với sàn HOSE và 4,5 đối với sàn HNX và UPCOM. Thời gian đã giao dịch là khoảng thời gian tính từ đầu phiên giao dịch đến thời điểm hiện tại. Bước 2: Xác định tỷ lệ khối lượng Tỷ lệ khối lượng = T.K.L ước lượng/ K.L TB 10 phiên Bước 3: Xác định tín hiệu chiến lược Tích Lũy Nếu tỷ lệ khối lượng > 2 và %thay đổi giá > 1% thì tín hiệu chiến lược Tích lũy được xác định Tỷ lệ khối lượng, % thay đổi giá có thể hiệu chỉnh trên cơ sở nhu cầu của người dùng. |

## 5.1.4 Hiển thị trên Fiintrade

Việc xác định cổ phiếu vượt đỉnh/thủng đáy được thể hiện tại chức năng **“Chiến lược đầu tư”** tab **“Chiến lược TA”** mục **“Tích lũy”**. Fiintrade cho phép tùy chỉnh **giai đoạn tích lũy, giá tăng và tỷ lệ khối lượng** để tìm danh sách những cổ phiếu có tín hiệu “Tích lũy” phù hợp.

<page_number>22</page_number>

FiinTrade logo FiinGroup logo

Screenshot of FiinTrade investment strategy interface

## 5.2 Vượt đỉnh/ Thủng đáy

### 5.2.1 Định nghĩa

**Vượt đỉnh** (hủng đáy) là chiến lược đầu tư tập trung vào những cổ phiếu có giá giao dịch lớn và giá vượt qua đỉnh (xuống dưới đáy) giá trong 3 tháng, 6 tháng, 9 tháng và 1 năm.

Hệ thống FiinTrade hỗ trợ nhà đầu tư thống kê các giao trên toàn thị trường, xác định các cổ phiếu vượt đỉnh (hủng đáy) và đột biến khối lượng trong phiên giao dịch..

### 5.2.2 Các chỉ tiêu xác định chiến lược

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | Tổng khối lượng khớp | Là tổng khối lượng khớp lệnh hiện tại |
| 2. | Giá khớp | Là giá khớp lệnh hiện tại |
| 3. | K.L TB 10 phiên | Là trung bình khối lượng giao dịch của 10 phiên liên tiếp (không bao gồm phiên giao dịch hiện tại) |
| 4. | Giá đỉnh | Là giá giao dịch lớn nhất trong 3 tháng (hoặc 6 tháng, 9 tháng, 12 tháng) |
| 5. | Giá đáy | Là giá giao dịch thấp nhất trong 3 tháng (hoặc 6 tháng, 9 tháng, 12 tháng) |

### 5.2.3 Phương pháp xác định chiến lược

| STT | Chiến lược | Mô tả |
| --- | --- | --- |

<page_number>23</page_number>

FiinTrade logo FiinGroup logo

| 1. | Vượt đỉnh | Bước 1: Xác định tổng khối lượng ước lượng T.K.L ước lượng = Tổng khối lượng khớp * (Tổng thời gian giao dịch)/ (Thời gian đã giao dịch) Trong đó: Tổng thời gian khớp = 4,25 đối với sàn HOSE và 4,5 đối với sàn HNX và UPCOM. Thời gian đã giao dịch là khoảng thời gian tính từ đầu phiên giao dịch đến thời điểm hiện tại. Bước 2: Xác định tỷ lệ khối lượng Tỷ lệ khối lượng = T.K.L ước lượng/ K.L TB 10 phiên Bước 3: Xác định tín hiệu chiến lược Vượt đỉnh Nếu tỷ lệ khối lượng > 1 và giá khớp > giá đỉnh trong 3 tháng thì tín hiệu chiến lược Vượt đỉnh được xác định Tỷ lệ khối lượng, thời gian giá đỉnh có thể hiệu chỉnh trên cơ sở nhu cầu của người dùng. |
| --- | --- | --- |
| 2. | Thủng đáy | Bước 1: Xác định tổng khối lượng ước lượng T.K.L ước lượng = Tổng khối lượng khớp * (Tổng thời gian giao dịch)/ (Thời gian đã giao dịch) Trong đó: Tổng thời gian khớp = 4,25 đối với sàn HOSE và 4,5 đối với sàn HNX và UPCOM. Thời gian đã giao dịch là khoảng thời gian tính từ đầu phiên giao dịch đến thời điểm hiện tại. Bước 2: Xác định tỷ lệ khối lượng Tỷ lệ khối lượng = T.K.L ước lượng/ K.L TB 10 phiên Bước 3: Xác định tín hiệu chiến lược Thủng đáy Nếu tỷ lệ khối lượng > 1 và giá khớp > giá đáy trong 3 tháng thì tín hiệu chiến lược Thủng đáy được xác định Tỷ lệ khối lượng, thời gian giá đỉnh có thể hiệu chỉnh trên cơ sở nhu cầu của người dùng. |

### 5.2.4 Hiển thị trên Fiintrade

Việc xác định cổ phiếu vượt đỉnh/thủng đáy được thể hiện tại chức năng **“Chiến lược đầu tư”** tab **“Chiến lược TA”** mục **“Vượt đỉnh/thủng đáy”**. Fiintrade cho phép tùy chỉnh **các tiêu chí đầu vào** để tìm danh sách những cổ phiếu có tín hiệu “Vượt đỉnh/ thủng đáy” phù hợp.

<page_number>24</page_number>

FiinTrade logo

FiinGroup ENLIGHTEN THE MARKET logo

Screenshot of FiinTrade investment strategy interface

# 5.3 Vượt MA

## 5.3.1 Định nghĩa

**Vượt lên MA (Cắt xuống MA)** là chiến lược đầu tư tập trung vào các mã cổ phiếu có biến động giá lớn hơn (nhỏ hơn) đường trung bình động MA và kèm theo khối lượng lớn.

Hệ thống FiinTrade hỗ trợ nhà đầu tư thống kê các giao trên toàn thị trường, xác định các cổ phiếu có tín hiệu kỹ thuật **Vượt lên MA (Cắt xuống MA)** và có đột biến trong phiên giao dịch.

## 5.3.2 Các chỉ tiêu xác định chiến lược

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | Tổng khối lượng khớp | Là tổng khối lượng khớp lệnh hiện tại |
| 2. | Giá khớp | Là giá khớp lệnh hiện tại |
| 3. | K.L TB 10 phiên | Là trung bình khối lượng giao dịch của 10 phiên liên tiếp (không bao gồm phiên giao dịch hiện tại) |
| 4. | SMA(x) | Là trung bình động giản đơn giá của (x) ngày giao dịch liền trước. |
| 5. | %Thay đổi | Là tỷ lệ tăng/giảm giá trong phiên hiện tại |

## 5.3.3 Phương pháp xác định chiến lược

| STT | Chiến lược | Mô tả |
| --- | --- | --- |

<page_number>25</page_number>

FiinTrade logo

FiinGroup logo

| 1. | Vượt lên MA | Bước 1: Xác định tổng khối lượng ước lượng T.K.L ước lượng = Tổng khối lượng khớp * (Tổng thời gian giao dịch)/ (Thời gian đã giao dịch) Trong đó: Tổng thời gian khớp = 4,25 đối với sàn HOSE và 4,5 đối với sàn HNX và UPCOM. Thời gian đã giao dịch là khoảng thời gian tính từ đầu phiên giao dịch đến thời điểm hiện tại. Bước 2: Xác định tỷ lệ khối lượng Tỷ lệ khối lượng = T.K.L ước lượng/ K.L TB 10 phiên Bước 3: Xác định tín hiệu chiến lược Vượt lên MA Nếu tỷ lệ khối lượng > 1 và giá khớp > SMA 20 và %thay đổi > 1% thì tín hiệu chiến lược Vượt lên MA được xác định Tỷ lệ khối lượng, SMA, %thay đổi có thể hiệu chỉnh trên cơ sở nhu cầu của người dùng. |
| --- | --- | --- |
| 2. | Cắt xuống MA | Bước 1: Xác định tổng khối lượng ước lượng T.K.L ước lượng = Tổng khối lượng khớp * (Tổng thời gian giao dịch)/ (Thời gian đã giao dịch) Trong đó: Tổng thời gian khớp = 4,25 đối với sàn HOSE và 4,5 đối với sàn HNX và UPCOM. Thời gian đã giao dịch là khoảng thời gian tính từ đầu phiên giao dịch đến thời điểm hiện tại. Bước 2: Xác định tỷ lệ khối lượng Tỷ lệ khối lượng = T.K.L ước lượng/ K.L TB 10 phiên Bước 3: Xác định tín hiệu chiến lược Cắt xuống MA Nếu tỷ lệ khối lượng > 1 và giá khớp < SMA20 và %thay đổi < 1% thì tín hiệu chiến lược Cắt xuống MA được xác định Tỷ lệ khối lượng, SMA, %thay đổi có thể hiệu chỉnh trên cơ sở nhu cầu của người dùng. |

### 5.3.4 Hiển thị trên Fiintrade

Việc xác định cổ phiếu vượt MA được thể hiện tại chức năng **“Chiến lược đầu tư”** tab **“Chiến lược TA”** mục **“Vượt MA”**. Fiintrade cho phép tùy chỉnh **các tiêu chí đầu vào** để tìm danh sách những cổ phiếu có tín hiệu “Vượt MA” phù hợp.

<page_number>26</page_number>

FiinTrade logo

FiinGroup logo

Screenshot of FiinTrade investment strategy interface

# 5.4 Cổ phiếu tốt trong đà giảm

## 5.4.1 Định nghĩa

**Cổ phiếu tốt trong đà giảm** là chiến lược đầu tư tập trung vào những cổ phiếu cho lợi nhuận tốt trong chu ký giảm của index. Hệ thống FiinTrade hỗ trợ nhà đầu tư thống kê các giao trên toàn thị trường, xác định các cổ phiếu có lợi nhuận trong chu kỳ giảm điểm của VN – Index.

## 5.4.2 Các chỉ tiêu xác định chiến lược

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | K.L T.B 1 tháng | Là khối lượng giao dịch trung bình trong 1 tháng |
| 2. | VNINDEX | Là chỉ số VNINDEX |
| 3. | Giá EOD | Là giá đóng cửa tại mỗi ngày giao dịch |

## 5.4.3 Phương pháp xác định chiến lược

| STT | Chiến lược | Mô tả |
| --- | --- | --- |
| 1. | Cổ phiếu tốt trong đà giảm | Bước 1: Xác định khoảng thời giản giảm của VnIndex Dựa trên khoảng thời gian người dùng chọn, hệ thống sẽ tìm ra 2 khoảng: thời gian t2 có min(VnIndex) và thời gian t₁ có max(Vnindex) (t₂> t₁) sao cho max(VnIndex) > 1,1 * min(VnIndex) |

<page_number>27</page_number>

FiinTrade logo FiinGroup logo

<u>**Bước 2**</u>: *Xác định lợi tức của cổ phiếu trong xu hướng giảm*
Lợi tức (từ t<sub>1</sub> đến t<sub>2</sub>) = (Giá đóng cửa t<sub>2</sub> /Giá đóng của t<sub>1</sub>)-1

<u>**Bước 3**</u>: *Xác định tín hiệu chiến lược Cổ phiếu tốt trong đà giảm*

Nếu K.T TB 1 tháng > 10,000 và sắp xếp lợi tức để xác định tín hiệu chiến lược Cổ phiếu tốt trong đà giảm

Người dùng có thể tùy chỉnh khoảng thời gian xác định xu hướng giảm của Vnindex và K.L T.B 1 tháng.

### 5.4.4 Hiển thị trên Fiintrade

Việc xác định cổ phiếu tốt trong đà giảm được thể hiện tại chức năng **“Chiến lược đầu tư”** tab **“Chiến lược TA”** mục **“CP tốt trong đà giảm”**. Fiintrade cho phép tùy chỉnh **các tiêu chí đầu vào** để tìm danh sách những cổ phiếu có tín hiệu “Cổ phiếu tốt trong đà giảm” phù hợp.

Screenshot of FiinTrade interface showing "CP TỐT TRONG ĐÀ GIẢM" strategy results

## 5.5 Biến động

### 5.5.1 Định nghĩa

**Biến động thị trường** là chiến lược tập trung vào những cổ phiếu với lợi nhuận tính theo ngày, tháng, quý lớn nhất. Hệ thống FiinTrade hỗ trợ nhà đầu tư thống kê dữ liệu lịch sử các giao trên toàn thị trường, xác định các cổ phiếu có lợi nhuận theo ngày, tháng, quý lớn nhất.

### 5.5.2 Các chỉ tiêu xác định chiến lược

| STT | Tên chỉ tiêu | Mô tả |
| --- | --- | --- |
| 1. | K.L TB 1 tháng | Là khối lượng giao dịch trung bình trong 1 tháng |

<page_number>28</page_number>

FiinTrade logo FiinGroup logo

| 2. | Giá EOD | Là giá đóng cửa tại mỗi ngày giao dịch |
| --- | --- | --- |

### 5.5.3 Phương pháp xác định chiến lược

| STT | Chiến lược | Mô tả |
| --- | --- | --- |
| 1. | Biến động thị trường | Bước 1: Xác định lợi tức cổ phiếu Dựa trên thời gian tính lợi tức (ngày, tháng hoặc quý) VD: lợi tức cổ phiếu (thứ 2) = (Giá EOD của thứ 2/ Giá EOD của thứ 2 tuần trước) -1 Bước 3: Xác định tín hiệu chiến lược Biến động thị trường Nếu K.T TB 1 tháng > 10,000 và sắp xếp lợi tức cổ phiếu để xác định tín hiệu chiến lược Biến động thị trường Người dùng có thể tùy chỉnh khoảng thời gian và K.L T.B 1 tháng. |

### 5.5.4 Hiển thị trên Fiintrade

Việc xác định biến động được thể hiện tại chức năng **“Chiến lược đầu tư”** tab **“Chiến lược TA”** mục **“biến động”**. Fiintrade cho phép tùy chỉnh **các tiêu chí đầu vào** để tìm danh sách những cổ phiếu có tín hiệu “Biến động thị trường” phù hợp.

Screenshot of FiinTrade Investment Strategy interface

## II Ứng dụng của việc xác định tín hiệu kỹ thuật trên FiinTrade

Việc xác định tín hiệu kỹ thuật có thể hỗ trợ Nhà đầu tư ở các phương diện:

<page_number>29</page_number>

FiinTrade logo

FiinGroup ENLIGHTEN THE MARKET logo

* **Đánh giá nhanh một cách trực quan biến động giá hiện tại và xu hướng ngắn hạn**, giúp Nhà đầu tư nhìn ngay ra dấu hiệu tích cực/tiêu cực của giá cổ phiếu theo dữ liệu giao dịch lịch sử. Dựa trên Bộ đánh giá chỉ báo được công bố bởi FiinGroup, nhà đầu tư có thể tham khảo và đưa ra quyết định giao dịch cho bản thân.

* **Hỗ trợ thông tin trong Tổng quan tín hiệu kỹ thuật trong ngắn hạn.** Được xây dựng kết hợp với mục Top giao dịch, nhà đầu tư có thể quan sát nhanh và lựa chọn ra các cổ phiếu mạnh trong ngắn hạn.

* **Phát hiện các cổ phiếu có giao dịch đáng chú ý.**

* **Screen nhanh danh sách các cổ phiếu theo các phương pháp kỹ thuật khác nhau trên toàn thị trường.**

<page_number>

30
</page_number>