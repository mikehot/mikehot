<p align="center">
  <a href="https://mikehot.cloud">
    <img src="./assets/profile-banner.svg" alt="Jacky Chou - Principal Applied AI Engineer & FDE" width="100%" />
  </a>
</p>

# Jacky Chou (周亚杰)

**`Principal Applied AI Engineer · Forward Deployed Engineer (FDE) · Full-Stack Native & Cloud Architect`**  
12 年软件系统工程经验（2014 年起至今，经历 Eclipse ADT ➔ Android Studio / Java ➔ Kotlin / Flutter 三端商业端 ➔ Spring Boot 权限中台 ➔ 生产级受控 Agent / FDE 现场交付）。

I engineer mission-critical systems, high-assurance multi-agent architectures, mobile native runtimes, and zero-leak enterprise AI platforms with mathematically verifiable evidence.

<p>
  <a href="https://github.com/mikehot/fde-tools"><img alt="FDE CLI" src="https://img.shields.io/badge/Open%20Source-fde--tools-050505?style=for-the-badge&labelColor=050505&color=ffffff&logo=gnu-bash"></a>
  <a href="https://mikehot.cloud"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-mikehot.cloud-050505?style=for-the-badge&labelColor=050505&color=ffffff"></a>
  <a href="https://mikehot.cloud/resume/"><img alt="Resume" src="https://img.shields.io/badge/Resume-Online%20(ZH%20%7C%20EN)-050505?style=for-the-badge&labelColor=050505&color=d7d7d7"></a>
  <a href="https://github.com/mikehot/springboot-ai-rag-demo"><img alt="Public Demo" src="https://img.shields.io/badge/Enterprise%20RAG-Spring%20Boot%203-050505?style=for-the-badge&labelColor=050505&color=ffffff"></a>
  <a href="mailto:mikehot668@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-mikehot668%40gmail.com-050505?style=for-the-badge&labelColor=050505&color=d7d7d7"></a>
</p>

---

## 🛡️ Four-Dimensional Engineering Moat (四维技术护城河)

```
                       ┌──────────────────────────────────────────────┐
                       │   High-Assurance Industrial AI & Systems     │
                       └──────────────────────┬───────────────────────┘
                                              │
         ┌────────────────────┬───────────────┴───────────────┬────────────────────┐
         ▼                    ▼                               ▼                    ▼
┌──────────────────┐ ┌──────────────────┐           ┌──────────────────┐ ┌──────────────────┐
│ Systems & Mobile │ │ Enterprise RAG   │           │ Controlled Agent │ │ Field Multimodal │
│ Native Runtimes  │ │ & RBAC Security  │           │ State Machine    │ │ Commercial Loop  │
├──────────────────┤ ├──────────────────┤           ├──────────────────┤ ├──────────────────┤
│ • 16KB Page Align│ │ • Java 21 / SB 3 │           │ • LangGraph DAG  │ │ • Dual-Vision QA │
│ • SafeMethodChan │ │ • Row-Level RBAC │           │ • FastMCP Tools  │ │ • Math Equation  │
│ • Dio 401 Mutex  │ │ • AST Citations  │           │ • 5-Step Breaker │ │ • pHash Idempot. │
└──────────────────┘ └──────────────────┘           └──────────────────┘ └──────────────────┘
```

### 1. 端侧与系统级穿透力 (Systems & Mobile Native Penetration)
* **Google Play 2026 16KB 内存页对齐**：深入 NDK 段表排查，开发纯 Python 64-bit ELF 自动解析器，精准定位非对齐 `.so` 依赖与汇编对齐修复。
* **Flutter-Native 安全通信基座**：设计 `SafeMethodChannel` 原子状态机调度，杜绝跨线程未初始化调用、死锁与内存悬垂指针。
* **网络与并发单飞互斥锁**：Dio 拦截器并发单飞（Single Flight）互斥锁，多请求并发 401 时仅单次换票、无缝重放，零重复请求风暴。

### 2. 严密权限中台与防幻觉基座 (Strict RBAC & Anti-Hallucination Base)
* **Java 21 + Spring Boot 3 + pgvector**：物理隔离与动态 Tenant 过滤，保证多租户 RAG 检索 **0% ACL 越权泄露**。
* **独创后端 AST 引用真实性校验器**：强制回答携带物理页码与文本 Chunk Hash，若无真实依据强行断言 `found=false` 并触发人工降级。

### 3. 受控工业级 Agent 状态机 (Controlled Industrial Agent State Machine)
* **LangGraph + FastMCP 协议标准**：构建有向无环图（DAG），设定 5 步硬熔断（Bounded Loop）阻断死循环。
* **复杂意图拆解与动态撤权**：支持多目标递归分解（Decomposition 解决率 100%），高危只读/写入分离，不可逆操作会话级动态撤权与 Human-in-the-Loop 拦截。

### 4. 现场服务多模态商业闭环 (Field Multimodal Commercial Loop)
* **现场单据自动化录入与智能核验**：双视觉模型互验交叉复核、金额等式硬断言（Subtotal + Tax == Total）。
* **感知哈希 (pHash) 幂等防重**：计算图片感知哈希与 MD5 组合键，网络弱网重试时 0 错误率、0 重复单，实现 3.3 个月商业 ROI 回收。

---

## 🌟 Featured Open Source & Production Toolkits

| Repository | Focus & Capability | Tech Stack | Status |
| :--- | :--- | :--- | :---: |
| [**`mikehot/fde-tools`**](https://github.com/mikehot/fde-tools) | **Field Deployed Engineer CLI Toolkit**: 16KB ELF alignment inspector, perceptual dHash idempotency generator, FastMCP server scaffolder, Golden Dataset Evals runner, and defensive security guard. | Python 3.9+ · Zero Heavy Deps · CLI | [![CI](https://github.com/mikehot/fde-tools/actions/workflows/ci.yml/badge.svg)](https://github.com/mikehot/fde-tools/actions) |
| [**`mikehot/springboot-ai-rag-demo`**](https://github.com/mikehot/springboot-ai-rag-demo) | **Enterprise RAG Knowledge Base Mid-End**: Sanitized Spring Boot 3 + pgvector API demonstrating strict RBAC security, AST citation validation, `found=false` boundaries, unit tests & CI. | Java 21 · Spring Boot 3 · pgvector | [![CI](https://github.com/mikehot/springboot-ai-rag-demo/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/mikehot/springboot-ai-rag-demo/actions) |
| [**`mikehot/doc-intake-agent`**](https://github.com/mikehot/doc-intake-agent) | **Field Service Document Intake Engine**: Offline-resilient document processing with dual-vision LLM cross-validation, financial math assertions, and Redis-backed idempotency lock. | Python · LangGraph · FastMCP | `Active` |
| [**`mikehot/pocket_home_flutter`**](https://mikehot.cloud/projects/pocket-home-flutter/) | **Multi-Platform Enterprise Business App**: Cross-platform Flutter architecture with Android/iOS native bridge hardening, atomic channel safety, and offline cache synchronization. | Flutter · Dart · Android Native | `Production` |

---

## ⚡ Fast Review Navigation

| For | Recommended Entry | What You Can Verify |
| :--- | :--- | :--- |
| **Hiring & Executive** | [Online Resume](https://mikehot.cloud/resume/) | 12-year system evolution, verified milestones, enterprise case studies, and delivery scope |
| **Enterprise Client** | [Commercial Portfolio](https://mikehot.cloud) | 3-Day PoC packages, enterprise private deployment, 16KB troubleshooting, and ROI pricing |
| **Engineering Leader** | [FDE CLI Toolkit](https://github.com/mikehot/fde-tools) | Pure Python ELF page parser, pHash idempotency, FastMCP scaffolding, and test harness |
| **Security & Architecture** | [Spring Boot RAG Demo](https://github.com/mikehot/springboot-ai-rag-demo) | Physical row-level RBAC filtering, AST citation verification, and regression tests |
| **Confidential Verification** | [Email Request](mailto:mikehot668@gmail.com) | Commit logs, production CI runs, system architecture blueprints, and benchmark logs |

---

## 🛠️ Technology Spectrum

| Layer | Core Competencies | Tools & Frameworks |
| :--- | :--- | :--- |
| **Multi-Agent & FDE** | LangGraph, FastMCP, Golden Dataset Evals, Human-in-the-Loop, Bounded Loops | Python, LangGraph, FastMCP, Pydantic, Pytest |
| **Enterprise Backend** | Java 21, Spring Boot 3, Row-Level RBAC, Tenant Isolation, Audit Trails | Spring Boot, PostgreSQL, pgvector, Redis, Docker |
| **Mobile & Systems** | 16KB Page Alignment, SafeMethodChannel, Dio Single-Flight, NDK Segments | Flutter, Dart, Android Java/Kotlin, C/C++ NDK, Gradle |
| **Front-End & Admin** | Enterprise Operations Dashboards, Real-time Ticket Workbenches, Role Matrix | Vue 3, TypeScript, Element Plus, TailwindCSS |
| **Delivery & SRE** | Zero-Downtime Releases, Automated CI/CD, Containerization, Reverse Proxy | GitHub Actions, Linux, Nginx, Docker, Shell |

---

## 📜 Core Delivery Principles

1. **Evidence First**: Architecture is not subjective; screenshots, build logs, lint checks, CI status, ELF headers, and unit benchmarks are integral parts of the deliverable.
2. **AI with Ironclad Boundaries**: AI models must never bypass business ACLs or invent citations. If proof is absent, emit `found=false` and trigger human handoff.
3. **Full-Stack Convergence**: Mobile UX, native runtime, backend state machines, and AI orchestration are treated as a unified, resilient product pathway.
4. **Instant Value Realization**: Every engagement begins with clear acceptance criteria and measurable ROI.

---

## 📬 Contact & Engagements

* **Personal Site**: [mikehot.cloud](https://mikehot.cloud)
* **Online Resume**: [mikehot.cloud/resume](https://mikehot.cloud/resume/)
* **Direct Email**: [mikehot668@gmail.com](mailto:mikehot668@gmail.com)
* **Location**: Shanghai, China / Remote Global Available
