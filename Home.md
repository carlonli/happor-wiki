#What's happor
**简单地说，happor是一个基于netty的小型web controller框架。**

在Java世界中，一般使用tomcat+各种MVC框架开发web应用。但是对于REST API开发，MVC框架就显得过重了，我们需要的也许只是一个controller框架。
> happor实现了以下特性：
* HTTP消息链式处理（根据URI路由）
* 支持同步handler，异步handler，转发handler
* 支持filter
* 支持URI自动解析注入
* 可与spring集成，提供自定义tag
* 支持注解开发

#Documents

1. [第一个例子](FirstDemo)