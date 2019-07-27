
# 介绍

> 商品展示组件，一行展示一个商品。

## 预览
![组件效果](image/goods-style1.png)

## 引用
```json
"usingComponents": {
  "em-goods": "path/to/blocks/goods-yf/goods-style1"
}
```

## 案例

基本使用方法
```html
<yz-goods-style1
    classname="wrap"
    name='[每人限购一份] 小葱 70g/份'
    sold='100000'
    surplus='1923'
    thumb="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1563613406943&di=32463e9ffc64925fb152d8b4493b4b36&imgtype=0&src=http%3A%2F%2Fs9.sinaimg.cn%2Fmw690%2F006hikKrzy7pzDEQbFe68%26690"
    price='10'
    discountPrice='30'
  >
  <view class="top">特价</view>
  </yz-goods-style1>
```

## 属性

| 属性 | 说明 | 类型 | 默认值 |
| --- | --- | --- | --- |
| classname | 如果填写则必须填写“wrap” | String | wrap |
| name | 商品介绍 | String | null |
| sold | 已经销售的商品件数，非必填项 | Number | null |
| surplus | 剩余商品数量，非必填项 | Number | null |
| thumb | 图片链接 | String | null |
| price | 商品现价 | Number | null |
| discountPrice | 商品原价 | Number | null |

备注：之所以属性不减化成Object的形式，主要考虑到用户的数据结构可能和我们定义的不一样，比如我们用name作为商品介绍，用户可能用title,这样就有冲突了，反而不好设置


## 事件

|事件名	| 说明 | 参数|
| --- | --- | --- |
|onclick	| 暂时没有 | goods:商品数据|
