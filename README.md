# 非官方 Work Wechat webhook Golang SDK

## 此工程仅封装了 Work Wechat 的 webhook 部分的请求

## 使用

将accessToken拷贝出来，然后执行下面方法即可

```Go
webhook := workwechat.Webhook(accessToken)
webhook.SendTextMsg("这是一个没有AT的文本消息", false)
```

## License

This project is licensed under the MIT License.
See the [LICENSE](https://github.com/rocklau/webhook_workwechat/blob/master/LICENSE) file
for the full license text.
