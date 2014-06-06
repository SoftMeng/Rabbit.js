基础依赖库
============

本框架使用了很多基础构建库来实现其最终的快速开发的目标。大概介绍下：

`express` 基础的http服务提供者。

`sequelize` 一个支持多种数据库的orm库，可以将数据库操作映射成js方法，将数据映射到js对象，使开发者更专注于编程，对提升开发效率有明显效果。

`rainbow` 一个微型库，作用就是根据目录层次生成对象的route，将route分组和梳理，方便管理，特别是route多了的时候效果更是明显。

其他库：

 - `less` css预编译，支持实时编译
 - `jade` 默认模板引擎
 - `moment` 模板中得全局对象，用来格式化显示时间
 - `node-uuid` 用来生成uuid，uuid可以做到全站唯一，且不可推导
 - `MD5` 用来生成md5
 - `coffee-script` 本框架的默认编程语言
 - `log4js` 用来做日志管理的库