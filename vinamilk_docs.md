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

# MỤC LỤC

- **Chương 1. GIỚI THIỆU CÔNG TY VINAMILK**
    - 1.1. Tổng quan về Vinamilk
        - 1.1.1. Lịch sử hình thành và phát triển
        - 1.1.2. Tầm nhìn, sứ mệnh, giá trị cốt lõi
        - 1.1.3. Quy mô và lĩnh vực kinh doanh
        - 1.1.4. Thành tựu nổi bật
    - 1.2. Cơ cấu tổ chức và hoạt động kinh doanh
        - 1.2.1. Cơ cấu tổ chức bộ máy quản lý
        - 1.2.2. Chiến lược Chuyển đổi số tại Vinamilk

- **Chương 2. HỆ THỐNG QUY TRÌNH NGHIỆP VỤ VINAMILK**
    - 2.1. Kiến trúc quy trình nghiệp vụ tổng thể (Process Architecture)
    - 2.2. Danh mục nhóm quy trình nghiệp vụ
        - 2.2.1. Nhóm quy trình Quản lý (Management Processes)
            - 2.1.1.1 Quy trình quản lý và giám sát an toàn lao động
                - 2.1.1.1.1 Mô tả quy trình
                - 2.1.1.1.2 Các tác nhân tham gia quy trình
                - 2.1.1.1.3 Khách hàng của quy trình
                - 2.1.1.1.4 Những kết quả có thể đạt được của quy trình
            - 2.1.1.2 Quy trình phê duyệt kế hoạch tuyển dụng nhân sự hàng năm
                - 2.1.1.2.1 Mô tả quy trình
                - 2.1.1.2.2 Các tác nhân tham gia quy trình
                - 2.1.1.2.3 Khách hàng của quy trình
                - 2.1.1.2.4 Những kết quả có thể đạt được của quy trình
            - 2.1.1.3 Quy trình đánh giá hiệu suất Nhà Phân Phối định kỳ
                - 2.1.1.3.1 Mô tả quy trình
                - 2.1.1.3.2 Các tác nhân tham gia quy trình
                - 2.1.1.3.3 Khách hàng của quy trình
                - 2.1.1.3.4 Những kết quả có thể đạt được của quy trình
            - 2.1.1.4 Nhận xét chung
        - 2.2.2. Nhóm quy trình Cốt lõi (Core Processes)
            - 2.2.2.1. Quy trình thu mua sữa tươi từ Hộ Nông Dân Liên kết
                - 2.2.2.1.1. Mô tả quy trình
                - 2.2.2.1.2. Các tác nhân tham gia quy trình
                - 2.2.2.1.3. Khách hàng của quy trình
                - 2.2.2.1.4. Những kết quả có thể đạt được của quy trình
            - 2.2.2.2. Quy trình xử lý đơn hàng cho Khách hàng doanh nghiệp (B2B)
                - 2.2.2.2.1. Mô tả quy trình
                - 2.2.2.2.2. Các tác nhân tham gia quy trình
                - 2.2.2.2.3. Khách hàng của quy trình
                - 2.2.2.2.4. Những kết quả có thể đạt được của quy trình
            - 2.2.2.3. Quy trình xử lý đơn hàng qua Website e-Commerce
                - 2.2.2.3.1. Mô tả quy trình
                - 2.2.2.3.2. Các tác nhân tham gia quy trình
                - 2.2.2.3.3. Khách hàng của quy trình
                - 2.2.2.3.4. Những kết quả có thể đạt được của quy trình
            - 2.2.2.4. Quy trình tài trợ và cấp phát sữa cho chương trình Sữa Học Đường
                - 2.2.2.4.1. Mô tả quy trình
                - 2.2.2.4.2. Các tác nhân tham gia quy trình
                - 2.2.2.4.3. Khách hàng của quy trình
                - 2.2.2.4.4. Những kết quả có thể đạt được của quy trình
            - 2.2.2.5. Nhận xét chung
        - 2.2.3. Nhóm quy trình Hỗ trợ (Support Processes)
            - 2.2.3.1. Quy trình quản lý và thu hồi tài sản khi nhân viên nghỉ việc
                - 2.2.3.1.1. Mô tả quy trình
                - 2.2.3.1.2. Các tác nhân tham gia quy trình
                - 2.2.3.1.3. Khách hàng của quy trình
                - 2.2.3.1.4. Những kết quả có thể đạt được của quy trình
            - 2.2.3.2. Quy trình xử lý và thanh toán chi phí khách sạn / vé máy bay
                - 2.2.3.2.1. Mô tả quy trình
                - 2.2.3.2.2. Các tác nhân tham gia quy trình
                - 2.2.3.2.3. Khách hàng của quy trình
                - 2.2.3.2.4. Những kết quả có thể đạt được của quy trình
            - 2.2.3.3. Quy trình khám sức khỏe định kỳ hàng năm
                - 2.2.3.3.1. Mô tả quy trình
                - 2.2.3.3.2. Các tác nhân tham gia quy trình
                - 2.2.3.3.3. Khách hàng của quy trình
                - 2.2.3.3.4. Những kết quả có thể đạt được của quy trình
            - 2.2.3.4. Nhận xét chung

