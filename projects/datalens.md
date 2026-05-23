# DataLens — 实时数据可视化仪表盘

**DataLens** 是一个交互式实时监控仪表盘，支持多数据源接入、自定义图表和告警规则引擎。

## 核心特性

### 📈 多数据源接入
支持 PostgreSQL、Redis、WebSocket、REST API 等多种数据源，统一数据查询接口。

### 🎨 自定义图表
基于 D3.js 构建的可视化组件库，支持折线图、柱状图、热力图、桑基图等十余种图表类型。

### 🔔 智能告警
灵活的告警规则引擎，支持阈值告警、同比/环比异常检测，多渠道推送通知。

## 技术架构

- **前端**: D3.js + Vanilla JavaScript
- **后端**: Node.js (Express) + WebSocket
- **数据层**: Redis 缓存 + PostgreSQL 持久化
- **部署**: Docker Compose

## 链接

- [GitHub 仓库](https://github.com/Fuyh314/datalens)