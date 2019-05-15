# Toolkit

每个开发者都应该有一个自己的工具箱，在将来漫长的职业生涯中，这些工具可以为我省下宝贵的时间，并帮助我更好的组织个人知识库。    

# Source of Inspiration

* 


----- 

# 前端
## UI

* [open logos](https://openlogos.org/)：一位老外给开源项目做的免费LOGO设计，需要联系作者申请免费版权。

### Design Guide & Components
* Google
  * [Meterial Design](https://material.io/design/): 大名鼎鼎的 Google Meterial Design，基于这套 style guide 下，提供了 Android，iOS，Web，Flutter 相应的组件库。
  * [Meterial Design for Web](https://github.com/material-components/material-components-web): 针对 JS 的组件库，不需依赖框架
  * [Meterial Design for React](https://github.com/material-components/material-components-web-react): React 组件库
  * [Meterial Design for Android](https://github.com/material-components/material-components-web-android): Android 组件库
  * [Meterial Design for iOS](https://github.com/material-components/material-components-web-ios): iOS 组件库
  * [Meterial Design for Flutter](https://github.com/material-components/material-components-web-flutter): Flutter 组件库
* 有赞
  * [Zan Design](https://design.youzan.com/)：有赞设计规范
  * [Zan UI](https://www.youzanyun.com/zanui): 有赞基于设计规范的前端组件库，包含了：PC端（Zent），移动端（Vant），小程序端（Vant-Wxapp）
* 饿了么
  * [Element UI](https://element.eleme.cn): 没有按端来区分设计元素，统一套设计组件，分别有：React、Vue（主打）、Angular 版本
* Semantic
  * [Semantic UI](https://element.eleme.cn): 一套老牌ui了，没有 style guide，直接给能开箱即用组件。不需要依赖框架，css 配合 jQuery 就能使用。
  * [Semantic React](https://react.semantic-ui.com/): React 版本的组件
  * [Semantic Ember](https://github.com/Semantic-Org/Semantic-UI-Ember): EmberJS 版本的组件库，不过很久不更新了。

## 动画&CSS
* [GreenSock | GSAP](https://greensock.com/gsap): CSS动画类库
* [easing](http://robertpenner.com/easing/): 函数式动画库
* [create.js](https://createjs.com/): 一套制作 HTML5 丰富交互的工具集合
* [pixi.js](http://www.pixijs.com/): 2D WebGL 动画库
* [css tricks](https://css-tricks.com/): 一个有很多CSS技巧的博客网站
* [cssreference](http://cssreference.io/): 一个动态展示各种CSS的学习库

## 图表
* [D3]():
* [ChartJS](https://github.com/chartjs/Chart.js): 一个UI很 Material Design 的图表库
* [Echarts](https://github.com/ecomfe/echarts): 百度开发的图表库

## 浏览器 & 兼容性
* [can i use](): 罗列了各大浏览器对于前端的新特性的支持情况
* [html5shiv](https://github.com/aFarkas/html5shiv): 可以让旧浏览器使用HTML5标签

## 工程化
* [webpack](): 资源打包工具
* [html-webpack-plugin](https://github.com/ampedandwired/html-webpack-plugin): 针对HTML处理的webpack插件
* [grunt](): 任务执行工具
* [gulp](): 任务执行工具
  - [gulp-load-plugins](https://www.npmjs.com/package/gulp-load-plugins)：自动加载 `package.json` 中的 gulp 插件
  - [gulp-rename](https://www.npmjs.com/package/gulp-rename)： 重命名
  - [gulp-uglify](https://www.npmjs.com/package/gulp-uglify)：文件压缩
  - [gulp-concat](https://www.npmjs.com/package/gulp-concat)：文件合并
  - [gulp-less](https://www.npmjs.com/package/gulp-less)：编译 less
  - [gulp-sass](https://www.npmjs.com/package/gulp-sass)：编译 sass
  - [gulp-clean-css](https://github.com/scniro/gulp-clean-css)：压缩 CSS 文件
  - [gulp-htmlmin](https://github.com/jonschlinkert/gulp-htmlmin)：压缩 HTML 文件
  - [gulp-babel](https://github.com/babel/gulp-babel): 使用 babel 编译 JS 文件
  - [gulp-jshint](https://www.npmjs.com/package/gulp-jshint)：jshint 检查
  - [gulp-imagemin](https://github.com/sindresorhus/gulp-imagemin)：压缩jpg、png、gif等图片
  - [gulp-livereload](https://github.com/vohof/gulp-livereload)：当代码变化时，它可以帮我们自动刷新页面
* [html-minifier](https://github.com/kangax/html-minifier): HTML压缩工具（提供Grunt、Gulp版本）
* [UglifyJS](https://github.com/mishoo/UglifyJS2): JS脏化工具

------

# Node.js
* [SailsJS](https://github.com/balderdashy/sails): NodeJS企业级开发框架
* [loopback](https://github.com/strongloop/loopback): StrongLoop出品的NodeJS企业级开发框架
* [koa](https://github.com/koajs/koa): 服务器开发框架
* [express](https://github.com/expressjs/express): 服务器开发框架
* [oauth2orize](https://github.com/jaredhanson/oauth2orize): OAuth2.0的实现
* [OAuthorize](https://github.com/jaredhanson/oauthorize): OAuth 的实现
* [node-oauth](https://github.com/ciaranj/node-oauth): OAuth1.0、OAuth2.0 的实现
* [passport](https://github.com/jaredhanson/passport): 封装授权的逻辑，支持本地登录以及OAuth第三方登录
* [forge](https://github.com/digitalbazaar/forge): 提供了大部分常见的传输层加密算法的实现（提供Browser版本）
* [superagent](https://github.com/visionmedia/superagent): 封装HTTP、Ajax实现（提供Browser版本）
* [supertest](https://github.com/visionmedia/supertest): 基于superagent,提供用于单元测试的API与封装实现
* [i18n-node](https://github.com/mashpie/i18n-node): 国际化实现
* [moment](https://github.com/moment/moment): 时间处理的工具库
* [consolidate.js](https://github.com/tj/consolidate.js): 集成常见的NodeJS模板引擎（TJ大神出品）
* [debug](https://github.com/visionmedia/debug): 调试工具
* [nodegreen](http://node.green/): 罗列了 NodeJS 个版本对于新的 ECMAScript 语法支持情况
* [mocha](): 测试框架
* [zombie](http://zombie.js.org/): 测试框架
* [istanbul](): 测试覆盖率工具
* [csurf](): express 中间件，实现 CSRF
* [helmet](): express 中间件，集成了常见网络安全防御的实现
* [yargs](http://yargs.js.org/): 制作 CLI 的库


-----

# 测试
* [wrk](): 压测工具
* [ab](): 压测工具
* [jmeter](): 压测工具

-----

# Linux 命令
* tar: 压缩、解压
* curl: 下载命令
* wget: 下载命令
* ag(the_sliver_searcher): 代码搜索工具
* autojump: 快速跳转目录工具
* ab: 性能压测命令

------

# 消息队列工具
* RabbitMQ
* Kafka
* Redis
* ZeroMQ
* ActiveMQ
* Ali MNS

------

# 服务 & SaaS

* [Let's Encrypt](https://letsencrypt.org/): 免费的HTTPS证书，有效期3个月，可以续期。
* [Certbot](https://certbot.eff.org/): 自动部署HTTPS证书，结合「Let's Encrypt」可以实现无限续期
* [神箭手](http://www.shenjianshou.cn/): 提供爬虫服务
* [loggly](https://www.loggly.com/): 提供日志服务
* [Taobao RAP](http://rapapi.org/): 淘宝提供的API接口 Mock 服务

------

# 开源框架
* [goaccess](https://goaccess.io/): 一个分析Nginx、Apache等分布式服务器日志的开源工具
* [Sentry](https://sentry.io/): 错误上报，报警监控工具。支持 JavaScript、PHP、NodeJS等    
  - [官方博客](https://blog.sentry.io/)    
  - [官方文档](https://docs.sentry.io/)     
  - 搭建教程：     
    - [Sentry 简易搭建指南](https://zhuanlan.zhihu.com/p/24445449)    


