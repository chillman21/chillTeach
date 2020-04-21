# chillTeach
chillTeach ：SpringBoot+SpringCloud分布式轻网课平台
![az](https://ftp.bmp.ovh/imgs/2020/04/6b0c7c591da7eb5a.png )
该项目实现了目前网课平台所拥有的包括课程、教师、订单、用户等方面的绝大多数功能，采用完全前后端分离模式，服务器端使用SpringBoot+SpringCloud的微服务架构，共9个模块，每个分布式模块拥有自己独立的分工。使用Nacos作为配置中心和注册中心，Feign作为客户端，使用nginx进行请求的转发。项目中使用MyBatisPlus结合Mybatis进行持久层的操作，使用了Redis作为中间件进行首页数据和短信验证码的缓存。用户方面使用了JWT的解决方案实现了用户手机短信注册登录，采用OAuth2的模式支持第三方授权登录，项目中整合了Spring Security进行了后台权限控制。该项目的前端分为前台与后台，网站用户端前台使用vue+element-ui，网站后台管理使用nuxt，都用到了axios发送ajax请求。
