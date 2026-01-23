## Hi there 👋

### OpenSkillsmd: 重新定义 Agent 的“进化”方式
OpenSkillsmd 是一个面向 AI Agent 技能的开源基础设施。我们不仅是技能的分发中心 (Docker Hub)，更是全球 Agent 技能的百科全书 (Wikipedia)。

📦 像 Docker 一样高效分发 通过标准化的 skill.md 协议，实现 Agent 技能的 pull 与 push。开发者可以一键下载官方认证或社区贡献的优质技能，实现 Agent 能力的瞬时扩展与即插即用。

📖 像 Wikipedia 一样共建知识 每一条 skill.md 都是 Agent 智慧的结晶。我们鼓励社区像编辑维基百科一样，持续迭代、交叉引用并完善技能文档，让 Agent 的指令集、工具定义与边界说明变得结构化、透明化。

📊 像评测机构一样客观打分 基于 AI 驱动的自动化评估系统，我们对公开的技能进行多维度评分（指令质量、稳定性、适应性）。只有通过严格评估的技能才能获得“官方认证”，确保开发者下载的每一行代码都是生产可用的。

### 核心口号
"Pull high-quality skills, Edit the future of Agents." 


## 仓库
最终仓库名,角色,核心职责
skillsmd,命令行入口,用户安装的二进制工具，负责所有本地操作。
skillsmd-hub,分发中心,类似 Docker Registry，负责 Skill 的版本管理与 API。
skillsmd-wiki,知识协作库,类似 Wikipedia 词条，存放可读性强、按分类组织的 Markdown。
skillsmd-judge,评估引擎,AI 自动化打分与认证，为优质 Skill 颁发 Badge。
