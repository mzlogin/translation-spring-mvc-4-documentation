# 21.16 配置Spring MVC

[21.2.1 WebApplicationContext中特殊的bean类型](http://docs.spring.io/spring-framework/docs/4.2.4.RELEASE/spring-framework-reference/html/mvc.html@mvc-servlet-special-bean-types "21.2.1 Special Bean Types In the WebApplicationContext")小节和[21.2.2 默认的DispatcherServlet配置](http://docs.spring.io/spring-framework/docs/4.2.4.RELEASE/spring-framework-reference/html/mvc.html#mvc-servlet-config "21.2.2 Default DispatcherServlet Configuration")小节解释了何谓Spring MVC的特殊bean，以及`DispatcherServlet`所使用的默认实现。在这小节中，你将了解配置Spring MVC的其他两种方式：MVC Java编程配置，以及MVC XML命名空间。

MVC Java编程配置和MVC命名空间都提供了相似的默认配置，以覆写`DispatcherServlet`的默认值。目标在于为大多数应用软件免去创建相同配置的麻烦，同时也想为配置Spring MVC提供一个更易理解的指南、一个简单的开始点，它只需要很少或不需任何关于底层配置的知识。

你可以选用MVC Java编程配置或MVC命名空间的方式，这完全取决于你的喜好。若你能读完后面的小节，你会发现使用MVC Java编程配置的方式能更容易看到底层具体的配置项，并且能对创建的Spring MVC bean有更细粒度的定制空间。不过，我们还是从头来看起吧。
