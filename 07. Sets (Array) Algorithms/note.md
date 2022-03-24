- Set là một Collection của Value (Object, Number) mà chính nó tạo nên một thực thể

- Cartesian Product: Product của 2 Set X và Y chứa tất cả các cặp (x, y) theo thứ tự, mà trong đó x thuộc Set X, y thuộc Set Y

- Độ phức tạp thời gian O(n^x) (giả sử n là độ dài của Set có số phần tử lớn nhất và x là số Set)
- Độ phức tạp không gian O(n^x) (giả sử n là độ dài của Set có số phần tử lớn nhất và x là số Set)

- Permutation (Hoán vị): Một sự kết hợp có thứ tự của các giá trị

- Hoán vị, không lặp lại phần tử: Độ phức tạp thời gian O(n!) (số hoán vị) (O(n!) tệ hơn O(2^n))
- Hoán vị, lặp lại phần từ: Độ phức tạp thời gian O(n^r) (số tổ hợp) (n là số phần tử, r là độ dài tổ hợp)
=> Tìm độ phức tạp thời gian dựa trên công thức tính số hoán vị và tổ hợp