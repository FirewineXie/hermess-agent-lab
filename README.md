# Hermess Agent Lab

一套给 [Hermess Agent Desktop](https://github.com/FirewineXie/hermess-agent-desktop) 用的开源资产，包含 **Agent（专家角色）、Skill（技能）、MCP（连接器配置）** 三类，开箱即用，全部基于本人真实在跑的工作流整理。

本仓库与主程序分开授权：这里的内容采用 **MIT 协议**，可自由使用、修改、商用，保留版权声明即可。主程序本身的协议见其仓库 COPYRIGHT。

## 当前状态

仓库正在重构，资产会以更完整、经过实测的形式陆续通过 Pull Request 合入。当前暂未收录正式资产，欢迎先点 Watch 关注更新，或在 Issues 提出你最想要的能力。

## 目录结构

```
hermess-agent-lab/
├── agents/    # 专家角色 Profile，导入即用
├── skills/    # 技能，含 SKILL.md 与配套文件
├── mcp/       # MCP 连接器配置模板与接线说明
└── examples/  # 调用示例与效果对照
```

后续计划收录的方向包括：去 AI 味写作、国产模型免费接入配置、定时整理文件、工作流编排等。具体内容以实际合入的目录为准。

## 协作方式

main 分支受保护，**所有改动都通过 Pull Request 提交，不直接推送 main**。每个 PR 会经过实测与隐私检查（不含账号、密钥、本机路径、个人身份信息）后再合入。

## 怎么安装

1. 下载本仓库（Code → Download ZIP，或 `git clone`）。
2. 打开 Hermess Agent Desktop，进入对应 Profile 的技能/角色/MCP 管理页。
3. 把对应目录导入，按各资产 README 填好自己的配置（如模型 Key、工作区路径）。
4. 具体每一步以各资产目录下的 README 为准。

## 适用版本

- Hermess Agent Desktop v0.1.7 及以上。
- 不同版本菜单位置可能变化，能力以你本机实际版本为准。

## 免责声明

资产按“现状”提供，运行前请先在测试工作区验证；涉及删文件、外发、花钱的动作，软件本身有审批机制，请保持人工把关。配置模板里的 Key 请用你自己的，不要把真实密钥提交到任何公开仓库。

## 交流

- 问题与需求：GitHub Issues
- 公众号：杰 AI SHIKER（实测过程与教程在这里发）
