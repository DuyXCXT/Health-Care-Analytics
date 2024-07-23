**Thông tin bộ dữ liệu**
• Tên bộ dữ liệu: Hospital Inpatient Discharges (SPARCS)
• Nguồn: https://health.data.ny.gov/
• Kích thước: 519 MB
• Định dạng file: csv
• Gồm: 6 file csv
• Thời gian: 2017 - 2018
Bộ dữ liệu này chứa hồ sơ xác định bệnh nhân nội trú của Hệ thống hợp tác nghiên cứu 
và lập kế hoạch toàn tiểu bang (SPARCS) chứa thông tin chi tiết về mức độ xuất
viện về đặc điểm, chẩn đoán, phương pháp điều trị trong bệnh viện và sau khi xuất viện, 
dịch vụ và chi phí của bệnh nhân. Tệp dữ liệu này chứa chi tiết tới mức bản ghi cơ bản 
cho lần nhập xuất viện, phương thức thanh toán,...

**Thông tin chi tiết từng bảng dữ liệu của bộ dữ liệu:**

Bảng Hospital: Chứa thông tin về các bệnh viện
• Permanent Facility Id: Mã bệnh viện
• Operating Certificate Number: số chứng chỉ hoạt động
• Facility Name: Tên Bệnh viện
• Hospital County: Quận bệnh viện
• Hospital Service Area: Khu vực Bệnh viện (tương đương State)

Bảng Patient: chứa các thông tin về bệnh nhân
• Patient Id: Mã bệnh nhân
• Permanent Facility Id : Mã bệnh viện
• Age Group : Nhóm tuổi
• Zip Code - 3 digits : Mã zip
• Gender : Giới tính
• Race : Chủng tộc
• Ethinicity: Sắc tộc
• Length of Stay: Thời gian lưu trú
• Type of Admission: Hình thức nhập viện
• Patient Disposition: Hình thức điều trị sau xuất viện
• CCS Diagnosis Code: Mã chuẩn đoán

Bảng APR DRG Info
• APR DRG Code: Mã bệnh
• APR DRG Description: Tên bệnh
• APR MDC Code: Mã nhóm bệnh
• APR MDC Description: Tên nhóm bệnh
• APR Severity of Illness Code: Mã mức độ nghiêm trọng của bệnh
• APR Severity of Illness Description: Mô tả mức độ nghiêm trọng của bệnh
• APR Risk of Mortality: Mức độ dẫn đến tử vong
• APR Medical Surgical Description: Chỉ định điều trị

Bảng CCS Info
• CCS Diagnosis Code: Mã chuẩn đoán
• CCS Diagnosis Description: Mô tả chuẩn đoán
• CCS Procedure Code: Mã thủ tục
• CCS Procedure Description: Mô tả thủ tục
• APR DRG Code: Mã bệnh

Bảng Payment
• Patient Id: Mã bệnh nhân
• Payment Typology: Loại hình thanh toán
• Emergency Department Indicator: Chỉ số khoa cấp cứu
• Total Charges: Tổng phí phải trả
• Total Costs: Tổng chi phí điều trị

Bảng Payment Type
• PaymentTypeID : Mã hình thức thanh toán
• Payment Typologogy: Các hình thức thanh toán
• Payment Typology Description: Mô tả loại hình thức thanh toán

**Yêu cầu phân tích Những người điều hành các cơ sở bệnh viện cần những báo cáo và
phân tích theo những khía cạnh sau:**
• Báo cáo tổng quan về tình hình các bệnh viện theo địa điểm (bang, khu vực), theo
thời gian, theo hình thức điều trị, theo độ tuổi, theo nhóm bệnh.
• Báo cáo về số lượng bệnh nhận theo địa điểm (bang, khu vực), theo thời gian, theo
hình thức điều trị, theo độ tuổi, theo nhóm bệnh, theo giới tính.
• Báo cáo về chi phí chi của bệnh nhân theo địa điểm (bang, khu vực), theo thời gian,
theo hình thức điều trị, theo độ tuổi, theo nhóm bệnh.

Chủ điểm phân tích:
Bệnh nhân
• Chỉ số : Số lượng.
• Khía cạnh: Tuổi, giới tính, bệnh viện, thời gian, loại bệnh, số ngày nằm viện, hình
thức nhập viện.

Chi phí
• Chỉ số : Tổng chi phí ,Tổng phải thanh toán.
• Khía cạnh: Tuổi, bệnh viện, thời gian, loại bệnh, hình thức thanh toán.
