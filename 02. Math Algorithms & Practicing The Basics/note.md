- Chủ yếu xem xét Worst Case (đa phần trường hợp Average Case có độ phức tạp thời gian giống Worst Case và trong thực tế không phải lúc nào cũng có thể rơi vào Best Case)

- Cải tiến thuật toán kiểm tra số nguyên tố: mỗi nhân tử tạo nên một số đều nhỏ hơn căn bậc hai của chính nó (nếu cả hai nhân tử đều lớn hơn căn bậc hai thì kết quả của phép nhân sẽ lớn hơn số đó)

- Thông thường Single Loop thường có độ phức tạp thời gian O(n), nhưng nên xem xét kĩ điều kiện thoát, biến đếm tăng bao nhiêu đơn vị sau mỗi lần lặp, code bên trong vòng lặp,... để đưa ra kết luận chính xác

- Cải tiến thuật toán kiểm tra một số có phải lũy thừa của 2 hay không:

* &: Trả về 1 với hai bit 1, 1; các trường hợp còn lại trả về 0
* Một số x là lũy thừa của 2 có biểu diễn dạng nhị phân: (0)...010...(0); số liền trước x chắc chắn sẽ không có biểu diễn dạng nhị phân giống x => Không xảy ra trường hợp 1 & 1 => Kết quả x & (x - 1) nếu x là lũy thừa của 2 sẽ luôn là 0
