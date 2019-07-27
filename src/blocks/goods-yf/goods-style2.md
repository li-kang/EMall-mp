
# 介绍

> 商品展示组件，一行展示两个商品。

## 预览
![组件效果](image/goods-style2.png)

## 引用
```json
"usingComponents": {
  "em-goods": "path/to/blocks/goods-yf/goods-style2"
}
```

## 案例

基本使用方法
```html
<yz-goods-style2
    class="wrap"
    name='[每人限购一份] 小葱70g/份'
    sold='100000'
    thumb="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1563561838686&di=98c5d8b4333f79bf40f9184fe42be11f&imgtype=0&src=http%3A%2F%2Fa1.att.hudong.com%2F16%2F05%2F01300000089596120609052312176.jpg"
    price='10'
    discountPrice='30'
    slottop="爆品"
    slotbot="省4.89"
  >
  </yz-goods-style2>
```

## 属性

| 属性 | 说明 | 类型 | 默认值 |
| --- | --- | --- | --- |
| name | 商品名称 | String | null |
| sold | 已经销售的商品件数 | Number | null |
| thumb | 图片链接 | String | null |
| price | 商品现价 | Number | null |
| discountPrice | 商品原价 | Number | null |
| slottop | 图片上部插件 | String | null |
| slotbot | 图片底部插件 | String | null |
备注：之所以属性不减化成Object的形式，主要考虑到用户的数据结构可能和我们定义的不一样，比如我们用name作为商品介绍，用户可能用title,这样就有冲突了，反而不好设置

## 事件

|事件名	| 说明 | 参数|
| --- | --- | --- |
|onclick	| 暂时没有 | goods:商品数据|
