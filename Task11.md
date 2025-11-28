

---

# **BÀI TẬP 1 — Tìm phần tử gần nhất so với một giá trị cho trước**

Cho mảng số nguyên:

```js
const numbers = [2, 15, 30, 55, 60, 77, 90];
```

Viết hàm `findNearest(arr, x)` trả về phần tử có giá trị gần nhất với `x`.
Không được sử dụng reduce hoặc các phương thức cao cấp khác.

---

# **BÀI TẬP 2 — Xây dựng mô phỏng giỏ hàng với các thao tác cơ bản**

Yêu cầu xây dựng ba hàm:

1. `addToCart(cart, product)`

   * Nếu sản phẩm chưa tồn tại trong cart, thêm mới với quantity = 1.
   * Nếu đã tồn tại, tăng quantity lên 1.

2. `removeFromCart(cart, id)`

   * Nếu quantity > 1, giảm quantity.
   * Nếu quantity = 1, xoá sản phẩm khỏi giỏ hàng.

3. `getTotal(cart)`

   * Tính tổng tiền (price * quantity).

Không sử dụng find hoặc filter.
Chỉ sử dụng vòng lặp cơ bản và các thao tác mảng như push, splice.

---

# **BÀI TẬP 3 — Chèn số vào mảng đã được chuẩn hoá và sắp xếp tăng dần**

## **Mô tả yêu cầu**

Viết hàm `insertNumber(arr, num)` với các yêu cầu sau:

1. **Chuẩn hoá mảng đầu vào:**

   * Loại bỏ toàn bộ giá trị không phải là số.
   * Loại bỏ các giá trị kiểu số nhưng không hợp lệ (NaN).

2. **Sắp xếp mảng theo thứ tự tăng dần.**
   Có thể sử dụng hoặc không sử dụng `sort()`, tuỳ lựa chọn của học viên.

3. **Chèn giá trị `num` vào mảng sao cho thứ tự tăng dần không bị thay đổi.**

   * Nếu `num` không phải số hợp lệ (NaN hoặc giá trị không phải number), không chèn.
   * Nếu mảng ban đầu rỗng, trả về mảng chỉ chứa `num`.

4. **Trả về mảng mới sau khi đã chèn.**

---

## **Mẫu hàm yêu cầu**

```js
function insertNumber(arr, num) {
  // Xử lý và in ra kết quả
}
```

---

## **Ví dụ kết quả mong muốn**

```js
insertNumber([1, 3, 5, 7, 9], 6);
// Output: [1, 3, 5, 6, 7, 9]

insertNumber([3, "hello", 1, NaN, 4, null], 2);
// Output: [1, 2, 3, 4]

insertNumber([], 5);
// Output: [5]

insertNumber([-1, 10, -5, "abc"], -3);
// Output: [-5, -3, -1, 10]

insertNumber([5, 2, 8], NaN);
// Output: [2, 5, 8]
```

---

## **Yêu cầu kỹ thuật**

* Không sử dụng `filter`, `map`, `reduce`.

* Chỉ sử dụng các công cụ đã học:

  * `for`, `for…in`, `for…of`
  * `push`, `pop`, `shift`, `unshift`, `splice`
  * Kiểm tra kiểu bằng `typeof`.
  * Kiểm tra NaN bằng `Number.isNaN()` hoặc `isNaN()`.


---

