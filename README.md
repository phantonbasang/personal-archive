# Markdown-syntax 

# Mục lục

[I. Cách sử dụng](#i-cách-sử-dụng)
- [1. Văn bản thuần](#1-văn-bản-thuần)
  - [1. Tiêu đề - Heading](#1-tiêu-đề---heading)
  - [2. Đoạn văn - Paragraph](#2-đoạn-văn---paragraph)
  - [3. Chữ in nghiêng - Italic](#3-chữ-in-nghiêng---italic)
  - [4. Chữ in đậm - Bold](#4-chữ-in-đậm---bold)
  - [5. In đậm và in nghiêng](#5-in-đậm-và-in-nghiêng)
  - [6. Chữ gạch giữa - Strikethrough](#6-chữ-gạch-giữa---strikethrough)
  - [7. Code trong dòng - Inline Code](#7-code-trong-dòng---inline-code)
- [2. Các khối](#2-các-khối)
  - [1. Trích dẫn - Blockquote](#1-trích-dẫn---blockquote)
  - [2. Danh sách có thứ tự - Ordered List](#2-danh-sách-có-thứ-tự---ordered-list)
  - [3. Danh sách không có thứ tự - Unordered List](#3-danh-sách-không-có-thứ-tự---unordered-list)
  - [4. Khối lệnh - Block Code](#4-khối-lệnh---block-code)
  - [5. Bảng - Table](#5-bảng---table)
- [3. Đặc biệt](#3-đặc-biệt)
  - [1. Đường kẻ ngang - Horizonal rules](#1-đường-kẻ-ngang---horizonal-rules)
  - [2. Liên kết - Link](#2-liên-kết---link)
  - [3. Hình ảnh - Image](#3-hình-ảnh---image)
  - [4. Biểu tượng cảm xúc - Icon](#4-biểu-tượng-cảm-xúc---icon)
  - [5. Checkbox](#5-checkbox)
  - [6. Escape markdown](#6-escape-markdown)




# I. Cách sử dụng

## 1. Văn bản thuần

### 1 Tiêu đề - Heading

Bạn có thể viết loại tiêu đề `<h1>, <h2>,... <h6>` bằng cách thêm các dấu # tương ứng vào đầu dòng.

Một dấu # tương đương với `<h1>`, hai dấu # tương đương với `<h2>` ...

Cú pháp:
```
# Tiêu đề loại 1
## Tiêu đề loại 2
### Tiêu đề loại 3
#### Tiêu đề loại 4
##### Tiêu đề loại 5
###### Tiêu đề loại 6
```
Kết quả:

# Tiêu đề loại 1
## Tiêu đề loại 2
### Tiêu đề loại 3
#### Tiêu đề loại 4
##### Tiêu đề loại 5
###### Tiêu đề loại 6

### 2. Đoạn văn - Paragraph

Để xuống dòng giữa các văn bản `<p>`, sử dụng một dòng trống để tách các dòng văn bản.

Cú pháp:
```
Đây là dòng 1

Đây là dòng 2
```
Kết quả:

Đây là dòng 1

Đây là dòng 2

### 3. Chữ in nghiêng - Italic

Để in nghiêng văn bản `<i>`, thêm một dấu * hoặc dấu _ trước và sau từ cần in nghiêng.

Cú pháp:
```
*Từ cần in nghiêng 1*

_Từ cần in nghiêng 2_
```
Kết quả:

*Từ cần in nghiêng 1*

_Từ cần in nghiêng 2_

### 4. Chữ in đậm - Bold

Để in đậm văn bản `<b>`, thêm hai dấu * hoặc dấu _ trước và sau từ cần in đậm.

Cú pháp:
```
**Từ cần in đậm 1**

__Từ cần in đậm 2__
```
Kết quả:

**Từ cần in đậm 1**

__Từ cần in đậm 2__

### 5. In đậm và in nghiêng

Đơn giản, bạn chỉ cần ba dấu * hoặc dấu _ trước và sau từ đó.

Cú pháp:
```
***Từ in đậm và in nghiêng 1***

___Từ in đậm và in nghiêng 2___
```
Kết quả:

***Từ in đậm và in nghiêng 1***

___Từ in đậm và in nghiêng 2___

### 6. Chữ gạch giữa - Strikethrough

Để tạo chữ gạch giữa, thêm 2 dấu ~ trước và sau từ đó.

Cú pháp:
```
~~Khuyến mại~~
```
Kết quả:

~~Khuyến mại~~

### 7. Code trong dòng - Inline Code

Để viết inline `<code>`, bạn dùng 2 dấu ` ở trước và sau từ đó.

Cú pháp:
```
`inline code`
```
Kết quả:

`inline code`

## 2. Các khối

### 1. Trích dẫn - Blockquote

Để tạo một `<blockquote>`, thêm dấu > vào trước mỗi dòng trích dẫn.

Cú pháp:
```
> Trích dẫn dòng 1
> Trích dẫn dòng 2
```
Kết quả:

> Trích dẫn dòng 1
> Trích dẫn dòng 2

### 2. Danh sách có thứ tự - Ordered List

Để tạo danh sách `<ol><li>`, bạn chỉ cần thêm các số, dấu chấm trước nội dung (dùng tab để phân cấp)

Cú pháp:
```
1. Mục thứ nhất
2. Mục thứ hai
3. Mục thứ ba
```
Kết quả:

1. Mục thứ nhất
2. Mục thứ hai
3. Mục thứ ba

### 3. Danh sách không có thứ tự - Unordered List

Để tạo danh sách `<ul><li>`, bạn chỉ cần thêm dấu * hoặc - hoặc + trước nội dung (dùng tab để phân cấp)

Cú pháp:
```
- Mục thứ nhất
- Mục thứ hai
- Mục thứ ba
```
Kết quả:

- Mục thứ nhất
- Mục thứ hai
- Mục thứ ba

### 4. Khối lệnh - Block Code

Để viết 1 đoạn `<code>`, bạn dùng 3 dấu ` ở trước và sau đoạn đó (có thể thêm format ngôn ngữ đó).

Cú pháp:


Kết quả:

```python
print("hello world")
```

### 5. Bảng - Table

Để tạo bảng `<table><tbody><tr><th><th>`, bạn chỉ cần ngăn cách bởi dấu | và cách đầu bảng với thân bảng bằng :--- (số dấu - tuỳ ý)

Cú pháp:
```
| Cột 1 | Cột 2 | Cột 3 | Cột 4 |
| :--- | :--- | :--- | :--- |
| A | B | C | D |
| E | F | G | H |
| I | K | L | M |
```
Kết quả

| Cột 1 | Cột 2 | Cột 3 | Cột 4 |
| :--- | :--- | :--- | :--- |
| A | B | C | D |
| E | F | G | H |
| I | K | L | M |

## 3. Đặc biệt

### 1. Đường kẻ ngang - Horizonal rules

Để tạo đường kẻ ngang, sử dụng ba dấu * hoặc - hoặc _ trên một dòng.

Cú pháp:
```
---
***
___
```
Kết quả:

---
***
___

### 2. Liên kết - Link

Để chèn trực tiếp, bạn có thể paste thẳng nó như bình thường.

Để dẫn liên kết 

Cú pháp:
```

```
Kết quả:

Trực tiếp: 

Gián tiếp: 

### 3. Hình ảnh - Image

Để chèn trực tiếp, bạn có thể paste thẳng nó như bình thường.

Để dẫn ảnh `

Hoặc `![](link ảnh)` nếu không cần chữ khi hover.

Cú pháp:
```

```
Kết quả:



Để chèn liên kết vào ảnh `<a href="link"><img src="link ảnh" alt="chữ"></a>` thì chỉ cần kết hợp đúng cú pháp là được.

```
[ ![chữ](link ảnh) ] (link)
```

### 4. Biểu tượng cảm xúc - Icon

Phần này tuỳ vào nền tảng (Github, Discord, ...) có icon đó không, bạn ghi dấu : và tên icon.

Cú pháp:



Kết quả:



> More information: 

### 5. Checkbox

Để chèn `checkbox/checked` (thường dùng cho to do list trên github) thì ta đánh dấu như list và thêm 1 cặp ngoặc vuông.

Cú pháp:

```
- [ ] Checkbox
- [x] Checked
```

Kết quả:

- [ ] Checkbox
- [x] Checked

### 6. Escape markdown

Đôi khi bạn sẽ cần những kí hiệu trùng với cú pháp của markdown. Để phân biệt, bạn chỉ cần thêm dấu \ trước những kí hiệu đó là được.

Cú pháp:
```
\`hai dấu nháy\`

\*\*\*ba dấu sao hai bên\*\*\*
```
Kết quả:

\`hai dấu nháy\`

\*\*\*ba dấu sao hai bên\*\*\*

