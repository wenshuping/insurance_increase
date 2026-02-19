# 保险营销平台

连接**客户、业务员、保险公司、平台运营**四方的保险营销平台。

---

## 技术栈

| 端 | 技术 |
|----|------|
| 客户端 H5/小程序 | Vue3 + uni-app + Tailwind |
| 业务员工作台 | Vue3 + Vant + Tailwind |
| 公司/运营后台 | Vue3 + Element Plus + Tailwind |
| 后端服务 | NestJS + TypeScript + PostgreSQL |
| 测试 | Playwright |

---

## 图标规范（强制）

**所有图标必须用 `better-icons` CLI 获取 inline SVG，禁止用 emoji 或字符代替。**

```bash
npx better-icons search "icon-name"
npx better-icons get "lucide:icon-name"   # lucide:* 为本项目首选图标集
```

- SVG 必须带 `stroke="currentColor"` 支持颜色继承
- 禁止：emoji 图标（🏠👥）、font-size 字符图标

---

## 文档输出规范

**禁止在项目根目录创建任何文档**，按类型存放：

| 文档类型 | 存放路径 |
|----------|----------|
| 架构/C4/系统设计 | `docs/architecture/` |
| API 接口文档 | `docs/api/` |
| 数据库/ER 图 | `docs/database/` |
| PRD/需求/用户故事 | `docs/product/` |
| ADR 架构决策记录 | `docs/decisions/` |
| 复盘报告 | `docs/postmortem/` |
| 设计系统/组件规范 | `design-system/` |
| 测试报告 | `tests/reports/` |
| 产品路线图 | `docs/` |

---

## 关键文档索引

- 设计系统：[design-system/MASTER.md](design-system/MASTER.md)
- 架构文档：[docs/architecture/](docs/architecture/)
- 产品路线图：[docs/product-roadmap.md](docs/product-roadmap.md)
- Skills 角色参考：[skills/](skills/)

---

## Skills 使用说明

Skills 按需调用，无需预加载。告知角色即可，例如：

```
"以前端开发角色，实现业务员工作台首页"
"以产品经理角色，排 Season 1 功能优先级"
"以保险业务专家角色，解释重疾险和医疗险的区别"
```

各角色完整 skills 列表见 [skills/](skills/) 目录。

# currentDate
Today's date is 2026-02-19.
