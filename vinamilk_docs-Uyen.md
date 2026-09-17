# BÁO CÁO MÔN HỆ THỐNG QUẢN LÝ QUY TRÌNH NGHIỆP VỤ

# ĐỀ TÀI: VINAMILK

**Môn học:** IE203.F33.CN2.CNTT - Hệ thống quản lý quy trình nghiệp vụ  
**Giảng viên hướng dẫn:** Hà Lê Hoài Trung  
**Mã số sinh viên:** 24210187 - 25210119 - 24210236

# LỜI MỞ ĐẦU

Trong bối cảnh nền kinh tế số và cạnh tranh toàn cầu hiện nay, quản trị quy trình nghiệp vụ (Business Process Management - BPM) đã trở thành công cụ cốt lõi giúp các doanh nghiệp nâng cao năng lực cạnh tranh, tối ưu hóa chi phí và linh hoạt thích ứng với sự thay đổi của thị trường. Là doanh nghiệp chế biến sữa hàng đầu Việt Nam nằm trong Top 40 công ty sữa lớn nhất thế giới, Công ty Cổ phần Sữa Việt Nam (Vinamilk) đang không ngừng đẩy mạnh chiến lược chuyển đổi số toàn diện.
Tuy nhiên, với quy mô vận hành khổng lồ gồm hàng chục trang trại, nhà máy và hệ thống phân phối rộng khắp, việc duy trì tính hiệu quả, đồng bộ và loại bỏ lãng phí trong các quy trình nghiệp vụ là một thách thức lớn. Đề tài "Nghiên cứu, mô hình hóa và phân tích hệ thống quy trình nghiệp vụ tại Công ty Cổ phần Sữa Việt Nam (Vinamilk)" được thực hiện nhằm xây dựng bức tranh tổng thể về kiến trúc quy trình (Process Architecture), ứng dụng chuẩn BPMN để mô hình hóa chi tiết các quy trình đại diện, đồng thời áp dụng các phương pháp phân tích định tính và định lượng nhằm đề xuất giải pháp cải tiến tối ưu.

<img width="1920" height="1008" alt="VINAMILK_PICS_1" src="https://github.com/user-attachments/assets/57f6b33a-0e7a-4638-a5cb-137b353361d8" />
<p align="center">Hình 1.1 Hình ảnh công ty Vinamilk</p>


- **CHƯƠNG 4. MÔ HÌNH HÓA CHI TIẾT CÁC QUY TRÌNH BẰNG BPMN VÀ PHÂN TÍCH CÁC QUY TRÌNH**
    - 4.1. Quy trình Quản lý và Giám sát An toàn Lao động
      
 - 4.1.1. Mô tả quy trình, tác nhân và khách hàng
          
     Quy trình do Ban An toàn - Sức khỏe - Môi trường (HSE) chủ trì nhằm đảm bảo an toàn lao động tại các nhà máy, kho và trang trại của Vinamilk. Định kỳ, HSE cập nhật kế hoạch và tiêu chuẩn an toàn lao động, sau đó phổ biến đến Quản đốc/Giám sát vận hành. Nội dung đào tạo được phân loại theo đối tượng (nhân viên mới hoặc đang làm việc) và được tổ chức cho Người lao động. HSE thực hiện kiểm tra định kỳ hoặc đột xuất, đồng thời kiểm tra song song hồ sơ/trang bị bảo hộ và hiện trường/máy móc. Khi phát hiện rủi ro, mức độ ảnh hưởng được đánh giá và phân loại nhẹ/nặng để xác định hướng xử lý: đơn vị tự khắc phục hoặc báo cáo Ban Điều hành ra quyết định. Kết quả khắc phục được HSE theo dõi liên tục cho đến khi đạt yêu cầu an toàn.

Tác nhân tham gia quy trình:  

•      Ban An toàn - Sức khỏe - Môi trường (HSE)

•      Quản đốc / Giám sát vận hành

•      Người lao động

•      Ban Điều hành

Khách hàng của quy trình:  

•      Người lao động (được đào tạo và làm việc trong môi trường an toàn)

•      Ban Điều hành (được cung cấp thông tin để ra quyết định xử lý rủi ro)

•      Cơ quan quản lý nhà nước về an toàn lao động (đảm bảo tuân thủ quy định pháp luật)


 - 4.1.2. Mô hình hóa quy trình bằng BPMN

<img width="4530" height="2730" alt="antoanlaodong" src="https://github.com/user-attachments/assets/c23c4298-1900-481f-bbf1-52f4efd60df3" />
<p align="center"><b>Hình 4.1. Sơ đồ BPMN - Quy trình Quản lý và Giám sát An toàn Lao động</b></p>

### 4.1.3. Phân tích định tính

#### 4.1.3.1. Phân tích giá trị gia tăng

<p align="center">
  <b>Bảng 4.1.1. Phân loại giá trị gia tăng - Quy trình Quản lý và Giám sát An toàn Lao động</b>
</p>

| STT | Hoạt động trong quy trình | Tác nhân thực hiện | Phân loại | Giải thích |
| :---: | --- | --- | :---: | --- |
| 1 | Cập nhật kế hoạch, yêu cầu ATLĐ | Ban HSE | **BVA** | Cần thiết để định hướng công tác an toàn cho cả năm nhưng chưa trực tiếp tạo giá trị an toàn. |
| 2 | Phổ biến tiêu chuẩn ATLĐ | Ban HSE | **BVA** | Hoạt động truyền thông nội bộ cần thiết để đơn vị vận hành nắm được yêu cầu. |
| 3 | Xác định nội dung đào tạo hội nhập / định kỳ | Ban HSE | **BVA** | Cần thiết để thiết kế nội dung phù hợp từng đối tượng. |
| 4 | Tổ chức đào tạo ATLĐ | Ban HSE | **VA** | Tạo giá trị trực tiếp: nâng cao nhận thức và kỹ năng an toàn cho người lao động. |
| 5 | Tham gia đào tạo ATLĐ | Người lao động | **VA** | Người lao động trực tiếp tiếp nhận kiến thức giúp phòng tránh tai nạn lao động. |
| 6 | Lập lịch kiểm tra định kỳ / Xác định phạm vi đột xuất | Ban HSE | **BVA** | Cần thiết để tổ chức hoạt động kiểm tra hiệu quả. |
| 7 | Kiểm tra hồ sơ, trang bị bảo hộ (PPE) | Ban HSE | **VA** | Phát hiện trực tiếp các thiếu sót về hồ sơ và trang bị bảo hộ. |
| 8 | Kiểm tra hiện trường, máy móc | Ban HSE | **VA** | Phát hiện trực tiếp các nguy cơ mất an toàn tại hiện trường. |
| 9 | Ghi nhận vấn đề an toàn | Ban HSE | **VA** | Là cơ sở trực tiếp để đánh giá và xử lý rủi ro. |
| 10 | Đánh giá mức độ ảnh hưởng | Ban HSE | **VA** | Xác định đúng mức độ ưu tiên xử lý, tạo giá trị trực tiếp trong kiểm soát rủi ro. |
| 11 | Yêu cầu đơn vị khắc phục (mức nhẹ) | Ban HSE | **VA** | Chỉ đạo xử lý trực tiếp giúp loại bỏ nguy cơ mất an toàn. |
| 12 | Điều tra & báo cáo sự cố (mức nặng) | Ban HSE | **NVA** | Là hoạt động xử lý ngoại lệ phát sinh ngoài kế hoạch, không tạo thêm giá trị mới mà nhằm khắc phục hậu quả. |
| 13 | Thực hiện khắc phục | Quản đốc / Giám sát vận hành | **VA** | Trực tiếp loại bỏ nguy cơ mất an toàn đã được ghi nhận. |
| 14 | Xem xét, quyết định xử lý | Ban Điều hành | **BVA** | Cần thiết cho các sự cố nghiêm trọng vượt thẩm quyền đơn vị. |
| 15 | Theo dõi kết quả khắc phục | Ban HSE | **BVA** | Cần thiết để đảm bảo vấn đề được xử lý dứt điểm. |

#### 4.1.3.2. Phân tích lãng phí

<p align="center">
  <b>Bảng 4.1.2. Phân loại lãng phí - Quy trình Quản lý và Giám sát An toàn Lao động</b>
</p>

