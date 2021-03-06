# 修改日志

## Release Beta6

* 默认 GraphQL API
* 修复安装时数据库地址不能输入 IP 的问题
* 修复安装时数据库密码不能输入"." 的BUG

## Release Beta5 fix 2

* 添加单元测试代码
* 添加功能测试代码
* 重构 JWT 验证机制
* 修正安装时对数据库及Redis连接、账号和密码的验证
* 扩展 MIME 类型，使返回的文件头信息正常
* 优化后台导航栏加载机制
* 优化后台侧边栏加载机制
* 修复后台导航栏无法加载模块导航的问题
* 修复后台侧边栏无法加载自定义页面菜单的问题
* 修复后台侧边栏无法加载插件菜单的问题
* 修复后台加载图形无法显示的问题
* 添加将域名配置写入json文件的功能（statics 目录下的 configuration.json）
* 重构模块安装流程
* 重构插件安装流程
* 重构模块开启/加载逻辑
* 重构插件开启/加载逻辑
* 修正配置文件缓存机制

## Release Beta5 fix 1

* 添加底层缓存机制，优化并提升性能（约5倍）
* 修复安装检测 public 及 pdo_mysql 问题
* 修复模块和插件加载的问题
* 修复树莓派下不能正常安装的问题
* 后台添加 Redis 版本的显示
* 后台系统信息显示优化
* 合并后台前端资源文件
* 修复 js 头部响应为 json 的问题

## Release Beta5

* 添加扩展机制，暂无后台管理
* 完善后台菜单的管理逻辑
* 主体框架、模块、插件的事件订阅器的自动发现
* 模块、插件的命令行命令的自动发现
* 资源（Resource）路由添加对控制器方法名的自定义
* Monaco 代码编辑器二次加载失败的 Bug
* 升级前端项目打包工具 Wepack 为版本 3
