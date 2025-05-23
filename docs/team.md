# 项目团队


| 团队   | 角色               | 姓名     | 职责                           | 备注       |
|--------|--------------------|----------|--------------------------------|------------|
| 产品   | Leader (Doc Manager)| 黄杨     | 负责团队管理和产品把控        | CEO、CPO   |
| 产品   | Product Developer   | 姚之远   | 负责产品设计和功能开发         |       |
| 全栈   | Full Stack Developer | 徐平 | 负责前后端开发和测试           | CTO        |
| 前端   | Proto & Designer    | 苏宇翔   | 原型设计和用户界面设计         |            |
| 前端   | Frontend Developer  | 徐嘉雯   | 前端开发和用户交互             |            |
| 后端  | API Manager         | 林凡钧   | API设计和管理                 |            |
| 后端   | Leader (Doc Manager)| 刘佳凡   | 后端架构和文档管理             |            |
| 测试   | Server Manager      | 翟怡丹   | 测试环境搭建和管理             |         |
| 测试   | Issue Manager       | 王博海   | 测试用例编写和管理             |            |
| 其他   | CKO                 | 董宜涛   | 管理团队知识、过程记录等       |  CKO          |



# 项目仓库目录结构

    MSE-AI-T4/
    ├── backend/               # 后端代码，主要由林凡钧、刘佳凡、徐平负责维护
    │   ├── app.py             # 主应用文件（如 Flask/Django/FastAPI）
    │   ├── requirements.txt   # Python依赖包列表
    │   ├── models/            # 存放模型相关的代码
    │   ├── services/          # 服务层逻辑（如与LLM交互）
    │   └── tests/             # 后端单元测试，主要由翟怡丹、王博海负责维护
    ├── frontend/              # 前端代码，主要由苏宇翔、徐嘉雯、徐平负责维护
    │   ├── public/            # 静态资源
    │   ├── src/               # React/Vue/Angular等前端框架代码
    │   │   ├── components/    # UI组件
    │   │   ├── pages/         # 页面组件
    │   │   └── App.js         # 主入口文件
    │   ├── package.json       # 前端依赖包列表
    │   └── README.md          # 前端说明文档
    ├── docs/                  # 文档目录，主要由黄杨、董宜涛、姚之远负责维护
    │   ├── api-docs.md        # API 文档
    │   ├── architecture.md    # 系统架构设计
    │   ├── user-guide.md      # 用户指南
    │   └── dev-guide.md       # 开发者指南
    ├── data/                  # 数据相关
    │   ├── raw/               # 原始数据集
    │   ├── processed/         # 处理后的数据
    │   └── README.md          # 数据说明
    ├── .gitignore             # 忽略文件规则
    ├── README.md              # 项目主说明文档
    └── LICENSE                # 开源许可证


# 项目主计划

#### 第1-2周（3月25日 - 4月7日）：项目初始化与需求分析
- **目标**：
    - 完成项目仓库的初始化设置。
    - 明确产品功能需求和技术选型。
    - 开始设计系统架构和数据库模型。
- **主要责任人**：
  - 黄杨、姚之远：负责产品需求的收集与确认。
  - 刘佳凡：负责后端架构设计。
  - 苏宇翔：负责UI/UX设计初稿。
  - 董宜涛：负责记录会议纪要及知识管理。
#### 第3-4周（4月8日 - 4月21日）：原型设计与初步开发
- **目标**：
  - 完成前端原型设计和用户界面设计。
  - 启动前后端基础框架搭建。
  - 编写并审核API文档。
- **主要责任人**：
  - 苏宇翔、徐嘉雯：完成前端原型设计。
  - 徐平：开始全栈开发工作。
  - 林凡钧：编写API规范并进行初步接口开发。
  - 翟怡丹：协助搭建测试环境。
#### 第5-6周（4月22日 - 5月5日）：核心功能开发
- 目标：
  - 实现核心业务逻辑和服务层交互。
  - 完成主要页面的功能开发。
  - 开始集成测试。
- 主要责任人：
  - 徐平、苏宇翔、徐嘉雯：继续前端开发。
  - 林凡钧、刘佳凡：推进后端服务开发。
  - 王博海：编写测试用例并执行单元测试。
  - 翟怡丹：维护测试环境。
#### 第7-8周（5月6日 - 5月19日）：功能完善与优化
- 目标：
  - 进行功能补充和完善。
  - 对现有功能进行性能优化。
  - 准备部署到预生产环境。
- 主要责任人：
  - 全体成员：根据反馈进行功能调整。
  - 徐平：优化前后端交互效率。
  - 翟怡丹、王博海：进行回归测试。
#### 第9-10周（5月20日 - 6月2日）：测试与修复
- 目标：
  - 执行全面的系统测试。
  - 解决所有发现的问题和漏洞。
  - 更新文档以反映最新状态。
- 主要责任人：
  - 翟怡丹、王博海：主导测试活动。
  - 全体成员：参与问题修复。
#### 第11-12周（6月3日 - 6月16日）：最终调整与上线准备
- 目标：
  - 最终审查和调整。
  - 准备上线发布材料。
  - 部署至生产环境。
- 主要责任人：
  - 黄杨：协调上线事宜。
  - 徐平：确保技术方案的可行性。
  - 刘佳凡：监督部署过程。

# 团队协同工作制度

- 每周末召开一次会议，由黄杨主持，全体成员参加。会上每位成员汇报本周进展和次周计划，讨论遇到的问题和解决方案。
- 在微信群中，定期分享项目进展和技术讨论。
- 使用GitHub Issues跟踪任务和Bug，确保所有工作都有迹可循，便于管理和回顾