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
* 可与HTTP容器分离，支持代码动态部署

#Documents

1. [第一个例子](Doc001.FirstDemo)
2. [happor基本概念](Doc002.Concept)
3. [最基础的使用方式](Doc003.BasicUse)
4. [controller的类型与使用说明](Doc004.ControllerType)
5. [简化的使用方式：自动扫描controllers](Doc005.AutoScanControllers)
6. [URI自动解析与注解注入](Doc006.UriParser)
7. [与spring容器结合](Doc007.WorkWithSpring)
8. [使用HTTP容器实现代码动态部署](Doc008.ContainerServer)
