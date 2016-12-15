## sanMvc
* 通过地址分析和路由实现地址美化
* 与数据库分离，数据库操作可以单独进行，可以用于开发不使用数据库的项目
* 模型父类包含了大部分常用数据操作，直接继承就能使用，不需要为每张表单独配置
* 视图父类包含了几个常用方法：显示数据和页面、提示、分页
* 控制器父类有一个权限验证方法，用于验证是否有控制器访问权限，不过很弱，可以自行更换可靠的
* 文件管理类适合处理少量小文件，主要用于页面内容管理，不推荐用于数据管理
* 暂时没有考虑模板引擎开发，感觉原生php页面挺方便的（笑）
* 功能完善中...
* [使用文档编写中...](https://github.com/FishInShallow/sanMvc/issues)
* [查看DEMO](http://bxu2359380510.my3w.com)
