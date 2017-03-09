#Blog
##1.功能强大的开源博客系统
它是一个开源的博客系统，用Flask开发，具有简洁的界面和强大的后台管理，
<br/>使用它可以轻松架设属于您自己的个人博客网站！
```
作者亲测，在网络环境良好的情况下，最快用3分钟即可以把Blog部署并上线！
```
<br/>已经有很多网友对Blog进行了体验，我们欢迎您使用，并且能就使用过程中的一些问题给予作者意见和建议。
##2.值得一学的源代码
如果你初学Python Web，或者你从来没有进行过一个完整项目的开发，或者你以后想从事Python web 开发相关的工作，
<br/>不妨阅读并学习一下Blog的源代码。
```
Blog采用结构清晰的MVC模式来设计开发
```
##3.技术支持
如果你在部署和使用过程中有疑问，请给作者留言：
<br/>作者个人博客网站：http://deepdark.cc
<br/>微博：http://weibo.com/geeksunc
<br/>知乎：https://www.zhihu.com/people/0x0004
##Demo
[0x0004's blog](deepdark.cc) is powered by Blog
##Dependency
###Backend
* Flask  
    * Flask-script
    * Flask-Login
    * Flask-WTF
    * Flask-SQLAlchemy
    * Flask-Migrate
    * Flask-WTF
    * Flask-Bootstrap
    * Flask-Moment
* WTForms
* SQLAlchemy

##How to run it ?

```
~/Blog# python manage.py deploy product
```
```
~/Blog# gunicorn --workers 4 manage:app -b 127.0.0.1:8080
```
###Enjoy it.:coffee::lollipop:
