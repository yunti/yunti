### 云梯 Yunti

[![Email](https://img.shields.io/badge/changwanyi53%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:changwanyi53@gmail.com)
[![WeChat](https://img.shields.io/badge/VX-%E5%BE%85%E5%A1%AB%E5%86%99-07C160?style=flat-square&logo=wechat&logoColor=white)](#)
![Location](https://img.shields.io/badge/China-000000?style=flat-square&logo=googlemaps&logoColor=white)

<!--
  ⚠️ 待解锁：followers 徽章。数字为 0 时是负向信号，建议 ≥50 再启用。
  ![GitHub Followers](https://img.shields.io/github/followers/yunti?color=ff69b4&style=flat-square)
  ⚠️ 上方的 WeChat 徽章是占位符，把「待填写」换成你的微信号即可；不想公开就整行删掉。
-->


「云梯」二字，一半取自《逍遥游》——「怒而飞，其翼若垂天之云」；一半取自《墨子·公输》——公输盘为楚造云梯之械。

**翼是往远处想，梯是往实处做。** 这也是我做工程的两面。

先写前端，后做后端，再往里扎进基建与交付。这几年只专心一件事：**让大模型从演示走进生产。**

我不训模型。我做的是让它能活下来的那一层——数据怎么进来、结果凭什么可信、失败之后怎么重来，以及一台连不上外网的机器，怎么用一条命令跑起来。

不擅言辞，惯于深夜动手。所成之器皆在此处；所守之道只有三个字——**能交付**。

<details>
<summary><b>English</b> — Full-stack engineer taking LLM apps from demo to production</summary>

**Yunti** — a name borrowed from two classics: the Peng bird "whose wings are like clouds hanging
from the sky" (*Zhuangzi*), and the siege ladder of *Mozi*. Wings for thinking far, a ladder for
climbing in practice.

I'm a full-stack engineer. Frontend first, then backend, now mostly infrastructure and delivery.
My focus is **taking LLM applications from demo to production** — not training models, but building
the layer that keeps them alive: data ingestion, verifiable output, retry on failure, and
one-command deployment on air-gapped machines.

</details>

---

### 🎯 专注方向

| 方向 | 具体在做的事 |
| :--- | :--- |
| **LLM 应用工程** | 让模型输出可校验、可重试、可观测，而不是"跑通一次就算完成" |
| **文档智能** | 表格 OCR 结构化 + 混合检索，把 PDF 与扫描件变成可查询资产 |
| **浏览器自动化** | 用 CDP 驱动真实 Chrome，处理重 SPA、登录态复用、需人工监督的场景 |
| **工程基建** | 开发基座 + Docker 离线部署 + tag 触发的发布流水线 |

<!--
  ═══════════════════════════════════════════════════════════════
  🚧 待解锁区块 A：项目卡片
  启用条件：chrome-rpa-browser 或其它原创项目公开后。
  把下面的注释去掉，替换 handle 与仓库名即可。星标徽章是实时的，会自动更新。
  ═══════════════════════════════════════════════════════════════

### 🚧 在做

- **[chrome-rpa-browser](https://github.com/yunti/chrome-rpa-browser)** <a href="https://github.com/yunti/chrome-rpa-browser"><img src="https://img.shields.io/github/stars/yunti/chrome-rpa-browser?style=social" alt="stars" height="16"></a> — 基于 CDP 的 Chrome 自动化框架，复用登录态、支持人工监督
- **[fastapi-vue-frame](https://github.com/yunti/fastapi-vue-frame)** <a href="https://github.com/yunti/fastapi-vue-frame"><img src="https://img.shields.io/github/stars/yunti/fastapi-vue-frame?style=social" alt="stars" height="16"></a> — FastAPI + Vue 3 中后台基座（基于 FastAPI-RuoYi-Vue3 二次开发）
-->

<!--
  ═══════════════════════════════════════════════════════════════
  🚧 待解锁区块 B：贡献上游
  启用条件：有 PR 被上游合并后。
  这是本页可信度最高的一块 —— 挂的是别人项目的星标，读者会把它关联到你身上。
  注意：只列**真实合并过**的项目，fork 不算贡献。
  ═══════════════════════════════════════════════════════════════

### 🤝 贡献上游

- **[FastAPI-RuoYi-Vue3](https://github.com/insistence/FastAPI-RuoYi-Vue3)** <a href="https://github.com/insistence/FastAPI-RuoYi-Vue3"><img src="https://img.shields.io/github/stars/insistence/FastAPI-RuoYi-Vue3?style=social" alt="stars" height="16"></a> — 若依体系的 FastAPI 实现
-->

---

### 🛠 技术栈

每一项都标出它在我手里**实际承担什么**，不只是罗列名字。

**后端 · 接口与异步任务**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy_Async-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-6BA81E?style=flat-square&logo=alembic&logoColor=white)

FastAPI 承载业务 API 与 OpenAPI 文档 · SQLAlchemy 全异步访问数据库 · Celery 跑文档解析这类长任务 · Alembic 管生产库迁移

**前端 · 中后台界面**

![Vue 3](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=flat-square&logo=pinia&logoColor=black)
![Element Plus](https://img.shields.io/badge/Element_Plus-409EFF?style=flat-square&logo=element&logoColor=white)

Vue 3 组合式 API 快速交付管理界面 · Vite 构建 · Pinia 管状态 · Element Plus 提供一致的中后台交互

**数据与检索 · 存储与知识库**

![MySQL](https://img.shields.io/badge/MySQL_8-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch_9-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO%2FS3-C72E49?style=flat-square&logo=minio&logoColor=white)

MySQL 存业务数据 · Redis 扛缓存、登录态与任务队列 · Elasticsearch 做知识库混合检索 · MinIO/S3 统一文件存储（存储层已做接口抽象，可替换实现）

**交付与运维 · 从开发到离线部署**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

Docker Compose 打包整套服务 · Nginx 托管前端并反代后端 · GitHub Actions 做 CI 与 tag 触发发布 · 含**内网离线部署**方案

**AI 与自动化**

![RAG](https://img.shields.io/badge/RAG-%E6%B7%B7%E5%90%88%E6%A3%80%E7%B4%A2-6E56CF?style=flat-square)
![OCR](https://img.shields.io/badge/OCR-%E8%A1%A8%E6%A0%BC%E7%BB%93%E6%9E%84%E5%8C%96-0EA5E9?style=flat-square)
![DeepSeek](https://img.shields.io/badge/DeepSeek_API-4D6BFE?style=flat-square)
![CDP](https://img.shields.io/badge/Chrome_DevTools_Protocol-4285F4?style=flat-square&logo=googlechrome&logoColor=white)

RAG 混合检索 · 表格 OCR 结构化 · 对接大模型 API 并处理重试、限流与结果校验 · 基于 CDP 驱动真实 Chrome

---

<div align="center">

**若你在做 LLM 落地、文档智能或浏览器自动化，欢迎来聊。**

<a href="mailto:changwanyi53@gmail.com"><img src="https://img.shields.io/badge/%E5%90%88%E4%BD%9C-%E5%8F%91%E9%82%AE%E4%BB%B6-2ea44f?style=flat-square" alt="合作"></a>

<sub>不接与自动化、爬虫相关的灰色用途，这条线不聊。</sub>

</div>
