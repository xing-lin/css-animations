# css animations

## [what css properties can be transitioned](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties)

## transition

1. transition-property（属性）: all / other property
2. transition-duration（持续时间） : 1s
3. transition-timing-function （方法）: how the change in the property will occur
   1. ease : the change starts slow then go faster then finishes slow
   2. linear : the change occurs at the same rate
   3. ease-in : the change starts slow then go faster before the end
   4. ease-out : the changes starts fast then slows down before the end
   5. ease-in-out : the change starts slow then go faster then finishes slow
4. transition-delay（延迟时间）: 3000ms / 3s
5. 多个属性写在 transition 中，顺序为 property duration timing-function delay，可写多个，以逗号隔开

## transform

1. translate(x: px, y: px) => translate(x, y) => translateX(x: px) + translateY(y: px)
   1. 水平、垂直方向偏移
   2. 单位是 px
   3. 数字可为负，向相反方向偏移
2. scale(n) => scale(n1, n2) => scaleX(n) + scaleY(n)
   1. 水平、垂直方向放大或缩小
   2. 无单位，数字表示是原来大小的 n 倍
   3. 数字可为负，向相反方向缩放
3. rotate(n:deg / turn / grad / rad)
   1. 顺时针旋转 n 度
   2. 单位是 css 角度单位: deg（360 度）、turn（1 圈）、grad（梯度，一个圆 400 梯度）、rad（弧度，一个圆 2pi 弧度）
   3. 可为负数，逆时针旋转
4. skew(n:deg / turn / grad / rad) => skew(n1, n2) => skewX(n) + skewY(n)
   1. 水平、垂直方向倾斜
   2. 单位是 css 角度单位: deg（360 度）、turn（1 圈）、grad（梯度，一个圆 400 梯度）、rad（弧度，一个圆 2pi 弧度）
   3. 可为负数，相反方向倾斜

## transform-origin

1. 接受关键词：top / right / bottom / left / top right / bottom right / top left / bottom left
2. 接受百分比：(30% , 50%)，x 轴偏移 30%，y 轴偏移 50%，找到中心点
3. 接受像素值

## perspective (3d 视图)

1. 需要设置一个视图容器大小

   ```css
   body {
     perspective: 500px;
   }
   ```

2. translateZ -> 向前、向后偏移
3. rotateZ 沿 z 轴旋转，与 2d rotate 旋转相同

## creative-rotating-button-effect

![markdown picture](./creative-rotating-button-effect/result.gif)

## creative-swipe-button-effect

![markdown picture](./creative-swipe-button-effect/result.gif)

## creative-swipe-text-button-effect

![markdown picture](./creative-swipe-text-button-effect/result.gif)

## creative-button-hover-effect

![markdown picture](./creative-button-hover-effect/result.gif)

## creative-button-stretching-effect

![markdown picture](./creative-button-stretching-effect/result.gif)

## creative-button-glowing-effect

![markdown picture](./creative-button-glowing-effect/result.gif)

## creative-two-layers-swapping-button-effect

![markdown picture](./creative-two-layers-swapping-button-effect/result.gif)

## creative-text-scaling-button-effect

![markdown picture](./creative-text-scaling-button-effect/result.gif)

## creative-circular-swapping-button-effect

![markdown picture](./creative-circular-swapping-button-effect/result.gif)

## creative-rotating-3-layers-button-effect

![markdown picture](./creative-rotating-3-layers-button-effect/result.gif)

## creative-layers-swapping-from-left-to-right-button-effect

![markdown picture](./creative-layers-swapping-from-left-to-right-button-effect/result.gif)

## creative-3-circles-to-background-button-effect

![markdown picture](./creative-3-circles-to-background-button-effect/result.gif)

## creative-hover-button-effect

![markdown picture](./creative-hover-button-effect/result.gif)

## creative-splitted-button-effect

![markdown picture](./creative-splitted-button-effect/result.gif)

## creative-border-swapping-button-effect

![markdown picture](./creative-border-swapping-button-effect/result.gif)

## creative-border-growing-button-effect

![markdown picture](./creative-border-growing-button-effect/result.gif)

## creative-first-letter-rotating-button-effect

