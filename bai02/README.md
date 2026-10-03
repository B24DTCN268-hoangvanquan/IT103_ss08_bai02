Phân tích lỗi :
Lỗi 1: Dùng .pop() lấy nhầm xe cuối mảng $\rightarrow$ Sửa thành .shift() để lấy xe đầu hàng (FIFO).
Lỗi 2: Vòng lặp i <= length duyệt thừa 1 lần $\rightarrow$ Sửa thành i < length để hết lỗi undefined.