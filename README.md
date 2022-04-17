# recommend_system
Hệ thống gợi ý mua hàng trên tiki.vn, sendo.vn

Có 2 kỹ thuật sẽ sử dụng
+ FP-Growth để gợi ý các mặt hàng hay được mua cùng nhau, có thể dùng cho từng category sẽ hiệu quả hơn, ví dụ category điện gia dụng, category mỹ phẩm, sách .. Kỹ thuật này cần phải có các transaction chứa các món hàng mua cùng nhau mới thực hiện được

+ SVD : Kỹ thuật collaborative filtering sử dụng factorization matrix, kỹ thuật này dùng rất tốt khi tỉ lệ rating nhiều, data từ tiki bị lệch nhiều về rating 5 sao, khiến độ dự đoán này có thể chỉ rơi vào các sách top rating 5, ngoài ra với lượng thông tin users, items khổng lồ => việc training sẽ lâu vì giải quyết bài toán tối ưu gradient decent vốn tốn nhiều tài nguyên để hoàn thành.


Author: Quan AI