| STT | Loại lãng phí | Ví dụ trong quy trình | Hướng khắc phục |
| :---: | --- | --- | --- |
| 1 | **Di chuyển** *(Move)* | Cán bộ HSE phải di chuyển giữa nhiều nhà máy, kho và trang trại phân tán để kiểm tra hiện trường trực tiếp. | Áp dụng kiểm tra từ xa qua camera/IoT cho các hạng mục có thể giám sát điện tử; lập lịch kiểm tra theo cụm địa lý để giảm số lượt di chuyển. |
| 2 | **Chờ đợi / Trì hoãn** *(Hold)* | Chờ đơn vị vận hành thực hiện khắc phục trước khi HSE xác nhận đóng vấn đề; chờ Ban Điều hành phê duyệt chỉ đạo xử lý cho sự cố nghiêm trọng. | Thiết lập thời hạn xử lý cụ thể cho từng mức độ rủi ro; phân cấp phê duyệt cho các sự cố mức trung bình để giảm thời gian chờ Ban Điều hành. |
| 3 | **Thừa / Trùng lặp** *(Overdo)* | Đào tạo lại toàn bộ nội dung cơ bản cho nhân viên đã được đào tạo tại đơn vị khác trong tập đoàn; lập nhiều biên bản kiểm tra trùng lặp cho cùng khu vực trong thời gian ngắn. | Công nhận kết quả đào tạo ATLĐ đã có trong hệ thống nội bộ Vinamilk; hợp nhất lịch kiểm tra định kỳ và đột xuất cho cùng khu vực khi có thể. |



 - 4.1.4. Phân tích định lượng
 - 
4.1.4.1. Phân tích định lượng về Thời gian (Time Flow Analysis)
   
Phân tích Thời gian chu kỳ (Cycle Time - CT) dựa trên nhánh rẽ chính của quy trình: "Mức độ nghiêm trọng của rủi ro".
•      Nhánh Nhẹ (giả định tần suất 85%): Kiểm tra & ghi nhận (1 ngày) + Yêu cầu và thực hiện khắc phục (3 ngày) = 4 ngày.
•      Nhánh Nặng (giả định tần suất 15%): Kiểm tra & ghi nhận (1 ngày) + Điều tra, báo cáo sự cố (2 ngày) + Chờ Ban Điều hành xem xét, quyết định (2 ngày) + Khắc phục theo chỉ đạo và theo dõi (5 ngày) = 10 ngày.
=> ACT = (0,85 × 4) + (0,15 × 10) = 3,4 + 1,5 = 4,9 ngày/vụ việc an toàn.

4.1.4.2. Phân tích định lượng về Chi phí (Cost Flow Analysis)

Ước tính dựa trên chi phí nhân sự HSE/đơn vị vận hành xử lý: 500.000 VNĐ/ngày; riêng nhánh Nặng phát sinh thêm chi phí họp Ban Điều hành 2.000.000 VNĐ/lần.
•      Chi phí Nhánh Nhẹ: C1 = 4 × 500.000 = 2.000.000 VNĐ.
•      Chi phí Nhánh Nặng: C2 = (10 × 500.000) + 2.000.000 = 5.000.000 + 2.000.000 = 7.000.000 VNĐ.
=> AC = (0,85 × 2.000.000) + (0,15 × 7.000.000) = 1.700.000 + 1.050.000 = 2.750.000 VNĐ/vụ việc.

<p align="center">
  <b>Bảng 4.1.3. Phân tích định lượng - Quy trình Quản lý và Giám sát An toàn Lao động</b>
</p>

| Nhánh / Kịch bản quy trình | Xác suất | Thời gian chu kỳ (CT) | Chi phí ước tính (VNĐ) |
| --- | :---: | :---: | :---: |
| Nhẹ (đơn vị tự khắc phục) | 85% | 4 ngày | 2.000.000 |
| Nặng (báo cáo Ban Điều hành) | 15% | 10 ngày | 7.000.000 |
| **Trung bình toàn quy trình** | **100%** | **4,9 ngày** | **2.750.000** |

 4.1.4.3. Phân tích định lượng về Chất lượng (Quality/Yield Analysis)
 
Tỷ lệ vụ việc xử lý đạt yêu cầu trong lần theo dõi đầu tiên ước tính đạt 82%; 18% còn lại cần thêm ít nhất một vòng theo dõi bổ sung. Điểm nghẽn chính nằm ở khâu chờ Ban Điều hành phê duyệt chỉ đạo xử lý đối với sự cố mức Nặng, chiếm tới 2/10 ngày (20%) thời gian xử lý của nhánh này.

4.1.4.4. Đề xuất cải tiến và nâng cao hiệu suất quy trình

•      Phân cấp phê duyệt: Ủy quyền cho Trưởng Ban HSE quyết định trực tiếp đối với các sự cố mức trung bình, chỉ trình Ban Điều hành các trường hợp vượt ngưỡng rủi ro cao, giúp giảm thời gian chờ phê duyệt.

•      Số hóa hồ sơ kiểm tra ATLĐ: Áp dụng biểu mẫu điện tử có ảnh/video hiện trường để rút ngắn thời gian ghi nhận và tổng hợp vấn đề an toàn.

•      Xây dựng thư viện giải pháp khắc phục theo mẫu sự cố thường gặp, giúp đơn vị vận hành rút ngắn thời gian từ 3 xuống còn khoảng 2 ngày cho nhánh Nhẹ.

4.2. Quy trình Phê duyệt Kế hoạch Tuyển dụng Nhân sự

Nhóm quy trình: QUẢN LÝ

4.2.1. Mô tả quy trình, tác nhân và khách hàng

Quy trình do Phòng Nhân sự (HR) chủ trì, khởi động vào đầu mỗi năm khi HR gửi yêu cầu thu thập nhu cầu nhân sự đến các Trưởng phòng ban/đơn vị vận hành. Sau khi tổng hợp, HR đối soát song song nhu cầu với định hướng hoạt động và nhu cầu thực tế của doanh nghiệp, rồi chuyển kế hoạch sang Phòng Tài chính - Kế toán để kiểm tra đồng thời quỹ lương và chi phí tuyển dụng. Khi ngân sách được xác nhận phù hợp, HR lập kế hoạch nhân sự tổng thể và trình Ban Điều hành xem xét, phê duyệt. Sau khi được phê duyệt, HR thông báo triển khai tuyển dụng đến các phòng ban liên quan để thực hiện.

Tác nhân tham gia quy trình:

•      Trưởng phòng ban / Đơn vị vận hành
•      Phòng Nhân sự (HR)

•      Phòng Tài chính - Kế toán

•      Ban Điều hành

Khách hàng của quy trình:

•      Trưởng phòng ban / Đơn vị vận hành (nhận nhân sự đúng nhu cầu, đúng tiến độ)

•      Ban Điều hành (kiểm soát ngân sách và định biên nhân sự toàn công ty)

4.2.2. Mô hình hóa quy trình bằng BPMN

<img width="4170" height="2550" alt="tuyendungnhansu" src="https://github.com/user-attachments/assets/05512b69-841a-41d2-8e89-f2224dfe93be" />

<p align="center">
  <b>Hình 4.2. Sơ đồ BPMN - Quy trình Phê duyệt Kế hoạch Tuyển dụng Nhân sự</b>
</p>

4.2.3. Phân tích định tính

4.2.3.1. Phân tích giá trị gia tăng

<p align="center">
  <b>Bảng 4.2.1. Phân loại giá trị gia tăng - Quy trình Phê duyệt Kế hoạch Tuyển dụng Nhân sự</b>
</p>

