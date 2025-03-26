# Wewe RSS Home Assistant Add-on

## 配置说明

### 必填项
- `AUTH_CODE`: 服务接口请求授权码
- `DATABASE_TYPE`: 数据库类型(默认sqlite)

### 可选项
- `FEED_MODE`: 提取全文内容模式
- `CRON_EXPRESSION`: 定时更新订阅源的Cron表达式
- `MAX_REQUEST_PER_MINUTE`: 服务接口请求限制(每分钟)
- `SERVER_ORIGIN_URL`: 外网访问地址

## 使用说明

1. 安装插件
2. 配置必要参数
3. 启动插件
4. 访问 http://your-ha-ip:4000 使用服务