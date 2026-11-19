<div align="center">
  <a href="https://github.com/silexhub">
    <img src="assets/symbol.svg" width="88" height="88" alt="SilexHub" />
  </a>
  <h1>SilexHub</h1>
  <p><strong>给 AI 用的专业工具与数据</strong></p>
  <p>把可追溯的专业数据、行业知识和工作工具带进你常用的 AI。</p>
  <p>
    <a href="https://silexhub.com">产品网站</a> ·
    <a href="https://github.com/silexhub/docs">文档</a> ·
    <a href="https://github.com/silexhub/mcp-server">MCP接入</a> ·
    <a href="#能力方向">能力方向</a> ·
    <a href="#从哪里开始">从这里开始</a> ·
    <a href="https://github.com/silexhub/silexhub/issues">提出能力需求</a> ·
    <a href="README.md">English</a>
  </p>
  <p>
    <a href="#当前可用状态"><img src="https://img.shields.io/badge/Stage-In_development-E65B31?style=flat-square" alt="开发阶段" /></a>
    <a href="README.md"><img src="https://img.shields.io/badge/Readme-English_%2F_中文-555?style=flat-square" alt="中英文介绍" /></a>
  </p>
</div>

---

首品预览是美股半导体地区收入。可查看[英伟达原披露、重列及 SEC 年报原表](https://silexhub-prelaunch.1255829396.workers.dev/)。

一个能做事的 Agent，除了模型，还需要合适的信息、执行动作的途径，以及能交给下一步的输出。SilexHub 关注的就是这些具体任务：输入是什么、做到哪里、最后交付什么，都应清楚。

这里是 **SilexHub 官方开发者入口**，集中发布产品介绍、可用状态和正式发布的接入资料。

## 为什么做 SilexHub

- **从任务出发。** 按要完成的工作找能力，先看能交付什么结果。
- **输入输出清楚。** 使用前知道需要提供什么、得到什么格式，以及范围和限制。
- **交付形式跟着任务走。** 文件、数据结果、工具调用和软件连接各有用途，选择适合下一步工作的形式。
- **人控制范围。** 人选择能力、决定授权，Agent 在约定范围内使用。

这些是产品的设计原则。下面的可用状态单独列出今天已经公开的资料，以及仍在开发中的接入。

## 能力方向

<table>
  <tr>
    <th align="left">工具</th>
    <th align="left">数据</th>
    <th align="left">软件连接</th>
  </tr>
  <tr>
    <td>把明确输入变成可用结果，例如转换、检查、比较或生成交付物。</td>
    <td>为任务提供结构化信息、数据集和知识资产。</td>
    <td>把经过授权的软件动作接入更大的工作流。</td>
  </tr>
  <tr>
    <td><strong>看什么：</strong>任务与输出。</td>
    <td><strong>看什么：</strong>来源、范围、格式与版本。</td>
    <td><strong>看什么：</strong>权限、动作与结果。</td>
  </tr>
</table>

按具体能力，交付物可能是文件、结构化结果、可复用工作流或软件接入。每项正式发布的能力会说明支持的格式和使用方式。

## 可以用来做什么

以下场景用于解释产品方向，**不代表已经上架的商品目录**。

| 工作流 | 你提供的输入 | 你需要的结果 |
| --- | --- | --- |
| 给 Agent 准备信息 | 原始材料和目标结构 | 能交给下一步使用的结构化交付物 |
| 检查和比较业务信息 | 记录、字段和比较规则 | 清晰的对照结果与待复核差异 |
| 为任务补充领域知识 | 问题和明确的信息范围 | 带来源、版本说明的相关数据或知识 |
| 把结果送进另一个工具 | 已授权的动作和必要字段 | 一次可检查结果的软件操作 |

有具体任务？[告诉我们你的工作流](https://github.com/silexhub/silexhub/issues/new)：输入是什么、想得到什么、接在哪一步。明确的小任务，能帮助我们决定先做好哪项能力。

## 一次使用如何衔接

```mermaid
flowchart LR
    A[选择任务] --> B[确认输入与输出]
    B --> C[授权使用范围]
    C --> D[人或 Agent 使用能力]
    D --> E[把结果交给下一步]
```

| 人的入口 | Agent 和开发者的入口 |
| --- | --- |
| 了解能力、查看样例、选择使用权限、领取结果。 | 阅读能力约定、提供输入，通过正式支持的接入方式取得输出。 |

SilexHub 正围绕这条共同链路设计。每项能力的接入资料会说明访问方式、消耗规则和失败后的处理。

## 当前可用状态

| 内容 | 状态 |
| --- | --- |
| 中英文网站 | [中文](https://silexhub.com) · [English](https://silexhub.com/en) |
| 实践文章与使用指南 | [文章](https://silexhub.com/articles) · [指南](https://silexhub.com/docs) |
| 只读工作台演示 | [免登录体验](https://silexhub.com/demo)，使用明确标注的合成样例 |
| 账户与工作台 | 正式站开发中 |
| 产品介绍与中英文 README | 已在本仓库公开 |
| 产品文档与MCP接入资料 | [文档仓](https://github.com/silexhub/docs) · [MCP仓](https://github.com/silexhub/mcp-server) |
| 公开提问与能力需求 | [GitHub Issues](https://github.com/silexhub/silexhub/issues) |
| 收费能力目录 | 尚未发布 |
| 公开 API、MCP 端点、可安装 SDK | 尚未发布 |
| 可运行的快速开始 | 随对应接入正式发布 |

**网站与只读演示已开放。** 访客可直接浏览公开样例、实践文章和使用指南。结账、收费能力、公开 API、MCP 服务与可安装 SDK 仍在开发。

## 从哪里开始

1. **先看一份样例。** 打开[只读演示](https://silexhub.com/demo)或[使用指南](https://silexhub.com/docs)，再按能力分类与工作流场景判断是否适合自己的任务。
2. **提出具体需求。** [创建能力需求 Issue](https://github.com/silexhub/silexhub/issues/new)，附一个小型合成样例。
3. **关注公开更新。** Watch 本仓库，从可用状态一节查找经过验证的正式接入。

一份有用的需求，包含：

- 要完成什么任务，谁使用结果。
- 能提供什么输入，希望输出什么格式。
- 接在哪里：手动任务、Agent，还是已有应用。
- 会改变方案的约束，例如更新频率或授权范围。

公开 Issue 请使用合成样例，不上传访问凭据、客户记录或保密材料。

## 一项正式接入应说明什么

| 问题 | 对应资料 |
| --- | --- |
| 能做什么？ | 具体任务、适用范围和限制 |
| 发什么、收什么？ | 必需输入、输出格式和完整样例 |
| 怎么接入？ | 正式支持的访问方式和鉴权步骤 |
| 怎么计算使用？ | 适用的计量单位、限制和发布时的价格 |
| 失败怎么办？ | 错误行为、重试办法和结果领取方式 |
| 能试一下吗？ | 对应正式接入的实测快速开始 |

## 常见问题

<details>
<summary><strong>SilexHub 是工具、数据集，还是平台？</strong></summary>

SilexHub 是我们自营工具、数据和软件连接的产品品牌。当前模式是提供自己建设与维护的能力，暂不涉及第三方卖家入驻。

</details>

<details>
<summary><strong>现在能通过 MCP 连接 Agent 吗？</strong></summary>

公开 MCP 服务尚未发布。正式接入可用时，这里会提供支持的客户端和经过验证的配置。

</details>

<details>
<summary><strong>克隆仓库后可以自己部署网站吗？</strong></summary>

本仓库是公开开发者入口，包含介绍资料和批准公开的品牌素材，不包含托管应用源码或可自行部署的服务发行版。

</details>

<details>
<summary><strong>在哪里提问、建议或修正文档？</strong></summary>

在 [GitHub Issues](https://github.com/silexhub/silexhub/issues) 提出公开产品问题、能力需求和文档反馈。文档修正也可以通过 Pull Request 提交。

</details>

## 官方入口

| 入口 | 用途 |
| --- | --- |
| [SilexHub 组织](https://github.com/silexhub) | 官方 GitHub 主页与公开仓库导航 |
| [开发者主仓](https://github.com/silexhub/silexhub) | 产品介绍与已发布接入资料 |
| [产品文档](https://github.com/silexhub/docs) | 入门、概念、工作流与可用状态 |
| [MCP接入](https://github.com/silexhub/mcp-server) | 连接指南、能力约定与发布条件 |
| [English](README.md) | 英文介绍与可用状态 |
| [产品域名](https://silexhub.com) | SilexHub 的产品网站地址 |

---

<div align="center">
  <strong>SilexHub</strong><br />
  工具 · 数据 · 软件连接<br />
  <a href="#silexhub">回到顶部 ↑</a>
</div>
