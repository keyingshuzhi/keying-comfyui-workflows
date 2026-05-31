# keying-comfyui-workflows

- 项目名称：`keying-comfyui-workflows`
- 当前版本：`v1.0`
- 更新时间：`2026-05-31`
- 目录位置：`user/default/workflows`

本目录用于维护可公开发布的 ComfyUI 工作流。

## 上传范围

以下工作流可上传到 GitHub（按当前目录文件名）：

- `Emoji_Base_Maker_v1.json`
- `Keying Romance Illustration Pro.json`
- `Logo 概念草图探索工作流.json`
- `创意文生图_中.json`
- `动漫生成.json`
- `抠图_批量模式.json`
- `抠图_精准模式.json`
- `柯影超清工坊.json`
- `视频超分_单视频模式.json`
- `视频超分_批量模式.json`

## 提交规范

1. 新增工作流时，先确认不属于“无限制”类别。
2. 提交前检查工作流 JSON，不包含本地绝对路径、密钥、账号等敏感信息。
3. 工作流依赖的自定义节点，建议在提交说明中标注对应节点仓库。
4. 文件名建议保持中文业务语义，必要时补充英文别名说明。

## 导入方式（ComfyUI）

1. 打开 ComfyUI。
2. 在 Workflow 菜单中选择 Load。
3. 选择本目录下对应 `.json` 文件导入。
