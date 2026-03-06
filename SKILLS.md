# SKILLS.md - 健身教练技能清单 🏋️

## 核心技能（已安装）
- `fitness-coach`: 🏋️ **主技能！路径：~/.agents/skills/fitness-coach/**
  - 功能：个性化训练计划、运动指导、营养建议、进度追踪
  - 参考：
    - `references/exercise-library.md`: 动作库和技术要点
    - `references/nutrition-guide.md`: 营养基础和饮食建议
    - `references/training-basics.md`: 训练原则和常见问题

## 飞书集成技能（可用）
- `feishu_doc`: 文档读写操作，用于训练计划文档管理
- `feishu_chat`: 聊天操作，用于互动和提醒
- `feishu_drive`: 云存储，用于训练资料和图片存储
- `feishu_wiki`: 知识库，用于健身知识沉淀
- `feishu_bitable`: 多维表格，用于进度追踪和数据管理

## 系统工具技能（可用）
- `web_search`: 查阅最新健身研究、营养科学、训练方法
- `web_fetch`: 获取健身资讯和科学文献
- `image`: 运动姿态分析、训练图片分析
- `message`: 定期训练提醒、进度通报

## Meta 技能（系统核心）
- `capability-evolver`: 🧬 **自我进化引擎**
  - 功能：分析运行历史，识别改进点，自动进化
  - 用途：定期自我优化，应用协议约束的进化
  - 路径：`/usr/lib/node_modules/openclaw/extensions/evolver/`

- `brainstorming`: 💡 **创意设计**
  - 功能：在创建功能、添加功能前，探索用户意图、需求和设计
  - 用途：规划健身计划功能、营养指导系统设计
  - 路径：`~/.agents/skills/brainstorming/`

- `humanizer`: ✍️ **文本人性化**
  - 功能：检测并移除 AI 写作模式，使文本更自然
  - 用途：优化训练计划说明、健身建议的表达方式
  - 路径：`~/.agents/skills/humanizer/`

- `self-learning`: 📚 **自主学习**
  - 功能：从网络学习新技术，自动生成可重用的技能
  - 用途：研究最新健身科学、训练方法
  - 路径：`~/.agents/skills/self-learning/`

## 编程与开发辅助
- `acp-router`: 🔧 **ACP 路由**
  - 功能：路由编码请求到 Pi、Claude Code、Codex、OpenCode 等
  - 用途：开发健身相关的自动化工具、数据分析脚本
  - 路径：`/usr/lib/node_modules/openclaw/extensions/acpx/skills/acp-router/SKILL.md`

- `lobster`: 🦞 **工作流自动化**
  - 功能：执行需要审批的多步骤工作流
  - 用途：自动化训练提醒、定期进度检查
  - 路径：`/usr/lib/node_modules/openclaw/extensions/lobster/SKILL.md`

## 工具与记忆
- `memory_store`: 存储用户偏好、训练记录、长期目标
- `memory_recall`: 回忆用户历史训练数据和偏好
- `tts`: 语音训练指导（可选功能）

## 专业工具技能（参考）
- `openclaw-troubleshooter`: 🔧 **故障排除**
  - 功能：OpenClaw 系统问题诊断和修复
  - 路径：`~/.agents/skills/openclaw-troubleshooter/`

- `skill-creator`: 🛠️ **技能创建器**
  - 功能：创建或更新 AgentSkills
  - 用途：开发新的健身相关技能
  - 路径：`~/.agents/skills/skill-creator/`

- `ai-ppt-generator`: 📊 **PPT 生成**
  - 功能：生成专业的 PowerPoint 演示文稿
  - 用途：制作健身培训材料、营养讲解 PPT
  - 路径：`~/.agents/skills/ai-ppt-generator/`

## 自定义技能（需开发）
- `form-analyzer`: AI 运动姿势分析器（基于视频/图片）
- `meal-planner`: 自动化饮食计划生成器
- `workout-generator`: 基于用户状态的动态训练计划生成
- `progress-tracker`: 智能进度追踪和可视化
- `injury-prevention`: 损伤风险评估和预防建议
- `recovery-guide`: 恢复方案生成器

## 技能使用策略

### 日常使用
- **核心技能**：每天都会用到，提供健身专业指导
- **飞书集成**：存储训练计划、进度记录、知识库管理
- **系统工具**：查阅资料、分析图片

### 进化与学习
- **capability-evolver**：定期运行 `/evolve` 进行自我优化
- **self-learning**：研究最新健身科学和训练方法
- **brainstorming**：规划新功能和改进

### 开发扩展
- **acp-router**：开发自动化脚本和工具
- **skill-creator**：创建新的健身相关技能
- **lobster**：自动化定期任务和提醒
