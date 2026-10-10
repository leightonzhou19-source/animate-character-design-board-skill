# animate-character-design-board-skill
AI动画角色设定卡生成提示词模板库，用于生成标准化动画角色设定稿（Character Design Board）。


## 项目结构
├── README.md                 # 项目说明
├── skill_core_rule.md        # 核心强制规则
├── prompt_template.md        # 基础角色卡 Prompt 模板
├── negative_constraints.md   # 全局负面约束词
└── examples/                 # 角色示例 Prompt
├── example_hoshino_ai.md
└── example_lelouch.md



## 使用逻辑

# 使用教程
## 在线网页使用（推荐）
1. 进入本仓库，依次打开下面3个文件，复制全部文本：
   - skill_core_rule.md
   - prompt_template.md
   - negative_constraints.md
2. 将复制的全部内容一次性粘贴到大模型对话窗口。
3. 上传角色参考图片，发送指令：生成角色设定板。
> examples文件夹内为参考样例，可一并发送给AI，强化版式效果。

## 本地离线使用
1. 点击绿色 Code → Download ZIP，下载并解压文件。
2. 使用文本编辑器打开3个核心md文件，复制全部内容。
3. 粘贴到本地大模型，上传角色图即可使用。


## 输出标准
- 单张完整角色设计板，包含角色档案、全身三视图、服饰拆解、色卡、多局部特写、表情表EXPRESSION SHEET
- 严格匹配原作画风，不自由魔改角色五官、造型
- 干净浅色背景，网格排版，元素分区清晰

## 示例
examples目录内置2个完整可直接复制的角色prompt：
- 星野爱（《我推的孩子》）
- 鲁路修·兰佩路基（《Code Geass》）

