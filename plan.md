# Xray_onekey - Xray 一键安装脚本 - 项目规划

## 项目概述
Xray 代理工具一键安装脚本（Shell 脚本，含多语言 README）。

---

## 2026-03-03 Claude 建议

### 建议
- **服务器部署工具**：主要用于快速部署 Xray 代理服务
- 与 `onekey-xray`（同名项目）可能重复，建议统一使用一个版本
- 注意跟踪 Xray-core 版本更新（安全漏洞修复）

### 扩展建议
- 添加常见配置模板（VLESS/VMESS/Trojan）
- 集成证书自动申请（Let's Encrypt）
- 与 `yum-lnmp`、`aliyun_env_inst` 整合为完整的服务器初始化脚本

### 技术建议
- 整合到统一的"服务器环境初始化工具包"中
