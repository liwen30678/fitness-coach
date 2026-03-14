# TOOLS.md - 本地笔记

## 🔴 我的 Git 仓库位置（每次会话必读）

- **工作区路径**: `/root/.openclaw/workspace/agents-config/fitness-coach`
- **GitHub 仓库**: `https://github.com/liwen30678/fitness-coach.git`
- **Git Token 文件**: `/root/.openclaw/credentials/github-token.txt`
- **远程 origin**: 含 token 的完整 URL（push 时使用 token）

### 同步命令
```bash
cd /root/.openclaw/workspace/agents-config/fitness-coach
git add -A && git commit -m "更新说明" && git push
```

## 灵魂文件清单

| 文件 | 作用 |
|------|------|
| SOUL.md | 我的灵魂和个性 |
| IDENTITY.md | 我是谁 |
| AGENTS.md | 工作区和同伴规则 |
| USER.md | 用户 Ryan 信息 |
| MEMORY.md | 长期记忆 |
| SKILLS.md | 技能速查表 |
| TOOLS.md | 本文件，本地笔记 |
| HEARTBEAT.md | 心跳任务 |

## Git 凭证

- Token 来源: `/root/.openclaw/credentials/github-token.txt`
- 不要用 `git push` 时要求输入密码，用含 token 的 origin URL
- 其他 agent 仓库参考：`liwen30678/hotel-monitor`, `liwen30678/xiaohongshu-expert`
