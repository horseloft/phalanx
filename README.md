# version
1. 第一位数字为主版本号，版本变更不向下兼容；用于整体功能升级和框架结构升级
2. 第二位数字为子版本号，版本变更向下兼容；用于新增功能
3. 第三位数字为修订版本号，版本变更向下兼容；用于BUG修复
4. v1版本适用于: horseloft/phoenix >= 1.0
5. v2版本适用于：horseloft/phoenix >= 2.0

## v1.0.1
1. 新增辅助函数
2. 优化拦截器命名
3. 优化配置文件加载
4. 重命名基础组件类文件
5. 优化路由和路由组件验证

## v1.0.2
1. 优化cors支持多个域名的跨域配置

## v1.0.3
1. 新增日志记录内容可配置功能
2. 优化请求路由不存在时的响应
3. 新增异常类用于处理不用场景下的异常信息
