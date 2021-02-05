# AutoCheck - 内测版

## 简陋的使用方法

先 Fork 一份到自己仓库，然后在 Settings -> Secrets 添加如下信息:
> 注意: 名字不能乱取，放心，这个别人是无法看到的
+ ZERO_USER: 零组的登录帐号
+ ZERO_PASSWD: 零组的登录密码
+ API_KEY: 第三方验证码识别API，内测期间找我要即可
+ API_SECRET: 第三方验证码识别API，内测期间找我要即可

添加完如下图
![step1.png](./doc/step1.png)

然后修改 [本README.md文件](https://github.com/TARI0510/AutoCheck/blob/master/README.md) ，加个空格，啥都行，提交就会自动执行了。
![step2.png](./doc/step2.png)

结果一般如下, 然后这个脚本是每天早上6点自动执行的
![result.png](./doc/result.png)

有问题欢迎提 issue