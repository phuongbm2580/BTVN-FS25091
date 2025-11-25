Dưới đây là **5 bài BTVN đã được chỉnh lại cho chuyên nghiệp, rõ ràng, dễ hiểu**, không dùng icon, không dùng ký tự trang trí.
Bạn có thể copy gửi thẳng cho học viên.

---

# BTVN – FUNCTION (5 bài luyện tập)

---

## Bài 1: Viết hàm đếm số từ trong câu

Hàm: `countWords(str)`

Yêu cầu:

* Xoá khoảng trắng dư ở đầu và cuối chuỗi.
* Thay các đoạn có nhiều khoảng trắng liên tiếp thành một khoảng trắng.
* Trả về số lượng từ trong câu.

Ví dụ:

```
countWords("   Hôm  nay   trời đẹp quá   ")
Kết quả: 5
```

---

## Bài 2: Viết hàm kiểm tra chuỗi palindrome

Hàm: `isPalindrome(str)`

Yêu cầu:

* Bỏ tất cả khoảng trắng trong chuỗi.
* Không phân biệt chữ hoa và chữ thường.
* Trả về true nếu chuỗi là palindrome, ngược lại trả về false.

Ví dụ:

```
isPalindrome("Race car")   → true
isPalindrome("hello")      → false
```

---

## Bài 3: Viết hàm tìm ký tự không bị lặp đầu tiên

Hàm: `firstUniqueChar(str)`

Yêu cầu:

* Tìm ký tự xuất hiện đúng một lần trong chuỗi.
* Trả về ký tự đó.
* Nếu không có ký tự nào thỏa điều kiện, trả về null.

Ví dụ:

```
firstUniqueChar("aabbccddef")   → "e"
firstUniqueChar("aabb")         → null
```

---

## Bài 4: Viết hàm rút gọn số lớn

Hàm: `shortNumber(num)`

Yêu cầu:

* Nếu số lớn hơn hoặc bằng 1.000.000, trả về dạng "x.xM".
* Nếu số lớn hơn hoặc bằng 1.000, trả về dạng "x.xK".
* Nếu nhỏ hơn 1.000, trả về số ban đầu ở dạng chuỗi.

Ví dụ:

```
shortNumber(1500)       → "1.5K"
shortNumber(2000000)    → "2M"
shortNumber(800)        → "800"
```

---

## Bài 5: Viết hàm ẩn một phần email

Hàm: `maskEmail(email)`

Yêu cầu:

* Giữ nguyên hai ký tự đầu của phần tên email.
* Giữ nguyên domain.
* Thay phần còn lại giữa hai ký tự đầu và domain bằng ba dấu "*".
* Trả về chuỗi email đã được ẩn thông tin.

Ví dụ:

```
maskEmail("phuong2003@gmail.com")
Kết quả: "ph***03@gmail.com"
```

---

Nếu bạn muốn mình viết thêm một bản đáp án chuẩn hoặc gợi ý từng bước giải để gửi riêng cho học viên thì có thể bảo mình.
