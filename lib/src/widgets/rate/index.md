---
widget: rate
title: 评分
---

对评价进行展示，对事物进行快速的评级操作。

## `widget` 自定义属性

参数 | 说明 | 类型 | 默认值
----|------|-----|------ 
count | 总星数 | `number` | `5`
allowClear | 是否允许再次点击后清除 | `boolean` | `true`
allowHalf | 是否允许半选 | `boolean` | `false`
autoFocus | 自动获取焦点 | `boolean` | `false`

## Demo

**基础**

```json
"rate": {
    "type": "number",
    "title": "评价",
    "default": 3,
    "widget": "rate"
}
```
