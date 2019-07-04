# shiro+buji-pac4j

buji-pac4j+shiro+cas+springmvc SSO

## Development server

Run mvn jetty:run -Djetty.port=2019


## 注销问题

1）url.properties中如果用localhost 那么 注销就不会成功,修改成本地ip

2）注销成功不跳到登录页面

  https://apereo.github.io/cas/5.3.x/installation/Configuration-Properties.html#logout 

  https://blog.csdn.net/qq_34021712/article/details/81515317


