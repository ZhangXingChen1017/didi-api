# 获取城市Id

## 接口说明

通过坐标获取城市id

## 请求地址

`/v1/city/getId`

## 请求方式

POST

## 请求参数

| 名称 | 类型  | 必选 | 描述 |
| ---- | ----- | ---- | ---- |
| lat  | float | yes  | 纬度 |
| lng  | float | yes  | 经度 |

## 返回结果

```json
{
  "errno": 0,
  "errmsg": "SUCCESS",
  "data": {
    "cityid": 1
  }
}
```

## 返回说明

| 返回字段 | 字段类型 | 字段说明 |
| -------- | -------- | -------- |
| errno    | int      | 错误码   |
| errmsg   | String   | 错误信息 |
| data     | object   |          |
| cityid   | int      | 城市id,  |
