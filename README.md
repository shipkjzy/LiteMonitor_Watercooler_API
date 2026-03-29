# LiteMonitor_Watercooler_API插件（全部由OpenAI完成）
使LiteMonitor在任务栏显示水冷机现行的风扇转速和泵电压

## 项目依赖
- https://github.com/Diorser/LiteMonitor
- https://github.com/shipkjzy/watercooler-manager

## 使用说明
- 启动watercooler-manager程序，在底部勾选“启用 API”，设置端口。
- 浏览器打开 http://127.0.0.1:端口/api/status 确认有 JSON 输出。
- 把 LiteMonitor_Watercooler_API.json 放到 LiteMonitor 的 resources/plugins/ 目录。
- 在 LiteMonitor 中重载插件，添加“水冷管理器本地API”，并把插件里的端口改成和程序一致。
