## 授权接口

GET
`
https://rfinex.vip/oauth/authorize
`

参数

```
	app_id:	系统分配的app_id
	call_back_url:	用户授权后的回调地址,此地址的host必须与预设的回调host一致
```

返回请求类型 GET

返回请求的URL call_back_url

返回参数
``` 
 code：授权码，10分钟有效期
```
