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
 <img width="942" height="714" alt="ngoinha" src="https://github.com/user-attachments/assets/c7f4440c-c2cc-4942-9f49-81d75bf5effb" />
<p align="center">Hình 1.2 Kiến trúc quy trình nghiệp vụ Vinamilk</p>
- Hệ thống vận hành của Vinamilk được tổng hợp và trực quan hóa thông qua mô hình “Ngôi nhà kiến trúc quy trình”. Mô hình giúp phân loại các quy trình theo vai trò và mức độ đóng góp vào hoạt động chung của doanh nghiệp, đồng thời thể hiện mối liên hệ giữa các nhóm quy trình. Kiến trúc quy trình được chia thành ba tầng chính gồm Quản lý (Management processes), Cốt lõi (Core processes) và Hỗ trợ (Support processes).

- Tầng Quản lý (Management processes) được thể hiện ở phần mái nhà, bao gồm các quy trình có chức năng định hướng, kiểm soát và đánh giá hoạt động của doanh nghiệp. Nhóm này gồm ba quy trình. Thứ nhất, Quy trình quản lý và giám sát an toàn lao động tập trung vào việc kiểm soát các vấn đề liên quan đến an toàn trong môi trường làm việc, góp phần hạn chế rủi ro trong quá trình vận hành và sản xuất. Thứ hai, Quy trình phê duyệt kế hoạch tuyển dụng nhân sự hàng năm nhằm xác định nhu cầu nhân sự và thực hiện việc phê duyệt kế hoạch tuyển dụng phù hợp với hoạt động của doanh nghiệp. Thứ ba, Quy trình đánh giá hiệu suất Nhà Phân Phối định kỳ được sử dụng để theo dõi và đánh giá hiệu quả hoạt động của các nhà phân phối, từ đó hỗ trợ công tác quản lý và kiểm soát hệ thống phân phối.
  
- Tầng Cốt lõi (Core processes) là phần thân nhà, bao gồm các quy trình trực tiếp tạo ra giá trị cho khách hàng và gắn liền với hoạt động kinh doanh chính của Vinamilk. Trong nhóm này, Quy trình xử lý đơn hàng cho Khách hàng doanh nghiệp (B2B) thực hiện việc tiếp nhận và xử lý các đơn hàng từ khách hàng doanh nghiệp. Bên cạnh đó, Quy trình xử lý đơn hàng qua Website e-Commerce quản lý các đơn hàng phát sinh từ kênh thương mại điện tử, giúp doanh nghiệp phục vụ khách hàng thông qua kênh bán hàng trực tuyến. Quy trình tài trợ và cấp phát sữa cho chương trình Sữa Học Đường liên quan đến việc thực hiện hoạt động tài trợ và cấp phát sản phẩm cho chương trình. Cuối cùng, Quy trình thu mua sữa tươi từ Hộ Nông Dân Liên kết đảm bảo việc tiếp nhận và thu mua nguồn nguyên liệu sữa tươi từ các hộ nông dân trong chuỗi liên kết. Đây là nhóm quy trình có vai trò quan trọng vì trực tiếp liên quan đến hoạt động cung ứng, bán hàng và tạo ra giá trị cho doanh nghiệp cũng như khách hàng.
  
- Tầng Hỗ trợ (Support processes) được thể hiện ở phần nền móng của ngôi nhà, có chức năng cung cấp nguồn lực và các dịch vụ cần thiết để các quy trình quản lý và cốt lõi có thể vận hành ổn định. Quy trình quản lý và thu hồi tài sản khi nhân viên nghỉ việc đảm bảo tài sản được kiểm kê, bàn giao và thu hồi khi có sự thay đổi nhân sự. Quy trình xử lý và thanh toán chi phí khách sạn/vé máy bay hỗ trợ việc xử lý các khoản chi phí phát sinh liên quan đến hoạt động công tác của nhân viên. Ngoài ra, Quy trình khám sức khỏe định kỳ hàng năm hỗ trợ công tác chăm sóc và theo dõi sức khỏe người lao động.
Nhìn chung, mô hình “Ngôi nhà kiến trúc quy trình” cho thấy mỗi nhóm quy trình đảm nhận một vai trò khác nhau nhưng có mối liên hệ chặt chẽ trong hệ thống vận hành. Quy trình Quản lý đóng vai trò định hướng và kiểm soát, quy trình Cốt lõi trực tiếp tạo ra giá trị và thực hiện hoạt động kinh doanh, trong khi quy trình Hỗ trợ cung cấp nguồn lực và dịch vụ cần thiết cho toàn hệ thống. Cách phân loại này giúp doanh nghiệp có cái nhìn tổng thể về hệ thống quy trình, đồng thời tạo cơ sở cho việc quản lý, đánh giá và cải tiến quy trình một cách có hệ thống.

    - 2.2. Danh mục nhóm quy trình nghiệp vụ
        - 2.2.1. Nhóm quy trình Quản lý (Management Processes)
          
         Nhóm quy trình Quản lý (Management Processes) là nhóm các quy trình có vai trò định hướng, kiểm soát và theo dõi các hoạt động quan trọng trong doanh nghiệp. Nếu các quy trình Cốt lõi tập trung trực tiếp vào việc tạo ra sản phẩm, cung cấp dịch vụ và phục vụ khách hàng, thì các quy trình Quản lý giúp doanh nghiệp đảm bảo những hoạt động đó được thực hiện trong điều kiện phù hợp, có kiểm soát và bám sát mục tiêu đã đề ra.
