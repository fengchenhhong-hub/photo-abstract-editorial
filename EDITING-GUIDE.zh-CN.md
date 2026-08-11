# 中文修改指南

- 分类：图片美术风格
- 风格：原片忠实保留 × 极简抽象记忆面板 × 诗意英文标题
- Codex 调用名：`$photo-abstract-editorial`
- 主要用途：把建筑、城市、人物和旅行照片编排成摄影—抽象双区作品。

## 最常改的地方

- 上方照片 / 下方抽象区比例：修改 `SKILL.md` 的构图规则。
- 抽象图形数量、线条与色块：修改抽象面板规则，仍从原照片提取。
- 英文标题语气：修改标题规则，保持简短且不遮挡原片。
- 保真要求：原照片不可重绘、滤镜化或替换主体。

## 授权边界

该上游项目只允许个人、教育、研究和非商业用途。商业使用、商业再分发或商业化工作流必须先取得原作者授权。

## 验证

```bash
python3 ~/.codex/skills/.system/skill-creator/scripts/quick_validate.py ~/.codex/skills/photo-abstract-editorial
```

本地修改只影响当前电脑；需要长期保存时，再提交回你的 GitHub Fork。
