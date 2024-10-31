# Đề tài: Nghiên cứu các yếu tố ảnh hưởng đến quyết định chấp nhận Upsell của từng phân khúc khách hàng trong lĩnh vực khách sạn

## Tổng Quan
- **Môn học**: Phân tích dữ liệu trong kinh doanh
- **Tên đề tài**: Nghiên cứu các yếu tố ảnh hưởng đến quyết định chấp nhận Upsell của từng phân khúc khách hàng trong lĩnh vực khách sạn
- **Giảng viên hướng dẫn**: Tiến sĩ Hồ Trung Thành
- **Thành viên nhóm 3**: 
  - Trần Thị Minh Hân
  - Lê Bảo Minh
  - Phùng Nguyễn Đăng Khoa
  - Nguyễn Phương Oanh
  - Phạm Thanh Thảo

### Mục tiêu dự án
Nghiên cứu này nhằm phân tích và xác định các yếu tố ảnh hưởng đến quyết định chấp nhận upsell của từng phân khúc khách hàng trong lĩnh vực khách sạn, từ đó đề xuất các chiến lược upsell hiệu quả để tối ưu hóa doanh thu và trải nghiệm khách hàng.


## Nội dung file
File ZIP nộp bao gồm các tài liệu sau đây:

1. ́**Datasets**:
    - `hotel_bookings.csv`: Đây là bộ dữ liệu gốc chứa các thông tin về đặt phòng khách sạn, bao gồm các biến như giá trị phòng, loại khách hàng, thời gian lưu trú, và trạng thái chấp nhận hoặc từ chối Upsell.
    - `hotel_bookings_clean.csv`: Bộ dữ liệu đã được làm sạch từ hotel_bookings.csv, đã qua các bước xử lý dữ liệu và chuẩn bị để sử dụng cho việc phân tích và xây dựng mô hình.
    - Đường dẫn Kaggle: https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand. Dữ liệu trong dự án này được lấy từ bài báo Hotel Booking Demand Datasets, do Nuno Antonio, Ana Almeida, và Luis Nunes thực hiện và công bố trên tạp chí Data in Brief, Tập 22, xuất bản vào tháng 2 năm 2019.

        
2.  **Power BI**:
     - `Customer Segment.pbix`: File Power BI này chứa bảng điều khiển tổng quan về khách hàng, bao gồm các phân tích về hành vi và đặc điểm của từng phân khúc khách hàng.
     - `ADR Segment & Upsell Analysis.pbix`: File Power BI  phân tích chi tiết về các phân  ADR (Average Daily Rate) và khả năng chấp nhận Upsell của từng phân khúc khách hàng. Các biểu đồ trực quan giúp hiểu rõ hơn về sự khác biệt giữa các phân khúc.
     
3. **Source Code**:
   - Thư mục `Source code` chứa các file mã nguồn Python để xử lý và phân tích dữ liệu. 
   - Các file chính bao gồm:
     - `CleanData.ipynb`: Chứa mã nguồn làm sạch dữ liệu.
     - `Decision Tree.ipynb`: Xây dựng và huấn luyện mô hình cây quyết định (Decision Tree).
     - `EDA.ipynb`: Thực hiện phân tích dữ liệu khám phá (Exploratory Data Analysis - EDA) để tìm hiểu các đặc điểm nổi bật trong dữ liệu.
     - `Implement_TT.ipynb`: Xử lý và triển khai mô hình thử nghiệm, bao gồm các thử nghiệm và tối ưu hóa mô hình.
     - `Logistics Regression.py`: Mã nguồn thực hiện Logistic Regression để phân tích các yếu tố ảnh hưởng đến quyết định chấp nhận Upsell.
     - `transfer_and_split.ipynb`: Thực hiện việc chia tách và chuyển đổi dữ liệu, chuẩn bị cho các bước phân tích tiếp theo.

4. **File Turnitin**:
   - `Checked Turnitin file.pdf`: Báo cáo PDF đã qua kiểm tra Turnitin, đảm bảo tỷ lệ trùng lặp dưới 30% và không có dấu hiệu sử dụng AI để viết nội dung.

5. **Báo cáo dự án**:
   - Thư mục `Report` chứa các phiên bản của báo cáo dự án:
     - `241MI1702_Group3_FinalProject.docx:`: Báo cáo chi tiết của nhóm ở định dạng Word.
     - `241MI1702_Group3_FinalProject.pdf`: Báo cáo đã chuyển đổi sang định dạng PDF.
     - **Nội dung chính báo cáo** bao gồm:
       - Tổng quan về lý 
       - Chuẩn bị dữ 
       - Kết quả thực nghiệm và đánh giá
       - Trực quan hóa và phân tích kết quả

7. **README file**:
   - File này (README.md) giúp hiểu rõ cấu trúc và nội dung của dự án.


## Người liên hệ
- Trưởng nhóm: hanttm21411c@st.uel.edu.vn



