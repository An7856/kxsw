# _worker脚本自动更新系统

## 📌 状态徽章

![工作流状态](https://img.shields.io/badge/工作流-运行中-brightgreen?style=flat-square)
![更新模式](https://img.shields.io/badge/更新模式-自动-green?style=flat-square)
![代码混淆](https://img.shields.io/badge/代码混淆-否-orange?style=flat-square)
![最后更新](https://img.shields.io/badge/最后更新-2025--08--03-blue?style=flat-square)

## 📚 使用说明

这是一个自动更新_worker脚本的工作流，支持以下功能：

- **自动更新**：每天北京时间0点检查更新
- **手动触发**：可指定更新模式和混淆选项
- **代码混淆**：可选高强度混淆保护代码
- **强制更新**：彻底清理仓库后重新创建_worker脚本（保留工作流文件）
- **变更追踪**：自动记录最新提交信息

## ⚙️ 当前配置

| 配置项 | 值 |
|--------|----|
| 🔄 更新模式 | 自动 |
| 🔒 代码混淆 | 否 |
| ⏰ 最后更新时间 | 2025-08-03 00:17:40 (北京时间) |
| 💥 更新类型 | 常规更新 |
| 🌐 时区 | 北京时间(UTC+8) |

## ⚙️ 配置选项说明

### 1. 更新模式
- **自动**：系统将按计划自动检查更新（默认）
- **手动**：仅通过手动触发更新

### 2. 代码混淆
- **是**：启用高强度代码混淆（使用javascript-obfuscator）
- **否**：保持原始代码（默认）

### 3. 强制更新
- **true**：彻底清理仓库后重新创建（保留工作流文件）
- **false**：常规更新（默认）

> 注意：强制更新会删除除 `.github` 工作流目录外的所有文件，请谨慎使用

## ⚠️ 注意事项

1. **强制更新**会删除除工作流文件外的所有文件并重新下载，请谨慎使用
2. 代码混淆后可能影响调试，建议测试环境先禁用混淆
3. 自动更新仅在更新模式为「自动」时生效

## 🔄 最近更新记录

📅 2025-08-01  
📝 Merge pull request #674 from Kwisma/patch-1  添加 cf token 判断

> 最后生成时间: 2025-08-03 00:17:40 (北京时间)

