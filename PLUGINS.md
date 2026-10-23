# 插件列表

Yunxi 自带的、合作伙伴的和推荐的插件。机器可读的一份在 [plugins.json](plugins.json)。

## Yunxi 内置

### EveryInfra 万有引擎 · 合作伙伴

一个 MCP 接进 90 个平台的 414 个数据接口、AI 搜索和验证码识别（小红书、抖音、淘宝、京东、B 站、TikTok、YouTube 等）；失败或空结果不收钱。

- **在 Yunxi 里**（下一版起）：「自定义 → 插件 → EveryInfra」填 API Key，就能看余额（充值 / 赠送、快过期的赠送、本月折扣、24 小时用量），一键「接入本机 Claude Code」，新开的对话就能直接用它的工具。Key 只加密存在你的电脑上。
- **直接装进 Claude Code**：

  ```bash
  claude plugin marketplace add everyinfra/everyinfra-agent-plugins
  claude plugin install everyinfra@everyinfra
  ```

- 官网 [cn.everyinfra.com](https://cn.everyinfra.com/) · 文档 [cn.everyinfra.com/docs](https://cn.everyinfra.com/docs) · 仓库 [everyinfra/everyinfra-agent-plugins](https://github.com/everyinfra/everyinfra-agent-plugins)

### Android 模拟器（Windows）

在 Yunxi 里管理 Android 虚拟设备：启动、停止，看运行日志。Windows 版自带。

## Claude Code 和 Codex 的插件

- **Codex**：「自定义 → 插件」列出这台电脑或当前服务器上 Codex 的插件目录，按分类找，点开就能装。
- **Claude Code**：按 Claude Code 自己的方式装（`claude plugin marketplace add …`、`claude plugin install …`）；装好以后它带来的技能会出现在「自定义 → 技能」里（下一版起本机也能列）。

## 推荐你的插件

开一个 Issue，选「插件推荐」模板：写清楚它做什么、在哪装、要不要账号或付费。
