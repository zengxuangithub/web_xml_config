#  web.xml 配置
## 作用
-  配置jsp
-  配置Servlet


```
<servlet>

    <servlet-name>timeServlet</servlet-name>
    <servlet-class>test.timeServlet</servlet-class>
    <!--配置应用启动时 创建该servlet实例，也可以通过Annotation注解的方式配置servlet-->
    <load-on-startup>1</load-on-startup>
</servlet>
```
-  配置listener
-  配置Filter
-  配置标签库
-  配置JAAS授权认证
-  配置资源引用
-  配置首页


//依次寻找以下页面作为网站首页
```
    
    <welcome-file-list>
    
    <welcome-file>index.html</welcome-file>
    <welcome-file>index.htm</welcome-file>
    <welcome-file>index.jsp</welcome-file>

</welcome-file-list>
```