# Code Tốt
Đưa ra tiêu chuẩn coding dành cho Frontend Developer.

## CSS
Resource: http://codeguide.co/ > Syntax

**Sử dụng tab space 2**

```
.item {
  color: #fff;
}
```

**Khi gộp nhiều class hoặc item, xuống dòng cho mỗi item.**

```
.list,
.grid {
  // .list và .grid xuống dòng
}
```

**Thêm 1 space vào trước dấu mở `{`
Dấu `}` sẽ nằm ở 1 line riêng**

```
.item {}
```

**Thêm 1 space vào sau thuộc tính trước khi tới giá trị thuộc tính.
Mỗi thuộc tính và giá trị nên đi liền cùng 1 dòng.
Kết thúc 1 thuộc tính, sử dụng dấu `;`**

```
color: #fff;
```

**Các giá trị nối liền nhau trong cùng 1 thuộc tính nên có 1 space sau các dấu `,`**

```
box-shadow: 0 1px 2px #ccc, inset 0 1px 0 #fff;
```

**Không sử dụng space trong các giá trị của rgb(), rgba(), hsl(), hsla(), hoặc rect()**

```
color: rgba(0,0,0,0.15);
```

 **Viết thường các mã màu**
 
 ```
 color: #fff;
 ```
 
 **Sử dụng mã màu rút gọn nếu có thể**
 
 ```
 color: #000; // thay vì #000000
 ```
 
 Sử dụng dấu double quotes `"` trong  các item
 
 ```
 input[type="text"]
 ```
 
 Không nhập đơn vị nếu số là `0`
 
 ```
 margin: 0;
 ```

 
