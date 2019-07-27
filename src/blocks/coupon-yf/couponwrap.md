
# 介绍

> 优惠券页面展示组件，展示优惠券模块。

## 预览
![组件效果](image/couponwrap.png)

## 引用
```json
"usingComponents": {
  "em-goods": "path/to/blocks/coupon-yf/couponwrap"
}
```

## 案例

基本使用方法
```html
<yz-couponwrap acprops="{{acprops}}" noprops="{{noprops}}"></yz-couponwrap>
```

## 属性
| 属性 | 说明 | 类型 | 默认值 |
| --- | --- | --- | --- |
| acprops | 激活状态的优惠券,具体数据查看下表 | Array | null |
| noprops | 失效状态的优惠券,具体数据查看下表 | Array | null |

| key | 说明 | 类型 | 默认值 |
| --- | --- | --- | --- |
| switcherac | 是否为激活状态，即字体是否显示红色 | String,Boolean | "true" |
| describe | 底部描述信息 | String | null |
| price | 折扣价 | String | null |
| limit | 使用门槛限制 | String | null |
| detail | 如：最多优惠12元 | String | null |
| name | 优惠券名称 | String | null |
| effective | 如：有效期：2019.08.10 - 2019.12.30 | String | null |

## 事件

|事件名	| 说明 | 参数|
| --- | --- | --- |
|暂时没有 |