| STT | Hoạt động trong quy trình | Tác nhân thực hiện | Phân loại | Giải thích |
| :---: | --- | --- | :---: | --- |
| 1 | Gửi yêu cầu thu thập nhu cầu nhân sự | Phòng Nhân sự (HR) | **BVA** | Cần thiết để khởi động chu kỳ lập kế hoạch. |
| 2 | Xác định nhu cầu, đề xuất vị trí | Trưởng phòng ban | **VA** | Tạo đầu vào giá trị trực tiếp cho kế hoạch nhân sự, phản ánh đúng nhu cầu thực tế. |
| 3 | Tổng hợp nhu cầu nhân sự | HR | **BVA** | Cần thiết để có bức tranh tổng thể toàn công ty. |
| 4 | Đối soát với định hướng hoạt động | HR | **VA** | Đảm bảo kế hoạch nhân sự phù hợp chiến lược kinh doanh, tạo giá trị định hướng trực tiếp. |
| 5 | Đối soát với nhu cầu thực tế | HR | **VA** | Đảm bảo tính khả thi và sát thực tế vận hành của kế hoạch. |
| 6 | Gửi kế hoạch sang Tài chính - Kế toán | HR | **BVA** | Bước chuyển giao cần thiết giữa hai bộ phận. |
| 7 | Kiểm tra quỹ lương | Phòng Tài chính - Kế toán | **VA** | Đảm bảo tính khả thi tài chính của kế hoạch nhân sự. |
| 8 | Kiểm tra chi phí tuyển dụng | Phòng Tài chính - Kế toán | **VA** | Đảm bảo chi phí tuyển dụng nằm trong ngân sách được duyệt. |
| 9 | Xác nhận ngân sách phù hợp | Phòng Tài chính - Kế toán | **BVA** | Chốt kiểm soát cần thiết trước khi trình phê duyệt. |
| 10 | Lập kế hoạch nhân sự tổng thể | HR | **VA** | Tổng hợp thành sản phẩm có giá trị sử dụng trực tiếp cho việc trình duyệt và triển khai. |
| 11 | Trình Ban Điều hành | HR | **BVA** | Thủ tục cần thiết theo đúng thẩm quyền phê duyệt. |
| 12 | Xem xét kế hoạch tổng thể | Ban Điều hành | **VA** | Đảm bảo kế hoạch phù hợp mục tiêu chiến lược và nguồn lực công ty. |
| 13 | Phê duyệt kế hoạch tuyển dụng | Ban Điều hành | **VA** | Kết quả quyết định trực tiếp, cho phép kế hoạch được triển khai. |
| 14 | Thông báo triển khai tuyển dụng | HR | **BVA** | Cần thiết để các phòng ban bắt đầu quá trình tuyển dụng. |
| 15 | Yêu cầu bổ sung xác nhận (biên bản chưa hợp lệ) | Ban Điều hành | **NVA** | Phát sinh do hồ sơ trình duyệt chưa đầy đủ, là vòng lặp làm lại không tạo thêm giá trị. |
| 16 | Đề xuất điều chỉnh ngân sách/nhu cầu (ngân sách không đủ) | Phòng Tài chính - Kế toán | **NVA** | Là vòng lặp điều chỉnh phát sinh khi kế hoạch vượt ngân sách. |
| 17 | Yêu cầu điều chỉnh phạm vi/số lượng (kế hoạch chưa phù hợp) | Ban Điều hành | **NVA** | Là vòng lặp làm lại khi kế hoạch chưa đạt yêu cầu phê duyệt. |

4.2.3.2. Phân tích lãng phí

<p align="center">
  <b>Bảng 4.2.2. Phân loại lãng phí - Quy trình Phê duyệt Kế hoạch Tuyển dụng Nhân sự</b>
</p>

| STT | Loại lãng phí | Ví dụ trong quy trình | Hướng khắc phục |
| :---: | --- | --- | --- |
| 1 | **Di chuyển** *(Move)* | Hồ sơ kế hoạch tuyển dụng được luân chuyển thủ công qua nhiều phòng ban (HR → Tài chính → Ban Điều hành → HR) qua nhiều vòng. | Áp dụng hệ thống luân chuyển hồ sơ điện tử (workflow) tích hợp chữ ký số, giảm thời gian và sai sót khi chuyển giao thủ công. |
| 2 | **Chờ đợi / Trì hoãn** *(Hold)* | Chờ Phòng Tài chính kiểm tra đồng thời quỹ lương và chi phí tuyển dụng; chờ lịch họp Ban Điều hành để xem xét kế hoạch tổng thể. | Thiết lập ngưỡng ngân sách tự động cảnh báo trên hệ thống ERP; bố trí lịch họp định kỳ cố định hằng tháng cho việc phê duyệt kế hoạch nhân sự thay vì họp phát sinh. |
| 3 | **Thừa / Trùng lặp** *(Overdo)* | Lập lại toàn bộ hồ sơ kế hoạch dù chỉ một phòng ban thay đổi nhu cầu; kế hoạch bị yêu cầu điều chỉnh nhiều vòng do thiếu chuẩn hóa biểu mẫu đầu vào. | Chuẩn hóa biểu mẫu đề xuất nhu cầu nhân sự có kiểm tra hợp lệ ngay từ đầu vào; cho phép chỉnh sửa từng phần thay vì lập lại toàn bộ hồ sơ. |

4.2.4. Phân tích định lượng

4.2.4.1. Phân tích định lượng về Thời gian (Time Flow Analysis)

Phân tích Thời gian chu kỳ (Cycle Time - CT) dựa trên nhánh rẽ chính của quy trình: "Kết quả kiểm tra ngân sách".

•      Kịch bản Đủ ngân sách (giả định 80%): Tổng hợp nhu cầu (2 ngày) + Đối soát (1 ngày) + Gửi & kiểm tra ngân sách (2 ngày) + Lập kế hoạch tổng thể (1 ngày) + Trình và chờ Ban Điều hành phê duyệt (3 ngày) + Thông báo triển khai (1 ngày) = 10 ngày.

•      Kịch bản Không đủ ngân sách (giả định 20%): Như trên + vòng lặp đề xuất điều chỉnh ngân sách/nhu cầu và kiểm tra lại (5 ngày) = 15 ngày.

=> ACT = (0,8 × 10) + (0,2 × 15) = 8 + 3 = 11 ngày/đợt kế hoạch.

4.2.4.2. Phân tích định lượng về Chi phí (Cost Flow Analysis)

Ước tính dựa trên chi phí nhân sự tham gia xử lý hồ sơ và họp xét duyệt: 300.000 VNĐ/ngày (gộp các bộ phận tham gia).

•      Chi phí kịch bản Đủ ngân sách: C1 = 10 × 300.000 = 4.000.000 VNĐ.

•      Chi phí kịch bản Không đủ ngân sách: C2 = 15 × 300.000 = 4.500.000 VNĐ.

=> AC = (0,8 × 4.000.000) + (0,2 × 4.500.000) = 2.400.000 + 900.000 = 4.300.000 VNĐ/đợt kế hoạch.

<p align="center">
  <b>Bảng 4.2.3. Phân tích định lượng - Quy trình Phê duyệt Kế hoạch Tuyển dụng Nhân sự</b>
</p>

| Nhánh / Kịch bản quy trình | Xác suất | Thời gian chu kỳ (CT) | Chi phí ước tính (VNĐ) |
| --- | :---: | :---: | :---: |
| Đủ ngân sách | 80% | 10 ngày | 4.000.000 |
| Không đủ ngân sách (cần điều chỉnh) | 20% | 15 ngày | 4.500.000 |
| **Trung bình toàn quy trình** | **100%** | **11 ngày** | **4.300.000** |

4.2.4.3. Phân tích định lượng về Chất lượng (Quality/Yield Analysis)

Tỷ lệ kế hoạch được phê duyệt ngay lần trình đầu tiên ước tính đạt 78%; 22% còn lại phải qua ít nhất một vòng điều chỉnh (do ngân sách hoặc do phạm vi chưa phù hợp). Điểm nghẽn chính là bước kiểm tra ngân sách - chiếm 20% xác suất phải làm lại và kéo dài thêm 50% thời gian xử lý.

4.2.4.4. Đề xuất cải tiến và nâng cao hiệu suất quy trình

•      Chuẩn hóa biểu mẫu đề xuất nhu cầu có kiểm tra ràng buộc ngân sách sơ bộ ngay từ Trưởng phòng ban, giảm tỷ lệ hồ sơ bị trả lại do vượt ngân sách.

•      Áp dụng cảnh báo ngân sách tự động trên hệ thống ERP để Phòng Tài chính phát hiện sớm sai lệch trước khi hồ sơ được trình Ban Điều hành.

•      Rút ngắn chu kỳ họp phê duyệt của Ban Điều hành bằng lịch họp cố định hằng tháng, ước tính giảm ACT từ 11 ngày xuống dưới 8 ngày/đợt kế hoạch.

4.3. Quy trình Thu mua Sữa tươi từ Hộ Nông Dân Liên kết

Nhóm quy trình: CỐT LÕI

4.3.1. Mô tả quy trình, tác nhân và khách hàng

Quy trình bắt đầu khi Hộ nông dân liên kết vắt sữa đúng khung giờ quy định và vận chuyển đến trạm thu mua. Trạm thu mua/Bộ phận QA lấy mẫu và kiểm tra song song hai chỉ tiêu lý-hóa và vi sinh; nếu đạt chuẩn, sữa được cân khối lượng, bơm vào bồn làm lạnh và cập nhật dữ liệu thu mua vào hệ thống. Đội vận chuyển tiếp nhận, duy trì nhiệt độ bảo quản và vận chuyển sữa về nhà máy, nơi Bộ phận QA nhà máy kiểm tra lại mẫu trước khi xác nhận nhập kho nguyên liệu. Cuối cùng, Phòng Kế toán - Tài chính đối soát khối lượng, chất lượng và thực hiện thanh toán tiền sữa cho hộ nông dân, khép kín chu kỳ thu mua.

Tác nhân tham gia quy trình:

•      Hộ nông dân liên kết

•      Trạm thu mua / Bộ phận QA

•      Đội vận chuyển

•      Phòng Kế toán - Tài chính

Khách hàng của quy trình:

•      Nhà máy sản xuất (nhận nguyên liệu sữa đạt chuẩn chất lượng, đúng khối lượng)

•      Hộ nông dân liên kết (nhận thanh toán đầy đủ, đúng hạn và minh bạch)

