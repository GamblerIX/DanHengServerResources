# DanHengServerResources

本仓库包含了 DanHengServer 项目所需的各种游戏配置与资源文件。

## 📂 目录结构

- **Config**: 包含游戏的各种核心系统配置文件。
- **ExcelOutput**: 从表格导出的 JSON 数据，涵盖物品、角色、技能等数值。
- **Story**: 游戏剧情、任务流程的脚本与配置。
- **TextMap**: 多语言文本映射文件。
- **ConfigManifest.json**: 资源的配置清单文件。
- **Version**: 当前资源版本的标识。

## 🚀 与 DanHengServer 配合使用

这些资源被 `DanHengServer` 解析，用于模拟游戏服务器环境。在使用时，请确保：

1. 将本仓库作为子模块克隆到 `DanHengServer` 的`Resources`目录下。
2. 保持资源文件与服务端代码的版本一致。

## 📝 许可证

[GNU APGLv3](LICENSE)