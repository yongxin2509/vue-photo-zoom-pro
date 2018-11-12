# vue-photo-zoom-pro

> Vue(2.x) 图片放大器

[demo](https://codepen.io/xbup/project/editor/AjnEgE)

## Get Start

```js
npm install vue-photo-zoom-pro
```
## Settings

| Prop  | Type  |	Default |Note|
| ------------ | ------------ | ------------ | ------------ |
|url|String||图片地址(photo url)|
|high-url|String||更清晰的图片,若不提供会采用url(more detailed photo url)|
|scale|Number| 3|放大倍数(scale)|
|type|String|square|放大镜类型(circle,square)(magnifying glass type  (circle,square))|
|hide-zoom|Boolean|false|隐藏放大镜，图像加载时不会显示放大镜(hide magnifying)|
|out-show|Boolean|true| 图片展示区域会在图片外部(image will be displayed on the outside)|
|move-event|当需要在外部监听移动事件时,请通过该字段传入事件（必须包含pageX,pageY）(Object/mouseEvent|null|When you need to listen for moving events outside the component)|
|leave-event|当需要在外部监听离开事件时，请通过该字段传入事件(Object/mouseEvent|null|When you need to listen for leaving events outside the component)|

|Method|Note|
| ------------ | ------------ |
|init|重置放大镜位置(reset zoom position)|

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright (c) 2018-present, xbup