4.3.2. Mô hình hóa quy trình bằng BPMN

<img width="3990" height="1710" alt="thumuasua" src="https://github.com/user-attachments/assets/3aedccf8-9787-495b-b277-645d54750575" />
<p align="center">
  <b>Hình 4.3. Sơ đồ BPMN - Quy trình Thu mua Sữa tươi từ Hộ Nông Dân Liên kết</b>
</p>

4.3.3. Phân tích định tính

4.3.3.1. Phân tích giá trị gia tăng

<p align="center">
  <b>Bảng 4.3.1. Phân loại giá trị gia tăng - Quy trình Thu mua Sữa tươi từ Hộ Nông Dân Liên kết</b>
</p>

| STT | Hoạt động trong quy trình | Tác nhân thực hiện | Phân loại | Giải thích |
| :---: | --- | --- | :---: | --- |
| 1 | Vắt sữa, vận chuyển đến trạm thu mua | Hộ nông dân liên kết | **VA** | Tạo ra nguyên liệu đầu vào - giá trị khởi nguồn của toàn chuỗi cung ứng. |
| 2 | Kiểm tra chỉ tiêu lý-hóa | Trạm thu mua / QA | **VA** | Đảm bảo trực tiếp chất lượng nguyên liệu đầu vào. |
| 3 | Kiểm tra chỉ tiêu vi sinh | Trạm thu mua / QA | **VA** | Đảm bảo trực tiếp an toàn vệ sinh của nguyên liệu. |
| 4 | Cân khối lượng, bơm bồn làm lạnh | Trạm thu mua / QA | **VA** | Bảo toàn chất lượng sữa và xác định chính xác khối lượng giao dịch. |
| 5 | Cập nhật dữ liệu thu mua | Trạm thu mua / QA | **BVA** | Cần thiết cho việc đối soát và thanh toán sau này. |
| 6 | Từ chối thu mua lô sữa (không đạt chuẩn) | Trạm thu mua / QA | **NVA** | Là hoạt động loại bỏ, không tạo giá trị nhưng cần thiết để kiểm soát chất lượng đầu vào. |
| 7 | Lập biên bản, đối chiếu tranh chấp (khối lượng không khớp) | Trạm thu mua / QA | **NVA** | Là hoạt động xử lý ngoại lệ phát sinh do sai lệch số liệu. |
| 8 | Tiếp nhận sữa, duy trì nhiệt độ 4°C | Đội vận chuyển | **VA** | Bảo toàn chất lượng sữa trong suốt quá trình vận chuyển. |
| 9 | Vận chuyển, giao sữa về nhà máy | Đội vận chuyển | **VA** | Đưa nguyên liệu đến đúng nơi sản xuất - tạo giá trị logistics trực tiếp. |
| 10 | Ghi nhận sự cố nhiệt độ (xe bồn trễ giờ) | Đội vận chuyển | **NVA** | Là hoạt động xử lý ngoại lệ, không tạo thêm giá trị. |
| 11 | QA nhà máy kiểm tra lại mẫu sữa | Trạm thu mua / QA (nhà máy) | **VA** | Bước kiểm soát chất lượng cuối cùng trước khi đưa vào sản xuất. |
| 12 | Xác nhận nhập kho nguyên liệu | Trạm thu mua / QA (nhà máy) | **BVA** | Thủ tục cần thiết để khép kín chuỗi cung ứng đầu vào. |
| 13 | Lập biên bản sự cố (không đạt sau vận chuyển) | Trạm thu mua / QA (nhà máy) | **NVA** | Xử lý ngoại lệ phát sinh từ biến động chất lượng trong vận chuyển. |
| 14 | Tổng hợp, đối soát khối lượng - chất lượng | Phòng Kế toán - Tài chính | **BVA** | Cần thiết làm căn cứ thanh toán chính xác. |
| 15 | Thanh toán tiền sữa cho hộ nông dân | Phòng Kế toán - Tài chính | **VA** | Kết quả tạo giá trị trực tiếp, đảm bảo quyền lợi hộ nông dân. |
| 16 | Yêu cầu xác minh lại (không khớp hợp đồng) | Phòng Kế toán - Tài chính | **NVA** | Vòng lặp xử lý phát sinh do sai lệch giữa số liệu thu mua và hợp đồng. |

4.3.3.2. Phân tích lãng phí

<p align="center">
  <b>Bảng 4.3.2. Phân loại lãng phí - Quy trình Thu mua Sữa tươi từ Hộ Nông Dân Liên kết</b>
</p>

| STT | Loại lãng phí | Ví dụ trong quy trình | Hướng khắc phục |
| :---: | --- | --- | --- |
| 1 | **Di chuyển** *(Move)* | Xe bồn phải di chuyển qua nhiều tuyến thu gom phân tán từ các hộ nông dân; phát sinh vận chuyển bổ sung khi cần đối chiếu trực tiếp tranh chấp khối lượng. | Tối ưu tuyến thu gom theo cụm địa lý hộ nông dân; số hóa việc ghi nhận khối lượng tại nguồn (cân điện tử kết nối hệ thống) để giảm tranh chấp cần đối chiếu trực tiếp. |
| 2 | **Chờ đợi / Trì hoãn** *(Hold)* | Chờ kết quả kiểm tra lý-hóa và vi sinh (hai nhánh song song) trước khi bơm bồn làm lạnh; chờ QA nhà máy kiểm tra lại mẫu trước khi xác nhận nhập kho. | Đầu tư thiết bị kiểm nhanh (rapid test) tại trạm thu mua để rút ngắn thời gian trả kết quả song song; áp dụng cơ chế công nhận kết quả kiểm tra tại trạm nếu đạt chuẩn, giảm bước kiểm tra lại toàn bộ tại nhà máy. |
| 3 | **Thừa / Trùng lặp** *(Overdo)* | Kiểm tra lại toàn bộ các chỉ tiêu tại nhà máy dù trạm thu mua đã kiểm tra đạt; ghi chép thủ công song song với nhập liệu vào hệ thống. | Áp dụng cơ chế kiểm tra xác suất (sampling) tại nhà máy thay vì kiểm tra lại 100%; số hóa toàn bộ quy trình ghi nhận dữ liệu, loại bỏ ghi chép giấy song song. |

4.3.4. Phân tích định lượng

4.3.4.1. Phân tích định lượng về Thời gian (Time Flow Analysis)

Phân tích Thời gian chu kỳ (Cycle Time - CT) dựa trên nhánh rẽ chính của quy trình: "Kết quả kiểm tra khối lượng ghi nhận".

•      Kịch bản Khớp (giả định 90%): Kiểm tra chất lượng & cân khối lượng (0,5 ngày) + Vận chuyển về nhà máy (0,5 ngày) + QA nhà máy kiểm tra lại (0,25 ngày) + Đối soát & thanh toán (1 ngày) = 2,25 ngày.

•      Kịch bản Không khớp (giả định 10%): Như trên + Lập biên bản, đối chiếu tranh chấp (1 ngày) = 3,25 ngày.

=> ACT = (0,9 × 2,25) + (0,1 × 3,25) = 2,025 + 0,325 = 2,35 ngày/lô sữa.

4.3.4.2. Phân tích định lượng về Chi phí (Cost Flow Analysis)

Ước tính dựa trên chi phí vận hành (nhân sự QA và đội vận chuyển): 400.000 VNĐ/ngày.

•      Chi phí kịch bản Khớp: C1 = 2,25 × 400.000 = 900.000 VNĐ.

•      Chi phí kịch bản Không khớp: C2 = 3,25 × 400.000 = 1.300.000 VNĐ.

=> AC = (0,9 × 900.000) + (0,1 × 1.300.000) = 810.000 + 130.000 = 940.000 VNĐ/lô sữa.

<p align="center">
  <b>Bảng 4.3.3. Phân tích định lượng - Quy trình Thu mua Sữa tươi từ Hộ Nông Dân Liên kết</b>
</p>

| Nhánh / Kịch bản quy trình | Xác suất | Thời gian chu kỳ (CT) | Chi phí ước tính (VNĐ) |
| --- | :---: | :---: | :---: |
| Khớp với ghi nhận hộ dân | 90% | 2,25 ngày | 900.000 |
| Không khớp (cần đối chiếu) | 10% | 3,25 ngày | 1.300.000 |
| **Trung bình toàn quy trình** | **100%** | **2,35 ngày** | **940.000** |

4.3.4.3. Phân tích định lượng về Chất lượng (Quality/Yield Analysis)

Tỷ lệ lô sữa đạt chuẩn kiểm nghiệm ngay lần đầu ước tính đạt 92%; 8% còn lại bị từ chối thu mua. Tỷ lệ khối lượng khớp ghi nhận đạt 90%, cho thấy sai lệch giữa hộ nông dân và trạm thu mua vẫn còn tồn tại ở mức đáng chú ý. Điểm nghẽn: bước kiểm tra song song lý-hóa/vi sinh là bước quyết định thời gian tối thiểu của toàn quy trình.

