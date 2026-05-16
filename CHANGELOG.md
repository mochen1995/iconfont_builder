## [1.0.7] - 适配 Flutter 3.41.7 / Dart 3，升级依赖与空安全

- SDK 约束升级为 `>=3.0.0 <4.0.0`
- 升级依赖：`args ^2.5.0`、`lpinyin ^2.0.3`
- 适配空安全（Null Safety）：顶层 `args` 改为 `late`、局部 `fileString` 初始化、`group(0)` 处理可空、`nameSet` 改为可空集合
- 生成代码同步适配空安全：`Icon` 工厂方法的 `color/key/size/textDirection` 参数改为可空类型
- 移除 pubspec 中已废弃的 `author` 字段，保留原有逻辑使用方式不变

## [1.0.6] - 忽略一些关键字

## [1.0.4] - 更新说明

## [1.0.3] - 更新说明

## [1.0.2] - 更新说明

## [1.0.1] - Add English Document

## [1.0.0] - 更新说明

## [0.2.3] - 修复最后一个 icon 没有加载

## [0.2.2] - 更新 README

## [0.2.1] - 添加 font-name 的配置参数

- 修改 --name 为 --class
- 添加 --family 用于自定义字体名
- 更新相应的 README

## [0.2.0] - IconData 编译为 const 属性

## [0.1.9] - 修改 README

## [0.1.8] - 修改 args 版本依赖

## [0.1.7] - 关联仓库和 github 的地址

## [0.1.6] - 修改类的参数和 Icon 参数一致

## [0.1.5] - 修改 README

## [0.1.4] - 添加 --name 参数

- --name 用于替换 Iconfont 类名

## [0.1.3] - 添修复 args --help

## [0.1.2] - 添加原始 icon-name 作为注释

## [0.1.1] - 修复 linux 路径

## [0.1.0] - 编译 Icon 和 IconData 两种 dart 对象

- TODO: 发布项目
