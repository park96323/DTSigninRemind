# DTSigninRemind

开发平台为Visual Studio 2015 Update3

源码是C#

UI框架用的SUI

    http://m.sui.taobao.org/

本机调试方法

    编辑 DTSigninRemind\.vs\config\applicationhost.config 文件167行，
    添加<binding protocol="http" bindingInformation="*:端口:你的真实域名网址" />
    保存后，将vs2015用管理员方式运行即可。

需要修改的地方:

    appsettings.json
    AgentID:钉钉微应用的AgentID
    CorpID:钉钉微应用设置里面的CorpID
    CorpName：企业名称
    CorpSecret:钉钉微应用设置里面的CorpSecret
    UserId：用于帮助页面人工服务调用电话，被叫方的钉钉userid，可以设置成管理员的userid调试
    Url:  钉钉后台微应用设置中的首页地址完全一致
          默认应为 http://你的网址/SigninRemind?id=你的CorpID&dd_nav_bgcolor=FF5E97F6
          nav_bgcolor参数为设置导航栏颜色
    UserName:新用户注册向管理员推送oa消息的默认用户名
    SmsCorpID:短信平台企业ID
    SmsLoginName:短信平台用户名
    SmsPasswd:短信平台密码
	DefaultConnection：数据库连接字符串
    
以下是项目截图示例

<div>
    <ul>
        <li>
            <img src="https://github.com/icodegame/DTSigninRemind/blob/master/src/DTSigninRemind/demopng/IMG_2310.PNG" />
        </li>
        <li>
            <img src="https://github.com/icodegame/DTSigninRemind/blob/master/src/DTSigninRemind/demopng/IMG_2308.PNG" />
        </li>
        <li>
            <img src="https://github.com/icodegame/DTSigninRemind/blob/master/src/DTSigninRemind/demopng/IMG_2309.PNG" />
        </li>
        <li>
            <img src="https://github.com/icodegame/DTSigninRemind/blob/master/src/DTSigninRemind/demopng/IMG_2311.PNG" />
        </li>
        <li>
            <img src="https://github.com/icodegame/DTSigninRemind/blob/master/src/DTSigninRemind/demopng/IMG_2312.PNG" />
        </li>
        <li>
            <img src="https://github.com/icodegame/DTSigninRemind/blob/master/src/DTSigninRemind/demopng/IMG_2313.PNG" />
        </li>
        <li>
            <img src="https://github.com/icodegame/DTSigninRemind/blob/master/src/DTSigninRemind/demopng/IMG_2314.PNG" />
        </li>
        <li>
            <img src="https://github.com/icodegame/DTSigninRemind/blob/master/src/DTSigninRemind/demopng/IMG_2315.PNG" />
        </li>
    </ul>
</div>