4.3.4.4. Đề xuất cải tiến và nâng cao hiệu suất quy trình

•      Trang bị cân điện tử kết nối trực tiếp hệ thống tại điểm thu gom để giảm sai lệch khối lượng, mục tiêu nâng tỷ lệ khớp từ 90% lên trên 97%.

•      Đầu tư thiết bị kiểm nhanh chỉ tiêu cơ bản tại trạm thu mua để rút ngắn thời gian chờ kết quả song song.

•      Áp dụng cơ chế công nhận một phần kết quả kiểm tra tại trạm cho bước kiểm tra lại tại nhà máy, giảm ACT từ 2,35 ngày xuống gần 2 ngày/lô sữa.

4.4. Quy trình Tài trợ và Cấp phát Sữa cho Chương trình Sữa Học Đường

Nhóm quy trình: CỐT LÕI

4.4.1. Mô tả quy trình, tác nhân và khách hàng

Quy trình do Ban Dự án Sữa Học Đường chủ trì, phối hợp với Sở Giáo dục & Đào tạo và Sở Y tế để thống nhất danh sách trường và định mức tài trợ. Sau khi lập kế hoạch cung ứng, Khối Sản xuất & QA tiến hành sản xuất, bổ sung vi chất dinh dưỡng và kiểm nghiệm song song hai chỉ tiêu: vi chất dinh dưỡng và an toàn vệ sinh thực phẩm. Sữa đạt chuẩn được chuyển kho trung chuyển và vận chuyển đến điểm trường theo hai tuyến song song (tuyến gần và tuyến vùng sâu, vùng xa), tùy điều kiện thời tiết và giao thông. Tại trường, Ban Giám hiệu/Giáo viên kiểm đếm, bảo quản, tổ chức cho học sinh uống sữa và ký biên bản nghiệm thu để Ban Dự án thực hiện thanh quyết toán, khép kín chu kỳ tài trợ.

Tác nhân tham gia quy trình:

•      Sở Giáo dục & Đào tạo / Sở Y tế

•      Ban Dự án Sữa Học Đường

•      Khối Sản xuất & QA / Logistics

•      Ban Giám hiệu / Giáo viên

Khách hàng của quy trình:

•      Học sinh tại các điểm trường (đối tượng thụ hưởng cuối cùng của chương trình)

•      Nhà trường (đơn vị tiếp nhận và tổ chức triển khai)

•      Sở Giáo dục & Đào tạo / Sở Y tế (giám sát việc thực hiện chương trình theo quy định)

4.4.2. Mô hình hóa quy trình bằng BPMN

<img width="4170" height="1710" alt="suahocduong" src="https://github.com/user-attachments/assets/9cc04a10-6ac0-44a4-b939-d15cc779c7cb" />
<p align="center">
  <b>Hình 4.4. Sơ đồ BPMN - Quy trình Tài trợ và Cấp phát Sữa cho Chương trình Sữa Học Đường</b>
</p>

4.4.3. Phân tích định tính

4.4.3.1. Phân tích giá trị gia tăng

<p align="center">
  <b>Bảng 4.4.1. Phân loại giá trị gia tăng - Quy trình Tài trợ và Cấp phát Sữa cho Chương trình Sữa Học Đường</b>
</p>

| STT | Hoạt động trong quy trình | Tác nhân thực hiện | Phân loại | Giải thích |
| :---: | --- | --- | :---: | --- |
| 1 | Làm việc, thống nhất danh sách trường và định mức với Sở GD&ĐT, Sở Y tế | Ban Dự án SHĐ / Sở GD&ĐT | **BVA** | Cần thiết để xác định phạm vi triển khai nhưng chưa trực tiếp tạo giá trị dinh dưỡng cho học sinh. |
| 2 | Lập kế hoạch cung ứng SHĐ | Ban Dự án SHĐ | **BVA** | Cần thiết cho việc điều phối sản xuất và vận chuyển. |
| 3 | Sản xuất, bổ sung vi chất, dán nhãn SHĐ | Khối Sản xuất & QA | **VA** | Tạo ra sản phẩm sữa đạt chuẩn dinh dưỡng - giá trị cốt lõi của chương trình. |
| 4 | Kiểm nghiệm vi chất dinh dưỡng | Khối Sản xuất & QA | **VA** | Đảm bảo trực tiếp chất lượng dinh dưỡng theo quy định Bộ Y tế. |
| 5 | Kiểm nghiệm an toàn vệ sinh thực phẩm | Khối Sản xuất & QA | **VA** | Đảm bảo trực tiếp an toàn sức khỏe cho học sinh. |
| 6 | Chuyển kho trung chuyển | Logistics | **BVA** | Cần thiết cho vận hành chuỗi cung ứng nhưng không trực tiếp tạo giá trị dinh dưỡng. |
| 7 | Lập kế hoạch vận chuyển, chia tuyến | Logistics | **BVA** | Cần thiết để tối ưu lộ trình giao hàng. |
| 8 | Vận chuyển đến điểm trường (tuyến gần / vùng sâu, vùng xa) | Logistics | **VA** | Đưa sản phẩm đến đúng đối tượng thụ hưởng - tạo giá trị trực tiếp. |
| 9 | Giao nhận, kiểm đếm thùng sữa | Ban Giám hiệu / Giáo viên | **BVA** | Cần thiết để xác nhận số lượng, đảm bảo minh bạch. |
| 10 | Bảo quản, tổ chức học sinh uống sữa | Ban Giám hiệu / Giáo viên | **VA** | Giá trị cuối cùng của quy trình: học sinh nhận và sử dụng sữa. |
| 11 | Ký biên bản nghiệm thu, xác nhận khối lượng | Ban Giám hiệu / Giáo viên | **BVA** | Thủ tục xác nhận cần thiết cho công tác thanh quyết toán. |
| 12 | Tổng hợp, thực hiện thanh quyết toán | Ban Dự án SHĐ | **BVA** | Cần thiết để khép kín chu trình tài trợ, không trực tiếp tạo giá trị dinh dưỡng. |
| 13 | Điều chỉnh lịch trình vận chuyển (do thời tiết/giao thông) | Logistics | **NVA** | Phát sinh ngoài kế hoạch, là hoạt động xử lý ngoại lệ không tạo thêm giá trị. |
| 14 | Điều chỉnh số liệu cấp phát theo sĩ số thực tế | Ban Giám hiệu / Giáo viên | **NVA** | Là hoạt động làm lại do sai lệch giữa kế hoạch và thực tế sĩ số. |
| 15 | Lập biên bản, đổi trả khẩn cấp khi có sự cố bao bì | Ban Giám hiệu / Giáo viên | **NVA** | Xử lý ngoại lệ phát sinh từ sự cố chất lượng bao bì trong vận chuyển. |

4.4.3.2. Phân tích lãng phí

<p align="center">
  <b>Bảng 4.4.2. Phân loại lãng phí - Quy trình Tài trợ và Cấp phát Sữa cho Chương trình Sữa Học Đường</b>
</p>

| STT | Loại lãng phí | Ví dụ trong quy trình | Hướng khắc phục |
| :---: | --- | --- | --- |
| 1 | **Di chuyển** *(Move)* | Vận chuyển đến các điểm trường vùng sâu, vùng xa tốn nhiều thời gian và quãng đường; phát sinh vận chuyển ngược khi thùng sữa bị lỗi bao bì cần đổi trả. | Thiết lập kho trung chuyển vệ tinh gần cụm trường vùng sâu, vùng xa; tăng cường kiểm tra bao bì trước khi xuất kho để giảm tỷ lệ đổi trả. |
| 2 | **Chờ đợi / Trì hoãn** *(Hold)* | Chờ kết quả kiểm nghiệm vi chất dinh dưỡng và an toàn vệ sinh thực phẩm (hai nhánh song song) trước khi xuất kho; chờ nhà trường xác nhận sĩ số thực tế trước khi chốt số lượng cấp phát cuối cùng. | Áp dụng phòng kiểm nghiệm đạt chuẩn có thời gian trả kết quả nhanh (rapid test) cho các chỉ tiêu cơ bản; yêu cầu trường cập nhật sĩ số trước một mốc thời gian cố định hằng tháng. |
| 3 | **Thừa / Trùng lặp** *(Overdo)* | Sản xuất dư số lượng do chưa cập nhật kịp biến động sĩ số học sinh; lập nhiều bộ báo cáo riêng lẻ trùng lặp nội dung gửi Sở GD&ĐT và Sở Y tế. | Xây dựng cơ chế cập nhật sĩ số định kỳ tự động từ nhà trường; hợp nhất báo cáo gửi hai Sở thành một bộ hồ sơ chung có xác nhận đồng thời. |