![markdown picture](./creative-first-letter-rotating-button-effect/result.gif)

## creative-4-borders-growing-button-effect

![markdown picture](./creative-4-borders-growing-button-effect/result.gif)

## creative-wavy-button-effect

![markdown picture](./creative-wavy-button-effect/result.gif)

## creative-2-cuts-button-effect

![markdown picture](./creative-2-cuts-button-effect/result.gif)

## creative-2-parts-skewed-button-effect

![markdown picture](./creative-2-parts-skewed-button-effect/result.gif)

## creative-pulsing-button-effect

![markdown picture](./creative-pulsing-button-effect/result.gif)

## diagonal-swipe-button-effect

![markdown picture](./diagonal-swipe-button-effect/result.gif)

## creative-image-effect-1

![markdown picture](./creative-image-effect-1/result.gif)

## creative-image-effect-2

![markdown picture](./creative-image-effect-2/result.gif)

## creative-image-effect-3

![markdown picture](./creative-image-effect-3/result.gif)

## creative-image-effect-4

![markdown picture](./creative-image-effect-4/result.gif)

## creative-image-effect-5

![markdown picture](./creative-image-effect-5/result.gif)

## creative-image-effect-6

![markdown picture](./creative-image-effect-6/result.gif)

## creative-image-effect-7

![markdown picture](./creative-image-effect-7/result.gif)

## creative-image-effect-8

![markdown picture](./creative-image-effect-8/result.gif)

## creative-image-effect-9

![markdown picture](./creative-image-effect-9/result.gif)

## creative-image-effect-10

![markdown picture](./creative-image-effect-10/result.gif)

## creative-growing-borders-menu-effect

![markdown picture](./creative-growing-borders-menu-effect/result.gif)

## creative-background-and-borders-menu-effect

![markdown picture](./creative-background-and-borders-menu-effect/result.gif)

## creative-splitted-background-menu-effect

![markdown picture](./creative-splitted-background-menu-effect/result.gif)

## creative-2-moving-bottom-borders-menu-effect

![markdown picture](./creative-2-moving-bottom-borders-menu-effect/result.gif)

## creative-menu-border-rotation-effect

![markdown picture](./creative-menu-border-rotation-effect/result.gif)

## borders-and-a-background-menu-effect

![markdown picture](./borders-and-a-background-menu-effect/result.gif)

## creative-colorful-layered-menu-effect

![markdown picture](./creative-colorful-layered-menu-effect/result.gif)

## background-translation-card-effect

![markdown picture](./background-translation-card-effect/result.gif)

## creative-double-face-card-effect

![markdown picture](./creative-double-face-card-effect/result.gif)

## creative-layered-card-hover-effect

![markdown picture](./creative-layered-card-hover-effect/result.gif)

## smoky-text-effect-using-css-transforms

![markdown picture](./smoky-text-effect-using-css-transforms/result.gif)

## fill-text-effect-on-hover

![markdown picture](./fill-text-effect-on-hover/result.gif)

## social-media-icons-hover-effect

![markdown picture](./social-media-icons-hover-effect/result.gif)

## creative-rotated-text-boder-effect

![markdown picture](./creative-rotated-text-boder-effect/result.gif)

## using-css-animation-floating-text

![markdown picture](./using-css-animation-floating-text/result.gif)

## using-css-animation-rotating-loading-effect

![markdown picture](./using-css-animation-rotating-loading-effect/result.gif)

## using-css-animation-driving-a-car

![markdown picture](./using-css-animation-driving-a-car/result.gif)

## using-css-animation-text-rotator

![markdown picture](./using-css-animation-text-rotator/result.gif)

## using-css-animation-button-shaking-hover

![markdown picture](./using-css-animation-button-shaking-hover/result.gif)

## using-css-animation-button-animated

![markdown picture](./using-css-animation-button-animated/result.gif)

## using-css-animation-lighting-text

![markdown picture](./using-css-animation-lighting-text/result.gif)

## using-css-animation-heartbeat

![markdown picture](./using-css-animation-heartbeat/result.gif)

## using-css-animation-text-background-animated

![markdown picture](./using-css-animation-text-background-animated/result.gif)
