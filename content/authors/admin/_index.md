---
# Display name
title: 刘琛琛

# Name pronunciation (optional)
name_pronunciation: Chen chen Liu

# Full name (for SEO)
first_name: Chen chen
last_name: Liu

# Pronouns (optional)
#pronouns: he/him

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Third-Year Master’s Student in Knowledge Graph 

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: 浙江工商大学
    url: https://www.zjgsu.edu.cn/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: '23020100082@pop.zjgsu.edu.cn'
    label: E-mail Me
  - icon: custom/bilibili
    url: https://space.bilibili.com/85472209
  - icon: brands/github
    url: https://github.com/liuchenlili
  - icon: brands/linkedin
    url: https://www.linkedin.com/


education:
  - area: 硕士
    institution: 浙江工商大学
    date_start: 2023-09-01
    date_end: 2026-06-30
    gpa: 3.55/5.0
    summary: |
      研究方向：知识图谱与人工智能

      主修课程：
      - 软件理论与工程
      - 数据科学与工程
      - 计算理论
      - 高级计算机体系结构
      - 高级人工智能
      - 嵌入式系统工程

  - area: 本科
    institution: 河南理工大学
    date_start: 2019-09-01
    date_end: 2023-06-30
    gpa: 3.05/4.0
    summary: |
      主修课程：
      - 计算机网络
      - 计算机组成原理
      - 深度学习
      - 数据结构
      - 操作系统
      - 软件工程
      - 编译原理
      - 模拟与数字电路


work:
  - position: 后端开发
    company_name: 麦麦票
    date_start: 2024-09-01
    date_end: 2024-12-31
    summary: |
      项目简介：基于 SpringBoot 构建的赛事演出门票购票平台，实现短信登录注册、票务管理、演出查询、门票抢购、热度榜单、社交功能等模块。
      技术栈：SpringBoot, MyBatis-Plus, Redis, MySQL, Nginx, WebSocket, Redisson, RabbitMQ
      主要工作与技术亮点：
      - 票务秒杀优化：使用 Redisson 分布式锁确保资源互斥，结合 Lua 脚本实现原子性库存扣减及流水记录，防止超卖，通过消息队列控制异步处理削峰填谷，支持高并发抢票场景。
      - 订单处理：通过乐观锁机制保持订单与库存场景的数据一致性。
      - 多级缓存：使用本地缓存和 Redis 缓存搭建二级缓存架构，降低数据库查询压力。
      - 缓存穿透：设置缓存空值和布隆过滤器机制，有效解决 Key 问题。
      - 缓存延迟：使用延迟删除方案解决缓存与数据库同步问题，结合动态 TTL 防止缓存雪崩。
      - 异步处理：利用 RabbitMQ 进行异步消息处理和订单超时自动取消逻辑。
      - 流量限流：使用 Redis + AOP 实现滑动窗口限流策略，支持用户多维度防止系统过载。

  - position: 后端开发
    company_name: AI智能知识库系统
    date_start: 2024-03-01
    date_end: 2024-08-31
    summary: |
      项目简介：基于大语言模型 (LLM) 的 RAG 知识库系统，整合外部知识源增强生成结果的可信度与准确性。基于 MCP 通过 AI 工作流指令调度 MCP 任务，自动化实现数据采集、存储及多平台内容发布。
      核心技术：Spring Boot, Spring AI, PostgreSQL, Redis, Docker, Ollama
      主要工作与技术亮点：
      - 文档向量库构建：利用 Spring AI 框架，采用 Tiktoken 进行文档分块，结合 TokenTextSplitter 分割文本并添加元数据，最终持久化至 PostgreSQL 向量库，实现知识的高效管理与语义检索。
      - 代码知识库集成：集成 JGit 实现 Git 仓库自动化拉取与解析，结合向量数据库打造智能代码知识库，支持精准智能检索与问答。
      - 工具调用框架：基于 @Tool 注解构建扩展工具框架，实现 LLM 与多源数据交互能力，并结合 ToolCallbackProvider 接口动态注册应答逻辑组件，将 AI 工具输入 Spring 上下文，提升开发效率。
      - 自动化发帖服务：设计并实现对接 CSDN、微信公众号等平台的发帖 MCP 服务，构建端到端的 AI 内容发布工作流。


# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: Java
        description: '熟悉 JVM 运行机制与内存模型，了解类加载与垃圾回收机制。'
        percent: 85
        icon: devicon/java
      - name: Spring Boot
        description: '熟悉分布式与微服务开发，掌握 Seata、Nginx、Nacos、Sentinel 等工具。'
        percent: 85
        icon: devicon/spring
      - name: MySQL
        description: '熟悉 MySQL 与 Oracle，了解底层数据结构、缓冲池、索引、事务与日志机制。'
        percent: 90
        icon: devicon/mysql
      - name: Redis
        description: '熟悉 Redis 分布式事务及缓存穿透、缓存雪崩等问题的解决方案。'
        percent: 85
        icon: devicon/redis
      - name: RabbitMQ
        description: '熟悉消息模型、消息持久化与 ACK 确认机制，掌握异步消息处理流程。'
        percent: 80
        icon: devicon/rabbitmq
      - name: Docker
        description: '熟悉容器化部署流程，掌握 Linux 常用命令及服务环境搭建。'
        percent: 80
        icon: devicon/docker
      - name: Git & Maven
        description: '熟练使用 Git 进行分支管理与协作开发，掌握 Maven 构建与依赖管理。'
        percent: 85
        icon: devicon/git
      - name: PyTorch
        description: '熟悉深度学习框架及 CV/NLP 领域常见算法。'
        percent: 70
        icon: devicon/pytorch
      - name: AI Tools
        description: '熟练使用 Cursor、Dify 等工具，了解 RAG、Agent 基本原理与应用。'
        percent: 75
        icon: devicon/openai

  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Hiking
        description: '热爱户外徒步与自然探索。'
        percent: 60
        icon: person-simple-walk
      - name: Cats
        description: '喜欢与动物相处。'
        percent: 100
        icon: cat
      - name: Photography
        description: '热衷于记录风景与人文摄影，关注光影与构图。'
        percent: 80
        icon: camera

languages:
  - name: Java
    percent: 90
  - name: Python
    percent: 85
  - name: C++
    percent: 70
  - name: PyTorch
    percent: 75


# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.

awards:
  - title: Huawei Cup – 21st China Postgraduate Mathematical Contest in Modeling, National Second Prize
    date: '2024-11-01'
    awarder: China Postgraduate Mathematical Modeling Competition Committee
    icon: mdi/math-compass
    summary: |
      Awarded the National Second Prize in the 21st “Huawei Cup” China Postgraduate Mathematical Contest in Modeling. 
      Our team’s research focused on highway video analysis for intelligent traffic management — determining whether emergency lanes should be activated based on real-time conditions. 
      I was primarily responsible for programming, data preprocessing, and model development, implementing machine learning algorithms to classify traffic flow patterns. 
      Through iterative optimization and close collaboration with teammates, we successfully built an efficient decision-support model for emergency lane activation.

  - title: PAT Advanced Level Certification
    date: '2022-08-01'
    awarder: Zhejiang University Programming Ability Test Platform
    icon: mdi/certificate
    summary: |
      Passed the PAT Advanced Level Examination (Summer 2022), demonstrating strong abilities in algorithm design, data structure implementation, and computational complexity optimization.

  - title: Kaggle Competition — MAP Charting Student Math Misunderstandings, Bronze Medal
    url: https://www.kaggle.com/competitions/charting-student-math-misunderstandings
    date: '2023-05-01'
    awarder: Kaggle
    icon: brands/kaggle
    summary: |
      Won a Bronze Medal in the Kaggle competition “MAP: Charting Student Math Misunderstandings.” 
      The project focused on modeling and predicting student misconceptions in mathematics. 
      Utilized deep learning and knowledge graph fusion techniques to enhance model performance and interpretability.

  - title: Multi-Feature Fusion Strategies for Enhancing Knowledge Graph Embedding
    date: '2025-01-01'
    awarder: IEEE Big Data 2025 (CCF-C)
    icon: brands/ieee
    summary: |
      First-author paper accepted by IEEE Big Data 2025, focusing on knowledge graph embedding and multi-feature fusion strategies. 
      Proposed a multimodal feature integration mechanism to improve embedding quality and representation learning. 


---

我是浙江工商大学计算机技术专业硕士研究生，研究方向为知识图谱与人工智能。本科毕业于河南理工大学计算机科学与技术专业，具备扎实的算法与工程实现能力。
在科研方面，关注大语言模型（LLM）与知识图谱融合技术，探索多特征融合在知识表示与语义检索中的应用，第一作者论文《Multi-Feature Fusion Strategies for Enhancing Knowledge Graph Embedding》已被 IEEE Big Data 2025 录用。  
在工程实践中，熟悉 Spring Boot、Redis、RabbitMQ、Docker 等后端技术体系，具备分布式与微服务项目的开发经验，独立设计并实现了基于 LLM 的智能知识库系统。
我热衷于将人工智能与行业应用结合，致力于构建高效、可信的数据智能系统。