4.4.4. Phân tích định lượng

4.4.4.1. Phân tích định lượng về Thời gian (Time Flow Analysis)

Phân tích Thời gian chu kỳ (Cycle Time - CT) dựa trên nhánh rẽ chính của quy trình: "Tuyến vận chuyển & điều kiện thời tiết, giao thông".  
•      Tuyến gần (giả định 70% số điểm trường): Thời gian vận chuyển cơ bản = 180 phút. Với 95% thuận lợi và 5% chậm trễ nhẹ (+60 phút): T(gần) = (0,95 × 180) + (0,05 × 240) = 183 phút.  
•      Tuyến vùng sâu, vùng xa (giả định 30% số điểm trường): Thời gian vận chuyển cơ bản = 480 phút. Với 80% thuận lợi và 20% không thuận lợi cần điều chỉnh lịch trình (+180 phút): T(xa) = (0,8 × 480) + (0,2 × 660) = 516 phút.  
=> ACT = (0,7 × 183) + (0,3 × 516) = 128,1 + 154,8 = 282,9 phút/lô hàng (≈ 4,7 giờ).  

4.4.4.2. Phân tích định lượng về Chi phí (Cost Flow Analysis)

Ước tính dựa trên đơn giá vận chuyển bình quân theo tuyến: tuyến gần 800.000 VNĐ/chuyến; tuyến xa 2.500.000 VNĐ/chuyến.

•      Chi phí tuyến gần: C1 = 800.000 VNĐ/chuyến.

•      Chi phí tuyến xa: C2 = 2.500.000 VNĐ/chuyến.

=> AC = (0,7 × 800.000) + (0,3 × 2.500.000) = 560.000 + 750.000 = 1.310.000 VNĐ/chuyến.

<p align="center">
  <b>Bảng 4.4.3. Phân tích định lượng - Quy trình Tài trợ và Cấp phát Sữa cho Chương trình Sữa Học Đường</b>
</p>

| Nhánh / Kịch bản quy trình | Xác suất | Thời gian chu kỳ (CT) | Chi phí ước tính (VNĐ) |
| --- | :---: | :---: | :---: |
| Tuyến điểm trường gần | 70% | 183 phút | 800.000 |
| Tuyến vùng sâu, vùng xa | 30% | 516 phút | 2.500.000 |
| **Trung bình toàn quy trình** | **100%** | **282,9 phút** | **1.310.000** |

4.4.4.3. Phân tích định lượng về Chất lượng (Quality/Yield Analysis)

Tỷ lệ lô sữa đạt kiểm nghiệm lần đầu ước tính 96%. Tỷ lệ sự cố bao bì trong vận chuyển ước tính 3%. Tỷ lệ giao hàng đúng hạn ước tính 88%, với 12% chậm trễ chủ yếu đến từ tuyến vùng sâu, vùng xa khi gặp thời tiết bất lợi. Điểm nghẽn: tuyến vùng sâu, vùng xa vừa chiếm chi phí cao nhất vừa có xác suất chậm trễ lớn nhất (20%).

4.4.4.4. Đề xuất cải tiến và nâng cao hiệu suất quy trình

•      Ứng dụng phần mềm định tuyến (route optimization) để giảm thời gian di chuyển đến các điểm trường vùng sâu, vùng xa, mục tiêu giảm ACT xuống dưới 250 phút/lô hàng.

•      Tăng cường đội xe dự phòng và lái xe có kinh nghiệm cho các tuyến có xác suất chậm trễ cao, giảm tỷ lệ không thuận lợi từ 20% xuống dưới 10%.

•      Chuẩn hóa quy cách đóng gói chống sốc để giảm tỷ lệ sự cố bao bì từ 3% xuống dưới 1%.

4.5. Quy trình Thu hồi Tài sản khi Nhân viên Nghỉ việc

Nhóm quy trình: HỖ TRỢ

4.5.1. Mô tả quy trình, tác nhân và khách hàng

Quy trình bắt đầu khi nhân viên nộp đơn xin nghỉ việc và được Trưởng bộ phận phê duyệt, đồng thời chỉ định nhân sự tiếp nhận công việc. Phòng Nhân sự lập danh mục thu hồi tài sản gửi đến nhân viên; nhân viên đồng thời bàn giao công việc, hồ sơ cho Trưởng bộ phận và bàn giao thiết bị phần cứng, CNTT cho Bộ phận Hành chính - Quản trị Tài sản/IT. Hai bộ phận này kiểm tra song song tài sản phần cứng và thu hồi dữ liệu, tài khoản truy cập trước khi xác nhận hoàn tất thu hồi. Sau đó, Phòng Nhân sự và Kế toán đối chiếu đồng thời công nợ tài sản và công nợ tài chính trước khi chốt sổ bảo hiểm xã hội, thanh lý hợp đồng lao động và chi trả quyết toán lương, trợ cấp cho nhân viên.

Tác nhân tham gia quy trình:

•      Nhân viên nghỉ việc

•      Trưởng bộ phận / Nhân sự tiếp nhận

•      Hành chính - Quản trị Tài sản / IT

•      Phòng Nhân sự (HR) / Kế toán

Khách hàng của quy trình:

•      Ban Điều hành (đảm bảo không thất thoát tài sản và dữ liệu doanh nghiệp)

•      Nhân viên nghỉ việc (nhận quyết toán lương, trợ cấp đầy đủ và đúng hạn)

4.5.2. Mô hình hóa quy trình bằng BPMN

<img width="4020" height="2580" alt="thuhoitaisan" src="https://github.com/user-attachments/assets/4f84d5a9-c329-4aa6-b1a2-f0090fc44286" />
<p align="center">
  <b>Hình 4.5. Sơ đồ BPMN - Quy trình Thu hồi Tài sản khi Nhân viên Nghỉ việc</b>
</p>

4.5.3. Phân tích định tính

4.5.3.1. Phân tích giá trị gia tăng

<p align="center">
  <b>Bảng 4.5.1. Phân loại giá trị gia tăng - Quy trình Thu hồi Tài sản khi Nhân viên Nghỉ việc</b>
</p>

| STT | Hoạt động trong quy trình | Tác nhân thực hiện | Phân loại | Giải thích |
| :---: | --- | --- | :---: | --- |
| 1 | Nộp đơn xin nghỉ việc | Nhân viên nghỉ việc | **BVA** | Thủ tục pháp lý bắt buộc để khởi động quy trình. |
| 2 | Chỉ định nhân sự tiếp nhận | Trưởng bộ phận | **BVA** | Cần thiết để đảm bảo công việc không bị gián đoạn. |
| 3 | Lập danh mục thu hồi tài sản | Phòng Nhân sự (HR) | **BVA** | Cần thiết làm căn cứ cho việc thu hồi. |
| 4 | Bàn giao công việc, hồ sơ | Nhân viên nghỉ việc | **VA** | Tạo giá trị trực tiếp: đảm bảo tính liên tục trong vận hành doanh nghiệp. |
| 5 | Kiểm tra, ký xác nhận bàn giao | Trưởng bộ phận | **VA** | Xác nhận trực tiếp chất lượng bàn giao công việc. |
| 6 | Bàn giao thiết bị phần cứng, CNTT | Nhân viên nghỉ việc | **VA** | Tạo giá trị trực tiếp: bảo vệ tài sản doanh nghiệp. |
| 7 | Kiểm tra, đối chiếu tài sản phần cứng | Hành chính - Quản trị Tài sản | **VA** | Xác nhận trực tiếp tình trạng tài sản thu hồi. |
| 8 | Kiểm tra kỹ thuật, thu hồi dữ liệu | IT | **VA** | Bảo vệ trực tiếp dữ liệu và hệ thống thông tin doanh nghiệp. |
| 9 | Xác nhận hoàn tất thu hồi | Hành chính - Quản trị Tài sản / IT | **BVA** | Chốt kiểm soát cần thiết trước khi khép hồ sơ. |
| 10 | Đối chiếu tiến độ bàn giao & thu hồi | Phòng Nhân sự (HR) | **BVA** | Cần thiết để tổng hợp trước bước quyết toán. |
| 11 | Xác nhận không nợ tài sản | Phòng Nhân sự (HR) | **VA** | Bảo vệ trực tiếp giá trị tài sản của doanh nghiệp. |
| 12 | Xác nhận không nợ tài chính | Kế toán | **VA** | Bảo vệ trực tiếp lợi ích tài chính của doanh nghiệp. |
| 13 | Chốt sổ BHXH, thanh lý HĐLĐ | Phòng Nhân sự (HR) | **BVA** | Thủ tục pháp lý bắt buộc để hoàn tất quan hệ lao động. |
| 14 | Chi trả quyết toán lương, trợ cấp | Kế toán | **VA** | Kết quả tạo giá trị trực tiếp, đảm bảo quyền lợi hợp pháp của nhân viên. |
| 15 | Yêu cầu bổ sung, hoàn thiện (bàn giao chưa đạt) | Trưởng bộ phận | **NVA** | Là vòng lặp làm lại do bàn giao công việc chưa đầy đủ. |
| 16 | Lập biên bản thiếu hụt / xử lý sự cố (tài sản/tài khoản chưa đầy đủ) | Hành chính - Quản trị Tài sản / IT | **NVA** | Xử lý ngoại lệ phát sinh khi thu hồi không đầy đủ. |
| 17 | Trích trừ công nợ vào lương (còn nợ) | Kế toán | **NVA** | Là hoạt động xử lý ngoại lệ khi phát sinh công nợ chưa thanh toán. |

