# 去防御性写作 · Anti-Defensive Writing

一个面向中英文学术写作的 skill：删除预先辩解、重复限定和多余免责声明，让文本直接表达证据支持的结论，同时保留真实的不确定性和研究边界。

## 适用场景

- 起草或改写论文摘要、引言、结果、讨论和结论。
- 整理研究计划、工程计算论文和审稿回复。
- 检查中文与英文文本中的防御性表达，并提供可直接使用的改写稿。

它以证据、命题和限定的实际功能作判断。真实局限、替代解释、不利结果以及相关与因果的区别应当保留。

## 使用方式

安装后，在支持 skill 的环境中调用：

```text
请使用 $anti-defensive-writing 改写下面的文本，去除不必要的防御性措辞，保留真实不确定性和研究边界。

【粘贴你的文本】
```

默认交付完整改写稿。需要检查或对照时，可以明确要求审计：

```text
请使用 $anti-defensive-writing 审计下面的段落，列出原句、问题及依据、处理建议，再给出改写稿。
```

也可以根据已有事实起草：

```text
请使用 $anti-defensive-writing，根据以下实验结果起草论文结论。保留数值、工况和验证范围。
```

## 改写示例

**已知事实**：基准模型平均相对误差为 6.2%，修改后为 5.8%。

**原句**：尽管改善幅度有限，但考虑到问题极具挑战性，该结果仍然令人鼓舞。

**改写**：修改后，平均相对误差由 6.2% 降至 5.8%。

更多中英文例子见 [references/examples.md](references/examples.md)。

## 在 Codex 中安装

将仓库克隆到个人 skills 目录，目录名使用 `anti-defensive-writing`。

Windows PowerShell：

```powershell
git clone https://github.com/zalee6666-crypto/anti-defensive-writing.git "$env:USERPROFILE\.codex\skills\anti-defensive-writing"
```

macOS / Linux：

```sh
git clone https://github.com/zalee6666-crypto/anti-defensive-writing.git ~/.codex/skills/anti-defensive-writing
```

使用自定义 `CODEX_HOME` 时，将仓库放入该目录下的 `skills/anti-defensive-writing`。

## 文件结构

```text
anti-defensive-writing/
├── SKILL.md                 # 核心写作规则与处理流程
├── agents/openai.yaml       # 界面名称、默认提示词和调用配置
├── assets/icon.svg          # skill 图标
├── references/examples.md   # 中英文判断与改写例子
└── README.md                # 仓库使用说明
```

核心规则见 [SKILL.md](SKILL.md)。
