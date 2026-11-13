# Cơ chế In-Context Learning trong Phân loại Review Khách hàng
## Phần 1:
In-Context Learning là việc AI hiểu và thực hiện nhiệm vụ dựa vào các ví dụ được cung cấp  trong prompt, mà không cần huấn luyện.
Nó sẽ lưu các thông tin cần học vào bộ nhớ tạm thời và học ngay tại thời điểm đó.
Chỉ có thể áp dụng tại cuộc trò chuyện đó không thể duy trì để sử dụng cho các cuộc trò chuyện khác.

## Phần 2:
Bạn là một chuyên gia phân tích cảm xúc khách hàng. Nhiệm vụ của bạn là đọc các đánh giá của khách hàng và phân loại chính xác xem đánh giá đó là mỉa mai/khen đều, chú ý đến ba yếu tố cốt lõi: Nhiệt độ thiết bị, Pin, và Thời gian giao hàng.
Ví dụ 1:
Input: "Mua con laptop về không cần mua thêm lò sưởi mùa đông nữa, mở máy lên 10 phút là ấm tay ngay."
Output: Đánh giá mỉa mai về Nhiệt độ thiết bị.
Ví dụ 2:
Input: "Điện thoại pin trâu kinh, sáng rút sạc 100% đến trưa chưa dùng gì đã sập nguồn. Đỡ tốn thời gian bấm điện thoại hại mắt."
Output: Đánh giá mỉa mai, khen đểu về Pin.
Ví dụ 3:
Input: "Đúng là dịch vụ giao hàng thần tốc, đặt hàng từ đầu tháng mà sang tận giữa tháng sau mới nhận được."
Output: Đánh giá mỉa mai về Thời gian giao hàng.