4.5.3.2. Phân tích lãng phí

<p align="center">
  <b>Bảng 4.5.2. Phân loại lãng phí - Quy trình Thu hồi Tài sản khi Nhân viên Nghỉ việc</b>
</p>

| STT | Loại lãng phí | Ví dụ trong quy trình | Hướng khắc phục |
| :---: | --- | --- | --- |
| 1 | **Di chuyển** *(Move)* | Nhân viên phải di chuyển qua nhiều bộ phận (Trưởng bộ phận, Hành chính, IT, HR) để hoàn tất từng bước bàn giao riêng lẻ. | Xây dựng quy trình bàn giao một cửa (one-stop) với checklist thống nhất, giảm số lượt di chuyển giữa các bộ phận. |
| 2 | **Chờ đợi / Trì hoãn** *(Hold)* | Chờ Trưởng bộ phận xác nhận bàn giao công việc trước khi HR ghi nhận; chờ đồng thời xác nhận công nợ tài sản và tài chính trước khi chốt sổ. | Thiết lập thời hạn xử lý cụ thể cho từng bước xác nhận trên hệ thống HRM; cho phép xử lý song song xác nhận công nợ tài sản và tài chính ngay khi có đủ dữ liệu. |
| 3 | **Thừa / Trùng lặp** *(Overdo)* | Yêu cầu nhân viên điền lại nhiều biểu mẫu bàn giao có nội dung trùng lặp giữa các bộ phận; kiểm tra lại toàn bộ danh mục tài sản dù nhân viên chỉ sử dụng một phần nhỏ. | Hợp nhất biểu mẫu bàn giao thành một bộ hồ sơ dùng chung cho tất cả các bộ phận; đối chiếu theo danh mục tài sản được cấp phát thực tế thay vì kiểm tra toàn bộ. |

4.5.4. Phân tích định lượng

4.5.4.1. Phân tích định lượng về Thời gian (Time Flow Analysis)

Phân tích Thời gian chu kỳ (Cycle Time - CT) dựa trên nhánh rẽ chính của quy trình: "Kết quả thu hồi tài sản và tài khoản".

•      Kịch bản Đầy đủ (giả định 88%): Bàn giao công việc (2 ngày) + Bàn giao & kiểm tra thiết bị song song (1 ngày) + Xác nhận hoàn tất thu hồi (0,5 ngày) + Đối chiếu công nợ (1 ngày) + Chốt sổ & quyết toán (2 ngày) = 6,5 ngày.

•      Kịch bản Không đầy đủ (giả định 12%): Như trên + Lập biên bản thiếu hụt, xử lý bổ sung (3 ngày) = 9,5 ngày.

=> ACT = (0,88 × 6,5) + (0,12 × 9,5) = 5,72 + 1,14 = 6,86 ngày/hồ sơ nghỉ việc.

4.5.4.2. Phân tích định lượng về Chi phí (Cost Flow Analysis)

Ước tính dựa trên chi phí xử lý hành chính - nhân sự tham gia: 350.000 VNĐ/ngày.

•      Chi phí kịch bản Đầy đủ: C1 = 6,5 × 350.000 = 2.275.000 VNĐ.

•      Chi phí kịch bản Không đầy đủ: C2 = 9,5 × 350.000 = 4.325.000 VNĐ.

=> AC = (0,88 × 2.275.000) + (0,12 × 4.325.000) = 2.002.000 + 399.000 = 2.401.000 VNĐ/hồ sơ.

<p align="center">
  <b>Bảng 4.5.3. Phân tích định lượng - Quy trình Thu hồi Tài sản khi Nhân viên Nghỉ việc</b>
</p>

| Nhánh / Kịch bản quy trình | Xác suất | Thời gian chu kỳ (CT) | Chi phí ước tính (VNĐ) |
| --- | :---: | :---: | :---: |
| Đầy đủ | 88% | 6,5 ngày | 2.275.000 |
| Không đầy đủ (cần xử lý bổ sung) | 12% | 9,5 ngày | 4.325.000 |
| **Trung bình toàn quy trình** | **100%** | **6,86 ngày** | **2.401.000** |

4.5.4.3. Phân tích định lượng về Chất lượng (Quality/Yield Analysis)

Tỷ lệ hồ sơ thu hồi đầy đủ ngay lần đầu ước tính đạt 88%; 12% còn lại phát sinh công nợ tài sản hoặc tài chính cần xử lý bổ sung, kéo dài thời gian quyết toán cho nhân viên. Điểm nghẽn: bước đối chiếu đồng thời công nợ tài sản và tài chính là điều kiện bắt buộc trước khi chốt sổ, dễ bị trì hoãn nếu một trong hai bộ phận chậm xác nhận.

4.5.4.4. Đề xuất cải tiến và nâng cao hiệu suất quy trình

•      Số hóa checklist bàn giao tài sản/CNTT ngay từ ngày nhân viên nộp đơn nghỉ việc, giúp phát hiện sớm rủi ro thiếu hụt trước ngày nghỉ chính thức.

•      Tự động hóa đối chiếu công nợ tài chính qua hệ thống ERP, giảm thời gian chờ xác nhận thủ công từ Kế toán.

•      Xây dựng cơ chế xử lý song song giữa xác nhận công nợ tài sản và tài chính, ước tính giảm ACT từ 6,86 ngày xuống dưới 5,5 ngày/hồ sơ.

4.6. Quy trình Khám sức khỏe định kỳ hàng năm

Nhóm quy trình: HỖ TRỢ

4.6.1. Mô tả quy trình, tác nhân và khách hàng

Quy trình do Phòng Nhân sự (HR)/Ban HSE chủ trì, bắt đầu từ đầu năm với việc khảo sát nhu cầu, xây dựng danh mục khám và lựa chọn cơ sở y tế đạt yêu cầu năng lực. Sau khi ký hợp đồng và thống nhất lịch khám chi tiết, HR thông báo đến các đơn vị để CBCNV chủ động sắp xếp đến khám theo lịch. Tại cơ sở y tế, CBCNV được khám song song lâm sàng và cận lâm sàng; kết quả được tổng hợp thành hồ sơ sức khỏe cá nhân, các trường hợp bất thường được chỉ định khám chuyên sâu bổ sung. HR bàn giao sổ khám cá nhân và lập phương án hỗ trợ điều trị cho các trường hợp không đạt yêu cầu sức khỏe để Y tế cơ quan/Ban Điều hành xem xét, quyết định điều chuyển vị trí hoặc phê duyệt hỗ trợ y tế, theo dõi định kỳ.

Tác nhân tham gia quy trình:

•      Phòng Nhân sự (HR) / Ban HSE

•      Bệnh viện / Cơ sở y tế hợp tác

•      CBCNV

•      Y tế cơ quan / Ban Điều hành

Khách hàng của quy trình:

•      CBCNV (được chăm sóc, theo dõi sức khỏe định kỳ)

•      Ban Điều hành (đảm bảo nguồn nhân lực khỏe mạnh, bố trí công việc phù hợp)

4.6.2. Mô hình hóa quy trình bằng BPMN

<img width="4170" height="1680" alt="khamsuckhoe" src="https://github.com/user-attachments/assets/e87843f0-c2e4-453b-b0e8-0afe71a9cb49" />
<p align="center">
  <b>Hình 4.6. Sơ đồ BPMN - Quy trình Khám sức khỏe định kỳ hàng năm</b>
</p>

4.6.3. Phân tích định tính

4.6.3.1. Phân tích giá trị gia tăng

<p align="center">
  <b>Bảng 4.6.1. Phân loại giá trị gia tăng - Quy trình Khám sức khỏe định kỳ hàng năm</b>
</p>

