---
title: API 鉴权方式
---

JieKou AI API 使用 `请求头` 中的 Authorization 字段携带 API 密钥进行身份认证。您可以在 [设置页面](https://tokensmind.ai/token) 查看和管理您的 API 密钥。

```js theme={null}
{
    "Authorization": "Bearer {{API Key}}"
}
```
