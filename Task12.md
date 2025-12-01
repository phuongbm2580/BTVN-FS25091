
---

# **Bài 2 – Lọc các số chẵn trong mảng** (2d)

**Mô tả:**
Viết hàm `filterEvenNumbers(arr)` để lọc và trả về một mảng mới chứa các số chẵn từ mảng đầu vào.

**Yêu cầu:**

* Chỉ lấy các phần tử thuộc kiểu number và có giá trị chia hết cho 2.
* Không làm thay đổi mảng gốc.
* Trả về mảng mới chứa các số chẵn.
* Nếu không có số chẵn, trả về mảng rỗng.

**Mẫu hàm:**

```js
function filterEvenNumbers(arr) {
  // Xử lý và trả về kết quả
}
```

**Ví dụ:**

```
filterEvenNumbers([1, 2, 3, 4, 5, 6]);      // [2, 4, 6]
filterEvenNumbers([1, 3, 5, 7]);            // []
filterEvenNumbers([]);                      // []
filterEvenNumbers([-2, -1, 0, 1, 2]);       // [-2, 0, 2]
```

---

# **Bài 3 – Lọc chuỗi có độ dài lớn hơn 5 ký tự** (2.5d)

**Mô tả:**
Viết hàm `filterLongStrings(arr)` để trả về một mảng gồm các chuỗi có độ dài lớn hơn 5 ký tự.

**Yêu cầu:**

* Chỉ xét các phần tử thuộc kiểu string.
* Trả về mảng mới chứa các chuỗi có độ dài > 5.
* Nếu không có chuỗi nào phù hợp, trả về mảng rỗng.

**Mẫu hàm:**

```js
function filterLongStrings(arr) {
  // Xử lý và trả về kết quả
}
```

**Ví dụ:**

```
filterLongStrings(["hello", "world", "javascript", "nodejs"]); 
// ["javascript", "nodejs"]

filterLongStrings(["hi", "hello world", "a b c", "goodbye!!"]); 
// ["hello world", "goodbye!!"]

filterLongStrings(["hi", "bye", "yes"]); 
// []
```

---

# **Bài 4 – Tìm giá trị lớn nhất, nhỏ nhất và trung bình cộng các số nguyên tố** (2.5d)

**Mô tả:**
Cho mảng số nguyên bất kỳ, hãy viết hàm `findMinMaxAverage(arr)` để tìm:

1. Số lớn nhất và vị trí của nó (lấy vị trí đầu tiên nếu có nhiều giá trị bằng nhau).
2. Số nhỏ nhất và vị trí của nó (lấy vị trí đầu tiên nếu có nhiều giá trị bằng nhau).
3. Trung bình cộng của các số nguyên tố trong mảng. Nếu không có số nguyên tố nào, trả về null.

**Mẫu hàm:**

```js
function findMinMaxAverage(arr) {
  // Xử lý và trả về kết quả
}
```

**Ví dụ:**

```
findMinMaxAverage([3, 1, 4, 1, 5, 9, 2, 6]);  
// {max: 9, maxIndex: 5, min: 1, minIndex: 1, primeAverage: 3.33 }

findMinMaxAverage([5, 5, 2, 2, 1]);  
// {max: 5, maxIndex: 0, min: 1, minIndex: 4, primeAverage: 3.5 }

findMinMaxAverage([-3, 7, -8, 11, 0]);  
// {max: 11, maxIndex: 3, min: -8, minIndex: 2, primeAverage: 9 }
```

---

# **Bài 16 – Loại bỏ phần tử trùng lặp (không sử dụng Set hoặc reduce)** (2d)

**Mô tả:**
Cho một mảng bất kỳ, hãy viết hàm `removeDuplicates(arr)` để loại bỏ toàn bộ phần tử trùng lặp và trả về một mảng mới chỉ chứa các phần tử duy nhất.

**Yêu cầu:**

* Không sử dụng Set.
* Không sử dụng reduce.
* Có thể sử dụng: filter, indexOf, findIndex hoặc vòng lặp.
* Không làm thay đổi mảng gốc.
* Chỉ giữ lại lần xuất hiện đầu tiên của mỗi phần tử.

**Mẫu hàm:**

```js
function removeDuplicates(arr) {
  // Xử lý và trả về kết quả
}
```

**Ví dụ:**

```
removeDuplicates([1, 2, 2, 3, 3, 3, 4]);  
// [1, 2, 3, 4]

removeDuplicates(["a", "b", "a", "c", "b"]);  
// ["a", "b", "c"]

removeDuplicates([]);  
// []
```

---

# **Bài 29 – Nén mảng theo nhóm (Run Length Encoding)** (1d)

**Mô tả:**
Cho một mảng đã được nhóm sẵn theo từng cụm phần tử giống nhau đứng liên tiếp, hãy viết hàm `compressArray(arr)` để chuyển mảng này sang dạng nén: mỗi phần tử được biểu diễn bởi một cặp `[giá trị, số lần xuất hiện liên tiếp]`.

**Yêu cầu:**

* Không sử dụng map.
* Không sử dụng reduce.
* Chỉ sử dụng: for, push, splice (nếu cần).
* Phải xử lý đúng nhóm cuối cùng trong mảng.
* Mảng có thể rỗng hoặc chỉ có một phần tử.

**Mẫu hàm:**

```js
function compressArray(arr) {
  // Xử lý và trả về kết quả
}
```

**Ví dụ:**

```
compressArray(["a", "a", "b", "b", "b", "c"]);  
// [["a",2], ["b",3], ["c",1]]

compressArray([1, 1, 1, 2, 2, 3]);  
// [[1,3], [2,2], [3,1]]

compressArray(["x"]);  
// [["x",1]]

compressArray([]);  
// []
```

---


