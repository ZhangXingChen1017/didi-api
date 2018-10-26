# 获取请求Id

## 接口说明

获取叫车请求id，没有id无法叫车

## 请求地址

`/v1/order/getId`

## 请求方式

POST

## 请求参数

无

## 返回结果

```json
{
    "errno": 0,
    "errmsg": "SUCCESS",
    "data": {
        "order_id": "4880109188406595918"
    }
}
```

## 返回说明

| 返回值字段    | 字段类型 | 字段说明 |
| ------------- | -------- | -------- |
| errno         | int      | 错误码   |
| errmsg        | String   | 错误信息 |
| data          | object   |          |
| data.order_id | String   | 返回的id |