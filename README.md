<!-- TOC -->
* [bootcss-plus](#bootcss-plus)
* [断点](#)
* [包内样式名目录](#)
  * [布局](#)
    * [Containers](#containers)
  * [页面内容](#)
    * [Typography](#typography)
  * [助手](#)
    * [清除浮动（Clearfix）](#clearfix)
    * [彩色链接（Colored link）](#colored-link)
    * [定位](#)
    * [Stacks](#stacks)
    * [文本截断](#)
    * [Vertical rule](#vertical-rule)
  * [工具类](#)
    * [Background](#background)
    * [Borders](#borders)
    * [Colors](#colors)
    * [display 属性](#display-)
    * [Flex](#flex)
    * [Float](#float)
    * [Interactions](#interactions)
    * [Opacity](#opacity)
    * [Overflow](#overflow)
    * [Position](#position)
    * [阴影(Shadows)](#--shadows-)
    * [尺寸（Sizing）](#sizing)
    * [Spacing](#spacing)
    * [Text](#text)
    * [纵向对齐（Vertical alignment）](#vertical-alignment)
    * [可见性（Visibility）](#visibility)
<!-- TOC -->

# bootcss-plus
bootcss-plus 只包含了 bootstrap@v5 中的部分样式，旨在做为单纯的 css 工具，提高编写自己页面布局的效率。

# [断点](https://v5.bootcss.com/docs/layout/breakpoints/)
| 断点                | 在类中的标识 | 尺寸      |
|-------------------|--------|---------|
| X-Small           | None   | <576px  |
| Small             | `sm`   | ≥576px  |
| Medium            | `md`   | ≥768px  |
| Large             | `lg`   | ≥992px  |
| Extra large       | `xl`   | ≥1200px |
| Extra extra large | `xxl`  | ≥1400px |
由此，约定通用占位符 <br>
{breakpoint} 可选值为：`sm` `md` `lg` `xl` `xxl`

# 包内样式名目录
## 布局

### [Containers](https://v5.bootcss.com/docs/layout/containers/)
| 样式名                       | 占位符可选值 |
|---------------------------|--------|
| `.container`              |        |
| `.container-fluid`        |        |
| `.container-{breakpoint}` |        |


## 页面内容

### [Typography](https://v5.bootcss.com/docs/content/typography/)
| 样式名            | 占位符可选值                      |
|----------------|-----------------------------|
| `.h{n}`        | {n}：`1` `2` `3` `4` `5` `6` |
| `.display-{n}` | {n}：`1` `2` `3` `4` `5` `6` |


## 助手

### [清除浮动（Clearfix）](https://v5.bootcss.com/docs/helpers/clearfix/)
| 样式名         | 占位符可选值 |
|-------------|--------|
| `.clearfix` |        |

### [彩色链接（Colored link）](https://v5.bootcss.com/docs/helpers/colored-links/)
| 样式名             | 占位符可选值                                                                           |
|-----------------|----------------------------------------------------------------------------------|
| `.link-{value}` | {value}：`primary` `secondary` `success` `info` `warning` `danger` `light` `dark` |

### [定位](https://v5.bootcss.com/docs/helpers/position/)
| 样式名                                                   | 占位符可选值                 |
|-------------------------------------------------------|------------------------|
| `.fixed-{value}`                                      | {value}：`top` `bottom` |
| `.sticky-{value}` <br> `.sticky-{breakpoint}-{value}` | {value}：`top` `bottom` |

### [Stacks](https://v5.bootcss.com/docs/helpers/stacks/)
| 样式名       | 占位符可选值 |
|-----------|--------|
| `.hstack` |        |
| `.vstack` |        |


### [文本截断](https://v5.bootcss.com/docs/helpers/text-truncation/)
| 样式名              | 占位符可选值 |
|------------------|--------|
| `.text-truncate` |        |

### [Vertical rule](https://v5.bootcss.com/docs/helpers/vertical-rule/)
| 样式名   | 占位符可选值 |
|-------|--------|
| `.vr` |        |


## 工具类

### [Background](https://v5.bootcss.com/docs/utilities/background/)
| 样式名               | 占位符可选值                                                                                                                |
|-------------------|-----------------------------------------------------------------------------------------------------------------------|
| `.bg-{value}`     | {value}：`primary` `secondary` `success` `info` `warning` `danger` `light` `dark` `black` `white` `body` `transparent` |
| `.bg-opacity-{n}` | {n}：`10` `25` `50` `75` `100`                                                                                         |

### [Borders](https://v5.bootcss.com/docs/utilities/borders/)
| 样式名                                      | 占位符可选值                                                                                   |
|------------------------------------------|------------------------------------------------------------------------------------------|
| `.border` <br> `.border-0`               |                                                                                          |
| `.border-top` <br> `.border-top-0`       |                                                                                          |
| `.border-end` <br> `.border-end-0`       |                                                                                          |
| `.border-bottom` <br> `.border-bottom-0` |                                                                                          |
| `.border-start` <br> `.border-start-0`   |                                                                                          |
| `.border-{color}`                        | {color}：`primary` `secondary` `success` `info` `warning` `danger` `light` `dark` `white` |
| `.border-{width}`                        | {width}：`1` `2` `3` `4` `5`                                                              |
| `.border-opacity-{n}`                    | {n}：`10` `25` `50` `75` `100`                                                            |
| `.rounded`  <br>    `.rounded-{value}`   | {value}：`0` `1` `2` `3` `circle` `pill`                                                  |
| `.rounded-top`                           |                                                                                          |
| `.rounded-end`                           |                                                                                          |
| `.rounded-bottom`                        |                                                                                          |
| `.rounded-start`                         |                                                                                          |

### [Colors](https://v5.bootcss.com/docs/utilities/colors/)
| 样式名                 | 占位符可选值                                                                                                                                        |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| `.text-{value}`     | {value}：`primary` `secondary` `success` `info` `warning` `danger` `light` `dark` `black` `white` `body` `muted` `black-50` `white-50` `reset` |
| `.text-opacity-{n}` | {n}：`25` `50` `75` `100`                                                                                                                      |

### [display 属性](https://v5.bootcss.com/docs/utilities/display/)
| 样式名                                                                 | 占位符可选值                                                                                                      |
|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| `.d-{value}` <br> `.d-print-{value}` <br> `.d-{breakpoint}-{value}` | {value}：`none` `inline` `inline-block` `block` `grid` `table` `table-cell` `table-row` `flex` `inline-flex` |

### [Flex](https://v5.bootcss.com/docs/utilities/flex/)
| 样式名                                                                      | 占位符可选值                                                      |
|--------------------------------------------------------------------------|-------------------------------------------------------------|
| `.flex-fill` <br> `.flex-{breakpoint}-fill`                              |                                                             |
| `.flex-{value}` <br> `.flex-{breakpoint}-{value}`                        | {value}：`row` `row-reverse` `column` `column-reverse`       |
| `.flex-grow-{n}` <br> `.flex-{breakpoint}-grow-{n}`                      | {n}：`0` `1`                                                 |
| `.flex-shrink-{n}` <br> `.flex-{breakpoint}-shrink-{n}`                  | {n}：`0` `1`                                                 |
| `.flex-{value}` <br> `.flex-{breakpoint}-{value}`                        | {value}：`wrap` `nowrap` `wrap-reverse`                      |
| `.gap-{n}` <br> `.gap-{breakpoint}-{n}`                                  | {n}：`0` `1` `2` `3` `4` `5`                                 |
| `.justify-content-{value}` <br> `.justify-content-{breakpoint}-{value}`  | {value}：`start` `end` `center` `between` `around` `evenly`  |
| `.align-items-{value}`   <br>      `.align-items-{breakpoint}-{value}`   | {value}：`start` `end` `center` `baseline` `stretch`         |
| `.align-content-{value}` <br>      `.align-content-{breakpoint}-{value}` | {value}：`start` `end` `center` `between` `around` `stretch` |
| `.align-self-{value}` <br>     `.align-self-{breakpoint}-{value}`        | {value}：`start` `end` `center` `baseline` `stretch` `auto`  |
| `.order-{value}` <br>     `.order-{breakpoint}-{value}`                  | {value}：`first` `0` `1` `2` `3` `4` `5` `last`              |

### [Float](https://v5.bootcss.com/docs/utilities/float/)
| 样式名                                                 | 占位符可选值                       |
|-----------------------------------------------------|------------------------------|
| `.float-{value}` <br> `.float-{breakpoint}-{value}` | {value}：`start` `end` `none` |

### [Interactions](https://v5.bootcss.com/docs/utilities/interactions/)
| 样式名                    | 占位符可选值                      |
|------------------------|-----------------------------|
| `.user-select-{value}` | {value}：`all` `auto` `none` |
| `.pe-{value}`          | {value}：`none` `auto`       |

### [Opacity](https://v5.bootcss.com/docs/utilities/opacity/)
| 样式名            | 占位符可选值                       |
|----------------|------------------------------|
| `.opacity-{n}` | {n}：`0` `25` `50` `75` `100` |

### [Overflow](https://v5.bootcss.com/docs/utilities/overflow/)
| 样式名                 | 占位符可选值                                     |
|---------------------|--------------------------------------------|
| `.overflow-{value}` | {value}：`auto` `hidden` `visible` `scroll` |

### [Position](https://v5.bootcss.com/docs/utilities/position/)
| 样式名                                                   | 占位符可选值                                                  |
|-------------------------------------------------------|---------------------------------------------------------|
| `.position-{value}`                                   | {value}：`static` `relative` `absolute` `fixed` `sticky` |
| `.top-{n}`                                            | {n}：`0` `50` `100`                                      |
| `.bottom-{n}`                                         | {n}：`0` `50` `100`                                      |
| `.start-{n}`                                          | {n}：`0` `50` `100`                                      |
| `.end-{n}`                                            | {n}：`0` `50` `100`                                      |
| `.translate-middle`  <br> `.translate-middle-{value}` | {value}：`x` `y`                                         |

### [阴影(Shadows)](https://v5.bootcss.com/docs/utilities/shadows/)
| 样式名                              | 占位符可选值                   |
|----------------------------------|--------------------------|
| `.shadow` <br> `.shadow-{value}` | {value}：`sm` `lg` `none` |

### [尺寸（Sizing）](https://v5.bootcss.com/docs/utilities/sizing/)
| 样式名           | 占位符可选值                              |
|---------------|-------------------------------------|
| `.w-{value}`  | {value}：`25` `50` `75` `100` `auto` |
| `.mw-100`     |                                     |
| `.vw-100`     |                                     |
| `.min-vw-100` |                                     |
| `.h-{value}`  | {value}：`25` `50` `75` `100` `auto` |
| `.mh-100`     |                                     |
| `.vh-100`     |                                     |
| `.min-vh-100` |                                     |

### [Spacing](https://v5.bootcss.com/docs/utilities/spacing/)
| 样式名                                           | 占位符可选值                                 |
|-----------------------------------------------|----------------------------------------|
| `.m-{value}` <br> `.m-{breakpoint}-{value}`   | {value}：`0` `1` `2` `3` `4` `5` `auto` |
| `.mx-{value}` <br> `.mx-{breakpoint}-{value}` | {value}：`0` `1` `2` `3` `4` `5` `auto` |
| `.my-{value}` <br> `.my-{breakpoint}-{value}` | {value}：`0` `1` `2` `3` `4` `5` `auto` |
| `.mt-{value}` <br> `.mt-{breakpoint}-{value}` | {value}：`0` `1` `2` `3` `4` `5` `auto` |
| `.me-{value}` <br> `.me-{breakpoint}-{value}` | {value}：`0` `1` `2` `3` `4` `5` `auto` |
| `.mb-{value}` <br> `.mb-{breakpoint}-{value}` | {value}：`0` `1` `2` `3` `4` `5` `auto` |
| `.ms-{value}` <br> `.ms-{breakpoint}-{value}` | {value}：`0` `1` `2` `3` `4` `5` `auto` |
| `.p-{value}` <br> `.p-{breakpoint}-{value}`   | {value}：`0` `1` `2` `3` `4` `5`        |
| `.px-{value}` <br> `.px-{breakpoint}-{value}` | {value}：`0` `1` `2` `3` `4` `5`        |
| `.py-{value}` <br> `.py-{breakpoint}-{value}` | {value}：`0` `1` `2` `3` `4` `5`        |
| `.pt-{value}` <br> `.pt-{breakpoint}-{value}` | {value}：`0` `1` `2` `3` `4` `5`        |
| `.pb-{value}` <br> `.pb-{breakpoint}-{value}` | {value}：`0` `1` `2` `3` `4` `5`        |
| `.ps-{value}` <br> `.ps-{breakpoint}-{value}` | {value}：`0` `1` `2` `3` `4` `5`        |
| `.pe-{value}` <br> `.pe-{breakpoint}-{value}` | {value}：`0` `1` `2` `3` `4` `5`        |

### [Text](https://v5.bootcss.com/docs/utilities/text/)
| 样式名                        | 占位符可选值                                                        |
|----------------------------|---------------------------------------------------------------|
| `.font-monospace`          |                                                               |
| `.fs-{n}`                  | {n}：`0` `1` `2` `3` `4` `5` `6`                               |
| `.fst-{value}`             | {value}：`italic` `normal`                                     |
| `.fw-{value}`              | {value}：`light` `lighter` `normal` `bold` `bolder` `semibold` |
| `.lh-{value}`              | {value}：`1` `sm` `base` `lg`                                  |
| `.text-{value}`            | {value}：`start` `end` `center`                                |
| `.text-decoration-{value}` | {value}：`none` `underline` `line-through`                     |
| `.text-{value}`            | {value}：`lowercase` `uppercase` `capitalize`                  |
| `.text-{value}`            | {value}：`wrap` `nowrap`                                       |
| `.text-break`              |                                                               |

### [纵向对齐（Vertical alignment）](https://v5.bootcss.com/docs/utilities/vertical-align/)
| 样式名              | 占位符可选值                                                              |
|------------------|---------------------------------------------------------------------|
| `.align-{value}` | {value}：`baseline` `top` `middle` `bottom` `text-bottom` `text-top` |


### [可见性（Visibility）](https://v5.bootcss.com/docs/utilities/visibility/)
| 样式名          | 占位符可选值 |
|--------------|--------|
| `.visible`   |        |
| `.invisible` |        |
