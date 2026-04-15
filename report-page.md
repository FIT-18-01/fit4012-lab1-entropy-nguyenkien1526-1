# Report 1 Page – FIT4012 Lab 1

## 1. Mục tiêu
Tìm hiểu cách tính entropy của chuỗi ký tự, tính độ dư thừa thông tin và cài đặt thuật toán tìm nghịch đảo modulo bằng Euclid mở rộng.

## 2. Cách làm
- Đọc hiểu chương trình entropy mẫu.
- Bổ sung hàm tính redundancy.
- Hoàn thiện hàm mod_inverse().
- Chạy thử trên nhiều test case.

## 3. Kết quả chính
### 3.1 Entropy và redundancy
| Input | Entropy | Redundancy | Nhận xét |
|---|---:|---:|---|
| aaaa | 0 | 8 | Entropy thấp, dữ liệu lặp lại hoàn toàn  |
| abcd | 2 | 6 | Phân bố đều, entropy cao hơn |
| hello world | 2.84535 | 5.15465 | Phân bố không đều, entropy trung bình|

### 3.2 Modulo inverse
| a | m | Kết quả mong đợi | Kết quả chương trình |
|---:|---:|---|---|
| 3 | 7 | 5 | 5 |
| 10 | 17 | 12 | 12 |
| 6 | 9 | Không tồn tại | Không tồn tại |

## 4. Kết luận
Em đã hiểu cách tính entropy, độ dư thừa thông tin và tìm nghịch đảo modulo bằng Euclid mở rộng. Khó khăn lớn nhất là hiểu rõ ý nghĩa của entropy và cách áp dụng công thức vào thực tế. Việc chạy thử nhiều test case giúp em hiểu rõ hơn về các khái niệm này.
