

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

