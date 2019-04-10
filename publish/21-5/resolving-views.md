# 21.5 视图解析

所有web应用的MVC框架都提供了视图相关的支持。Spring提供了一些视图解析器，它们让你能够在浏览器中渲染模型，并支持你自由选用适合的视图技术而不必与框架绑定到一起。Spring原生支持JSP视图技术、Velocity模板技术和XSLT视图等。你可以阅读文档的[第22章 _视图技术_](http://docs.spring.io/spring-framework/docs/4.2.4.RELEASE/spring-framework-reference/html/view.html "22. View technologies")一章，里面讨论了如何集成并使用许多独立的视图技术。

有两个接口在Spring处理视图相关事宜时至关重要，分别是视图解析器接口`ViewResolver`和视图接口本身`View`。视图解析器`ViewResolver`负责处理视图名与实际视图之间的映射关系。视图接口`View`负责准备请求，并将请求的渲染交给某种具体的视图技术实现。
