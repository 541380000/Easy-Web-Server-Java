# Easy-Web-Server-Java
A simple web server like Tomcat developed in Java, and with different and fast-changing version, you can clearly see the improvement.
这是一款简易的Web服务器，使用JavaSE的基本工具，实现了主页、404页面、登录、注册、动态页面等最原始的功能。

        通过敏捷开发的方式，14个小版本快速更迭，能够看到代码的快速变化与结构调整。

        项目实现的具体功能有：

1、对Http请求的解析、基本的Http响应的发送

2、多线程接收Http请求，进行响应

3、针对不同的业务请求，将具体的servlet业务处理类与服务器代码分开，将动态数据和静态页面模板分开，大大减小了耦合

4、支持中文编解码，能够使用thymeleaf生成动态网页

14个版本的改进，详见项目的schedula表格
请在Eclipse中导入打开
