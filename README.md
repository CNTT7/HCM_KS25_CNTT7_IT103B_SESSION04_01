Phân tích lỗi & Lập bảng Test Cases (trình bày trong README.md):
Đọc hiểu mã nguồn, xác định dòng lệnh sai logic và phân tích nguyên nhân kỹ thuật dẫn đến sự cố nghiệp vụ.
- đề thiếu ghi chú đọc hơi không hiểu, đề sai ở chỗ vòng lặp ở phần cupIndex = 1 và giảm giá cho member
Lập bảng 02 Test Cases đối chứng gồm các cột: Trường hợp kiểm thử, Dữ liệu đầu vào, Kết quả sai thực tế, Kết quả đúng mong đợi.

Trường hợp kiểm thử: đề cho 
Dữ liệu đầu vào: orderQuantity = 3;toppingsPerCup = 2;drinkSize = "M";
Kết quả sai thực tế: 87210 
Kết quả đúng mong đợi:  137700 

Trường hợp kiểm thử: đề cho 
Dữ liệu đầu vào: orderQuantity = 10;toppingsPerCup = 2;drinkSize = "M";
Kết quả sai thực tế: 281173.99554900004
Kết quả đúng mong đợi: 459000 