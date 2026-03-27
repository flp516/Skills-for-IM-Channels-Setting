# OpenClaw IM Channel Skills

OpenClaw IM 通道配置技能集合 - 包含主流 IM 平台的 Channel 配置技能。

## 📦 技能列表

| 技能名称 | IM 通道 | 功能描述 | 安装链接 |
|---------|---------|----------|----------|
| **钉钉 Channel 配置** | 钉钉 | 配置钉钉机器人与 OpenClaw 集成 | [查看文档](./dingtalk-channel-setup/) |
| **飞书 Channel 配置** | 飞书 | 配置飞书机器人与 OpenClaw 集成 | [查看文档](./feishu-channel-skill/) |
| **QQ ClawBot 配置** | QQ | 配置 QQ 私聊/群聊/频道与 OpenClaw 集成 | [查看文档](./qq-clawbot-setup/) |
| **企业微信机器人配置** | 企业微信 | 配置企业微信智能机器人与 OpenClaw 集成 | [查看文档](./wecom-bot-setup/) |
| **微信 ClawBot 配置** | 微信 | 配置微信 ClawBot 插件与 OpenClaw 集成 | [查看文档](./weixin-clawbot-setup/) |
| **微博 ClawBot 配置** | 微博 | 配置微博私信与 OpenClaw 集成 | [查看文档](./weibo-clawbot-setup/) |

---

## 🚀 快速开始

### 钉钉 Channel 配置

```bash
cd dingtalk-channel-setup
./scripts/configure.sh <clientId> <clientSecret>
```

### 飞书 Channel 配置

```bash
cd feishu-channel-skill
./scripts/configure.sh <appId> <appSecret>
```

### QQ ClawBot 配置

1. 在 QQ 开放平台创建机器人：https://q.qq.com/
2. 获取 AppID 和 AppSecret
3. 运行配置脚本

### 微博 ClawBot 配置

1. 打开微博客户端，私信 **@微博龙虾助手**
2. 发送消息：`连接龙虾`
3. 获取 AppId 和 AppSecret
4. 运行配置脚本

---

## 📁 目录结构

```
Skills-for-IM-Channels-Setting/
├── README.md                      # 项目说明
├── dingtalk-channel-setup/        # 钉钉 Channel 配置技能
│   ├── SKILL.md                   # 技能定义
│   ├── GUIDE.md                   # 详细指导书
│   └── scripts/
│       └── configure.sh           # 自动配置脚本
├── feishu-channel-skill/          # 飞书 Channel 配置技能
│   ├── SKILL.md                   # 技能定义
│   ├── GUIDE.md                   # 详细指导书
│   └── scripts/
│       └── configure.sh           # 自动配置脚本
├── qq-clawbot-setup/              # QQ ClawBot 配置技能
│   └── SKILL.md                   # 技能定义
├── wecom-bot-setup/               # 企业微信机器人配置技能
│   ├── SKILL.md                   # 技能定义
│   └── scripts/
│       └── setup_wecom_bot.py     # 自动配置脚本
├── weibo-clawbot-setup/           # 微博 ClawBot 配置技能
│   └── SKILL.md                   # 技能定义
└── weixin-clawbot-setup/          # 微信 ClawBot 配置技能
    └── SKILL.md                   # 技能定义
```

---

## 🔧 凭证获取方式

| IM 通道 | 凭证获取方式 |
|---------|-------------|
| **钉钉** | [钉钉开放平台](https://open.dingtalk.com/) 创建应用 |
| **飞书** | [飞书开放平台](https://open.feishu.cn/) 创建应用 |
| **QQ** | [QQ 开放平台](https://q.qq.com/) 创建机器人 |
| **企业微信** | [企业微信管理后台](https://work.weixin.qq.com/) 创建智能机器人 |
| **微信** | 微信扫码绑定 |
| **微博** | 微博客户端私信 **@微博龙虾助手** 发送 `连接龙虾` |

---

## 📄 License

MIT

---

## 🔗 相关链接

- [OpenClaw 文档](https://docs.openclaw.ai)
- [OpenClaw GitHub](https://github.com/openclaw/openclaw)
- [ClawHub 技能市场](https://clawhub.com)
