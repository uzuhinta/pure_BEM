# BEM

Ý nghĩa:

 - Viết tắt: Block Element Modifier
  - Block: khối
  - Element: thành phần
  - Modifier: bổ sung

Cú pháp:

```css
.block
.block__element

.block--modifier
.block__element-modifier
```

Ví dụ

```html
    <div class="card card--sucess">
        <h2 class="card__heading"></h2>
        <div class="card__body"></div>
        <div class="card__btn card_btn--large"></div>
    </div>
```

Ưu điểm:

- Rõ ràng
- Tái sử dụng
- Giúp hoạt động nhóm
- Tính module, không lo class này ảnh hưởng lên class khác

Nhược điểm: 

- Tên class dài
- m