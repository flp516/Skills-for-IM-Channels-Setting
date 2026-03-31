# 微信 ClawBot 配置技能

帮助用户在 OpenClaw 中配置微信 ClawBot 插件的技能。

## 功能

- 指导用户完成微信 ClawBot 插件的安装和配置
- 明确微信版本要求
- 支持 iOS、Android、鸿蒙微信版本
- 提供常见问题 Q&A 和故障排除指南

## 微信版本支持

| 平台 | 支持状态 |
|------|----------|
| **iOS** | ✅ 微信 8.0.70 及以上 |
| **Android** | ✅ 微信 8.0.69 及以上 |
| **HarmonyOS（鸿蒙）** | ✅ 微信 8.0.16 及以上 |

## 使用方法

将此技能安装到 OpenClaw 的 skills 目录中，然后询问「如何配置微信 ClawBot」即可触发。

## 核心步骤

1. 更新微信：确保版本符合要求
2. 安装插件：`npx -y @tencent-weixin/openclaw-weixin-cli@latest install`
3. 扫码绑定：用微信扫描二维码
4. 启用插件：在 `openclaw.json` 中添加 `"openclaw-weixin": { "enabled": true }`
5. 重启 Gateway：`openclaw gateway restart`
6. 验证连接：`openclaw channels list`

## 许可证

MIT License
