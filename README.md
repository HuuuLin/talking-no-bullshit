# talking-no-bullshit

面向中文技术写作的 Codex 技能，用于起草、审阅与改写论文和工程说明。检查符号、单位与论证，让结论与证据相称。

例如，实验记录只比较了两种方案，各运行一次。把结果写成“B 的性能显著提升”，读者看不出测了什么，也无法判断“显著”的依据。可以写成“本次测试中，A 耗时 120 ms，B 耗时 90 ms”。数字是演示数据，判断只覆盖这一次比较。

## 安装

将仓库克隆到 Codex 的个人技能目录。以默认位置为例，在 PowerShell 中运行：

```powershell
git clone https://github.com/Mapleiu/talking-no-bullshit.git "$HOME/.codex/skills/talking-no-bullshit"
```
或者将该仓库链接直接发给codex来安装

## 使用

在 Codex 中输入 `$talking-no-bullshit`，接上任务和材料。

| 任务 | 可以这样问 |
| --- | --- |
| 起草 | `$talking-no-bullshit 根据下面的测试记录写论文结果段。保留测试条件和单位。` |
| 审阅 | `$talking-no-bullshit 只审阅这段推导。指出第一次出现但没有定义的符号，以及哪一步缺少成立条件。` |
| 改写 | `$talking-no-bullshit 只改最后一段工程交接说明。接手人需要知道为什么还保留旧接口。` |

报告和论文采用学术语体，工程说明和内部记录按实际用途组织。回答追问时从本轮问题写起，独立成文时则补足新读者需要的背景。

[查看完整规则](SKILL.md) · [查看改写示例](references/examples.md)
