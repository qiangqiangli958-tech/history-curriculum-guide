初中历史新课标考点解读
帮助初中生和家长基于 2022 年版义务教育历史课程标准，快速定位知识点、理解学业要求、预判考查方式、明确学习方向。

这个技能能做什么？
输入一个具体的历史知识点、人物、制度、事件或概念，例如：

商鞅变法
辛亥革命
工业革命
分封制
闭关锁国
输出结构化解读：

课标定位：该知识点属于哪个历史阶段、学习主题、历史线索
新课标要求：要掌握到什么程度，用课标行为动词区分识记/理解/评价层级
核心素养指向：对应唯物史观、时空观念、史料实证、历史解释、家国情怀中的哪些
可能怎么考：选择题、材料题、比较题、观点论述题的常见考法
常见命题角度：3-5 个最可能被考到的具体角度
学习建议：时间线怎么放、概念怎么抓、和哪些知识点一起复习、容易踩的坑
一句话总结：学习重点和方向
安装方法
前置要求
已安装 WorkBuddy 客户端
了解 ~/.workbuddy/skills/ 目录位置（即本地技能存放目录）
步骤
⚠️ 注意：本仓库名为 -，直接 clone 会生成名为 - 的文件夹。安装时必须将其重命名为 history-curriculum-guide，否则 WorkBuddy 无法正确识别。

克隆仓库到本地

bash
git clone https://github.com/qiangqiangli958-tech/-.git
重命名为正确的技能目录名

bash
# Windows PowerShell
Rename-Item -Path "-" -NewName "history-curriculum-guide"

# macOS / Linux / Git Bash
mv - history-curriculum-guide
移动到 WorkBuddy 技能目录

bash
# Windows PowerShell
Move-Item -Path "history-curriculum-guide" -Destination "$env:USERPROFILE\.workbuddy\skills\"

# macOS / Linux
mv history-curriculum-guide ~/.workbuddy/skills/
重启或刷新 WorkBuddy，使技能生效。

安装完成后，技能目录应为：

~/.workbuddy/skills/history-curriculum-guide/
├── SKILL.md
├── knowledge-md/
├── index/
└── examples/
目录结构
history-curriculum-guide/
├── SKILL.md                          # 技能入口文件
├── knowledge-md/                     # 课标解读材料（Markdown 版）
│   ├── 01 义务教育历史课程目标解读.md
│   ├── 02课程内容结构分析.md
│   ├── 03-1中国古代史内容分析.md
│   ├── 03-2中国近代史内容分析.md
│   ├── 03-3中国现代史内容分析.md
│   ├── 03-4世界古代史内容分析.md
│   ├── 03-5世界近代史内容分析.md
│   ├── 03-6世界现代史内容分析.md
│   ├── 04历史学业质量分析.md
│   └── 05学业水平考试命题要求.md
├── index/                            # 索引文件
│   ├── 知识点索引.md
│   ├── 学习主题索引.md
│   └── 考查方式索引.md
└── examples/                         # 示例输出
    ├── 商鞅变法.md
    ├── 工业革命.md
    └── 洋务运动.md
使用示例
安装完成后，在 WorkBuddy 中直接输入：

商鞅变法
或：

帮我看看工业革命这个知识点
技能会根据输入自动检索对应课标解读材料，并返回结构化分析。

数据来源
全部解读材料基于教育部 2022 年版《义务教育历史课程标准》及配套解读文本。

许可
本项目采用 CC BY-NC-SA 4.0 许可。

署名：转载或改编时请注明出处
非商业：禁止用于商业用途
相同方式共享：改编作品需采用相同许可
反馈与更新
如发现解读内容有误或需要补充知识点，欢迎通过 GitHub Issue 提交。

更多初中历史学习方法，欢迎关注公众号：历史应该这样学
