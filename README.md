<p align="center">
  <img src="./assets/hero-banner.png" alt="Hidden Value · Opportunity Map — 个人隐性价值与商业机会发现" width="100%">
</p>

<h1 align="center">个人隐性价值与商业机会发现</h1>

<p align="center">
  基于行为证据的访谈式 Codex Skill：从真实经历中发现可迁移优势、职业方向与低成本商业机会
</p>

<p align="center">
  <img alt="license MIT" src="https://img.shields.io/badge/license-MIT-C9A85C">
  <img alt="type Codex Skill" src="https://img.shields.io/badge/type-Codex%20Skill-0E5962">
  <img alt="language 中文" src="https://img.shields.io/badge/language-%E4%B8%AD%E6%96%87-1C7180">
  <img alt="status v1.0.0" src="https://img.shields.io/badge/status-v1.0.0-2E8B70">
</p>

---

## 项目简介

这是一个访谈式 Codex Skill。它从用户真实做过的事情、成果、外部认可、资源和现实约束中，提炼可迁移能力，比较职业与商业机会，并生成低成本的 30/60/90 天验证计划。

它适合三类主要情境：

- 在职，希望提升职业安全感、升职转岗或探索低风险副业；
- 待业或准备转行，希望识别可迁移能力和现实路径；
- 自由职业、个体经营或小型创业，希望发现服务、产品、内容或可扩展机会。

## 主要特点

- 每次只选择一个主身份，避免报告失焦；
- 七个共同诊断板块，三套独立访谈路径；
- 一次只问一个问题，通常 10–14 题，最多 18 题；
- 使用事实、外部信号、推断和待验证四种证据标签；
- 区分个人优势与市场需求，不保证收入；
- 优先零成本或低成本验证，不鼓励未经验证就辞职、借钱或高投入创业；
- 报告明确说明已经做得好的、值得深挖的、证据不足的和下一步最值得讨论的内容。

## 安装

将整个 `discovering-personal-value-opportunities` 文件夹复制到 Codex Skills 目录，保持内部结构不变。重新启动或刷新 Codex 后，即可通过名称调用。

示例：

```text
Use $discovering-personal-value-opportunities to help me find overlooked strengths and realistic income opportunities.
```

也可以直接用中文表达：

```text
请用个人隐性价值与商业机会发现 Skill 访谈我，帮我分析职业优势和可验证的收入机会。
```

## 文件结构

```text
discovering-personal-value-opportunities/
├── SKILL.md
├── README.md
├── LICENSE
├── .gitignore
├── assets/
│   └── hero-banner.png
├── agents/
│   └── openai.yaml
└── references/
    ├── interview-core.md
    ├── interview-employed.md
    ├── interview-transition.md
    ├── interview-independent.md
    ├── evidence-and-opportunities.md
    └── report-template.md
```

顶部横幅仅用于 GitHub 项目展示。Skill 运行不需要脚本、付费 API、插件、云服务或后台任务。

## 方法边界

这是基于行为证据的个人价值盘点与机会发现工具，不是心理诊断、标准化职业测评、法律或财务建议，也不是收入保证。涉及实时市场、价格、平台规则或竞争情况时，应在用户同意后使用当前资料核实。

请勿输入身份证号、账号密码、财务凭证、客户名单、雇主机密、未公开合同或其他敏感资料。

## License

MIT License，详见 [LICENSE](LICENSE)。

