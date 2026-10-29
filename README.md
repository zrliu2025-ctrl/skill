# Skills

用于 Codex 的个人技能集合。

| Skill | 用途 |
| --- | --- |
| [read-paper-zr](skills/read-paper-zr/SKILL.md) | 中文精读指定论文，整理背景、动机、技术与相关工作、创新、方法、实验、局限及借鉴方向；将完整笔记写入 Obsidian 的 `1-reading` 文件夹，以论文原文标题命名。 |

`read-paper-zr` 包含相关工作与实验表模板，以及已确认的学术方法示意图风格说明和参考图片。图中模块与连接根据每篇论文的真实方法调整。

## 安装与使用

在 Codex 中发送：

> 请从 https://github.com/zrliu2025-ctrl/skill 安装 `skills/read-paper-zr`。

安装后，在下一轮对话中使用：

```text
$read-paper-zr 帮我精读这篇论文：<PDF 路径、论文链接、DOI 或标题>
```

也可直接发送论文并要求阅读。默认完整精读，明确要求速读时压缩；单点追问只解释相关内容。

需要可用的 PDF 读取、图片生成及 Obsidian 笔记写入能力。优先复用已确定的 Obsidian 库；首次无法确定目标库时，会询问库位置。已有同名笔记不会被静默覆盖。
