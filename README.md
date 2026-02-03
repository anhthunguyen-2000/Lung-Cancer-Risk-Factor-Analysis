# Lung Cancer Risk Factor Analysis  
Tools: Power BI  
Objective: Trực quan hóa dữ liệu để phân tích các yếu tố nguy cơ liên quan đến ung thư phổi, bao gồm lối sống, triệu chứng, bệnh nền và thông tin nhân khẩu học.

---

## 1. Giới thiệu dự án  
Ung thư phổi là một trong những căn bệnh có tỷ lệ tử vong cao. Việc phân tích các yếu tố nguy cơ giúp nhận diện các dấu hiệu quan trọng, hỗ trợ tầm soát sớm và đưa ra các biện pháp phòng ngừa hiệu quả.

Dự án này sử dụng Power BI để:
- Làm sạch dữ liệu  
- Trực quan hóa các yếu tố nguy cơ  
- Khám phá mối quan hệ giữa triệu chứng, thói quen và mức độ nguy cơ  
- Trình bày các insight theo từng nhóm yếu tố

---

## 2. Dataset  
<img width="503" height="409" alt="image" src="https://github.com/user-attachments/assets/876cd289-8f68-4c7e-a5c4-016d5e01c2fa" />
<img width="506" height="411" alt="image" src="https://github.com/user-attachments/assets/c3dc5858-58e6-4509-9594-563edcc5fa6d" />

---

## 3. Tiền xử lý dữ liệu (Data Cleaning trong Power BI)

Các thao tác chính trong Power Query:
- Dữ liệu bao gồm các thang đo khác nhau cho từng biến: thang đo 1-7, thang đo 1-8, thang đo 1-9 → Chuẩn hóa tất cả các biến liên quan đến sức khỏe về thang đo 0-1  
- Chuẩn hóa định dạng dữ liệu  
- Kiểm tra dữ liệu thiếu hoặc bất thường  
- Tạo lại cấu trúc bảng theo nhóm biến (Lifestyle, Symptoms, Genetic & Biological, General Health Symptoms)  
- Bổ sung cột phân loại mức độ nguy cơ (Risk Level) theo dữ liệu mẫu  

---

## 4. Dashboard trong Power BI  

Dashboard được chia thành nhiều phần:

### 4.1. Tổng quan dữ liệu  
- Tỷ lệ mắc ung thư phổi theo giới tính  
- Phân bố độ tuổi  
- Phân bổ theo mức độ  

### 4.2. Phân tích theo nhóm yếu tố  
- Lifestyle vs Lung Cancer  
- Symptoms vs Lung Cancer  
- Genetic & Biological
- General Health Symptoms

### 4.3. Phân tích triệu chứng  
- Tần suất xuất hiện các triệu chứng  
- Số triệu chứng xuất hiện theo nhóm nguy cơ  
- Mối liên hệ giữa triệu chứng và kết quả Lung Cancer  

### 4.4. Correlation View  
- Biểu đồ tương quan giữa các yếu tố nguy cơ  
- Nhóm yếu tố ảnh hưởng mạnh nhất

---

## 5. Kết quả chính (Key Findings)

### 5.1. Nhóm yếu tố nguy cơ mạnh nhất  
Dựa trên biểu đồ tương quan và mức độ xuất hiện trong nhóm Lung Cancer = Yes:

1. Smoking  
2. Chronic Disease  
3. Wheezing  
4. Shortness of breath  
5. Chest pain  

### 5.2. Nhân khẩu học  
- Nam giới có tỷ lệ nguy cơ cao hơn nữ  
- Nhóm 31–45 tuổi có tỷ lệ mắc cao nhất  

### 5.3. Lối sống  
- Smoking ảnh hưởng mạnh nhất  
- Peer pressure có tác động gián tiếp lên tỷ lệ hút thuốc  
- Alcohol có tác động nhưng yếu hơn các yếu tố khác  

### 5.4. Nhóm triệu chứng  
Những triệu chứng mang tính cảnh báo mạnh:
- Khó thở  
- Đau ngực  
- Ho kéo dài  
- Thở khò khè  

Tổ hợp “khó thở + đau ngực” xuất hiện nhiều ở nhóm nguy cơ cao.

---

## 6. Kết luận  
Kết quả phân tích cho thấy ung thư phổi bị ảnh hưởng bởi:
- Lối sống (đặc biệt là hút thuốc)  
- Các triệu chứng hô hấp  
- Bệnh nền hô hấp hoặc mãn tính  
- Tuổi và giới tính  

Smoking là yếu tố nguy cơ chính và có sức ảnh hưởng lớn nhất.

---

## 7. Khuyến nghị  

### Cho cộng đồng  
- Giảm hoặc loại bỏ hút thuốc  
- Chủ động khám khi xuất hiện triệu chứng kéo dài  
- Chú ý nhóm người >45 tuổi hoặc có bệnh nền  

---

## 8. File đính kèm  
- lung_cancer_dashboard.pbix   
- README.md  

---

## 9. Kỹ năng sử dụng  
- Power BI Data Cleaning (Power Query)  
- Data Visualization  
- Dashboard Design  
- Phân tích tương quan  
- Diễn giải insight  
- Dựng báo cáo storytelling  

