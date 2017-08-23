# ele-for-pc

项目实训时，小组制作的，本人负责“登录页面”、“首页”、“商家列表“，内容样式参考原网址: https://github.com/bailicangdu/node-elm 
<br/>
首页和商家列表使用了开放接口，直接在github上演示会有跨域问题，数据无法显示，其他页面使用静态JSON文件，无影响 
<br/>
个人在制作项目中遇到的问题有： 
<br/>
1.路由拦截，防止未登录的情况下，手动输入路径，用到vue-router的beforeEach()钩子解决 
<br/>
 2.keep-alive,由于首页有较多AJAX请求，所以想路由返回时，页面不刷新，保留组建状态 
