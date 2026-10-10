# 个人常用 Skills

收集和维护个人常用的 AI 助手 skills，每个 skill 独立存放在 `skills/` 目录中。

## 已收录

| Skill | 说明 |
| --- | --- |
| [paper-reading-notes](skills/paper-reading-notes/SKILL.md) | 按统一格式阅读和讲解论文，给出完整中文摘要、核心方法、通俗解释与实验边界；按需分析项目启示、保存或整理 Markdown 笔记。 |

## 目录结构

```text
skills/
└── paper-reading-notes/
    ├── SKILL.md                  # 使用范围与工作流程
    ├── agents/openai.yaml        # 界面名称、简介与默认提示词
    └── references/note-format.md # 阅读与笔记的统一格式
```

## 使用示例

导入 `skills/paper-reading-notes` 目录后，可用以下提示词调用：

> 使用 $paper-reading-notes 阅读这篇论文，按固定格式给出完整中文摘要、核心方法、通俗解释和实验边界。

需要项目分析或保存笔记时，在请求中补充具体项目或保存要求。详细流程见 [SKILL.md](skills/paper-reading-notes/SKILL.md)，输出格式见 [笔记格式模板](skills/paper-reading-notes/references/note-format.md)。
