# Đề tài: Prediction Mobile
## Thành viên tham gia Project + Công Việc
- Lý Quốc Dũng - 19133015 - 19133015@student.hcmute.edu.vn - EDA + Mô Hình
- Nguyễn Quốc Bảo - 19133002- 19133038@student.hcmute.edu.vn- EDA + Mô Hình
- Đoàn Trần Đăng Khoa - 19133028 - 19133028@student.hcmute.edu.vn - EDA + Mô Hình
- Võ Hoàng Khả Diệu - 19133014 - 19133014@student.hcmute.edu.vn- EDA + Mô Hình + Mối tương quan

# Tổng Quan Đề Tài
- Nguồn: https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification?datasetId=11167
- Các Cột:  
Id: mã của điện thoại;
battery_power: Tổng năng lượng pin có thể lưu trữ;
blue: Có bluetooth hay không;
clock_speed:tốc độ mà bộ vi xử lý thực hiện các lệnh;
dual_sim: có hỗ trợ hai sim hay không;
fc: Độ phân giải camera trước;
four_g: có 4g hay không;
int_memory: dung lượng bộ nhớ trong;
m_dep: độ dày điện thoại;
mobile_wt: độ nặng điện thoại;
n_cores:Số lõi của bộ xử lý
pc: Độ phân giải camera sau;
px_height: chiều cao của độ phân giải màn hình;
px_width: chiều rộng của độ phân giải màn hình;
ram: Dung lượng của Ram;
sc_h: chiều cao màn hình;
sc_w: chiều rộng màn hình;
talk_time: thời gian dài nhất khi sạc điện thoại;
three_g: có 3g hay không;
touch_screen: có màn hình cảm ứng hay không;
wifi: có wifi hay không;
price_range: khoảng giá trị chi phí điện thoại (0,1,2,3)

# Mục tiêu của đề tài:
## Phân tích tập dữ liệu dự đoán giá Mobile:
- Dự đoán để phân loại các điện thoại theo mức giá (0,1,2,3)
- Để xác định tính năng nào hoặc một loạt các tính năng nào là quan trọng nhất để xác định điện thoại đó thuộc về mức giá nào.
##Mô Hình:
- Decision Tree
- linear regression,
- Support vector machine (SVM), 
- K-nearest neighbors 

# Các câu hỏi chính về công nghệ:
- So sánh các mô hình khác nhau
- Lợi ích của việc xác định các tính năng
- Các tính năng ảnh hưởng đến độ chính xác mô hình
- Tìm ra các tính năng có mối tương quan với giá

# Tiếp cận:
- Đối với mỗi phương pháp phân loại: Chia dữ liệu: training set (xây dựng mô hình, 75%), and test set  (đánh giá hiệu suất, 25%)
- So sánh dự đoán của của mô hình với kết quả thực tế


# Các Link:
- Link Video Buổi Họp: https://drive.google.com/file/d/1jHVez2gMj1AHM8s_fXsdlltNalJwSmud/view?usp=sharing
- Link đề tài:https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification?datasetId=11167