- **CHƯƠNG 3: PHƯƠNG PHÁP THỰC HIỆN**
    - 3.1. Phương pháp dựa trên bằng chứng (Evidence-based)
        - 3.1.1. Sơ đồ tổ chức và phân quyền chức năng
        - 3.1.2. Mô tả tài liệu quy trình hiện có
        - 3.1.3. Kế hoạch làm việc của 6 quy trình trọng yếu
        - 3.1.4. Thuật ngữ, sổ tay và biểu mẫu quản trị chuẩn hóa
    - 3.2. Phương pháp phỏng vấn
        - 3.2.1. Danh mục đối tượng phỏng vấn
        - 3.2.2. Bộ câu hỏi định lượng (20 câu)

- **CHƯƠNG 4. MÔ HÌNH HÓA CHI TIẾT CÁC QUY TRÌNH BẰNG BPMN VÀ PHÂN TÍCH CÁC QUY TRÌNH**
    - 4.1. Quy trình Quản lý và Giám sát An toàn Lao động
        - 4.1.1. Mô tả quy trình, tác nhân và khách hàng
        - 4.1.2. Mô hình hóa quy trình bằng BPMN
        - 4.1.3. Phân tích định tính
        - 4.1.4. Phân tích định lượng
    - 4.2. Quy trình Phê duyệt Kế hoạch Tuyển dụng Nhân sự
        - 4.2.1. Mô tả quy trình, tác nhân và khách hàng
        - 4.2.2. Mô hình hóa quy trình bằng BPMN
        - 4.2.3. Phân tích định tính
        - 4.2.4. Phân tích định lượng
    - 4.3. Quy trình Thu mua Sữa tươi từ Hộ Nông Dân Liên kết
        - 4.3.1. Mô tả quy trình, tác nhân và khách hàng
        - 4.3.2. Mô hình hóa quy trình bằng BPMN
        - 4.3.3. Phân tích định tính
        - 4.3.4. Phân tích định lượng
    - 4.4. Quy trình Tài trợ và Cấp phát Sữa cho Chương trình Sữa Học Đường
        - 4.4.1. Mô tả quy trình, tác nhân và khách hàng
        - 4.4.2. Mô hình hóa quy trình bằng BPMN
        - 4.4.3. Phân tích định tính
        - 4.4.4. Phân tích định lượng
    - 4.5. Quy trình Thu hồi Tài sản khi Nhân viên Nghỉ việc
        - 4.5.1. Mô tả quy trình, tác nhân và khách hàng
        - 4.5.2. Mô hình hóa quy trình bằng BPMN
        - 4.5.3. Phân tích định tính
        - 4.5.4. Phân tích định lượng
    - 4.6. Quy trình Khám sức khỏe định kỳ hàng năm
        - 4.6.1. Mô tả quy trình, tác nhân và khách hàng
        - 4.6.2. Mô hình hóa quy trình bằng BPMN
        - 4.6.3. Phân tích định tính
        - 4.6.4. Phân tích định lượng

- **CHƯƠNG 5. KẾT LUẬN VÀ ĐỀ XUẤT CẢI TIẾN**
    - 5.1. Kết quả đạt được của đề tài
        - 5.1.1. Nền tảng và phương pháp
        - 5.1.2. Lập bản đồ và kiến trúc quy trình (Process Architecture)
        - 5.1.3. Phân tích chuyên sâu và bóc tách dữ liệu
    - 5.2. Hạn chế của đề tài
    - 5.3. Đề xuất cải tiến tổng thể & Hướng phát triển
        - 5.3.1. Đề xuất cải tiến tổng thể hệ thống quy trình (To-Be Roadmap)
            - 5.3.1.1. Số hóa, tự động hóa và tích hợp dữ liệu liền mạch (Loại trừ lãng phí Move & Overdo)
            - 5.3.1.2. Tái cấu trúc ma trận thẩm quyền (Loại trừ lãng phí Hold)
            - 5.3.1.3. Tối ưu hóa điều phối chuỗi cung ứng và hiện trường (Loại trừ lãng phí Move & Yield)
        - 5.3.2. Hướng phát triển tiếp theo của đề tài
