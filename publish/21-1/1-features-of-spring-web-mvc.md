# 21.1.1 Spring Web MVC的新特性

> Spring Web Flow
>
> Spring Web Flow (SWF) 意在成为web应用中的页面流(page flow)管理中最好的解决方案。
>
> SWF在Servlet环境和Portlet环境下集成了现有的框架，如Spring MVC和JSF等。如果你的业务流程有一个贯穿始终的模型，而非单纯分立的请求，那么SWF可能是适合你的解决方案。
>
> SWF允许你将逻辑上的页面流抽取成独立可复用的模块，这对于构建一个web应用的多个模块是有益的。that guide the user through controlled navigations that drive business processes.
>
> 关于SWF的更多信息，请访问[Spring Web Flow的官网](http://projects.spring.io/spring-webflow/)。

Spring的web模块支持许多web相关的特性：

* 清晰的职责分离。每个角色——控制器，验证器，命令对象，表单对象，模型对象，`DispatcherServlet`，处理器映射，视图解析器，等等许多——的工作，都可以由相应的对象来完成。
* 强大、直观的框架和应用bean的配置。这种配置能力包括能够从不同的上下文中进行简单的引用，比如在web控制器中引用业务对象、验证器等。
* 强大的适配能力、非侵入性和灵活性。Spring MVC支持你定义任意的控制器方法签名，在特定的场景下你还可以添加适合的注解（比如`@RequestParam`、`@RequestHeader`、`@PathVariable`等）
* 可复用的业务代码，使你远离重复代码。你可以使用已有的业务对象作为命令对象或表单对象，而不需让它们去继承一个框架提供的什么基类。
* 可定制的数据绑定和验证。类型不匹配仅被认为是应用级别的验证错误，错误值、本地化日期、数字绑定等会被保存。你不需要再在表单对象使用全String字段，然后再手动将它们转换成业务对象。
* 可定制的处理器映射和视图解析。处理器映射和视图解析策略从简单的基于URL配置，到精细专用的解析策略，Spring全都支持。在这一点上，Spring比一些依赖于特定技术的web框架要更加灵活。
* 灵活的模型传递。Spring使用一个名称/值对的Map来做模型，这使得模型很容易集成、传递给任何类型的视图技术。
* 可定制的本地化信息、时区和主题解析。支持用/不用Spring标签库的JSP技术，支持JSTL，支持无需额外配置的Velocity模板，等等。
* 一个简单但功能强大的JSP标签库，通常称为Spring标签库，它提供了诸如数据绑定、主题支持等一些特性的支持。这些定制的标签为标记（markup）你的代码提供了最大程度的灵活性。关于标签库描述符（descriptor）的更多信息，请参考附录[第42章 Spring JSP标签库](http://docs.spring.io/spring-framework/docs/4.2.4.RELEASE/spring-framework-reference/html/spring-tld.html)
* 一个Spring 2.0开始引入的JSP表单标签库。它让你在JSP页面中编写表单简单许多。关于标签库描述符（descriptor）的更多信息，请参考附录 [第43章 Spring表单的JSP标签库](http://docs.spring.io/spring-framework/docs/4.2.4.RELEASE/spring-framework-reference/html/spring-form-tld.html)
* 新增生命周期仅绑定到当前HTTP请求或HTTP会话的Bean类型。严格来说，这不是Spring MVC自身的特性，而是Spring MVC使用的上下文容器`WebApplicationContext`所提供的特性。这些bean的scope在[6.5.4 请求、会话及全局会话scope](http://docs.spring.io/spring-framework/docs/4.2.4.RELEASE/spring-framework-reference/html/beans.html#beans-factory-scopes-other)一节有详细描述。
