### 使用

```html
<style>
  @import all.scss;
</style>
```

### 功能

- 常用 media queries
- 網格系統 (仿 BS4)

* syntax: col-\*\[斷點\]-\[格數\]
* 斷點: sm, md, lg, xl
* 斷點與格數調整 (\_variable.scss)

```scss
$gutter-width: 30px;
$grid-columns: 12;

$xl-breakpoint: 1024px;
$lg-breakpoint: 768px;
$md-breakpoint: 570px;
$sm-breakpoint: 375px;
```

- 顏色, 字型, 內距與外距的調整 (\_variable.scss)
