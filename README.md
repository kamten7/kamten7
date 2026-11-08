<div align="center">

<img src="./assets/header.svg" alt="kamten7 · Java backend & LLM application engineering" width="100%"/>

<a href="https://github.com/kamten7">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2600&pause=1500&color=2DD4BF&center=true&vCenter=true&width=740&lines=Java+Backend+Developer+%C2%B7+LLM+Application+Engineer;Spring+Boot+%C2%B7+MyBatis-Plus+%C2%B7+MySQL+%C2%B7+Redis;LangChain4j+%C2%B7+Function+Calling+%C2%B7+SSE+Streaming;Open+to+2026+Java+Backend+Internship" alt="typing"/>
</a>

<br/>

<img src="https://img.shields.io/badge/status-open_to_internship-2DD4BF?style=flat-square&labelColor=0B1220"/>
<img src="https://img.shields.io/badge/focus-Java_backend_/_LLM_apps-161F2E?style=flat-square&labelColor=0B1220"/>
<img src="https://img.shields.io/badge/base-Zhanjiang_%E2%86%92_Guangzhou-161F2E?style=flat-square&labelColor=0B1220"/>
<a href="mailto:linchaofeng05@outlook.com"><img src="https://img.shields.io/badge/mail-linchaofeng05%40outlook.com-161F2E?style=flat-square&labelColor=0B1220&logo=microsoftoutlook&logoColor=2DD4BF"/></a>

</div>

---

## 关于我 / About

Lin ChaoFeng（kamten7），岭南师范学院软件工程大三。Java 后端方向，也做 JVM 上的大模型应用：LangChain4j 的 Function Calling、会话记忆与 SSE 流式输出。求职目标：广州，Java 后端实习。

## 精选项目 / Selected work

### 🏠 Nest_Backend — 租房平台后端

<sub>`Java 21` `Spring Boot 3.4` `MyBatis-Plus` `MySQL` `Redis` `LangChain4j`</sub>

**8 个 Maven 模块** · **19 张业务表** · **110 个单元测试**

- **模块划分**：`nest-order` / `nest-wallet` / `nest-ai` / `nest-common` 各自独立打包，依赖单向，业务模块之间不直接调用。
- **基础设施统一在 `nest-common`**：JWT 鉴权、全局异常处理、参数校验、MinIO 文件存储。
- **大模型接入**：LangChain4j 注册 5 个 `@Tool` 用于查询房源与计算价格，SSE 推流，Redis 保存多轮会话；对外仍是普通 HTTP 接口。

### 📦 TradeTrail — 商城交易闭环

<sub>`Java 21` `Spring Boot 3.5` `MySQL 8.4` `Vue 3` `Maven ×7`</sub>

**7 个 Maven 模块** · **3 个操作入口**（商城 / 管理台 / 物流模拟端）· **CI + Docker Compose**

- **订单状态机**：下单「可售 → 预留」、支付「预留 → 已售」、退款「已售 → 回补」，状态转换均为带条件的更新；库存不足整体回滚，未付款超时释放预留。
- **幂等与补偿**：支付渠道记录与金额双重校验，重复通知不重复确认；失败任务支持在管理台重放。
- **物流独立服务**：独立数据库与轨迹表，通过签名 HTTP 向商城推送事件。

### 🤝 anxin-backend — 合同风险分析 <sub>（3 人团队，我负责文档解析 / OCR / 风险分析三个模块）</sub>

<sub>`Spring Boot` `Apache Tika` `PP-OCR` `LangChain4j`</sub>

**文档解析 → 条款切分 → 大模型风险分析**：Apache Tika 抽取全文，纯 Java 在 JVM 内实现 PP-OCR（不依赖 Python 环境），模型输出做结构化解析与失败降级。

### 📱 Nest_uniapp / Nest_frontend — 用户端与房东端

[Nest_uniapp](https://github.com/kamten7/Nest_uniapp) 微信小程序：登录鉴权、房源检索、地图定位、在线预订，封装统一请求拦截与 Vuex 状态管理。<br/>
[Nest_frontend](https://github.com/kamten7/Nest_frontend) 房东管理台：房源上架、订单处理、数据看板（Vue 3 + TypeScript + Vite）。

## 技术栈 / Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=java,spring,mysql,redis,maven,git,linux,docker,ts,vue,idea&theme=dark" alt="tech stack"/>
</div>

- **主力** Java 21 · Spring Boot 3 · Spring MVC · MyBatis-Plus · Maven 多模块
- **数据** MySQL（表设计 / 索引 / 慢查询）· Redis（缓存 / 会话）
- **大模型应用** LangChain4j · Function Calling · SSE 流式 · 结构化输出与容错
- **前端** Vue 3 · TypeScript · uni-app

## 数据 / Numbers

<div align="center">

<img src="./assets/langs.svg" alt="language spectrum" width="100%"/>

<img src="./assets/commits.svg" alt="commit activity" width="100%"/>

</div>

## 联系 / Contact

<div align="center">

<a href="mailto:linchaofeng05@outlook.com"><img src="https://img.shields.io/badge/mail-linchaofeng05%40outlook.com-161F2E?style=flat-square&labelColor=0B1220&logo=microsoftoutlook&logoColor=2DD4BF"/></a> <a href="https://github.com/kamten7"><img src="https://img.shields.io/badge/github-kamten7-161F2E?style=flat-square&labelColor=0B1220&logo=github&logoColor=2DD4BF"/></a>

</div>

<br/>

<img src="./assets/footer.svg" alt="footer" width="100%"/>