Trong mô hình “Ngôi nhà kiến trúc quy trình” của Vinamilk, nhóm Quản lý được đặt ở phần mái nhà, thể hiện vai trò quản lý và giám sát đối với toàn bộ hệ thống. Trong phạm vi nghiên cứu, nhóm này gồm ba quy trình: Quy trình quản lý và giám sát an toàn lao động; Quy trình phê duyệt kế hoạch tuyển dụng nhân sự hàng năm; và Quy trình đánh giá hiệu suất Nhà Phân Phối định kỳ. Ba quy trình tuy thuộc các lĩnh vực khác nhau nhưng cùng hướng đến mục tiêu duy trì sự ổn định, kiểm soát rủi ro và nâng cao hiệu quả hoạt động của doanh nghiệp.

            - 2.1.1.1 Quy trình quản lý và giám sát an toàn lao động
                - 2.1.1.1.1 Mô tả quy trình
                   
                  Quy trình quản lý và giám sát an toàn lao động được thực hiện nhằm đảm bảo môi trường làm việc an toàn cho người lao động tại các nhà máy, trang trại và các cơ sở vận hành của Vinamilk. Do đặc thù hoạt động liên quan đến sản xuất, kho vận và chăn nuôi, việc kiểm soát các nguy cơ mất an toàn cần được thực hiện thường xuyên thay vì chỉ xử lý khi sự cố đã xảy ra. Vì vậy, quy trình tập trung vào việc thiết lập các yêu cầu an toàn, đào tạo người lao động, kiểm tra thực tế, ghi nhận rủi ro và thực hiện các biện pháp khắc phục.
                  
                  Quy trình được bắt đầu bằng việc Ban An toàn - Sức khỏe - Môi trường (HSE) xây dựng hoặc cập nhật kế hoạch và các yêu cầu về an toàn lao động. Các tiêu chuẩn được phổ biến đến những đơn vị có liên quan để làm cơ sở thực hiện và kiểm tra trong quá trình vận hành.  

                    Tiếp theo, người lao động được đào tạo và phổ biến các quy định về an toàn lao động. Hoạt động này đặc biệt quan trọng đối với nhân viên mới, đồng thời cần được thực hiện định kỳ đối với nhân viên đang làm việc nhằm duy trì ý thức tuân thủ và cập nhật các yêu cầu mới.  

                    Sau khi các yêu cầu được phổ biến, bộ phận HSE phối hợp với quản lý tại các đơn vị tiến hành kiểm tra và giám sát thực tế. Việc kiểm tra có thể được thực hiện theo kế hoạch hoặc đột xuất tại các khu vực như nhà máy, kho vận, khu vực sản xuất và trang trại. Trong quá trình kiểm tra, các vấn đề liên quan đến điều kiện làm việc, trang thiết bị bảo hộ, máy móc và các nguy cơ mất an toàn được ghi nhận.  

                    Khi phát hiện rủi ro hoặc hành vi chưa tuân thủ, bộ phận phụ trách tiến hành đánh giá mức độ ảnh hưởng và yêu cầu đơn vị liên quan thực hiện biện pháp khắc phục. Đối với những vấn đề nghiêm trọng hoặc sự cố xảy ra trong thực tế, việc điều tra nguyên nhân và báo cáo cấp quản lý được thực hiện để xác định biện pháp xử lý phù hợp, đồng thời hạn chế khả năng sự cố tương tự tái diễn.  

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
