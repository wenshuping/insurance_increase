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
  - skill-creator               # 创建自定义 skills
  - product-manager-toolkit     # PM 综合工具包
  - prd-generator               # PRD 需求文档生成
  - user-story-mapping          # 用户故事地图
```

### 📁 项目经理

```
skills:
  - prioritizing-roadmap        # 里程碑规划、任务拆解
  - architecture-decision-records  # 决策日志跟踪
  - postmortem-writing          # 项目复盘
  - c4-architecture             # 辅助跨团队沟通
  - planning-with-files         # 文件驱动项目规划
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
  - better-icons               # 图标库设计
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

### 📣 市场营销 (Marketing)

```
skills:
  - copywriting                # 营销文案写作
  - marketing-psychology       # 营销心理学
  - content-strategy           # 内容策略规划
  - seo-audit                  # SEO 审查优化
  - programmatic-seo           # 程序化 SEO
  - product-marketing-context  # 产品营销定位
```

### 👥 客户角色 (Customer Persona)

> 模拟真实用户体验产品，用于测试、用研、体验验证

```
skills:
  - customer-persona           # 客户角色模拟（多年龄/性别/身份）
```

**内置角色：**
- 青年群体：小王（互联网男）、小李（应届女生）、阿杰（自由职业）、小美（已婚白领）
- 中年群体：张总（企业主）、王姐（全职主妇）、老陈（国企中层）、林姐（教师）
- 老年群体：王阿姨（退休工人）、李大爷（退休干部）
- 特殊群体：外卖小哥阿明、海归Lucy、宝妈小雪

### 🏢 保险从业人员角色 (Insurance Staff Persona)

> 模拟业务员、团队长、公司高管视角，用于 B 端产品测试和需求验证

```
skills:
  - insurance-staff-persona    # 从业人员角色模拟（不同层级/阅历）
```

**内置角色：**
- 新人业务员：小陈（应届转行）、小敏（宝妈兼职）
- 成长型业务员：阿强（主力销售）、晓琳（女性客群）、老黄（二线城市）
- 资深业务员：刘哥（行业老炮）、美姐（转型培训）
- 团队长：王姐（初级）、陈总监（资深30人团队）
- 保险公司高管：林副总（渠道总监）、李总（VP）、郑总（CTO）
- 经纪公司高管：钱总（小型创始人）、吴CEO（B轮）、许CTO（技术）

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
