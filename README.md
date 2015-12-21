# PlayMall API

## Error handle
通用API错误用rescume_from 进行异常处理

### 错误码约定
错误码以http status code做为前缀, 后面4位指定这个http status code对应这类错误的具体
代码。

以400(bad reqeuest)为例:
400 0001: 手机号已注册

### 错误码后四位分配
|姓名|错误码前缀|示例|
|---|---|---|
|刘军|0|0001|
|赵子豪|1|10001|
|李浩|2|20001|

### 错误码对照表
|错误码|错误说明|
|---|---|
|4000001|手机号已注册|
|4000002|手机号未注册|
|4000003|验证码错误|
|4000004|用户被禁用|
|4000005|手机号或密码错误|
|4000006|原密码不正确|
|4000007|新旧密码一致|
