<!-- TOC -->
* [bootcss-plus](#bootcss-plus)
* [约定样式命名格式 - 公共占位符](#---)
    * [Typography](#typography)
    * [Containers](#containers)
    * [清除浮动（Clearfix）](#clearfix)
    * [彩色链接（Colored link）](#colored-link)
    * [定位](#)
    * [文本截断](#)
    * [Vertical rule](#vertical-rule)
    * [纵向对齐（Vertical alignment）](#vertical-alignment)
    * [Float](#float)
    * [Opacity](#opacity)
    * [Overflow](#overflow)
    * [display 属性](#display-)
    * [阴影(Shadows)](#--shadows-)
    * [Position](#position)
    * [Borders](#borders)
    * [尺寸（Sizing）](#sizing)
<!-- TOC -->

# bootcss-plus
自定义bootstrap主题

# 约定样式命名格式 - 公共占位符
- {breakpoint} 可选值为：`xs` `sm` `md` `lg` `xl` `xxl`
- {color} 可选值为：`primary` `secondary` `success` `danger` `warning` `info` `light` `dark`
- {property} 可选值为：`top` `bottom` `start` `end`

### [Typography](https://v5.bootcss.com/docs/content/typography/)
- `.h{n}` 和 `.display-{n}`
  - {n} 可选值为：`1` `2` `3` `4` `5` `6`
- `.text-muted`
- `.text-decoration-{value}`
  - {value} 可选值为：`underline` `line-through` `none`

### [Containers](https://v5.bootcss.com/docs/layout/containers/)
- `.container`
- `.container-fluid`
- `.container-{breakpoint}`

### [清除浮动（Clearfix）](https://v5.bootcss.com/docs/helpers/clearfix/)
- `.clearfix`

### [彩色链接（Colored link）](https://v5.bootcss.com/docs/helpers/colored-links/)
- `.link-{color}`

### [定位](https://v5.bootcss.com/docs/helpers/position/)
- `.fixed-{value}`
- `.sticky-{value}`
- `.sticky-{breakpoint}-{value}`
  - {value} 可选值为：`top` `bottom`

### [文本截断](https://v5.bootcss.com/docs/helpers/text-truncation/)
- `.text-truncate`

### [Vertical rule](https://v5.bootcss.com/docs/helpers/vertical-rule/)
- `.vr`

### [纵向对齐（Vertical alignment）](https://v5.bootcss.com/docs/utilities/vertical-align/)
- `.align-{value}`
  - {value} 可选值为：`baseline` `top` `middle` `bottom` `text-bottom` `text-top`

### [Float](https://v5.bootcss.com/docs/utilities/float/)
- `.float-{value}`
- `.float-{breakpoint}-{value}`
  - {value} 可选值为：`start` `end` `none`

### [Opacity](https://v5.bootcss.com/docs/utilities/opacity/)
- `.opacity-{n}`
  - {n} 可选值为 `0` `25` `50` `75` `100`

### [Overflow](https://v5.bootcss.com/docs/utilities/overflow/)
- `.overflow-{value}`
  - {value} 可选值为：`auto` `hidden` `visible` `scroll`

### [display 属性](https://v5.bootcss.com/docs/utilities/display/)
- `.d-{value}`
- `.d-print-{value}`
- `.d-{breakpoint}-{value}`
  - {value} 可选值为：`none` `inline` `inline-block` `block` `grid` `table` `table-cell` `table-row` `flex` `inline-flex`

### [阴影(Shadows)](https://v5.bootcss.com/docs/utilities/shadows/)
- `.shadow`
- `.shadow-{size}`
  - {size} 可选值为：`sm` `lg` `none`

### [Position](https://v5.bootcss.com/docs/utilities/position/)
- `.position-{value}`
  - {value} 可选值为：`static` `relative` `absolute` `fixed` `sticky`
- `.{property}-{position}`
  - {position} 可选值为 `0` `50` `100`
- `.translate-middle`
- `.translate-middle-{value}`
  - {value} 可选值为：`x` `y`

### [Borders](https://v5.bootcss.com/docs/utilities/borders/)
- `.border`
- `.border-0`
- `.border-{property}`
- `.border-{property}-0`
- `.border-{color}`
- `.border-{width}`
  - {width} 可选值为：`1` `2` `3` `4` `5`
- `.border-opacity-{n}`
  - {n} 可选值为：`10` `25` `50` `75` `100`
- `.rounded`
- `.rounded-{property}`
- `.rounded-{value}`
  - {value} 可选值为：`0` `1` `2` `3` `circle` `pill`

### [尺寸（Sizing）](https://v5.bootcss.com/docs/utilities/sizing/)
- `.w-{value}` 和 `.h-{value}`
  - {value} 可选值为：`25` `50` `75` `100` `auto`
- `.mw-100` 和 `.mh-100`
- `.vw-100` 和 `.vh-100`
- `.min-vw-100` 和 `.min-vh-100`
