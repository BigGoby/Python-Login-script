# Python-Login-script
不定时更新一些国内网站py的登录脚本

## 触电新闻
https://media.itouchtv.cn/login

    - 提交信息时账号密码明文提交，无验证码
    - 登录后进行相关请求时需要生成sign，并且GET和POST请求时加密方式不一致
    
   ![Image text](https://github.com/BigGoby/Python-Login-script/raw/master/image/12.png)
    
## 豆瓣电影
https://www.douban.com/

    - 无验证码，密码明文提交
    
   登录失败
   ![Image text](https://github.com/BigGoby/Python-Login-script/raw/master/image/9.png)
    
   登录成功
   ![Image text](https://github.com/BigGoby/Python-Login-script/raw/master/image/10.png)
   
## 凤凰新闻
https://id.ifeng.com/

    - PC浏览器页面实现
    - 登录需要验证码
    - 其中密码以明文提交

## 今日头条
https://www.toutiao.com/
https://m.toutiao.com/

    - 头条账号登陆存在验证码
    - PC-Web页面为滑动验证码
    - 移动端页面为图片字母数字验证码
    - 实现：先经过移动端页面进行登录后，再切换至PC页面
    
    验证码经过base64编码 可在浏览器中直接查看 / 或者使用 http://tool.chinaz.com/tools/imgtobase/ 进行解码
    说明: 为了对接第三方验证码处理平台 比如:百度Ai开放平台
    
   登录失败:
   ![Image text](https://github.com/BigGoby/Python-Login-script/raw/master/image/4.png)
    
   登录成功:
   ![Image text](https://github.com/BigGoby/Python-Login-script/raw/master/image/5.png)
    
## 搜狐新闻
https://m.passport.sohu.com/

    - 采用移动端浏览器Web页面进行登录
    - 无验证码，密码采用md5加密
    
   登录失败:
   ![Image text](https://github.com/BigGoby/Python-Login-script/raw/master/image/7.png)
    
   登录成功:
   ![Image text](https://github.com/BigGoby/Python-Login-script/raw/master/image/6.png)
    
 ## 新浪微博
 https://weibo.com/
 
    - 用户名和密码均加密后提交，其中密码采用rsa加密
    - 验证码下载到本地,人工输入,如有需求可更改
    
   验证码输入:
   ![Image text](https://github.com/BigGoby/Python-Login-script/raw/master/image/1.png)
    
   项目目录:
   ![Image text](https://github.com/BigGoby/Python-Login-script/raw/master/image/2.png)
    
   登录成功:
   ![Image text](https://github.com/BigGoby/Python-Login-script/raw/master/image/3.png)
    
    
    
    
