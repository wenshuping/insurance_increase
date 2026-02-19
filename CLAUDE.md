# 保险营销平台 — 项目 Skills 配置

## 项目简介

保险营销平台，连接 **保险客户、保险业务员、保险公司、平台运营** 四方。

---

## Skills 配置（按角色）

以下 skills 已全局安装，本项目按角色自动加载。

### 🏛️ 架构师

```
skills:
  - architecture-patterns       # Clean Architecture / DDD / Hexagonal
  - architecture-decision-records  # ADR 决策记录
  - c4-architecture             # C4 架构图（Mermaid）
  - microservices-patterns      # 微服务设计
```

### 📋 产品经理

```
skills:
  - prioritizing-roadmap        # 功能优先级排序
  - product-marketing-context   # 产品定位文档
  - postmortem-writing          # 复盘报告
  - find-skills                 # 发现新 skills
```

### 📁 项目经理

```
skills:
  - prioritizing-roadmap        # 里程碑规划、任务拆解
  - architecture-decision-records  # 决策日志跟踪
  - postmortem-writing          # 项目复盘
  - c4-architecture             # 辅助跨团队沟通
```

### 🎨 UI 设计师

```
skills:
  - ui-ux-pro-max              # 50 种风格、21 种配色
  - ui                         # UI 设计
  - product-designer           # UX/原型/用户研究
  - tailwind-design-system     # Tailwind v4 设计系统
  - web-design-guidelines      # UI 规范审查
  - accessibility-compliance   # WCAG 2.2 无障碍
```

### 💻 前端开发

```
skills:
  - frontend-design            # 生产级前端界面
  - vercel-react-best-practices  # React/Next.js 最佳实践
  - tailwind-design-system     # 组件实现
  - accessibility-compliance   # 无障碍交互
```

### ⚙️ 后端开发

```
skills:
  - architecture-patterns      # 分层架构、领域模型
  - microservices-patterns     # 服务间通信
```

### 🧪 测试工程师

```
skills:
  - webapp-testing             # Playwright 自动化测试
  - accessibility-compliance   # 无障碍合规测试
  - postmortem-writing         # Bug 复盘报告
```

---

## 使用方式

直接描述角色 + 需求，Claude 自动调用对应 skill：

```
"以架构师角色，画保险投保流程的 C4 架构图"
"以产品经理角色，排 Season 1 功能优先级"
"以前端开发角色，实现业务员工作台首页"
"以 UI 设计师角色，设计保费计算器组件"
"以测试工程师角色，为投保流程写 Playwright 测试"
```

---

## 技术栈

| 端 | 技术 |
|----|------|
| 客户端 H5/小程序 | Vue3 + uni-app + Tailwind |
| 业务员工作台 | Vue3 + Vant + Tailwind |
| 公司/运营后台 | Vue3 + Element Plus + Tailwind |
| 后端服务 | NestJS + TypeScript + PostgreSQL |
| 测试 | Playwright |

## 设计系统

见 [design-system/MASTER.md](design-system/MASTER.md)

## 架构文档

见 [docs/architecture/](docs/architecture/)

## 产品路线图

见 [docs/product-roadmap.md](docs/product-roadmap.md)
