# prompt_template.md
以用户上传的参考图作为唯一最高视觉依据，生成 single complete professional character design board，角色为【自动填充角色描述】。严格复刻参考图中的同一角色，不得重新设计、不得美化简化、不得改风格。

角色总述：【自动填充：年龄感、体型、脸型、肤色、眼睛、发型、标志性特征】
主服装：【自动填充全套服饰、配饰、纹样、特殊标记】

版式：单张完整设计板，非拼贴、非海报、非多张独立图片；干净的中性浅色背景，专业设计稿网格排版，标注清晰不遮挡主体，信息分区明确。
1. 角色档案区：代号、年龄、身份、气质关键词的简短文字栏。
2. 主视觉：最大的半身胸像，脸部、发型、配饰、标志性特征清晰可辨。
3. 全身三视图：正面、侧面、背面，同一角色、同一服装、同一发型、同一比例、同一画风。
4. 服饰层级拆解：【自动填充服装分层】分层单独展示。
5. 色卡：从参考图取样的发色、肤色、服装颜色、配饰颜色，并列色块。
6. 材质特写：【自动填充面料/材质描述】
7. 局部特写小窗（7~8个）：【自动选取角色标志性细节】
8. 面部特写：眼型、眉形、唇形、鼻梁单独放大。
9. 独立区块，标题必须为 "EXPRESSION SHEET / 表情特写"，包含四个等大头像小窗，分别标注 "喜 Joy"、"怒 Anger"、"哀 Sorrow"、"乐 Happiness"；四格必须是同一张脸、同一脸部比例、同一发型与配饰，仅改变表情；不得并入面部特写或细节区。缺失该区块即视为角色板不完整。
10. 发型发饰区：前发刘海走向、侧发长度、脑后发尾细节。
11. 专属道具区：【自动填充道具，无则写无额外道具】，单独放置，不污染常态三视图。

画风：【自动识别参考图画风，例如：日系TV动画赛璐璐上色，干净利落的黑色线稿】

Negative constraints: no missing expression sheet, no fewer than four expression panels, no unlabeled expression panels, no changing face, no changing expression identity, no changing hairstyle, no changing hair color, no removing marks/accessories, no changing outfit, no changing accessories, no changing color palette, no changing material, no changing body type, no changing art style, no invented core props, no extra characters, no inconsistent turnaround, no inconsistent face between views, no missing front/side/back views, no unreadable layout, no decorative clutter, no watermark, no logo, no fake UI, no polaroid frame, no photo-of-a-photo effect.
