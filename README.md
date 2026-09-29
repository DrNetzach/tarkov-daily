# 诺文斯克日报

> 塔科夫每日速览 —— 官方改动 · 社区风向 · 萌新提示

每天一分钟，看完塔科夫。把官方的补丁、活动、社区讨论压成一份能快速读完的简报。

站点：https://tarkov-daily.pages.dev/

## 每期结构

- 📌 **今日头条** —— 今天最要紧的那件事
- 🔧 **官方改动** —— 补丁 / 活动 / 赛季
- 💬 **社区在聊什么** —— Reddit、B站 UP 主的反应
- 🎯 **萌新提示** —— 今天该注意什么
- 🐟 **主编判断** —— 个人看法（只有站长写，AI 不代笔）

## 本地开发

```bash
pip install -r requirements.txt
mkdocs serve
```

然后打开 http://127.0.0.1:8000

## 写一期

在 `docs/blog/posts/` 下新建 `YYYY-MM-DD.md`：

```markdown
---
date: 2026-09-29
categories: [补丁, 活动]
tags: [灯塔, 空投]
---

# 2026-09-29 速览

## 📌 今日头条
...

## 🔧 官方改动
...
```

## 部署

push 到 `main` 分支 → GitHub Actions 自动 `mkdocs build` → 推送到 Cloudflare Pages。

## 素材来源

- Steam 官方公告 RSS（自带中文补丁全文）
- B站：纱雾最可爱辣 / 三笠Ackerman01 / MR茼蒿 / 大傻哥丶 / 油墨香车
- Reddit r/EscapeFromTarkov

## 许可

[CC BY-NC-SA 4.0](LICENSE) —— 欢迎转载，禁止商用

## 系列站

- [塔科夫 PVE 手册](https://tarkov-pve-guide.pages.dev/)
- [塔科夫百科全书](https://tarkov-encyclopedia-site.pages.dev/)
