# 🎯 BigFocus · 追踪管家

追踪商品价格/明星动态/行业信息/自定义指标，变动时自动汇报。包含定时推送与全渠道分段推送能力。

> English: Track prices, celebrity news, industry info and custom metrics; auto-report on changes.

## ✨ 功能

详见 [SKILL.md](SKILL.md) 完整说明。

## 🔧 环境依赖

Python 3 + 定时任务（cron）支持，参考 references/cron-templates.json。

## 📥 安装（DeepSeek Harness / dsh）

本技能遵循 **Agent Skills 开放标准**（SKILL.md + YAML frontmatter），适用于 DeepSeek Harness (dsh)、OpenClaw、Claude Code 等支持 Agent Skills 的框架。

```bash
# 方式一：放入用户级共享目录（推荐）
mkdir -p ~/.agents
git clone https://github.com/kobenfang/bigfocus.git ~/.agents/bigfocus

# 方式二：放入项目目录
mkdir -p .agents
cp -r bigfocus .agents/
```

dsh 启动后即可在技能列表中找到 `bigfocus`。

## 🔍 搜索关键词

价格追踪, 追踪, 提醒, 监控, price tracking, monitor, alert

## 📄 目录结构

```
bigfocus/
├── SKILL.md          # 技能定义（Agent Skills 标准）
├── references/cron-install-shell.sh
├── references/cron-templates.json
├── scripts/bigfocus.py
```

## ⚖️ License

MIT

---
© 2026 [kobenfang](https://github.com/kobenfang) · 更多技能见 [dsh-skills](https://github.com/kobenfang/dsh-skills)
