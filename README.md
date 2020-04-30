# yii2资料集 #

## 文档 ##
- [Yii2 干货集](https://github.com/forecho/awesome-yii2)
- [Yii 2.0 权威指南中文版](https://www.yiichina.com/doc/guide/2.0)
- [Yii Framework 2.0 API 文档](https://www.yiichina.com/doc/api/2.0)

## 项目模板 ##
- [yii2-app-basic](https://github.com/yiisoft/yii2-app-basic) 基础模版
    composer create-project --prefer-dist yiisoft/yii2-app-basic basic
- [yii2-app-advanced](https://github.com/yiisoft/yii2-app-advanced) 高级模版
- [我自己的多项目模板 包括admin frantend restful statics, 集成了yiisoft/yii2-bootstrap yiisoft/yii2-smarty yiiexttbq/adminlte sizeg/yii2-jwt yiiexttbq/user](https://github.com/yiiapps/yii-advanced)
- [单项目模板 ](https://github.com/yiiapps/yii-basic-smarty-adminlte)

## 开源程序 ##
- [yiiapps/basic-blog](https://github.com/yiiapps/basic-blog) 一个简易博客, 使用basic模版开发, 使用了blog扩展 admin扩展 adminlte为后台html模版
- [tbqphp/cms_yii_liufee 一个cms](https://gitee.com/tbqphp/cms_yii_liufee)
- [GetYii：论坛](https://github.com/iiyii/getyii)

## 扩展 ##
- [yiiexttbq/blog](https://github.com/yiiapps/blogmodule) 一个blog扩展 [yiiapps/adminlte-asset-ext](https://github.com/yiiapps/adminlte-asset-ext)和[Yii2 Blog](https://github.com/funson86/yii2-blog)
- [yiiapps/adminlte-asset-ext(yiiexttbq/adminlte)](https://github.com/yiiapps/adminlte-asset-ext) 基于mdmsoft/yii2-admin和[dmstr/yii2-adminlte-asset](https://github.com/dmstr/yii2-adminlte-asset)
- yiiexttbq/user
- yiiexttbq/yuqiutils
- yiisoft/yii2-bootstrap
- yiisoft/yii2-smarty
- sizeg/yii2-jwt

-----------------------------

## 未验证 等待验证 ##
- zhuravljov/yii2-rest Yii2 REST 客户端
- [yii2-setting](https://github.com/funson86/yii2-setting)：常见的在后台设置,可以使用在任何地方
- CostaRico/yii2-images：图片尺寸裁剪解决方案
- bedezign/yii2-audit：记录和显示web/cli请求，数据库更改php/js错误和相关数据。
- Chiliec/yii2-vote：提供点赞的模块
- [yiier/yii2-humans-log](https://github.com/yiier/yii2-humans-log): 人类能看得懂的操作日志
- [yiier/yii2-smser](https://github.com/yiier/yii2-smser) 短信系统
- yii2tech/sitemap
- yii2tech/html2pdf
- https://github.com/robregonm/yii2-pdf
- https://github.com/yii2tech/config
- https://github.com/yii2tech/crontab
- https://github.com/yii2tech/file-storage
- https://github.com/funson86/yii2-setting
- https://github.com/funson86/yii2-cms
- Hzhihua/yii2-dump：用命令行的方式自动对现有的数据库（SQL）生成数据库迁移（migrate）文件，内有预览图。
- jamband/yii2-schemadump：用命令的方式对现有的数据库（SQL）生成数据库迁移（migrate）代码，内有 gif 演示。
- DenisOgr/yii2-cronjobs：用系统计划任务来每分钟运行这个PHP计划任务，然后你程序的计划任务的调用就写在 cron 这个控制器里就可以了。
- yiier/yii2-backup：通过命令备份数据库的扩展，可以添加到定时任务实现定时备份发送到 Email。
- yiier/yii2-aliyun-oss：基于官网 SDK 封装的 Yii2 使用阿里云OSS。
- zhuravljov/yii2-queue：有望成为官网异步扩展的队列
- moonlandsoft/yii2-phpexcel：导出 Excel
- yiier/yii2-notification: 管理通知
- creocoder/yii2-taggable：文章标签解决方案
- OmgDef/yii2-multilingual-behavior：多语言文章解决方案
- cornernote/yii2-softdelete：软删除（伪删除）
- yii2mod/yii2-behaviors：两个行为，CarbonBehavior 处理跟时间日期有关系的事情。PurifyBehavior 使用 HTMLPurifier 保证输出数据的安全性。

---------------------
Module 模块

    yii2-webshell 在 web 下运行shell
    zhuravljov/yii2-rest Yii2 REST 客户端
    mdmsoft/yii2-admin RBAC Manager 基于角色的权限管理
    yii2-user
    yii2-plugins-system Yii2 plugins system module with event manager and shortcodes as WordPress
    yii2-notification-wrapper Yii2-notification-wrapper module renders a message from session flash (with ajax, pjax support and etc.) through Growl, Noty, Toastr and more libraries
    yii2-setting：常见的在后台设置,可以使用在任何地方
    yii2-wechat：基于Yii2实现的微信模块
    CostaRico/yii2-images：图片尺寸裁剪解决方案
    myweishanli/yii2-extjs-rbac：Yii2 ExtJs5 RBAC+ACL 权限管理系统
    bedezign/yii2-audit：记录和显示web/cli请求，数据库更改php/js错误和相关数据。
    Chiliec/yii2-vote：提供点赞的模块
    codemix/yii2-bs3activeform :Yii2 表单增强模块，有在线 Demo。
    yii2mod/yii2-cashier：帮你处理付费订阅棘手问题，比方说订阅专栏一个月/一年等。
    yiier/yii2-rbac: 又一个 RBAC 模块
    yiier/yii2-humans-log: 人类能看得懂的操作日志

Widgets 小部件

    kop/yii2-scroll-pager：瀑布滚动翻页
    yii2-widget-linkpager：带分页大小的分页栏
    yii2-ajaxform：通过ajax提交表单
    lichunqiang/yii2-sweet-submit：sweetalert一个漂亮的弹出框
    bizley/yii2-content-tools：Yii2 实现 ContentTools 编辑器
    bupy7/yii2-dynamic-fields：表单动态增加行的组件（demo可以看Adding dynamic field）

Extension 扩展

    yiisoft：Yii2 官方扩展
    kartik-v：kartik-v 高产合集
    2amigos：2amigos 团队高产合集
    yii2tech：yii2tech 团队合集
    wbraganca：又一个扩展集合，包括收货地址、上传图片、动态嵌套表单、选择框、标签框、上传图片、视频等扩展，最重要的是有在线 demo 体验。
    yii2-beanstalk：beanstalk 队列
    yii2-imagine：图片处理，缩略图生成
    yii2-yunpian：一个基于 Yii2 的短信 SDK
    yii2-qiniu：集成七牛的 SDK
    pingpp-yii2：Yii2 化 Ping++ SDK
    crontab：Yii2 定时任务
    yii2-contextmenu：Yii2 grid行右击操作
    yii2-smser：国内短信扩展
    yii2-echarts：Yii2 ECharts扩展
    yiidoc/yii2-redactor：大名鼎鼎的 Redactor 在线编辑器
    Hzhihua/yii2-dump：用命令行的方式自动对现有的数据库（SQL）生成数据库迁移（migrate）文件，内有预览图。
    jamband/yii2-schemadump：用命令的方式对现有的数据库（SQL）生成数据库迁移（migrate）代码，内有 gif 演示。
    DenisOgr/yii2-cronjobs：用系统计划任务来每分钟运行这个PHP计划任务，然后你程序的计划任务的调用就写在 cron 这个控制器里就可以了。
    trntv/yii2-aceeditor：Yii2 封装 ace 在线编辑器
    zelenin/yii2-semantic-ui：Yii2 封装 Semantic UI
    yiier/yii2-backup：通过命令备份数据库的扩展，可以添加到定时任务实现定时备份发送到 Email。
    yiier/yii2-aliyun-oss：基于官网 SDK 封装的 Yii2 使用阿里云OSS。
    yiier/yiier-return-url：登录之后自动跳转登录之前的页面。
    lichunqiang/yii2-swagger：Yii2 结合 swagger 让写 API 文档不再是难事。Demo 地址
    boundstate/yii2-mailgun：mailgun 邮箱服务扩展。
    abhi1693/yii2-system-info：获取 Windows 或者 Linux 系统信息。
    imanilchaudhari/yii2-rrssb：分享到社交网络（主要是针对国外一些网站）。
    alexandernst/yii2-device-detect：获取访问网站的设备信息。
    yiister/yii2-advanced-grid：高级版的 grid，有在线 demo 体验。
    hellowearemito/yii2-sentry： 收集日志神器——Sentry 的 Yii2 扩展。
    zhuravljov/yii2-queue：有望成为官网异步扩展的队列
    moonlandsoft/yii2-phpexcel：导出 Excel
    windhoney/yii2-rest-rbac：Yii2前后分离，权限管理rbac--rest接口方式
    imyangjin/yii2-mysql-json：扩展Yii2的ActiveRecord和ActiveQuery支持mysql json格式。使mysql json字段的操作和yii2无缝对接，使用更加简单。
    yiier/yii2-action-store: 让你不再为点赞、收藏等烦恼的扩展。
    yiier/yii2-smser: 发短信
    yiier/yii2-notification: 管理通知

Themes 主题模板

    dmstr/yii2-adminlte-asset：大名鼎鼎的 AdminLTE 开源后台，我现在很多后台就用这个。配合Yii2 使用 AdminLTE 模板教程使用更佳。
    yiister/yii2-adminlte：AdminLTE 后台模板的另一个选择，有做简单的 widget 封装，在线体验地址
    yiister/yii2-gentelella：Gentelella 后台模板，在线体验地址

Behaviors 行为

    creocoder/yii2-nested-sets：无限极嵌套分类
    creocoder/yii2-taggable：文章标签解决方案
    OmgDef/yii2-multilingual-behavior：多语言文章解决方案
    cornernote/yii2-softdelete：软删除（伪删除）
    yii2mod/yii2-behaviors：两个行为，CarbonBehavior 处理跟时间日期有关系的事情。PurifyBehavior 使用 HTMLPurifier 保证输出数据的安全性。
    paulzi/yii2-nested-intervals：数结构分类的行为、层级分类行为。

Helpers 助手

    kartik-v/yii2-helpers：HTML 和 枚举的 helper
    DevGroup-ru/yii2-tag-dependency-helper：非常棒的缓存设计方法，具体实现可以参考 dotplant2 代码。
    xinnianq/yii2-routes ：获取yii2项目所有路由，方便权限控制

Posts 文章

    Yii2 Day 1~7 系列文章 文章不是非常深入，但是对初学者非常有用
    Yii2 - What you need to know
    使用Yii2时遇到的实际问题
    深入理解 Yii2.0
    Bsourcecode Yii2.0 系列文章（英文）
    krajee Yii2.0 系列文章（英文）
    PHP开源框架Yii2系列：有很多关于 Yii2 RESTful 的使用

Videos 视频

    与《YII框架》不得不说的故事—基础篇：讲的很基础，建议初学者过一遍
    与《YII框架》不得不说的故事—高效篇：主要讲了缓存和 Gii 的使用
    与《YII框架》不得不说的故事—安全篇：主要讲了 XSS 和 CSRF 等
    与《YII框架》不得不说的故事—扩展篇：主要讲了模块化、事件机制和行为还有依赖注入，话题越来越高级，很赞。
    与《YII框架》不得不说的故事—工具篇：主要讲了Gii、Composer 还有 Yii2 Debug 工具。
    yii框架入门
    深入理解 Yii2.0 视频
    Yii2 Development Visualization - youtube / 三分钟看尽Yii2开发的三年历程 - 优酷
    Yii2 Lessons - youtube
    魏曦的 Yii2.0 视频教程 与 源码 michaelweixi/Yii2Blog
