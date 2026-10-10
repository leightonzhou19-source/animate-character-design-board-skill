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
1. 读取 `skill_core_rule.md` 强制规则
2. 套用 `prompt_template.md` 基础模板
3. 填入角色信息，替换角色描述、画风、道具
4. 末尾追加 `negative_constraints.md` 负面约束
5. 生成完整角色设定板

## 输出标准
- 单张完整角色设计板，包含角色档案、全身三视图、服饰拆解、色卡、多局部特写、表情表EXPRESSION SHEET
- 严格匹配原作画风，不自由魔改角色五官、造型
- 干净浅色背景，网格排版，元素分区清晰

## 示例
examples目录内置2个完整可直接复制的角色prompt：
- 星野爱（《我推的孩子》）
- 鲁路修·兰佩路基（《Code Geass》）

