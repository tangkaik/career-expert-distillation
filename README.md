# 张雪峰 · 求职择业AI顾问

> 基于张雪峰公开言论蒸馏的 AI 思维分身 — 用他的认知框架帮你分析职业选择、求职策略、人生规划。

## 快速开始

1. 用浏览器打开 `index.html`
2. 点击右上角 ⚙️ 设置你的 DeepSeek API Key
3. 开始提问

## 项目结构

```
【专家蒸馏原型】/
├── index.html          ← 完整的聊天应用（UI + API调用 + 对话管理）
├── skill.md            ← 蒸馏产物——张雪峰认知操作系统
├── references/         ← 6份原始研究资料（展示完整蒸馏链路）
│   ├── 01-writings.md       ← 5本著作核心思想
│   ├── 02-conversations.md  ← 15+篇访谈/综艺/直播
│   ├── 03-expression-dna.md ← 表达风格DNA分析
│   ├── 04-external-views.md ← 他者评价（正反两面）
│   ├── 05-decisions.md      ← 11个关键决策 + 行为模式
│   └── 06-timeline.md       ← 1984-2026完整时间线
└── README.md
```

## 功能特性

- 🎓 **张雪峰风格回答** — 东北话、段子、金句、反问
- 📊 **数据驱动建议** — 引导模型搜索最新数据再回答
- 💬 **流式渲染** — 打字机效果实时输出
- 🌓 **暗色/亮色主题** — 一键切换
- 💾 **对话持久化** — 刷新不丢失
- 📱 **响应式设计** — 手机/桌面都可用
- ⚙️ **可调节参数** — API Key / 模型 / Temperature
- 🔗 **5个核心心智模型** + **8条决策启发式**

## 技术栈

- 纯前端 (HTML + CSS + Vanilla JS)
- DeepSeek API (兼容 OpenAI 格式)
- marked.js (Markdown 渲染)
- localStorage (对话/设置持久化)

## 如何替换蒸馏专家

如果你想蒸馏其他专家（求职导师、行业大牛等）：

### 1. 收集资料（6个维度）
照着 `references/` 的 6 份文件结构，收集新专家的资料：
- **01-writings**: 著作、论文、长文
- **02-conversations**: 访谈、播客、演讲
- **03-expression-dna**: 金句、口头禅、表达习惯
- **04-external-views**: 他者评价、批评
- **05-decisions**: 关键决策、行为模式
- **06-timeline**: 完整人生经历

### 2. 提炼认知框架
从资料中提取：
- **3-7 个核心心智模型** — 专家"怎么想"的底层框架
- **5-10 条决策启发式** — if-then 的快速判断规则
- **表达 DNA** — 句式、节奏、用词偏好
- **诚实边界** — 明确标注做不到什么

### 3. 更新 SKILL.md
将提炼结果写入 `skill.md`，参考现有结构。

### 4. 更新 index.html
替换 `index.html` 中的：
- `SYSTEM_PROMPT` 常量（~100行系统提示词）
- 页面标题和欢迎文案
- 快捷问题按钮

详细方法论见 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 项目。

## 验证蒸馏质量的标准（来自女娲.skill）

- [ ] 心智模型 3-7 个，每个有证据支撑
- [ ] 每个模型标注了局限性（不能光写优点）
- [ ] 表达DNA在100字内可辨识（不像通用ChatGPT）
- [ ] 诚实边界 ≥ 3 条
- [ ] 内在张力 ≥ 2 处（真人有矛盾，神没有）

## 致谢

- 蒸馏方法论来自 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)
- SKILL.md 基于 [alchaincyf/zhangxuefeng-skill](https://github.com/alchaincyf/zhangxuefeng-skill) 和 [ZhangXueFeng-skill v2.0](https://github.com/a18515373115-droid/ZhangXueFeng-skill)
- 张雪峰（1984-2026），感谢他为普通家庭的孩子说了那么多真话

## License

MIT
