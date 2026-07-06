<p align="center">
  <img src="assets/intro-card.png" alt="China Litigation Rehearsal intro card" width="100%">
</p>

# china-litigation-rehearsal · 中国大陆模拟法庭 Skill

中国大陆民商事诉讼庭前预演与败诉风险排查 Codex Skill。它默认以交互引导开始，帮助律师在脱敏案情基础上选择快速体检、标准预演、深度打磨、单点训练或庭前实战手册整理。

China Litigation Rehearsal is a Codex Skill for PRC civil/commercial litigation rehearsal. It is designed for lawyers preparing hearings, organizing risks, and stress-testing case strategy.

## 适用场景

- 程序闸门、争议焦点、证据缺口快速体检
- 对方律师红队攻防与抗辩预判
- 法官追问与口头回答演练
- 关键人物陈述、发问和庭前沟通准备
- 败诉风险排查与庭前实战手册整理

## 安装方式

在终端运行：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/katejianglaw/china-litigation-rehearsal.git ~/.codex/skills/china-litigation-rehearsal
```

安装后，在 Codex 中调用：

```text
使用 $china-litigation-rehearsal
```

也可以直接提供脱敏案情、程序阶段、诉求或抗辩目标、证据目录，Skill 会默认进入引导模式。

## Disclaimer

本 Skill 仅作庭前演练、思路整理和风险排查，不构成法律意见，也不预测案件结果。所有法条、司法解释、指导性案例、参考案例、类案和地方规则均需在官方来源核验后再用于正式法律文件或对外沟通。

请勿输入真实姓名、身份证号、联系方式、商业秘密、未公开客户材料、完整合同原文或其他敏感个人信息。建议仅使用脱敏事实、证据摘要和必要的程序信息。

This skill is for rehearsal and risk-spotting only. It is not legal advice and does not predict litigation outcomes. Verify all legal authorities through official sources before external use.

## 文件结构

- `SKILL.md`: Skill 主指令
- `agents/openai.yaml`: Codex 展示元数据
- `references/`: 程序框架、输出契约、角色模块和法律依据核验索引
- `assets/intro-card.*`: GitHub 页面介绍图

## 版本

当前发布版本：`v1.0`
