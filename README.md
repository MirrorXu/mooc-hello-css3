# mooc-hello-css3
重拾CSS3

## 边框阴影 `box-shadow`

```
box-shadow: x轴偏移量 ， Y轴偏移量 ， [阴影模糊半径] ， [阴影扩展半径] ，[阴影颜色] ， [投影方式]（默认外投影，inset） 为内投影
```
* 示例 [demo / box-shadow](demo/1-box-shadow.html)


## 边框颜色 `border-image`

```
border-image-source: url('图片路径')

border-iamge-slice: 背景图切割位置（ 上 ， 右 ， 下 ， 左 ）数字或百分比（相对于背景自身的百分比）

border-image-repeat：	[ stretch（拉伸） | repeat（重复） | round（自动贴合） ]

border-image: url('图片路径') 背景图切割位置 展示方式

```
- 示例：[demo / 2-border-image.html](demo/2-border-image.html)

## 渐变色彩  `linear-gradient` 线性渐变

```
background-image: linear-gradient( 方向[ 90deg | to bottom] , 颜色1 ，颜色2 ，... , 颜色n )
```

- demo [demo / 3-linear-gradient.html ](demo/3-linear-gradient.html)



## 文本处理 `text-overflow`和 `word-wrap`

- 强制文本在一行显示 `white-space:nowrap`
```
text-overflow:[clip(裁剪) | ellipsis(显示省略标记)]

word-wrap : [ normal(默认 ， 正常) | break-word （打断） ];

```

- demo [demo/4-text-overflow.html](demo/4-text-overflow.html)

##文本阴影 `text-shadow`

```
text-shadow: X-offset(x偏移量) Y-offset（Y偏移量） blue（羽化值） color（颜色） ;

```
- deme []()