| STT | Hoạt động trong quy trình | Tác nhân thực hiện | Phân loại | Giải thích |
| :---: | --- | --- | :---: | --- |
| 1 | Khảo sát nhu cầu, dự toán ngân sách khám SK | Phòng Nhân sự (HR) / Ban HSE | **BVA** | Cần thiết để xây dựng kế hoạch phù hợp với quy mô nhân sự, nhưng không trực tiếp tạo giá trị y tế. |
| 2 | Xây dựng danh mục khám định kỳ | HR / Ban HSE | **BVA** | Cần thiết để đảm bảo phạm vi khám đáp ứng quy định pháp luật và đặc thù công việc. |
| 3 | Mời thầu, đánh giá cơ sở y tế | HR / Ban HSE | **BVA** | Là bước kiểm soát cần thiết để chọn được đối tác đủ năng lực. |
| 4 | Ký kết hợp đồng với cơ sở y tế | HR / Ban HSE | **BVA** | Thủ tục pháp lý bắt buộc để triển khai chương trình khám. |
| 5 | Thống nhất lịch khám chi tiết | Bệnh viện / Cơ sở y tế | **BVA** | Cần thiết cho việc điều phối nguồn lực khám. |
| 6 | Thông báo lịch khám đến các đơn vị | HR / Ban HSE | **BVA** | Hoạt động truyền thông nội bộ cần thiết để CBCNV chủ động sắp xếp thời gian. |
| 7 | Đến cơ sở y tế khám theo lịch | CBCNV | **VA** | Bước khởi đầu trực tiếp của quá trình chăm sóc sức khỏe. |
| 8 | Khám lâm sàng (nội, ngoại, mắt...) | Bệnh viện / Cơ sở y tế | **VA** | Tạo giá trị trực tiếp: phát hiện sớm các vấn đề sức khỏe của CBCNV. |
| 9 | Khám cận lâm sàng (xét nghiệm, X-quang) | Bệnh viện / Cơ sở y tế | **VA** | Tạo giá trị trực tiếp: cung cấp dữ liệu cận lâm sàng hỗ trợ chẩn đoán chính xác. |
| 10 | Tổng hợp kết quả, lập hồ sơ sức khỏe | Bệnh viện / Cơ sở y tế | **VA** | Kết quả cuối cùng có giá trị sử dụng trực tiếp cho CBCNV và doanh nghiệp. |
| 11 | Chỉ định khám chuyên sâu bổ sung | Bệnh viện / Cơ sở y tế | **NVA** | Phát sinh ngoài kế hoạch ban đầu do phát hiện bất thường; không tạo thêm giá trị mới, chỉ xử lý ngoại lệ. |
| 12 | Lập báo cáo tổng hợp sức khỏe | Bệnh viện / Cơ sở y tế | **BVA** | Cần thiết để doanh nghiệp theo dõi tình hình sức khỏe tổng thể. |
| 13 | Rà soát, nhắc nhở các trường hợp chưa khám | HR / Ban HSE | **NVA** | Là hoạt động làm lại do tỷ lệ tham gia chưa đạt mục tiêu. |
| 14 | Bàn giao sổ khám cá nhân | HR / Ban HSE | **BVA** | Thủ tục cần thiết nhưng mang tính hành chính. |
| 15 | Lập phương án hỗ trợ điều trị | HR / Ban HSE | **VA** | Tạo giá trị trực tiếp cho CBCNV có vấn đề sức khỏe cần can thiệp. |
| 16 | Xem xét, tham mưu điều chuyển vị trí | Y tế cơ quan / Ban Điều hành | **VA** | Bảo vệ trực tiếp sức khỏe CBCNV khi vị trí công việc hiện tại không còn phù hợp. |
| 17 | Quyết định điều chuyển / Phê duyệt hỗ trợ y tế | Y tế cơ quan / Ban Điều hành | **VA** | Kết quả cuối cùng mang lại giá trị thiết thực, bảo vệ sức khỏe và quyền lợi CBCNV. |

4.6.3.2. Phân tích lãng phí

**Bảng 4.6.2. Phân loại lãng phí - Quy trình Khám sức khỏe định kỳ hàng năm**

| STT | Loại lãng phí | Ví dụ trong quy trình | Hướng khắc phục |
| :---: | --- | --- | --- |
| 1 | **Di chuyển** *(Move)* | CBCNV tại nhà máy/trang trại xa cơ sở y tế phải di chuyển nhiều giờ để khám; phải di chuyển thêm lần nữa nếu được chỉ định khám chuyên sâu bổ sung. | Hợp tác với nhiều cơ sở y tế theo cụm khu vực; bố trí xe đưa đón tập trung theo ca để giảm số lượt di chuyển cá nhân. |
| 2 | **Chờ đợi / Trì hoãn** *(Hold)* | Chờ Bệnh viện tổng hợp kết quả từ hai nhánh song song (khám lâm sàng và cận lâm sàng) trước khi lập hồ sơ; chờ Ban Điều hành phê duyệt phương án hỗ trợ điều trị. | Áp dụng hệ thống quản lý kết quả khám điện tử để hai nhánh cùng cập nhật theo thời gian thực; phân cấp phê duyệt cho các trường hợp hỗ trợ y tế mức độ nhẹ. |
| 3 | **Thừa / Trùng lặp** *(Overdo)* | Gửi thông báo lịch khám qua nhiều kênh trùng lặp mà không có kênh xác nhận tập trung; khám lại các chỉ tiêu cơ bản cho nhân viên vừa khám sức khỏe ở nơi khác trong năm. | Chuẩn hóa một kênh thông báo chính có xác nhận đã đọc; cho phép CBCNV nộp kết quả khám sức khỏe gần nhất (trong 6 tháng) để miễn một số hạng mục trùng lặp. |

4.6.4. Phân tích định lượng

4.6.4.1. Phân tích định lượng về Thời gian (Time Flow Analysis)

Phân tích Thời gian chu kỳ (Cycle Time - CT) dựa trên nhánh rẽ chính của quy trình: "Kết quả sàng lọc bất thường".

•      Nhánh 1 - Không phát hiện bất thường (giả định 85%): Thủ tục tiếp nhận (15 phút) + Khám lâm sàng và cận lâm sàng song song, lấy nhánh dài hơn (25 phút) + Tổng hợp kết quả (10 phút) = 50 phút.

•      Nhánh 2 - Có bất thường (giả định 15%): 50 phút (như Nhánh 1) + Khám chuyên sâu bổ sung (30 phút) = 80 phút.

=> ACT = (0,85 × 50) + (0,15 × 80) = 42,5 + 12 = 54,5 phút/CBCNV.

4.6.4.2. Phân tích định lượng về Chi phí (Cost Flow Analysis)

Ước tính dựa trên đơn giá gói khám: gói cơ bản 350.000 VNĐ/người; khám chuyên sâu bổ sung phát sinh thêm 200.000 VNĐ/người.

•      Chi phí Nhánh 1: C1 = 350.000 VNĐ.

•      Chi phí Nhánh 2: C2 = 350.000 + 200.000 = 550.000 VNĐ.

=> AC = (0,85 × 350.000) + (0,15 × 550.000) = 297.500 + 82.500 = 380.000 VNĐ/người.


<p align="center">
  <b>Bảng 4.6.3. Phân tích định lượng - Quy trình Khám sức khỏe định kỳ hàng năm</b>
</p>

| Nhánh / Kịch bản quy trình | Xác suất | Thời gian chu kỳ (CT) | Chi phí ước tính (VNĐ) |
| --- | :---: | :---: | :---: |
| Không phát hiện bất thường | 85% | 50 phút | 350.000 |
| Có bất thường (khám chuyên sâu bổ sung) | 15% | 80 phút | 550.000 |
| **Trung bình toàn quy trình** | **100%** | **54,5 phút** | **380.000** |

4.6.4.3. Phân tích định lượng về Chất lượng (Quality/Yield Analysis)

Tỷ lệ tham gia khám đúng đợt ước tính đạt 92% so với kế hoạch; 8% còn lại cần sắp xếp lịch khám bổ sung. Tỷ lệ phát hiện bất thường 15% phản ánh hiệu quả sàng lọc sớm nhưng cũng là điểm nghẽn làm tăng CT trung bình. Điểm nghẽn chính: bước tổng hợp kết quả từ hai nhánh khám song song, vì hồ sơ chỉ được lập khi cả hai nhánh đã hoàn tất.

4.6.4.4. Đề xuất cải tiến và nâng cao hiệu suất quy trình

•      Đa dạng hóa khung giờ và địa điểm khám (ca ngoài giờ, khám lưu động) để nâng tỷ lệ tham gia từ 92% lên trên 98%.

•      Số hóa kênh thông báo và xác nhận lịch khám để giảm hoạt động rà soát, nhắc nhở (NVA).

•      Đồng bộ dữ liệu kết quả khám theo thời gian thực giữa hai nhánh song song, ước tính giảm CT trung bình từ 54,5 phút xuống dưới 45 phút/CBCNV.
