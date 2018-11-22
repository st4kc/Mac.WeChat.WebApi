# 微信mac协议，webapi版本。
 请进入  http://www.keduoduo.online/ 进行注册授权<br/>
 注册后将授权配置到web.config即可使用<br/>
 支持功能如下:<br/>

<a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=3194af004cbc013eff0a61b99a46ae6f66c2c1f1fc62a9cdf58de1fd2b471058">加入qq群</a>
<br/>
<a href="https://github.com/changtuiqie/Mac.WeChat.WebApi/blob/master/API.txt" title="支持功能API文档">支持功能API文档（直接调用Xzy.IPAD.Core.dll）</a><br/>

如不行直接调用Xzy.IPAD.Core.dll 可以通过部署该项目 使用websocket+webapi的形式调用

该项目使用websocket和webapi的形式进行服务端与前端通讯，
查看使用方法查看<a href="https://github.com/changtuiqie/Mac.WeChat.WebApi/blob/master/WebDemo/www/Test.html"> www/test.html </a>

创建websocket链接以后，服务端会返回登录二维码 ，登录以后服务端通过websocket返回好友列表 日志 及群列表等信息，其余接口使用http （post/get）

具体接口查看如下：

使用vs2017 运行后，打开项目地址 http://localhost/swagger 即可查看webapi接口文档。

测试地址：http://macwechat.keduoduo.online/swagger/ui/index#/WeChat