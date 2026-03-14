# MEMORY.md - 长期记忆

## 工作模式与健身提醒策略

### 工作时间
- **时间段**: 每天 08:00 - 21:00
- **性质**: 工作时间 = 锻炼时间

### 碎片化健身提醒机制
当检测到小玥处理任务较慢（10秒到几分钟的空闲时间）时，主动提醒进行碎片化锻炼。

**锻炼类型示例**:
- 30个蹲起
- 1分钟平板支撑
- 俯卧撑（数量动态调整）
- 原地高抬腿（1分钟）
- 开合跳（30-50个）
- 靠墙静蹲（30-60秒）

### 触发条件
- 小玥执行需要几分钟的任务（如安装、下载、构建等）
- 用户在等待期间有空闲（不是持续输入或快速操作）
- 碎片时间窗口：10秒 - 5分钟

### 提醒方式
- 直接、简洁，不要废话
- 给出具体动作和数量/时长
- 可根据当天身体状况调整难度

## 重要决策记录
- 2026-03-07: 确立工作时间内主动健身提醒机制，利用碎片时间锻炼
- 2026-03-14: 建立 GitHub 仓库 https://github.com/liwen30678/fitness-coach.git，定期同步灵魂文件

## 我的工作区位置
- **工作区路径**: /root/.openclaw/workspace/agents-config/fitness-coach
- **GitHub 仓库**: https://github.com/liwen30678/fitness-coach.git
- **Git Token**: /root/.openclaw/credentials/github-token.txt

## 灵魂文件列表（每次会话必须读取）
1. SOUL.md - 我的灵魂和个性
2. IDENTITY.md - 我是谁
3. AGENTS.md - 我的工作区和同伴
4. TOOLS.md - 本地笔记
5. USER.md - 用户信息（Ryan）
6. MEMORY.md - 长期记忆（本文件）
7. SKILLS.md - 技能速查表
8. HEARTBEAT.md - 心跳任务

## 新会话启动检查清单
1. 读取 SOUL.md - 确认我是谁
2. 读取 AGENTS.md - 了解同伴和协作规则
3. 读取 USER.md - 了解用户 Ryan
4. 读取 MEMORY.md - 恢复长期记忆
5. 检查 git 状态 - 是否需要同步更新到 GitHub
