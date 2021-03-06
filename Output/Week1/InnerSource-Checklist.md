# 公司实施内源的检查列表
*翻译自《Understanding the InnerSource Checklist》* 
1. 准备
  - 个人
    - 你认为内源对你的公司来说是一个可行的策略，还是仅仅出于意识形态上的承诺和理想主义？
    - 你是否明白成功实施内源所需要作出的改变？
    - 你是否擅长向其他人展现自己的想法、聆听他人的顾虑、并且能够不带偏见地找出共同点？
  - 项目
    - 这个项目对于公司而言重要吗？它有可能在战略变化中幸存下来吗？
    - 适用性
      - 除原来团队外，外部的开发人员对这个项目有兴趣吗？
        - 项目目前或者将来可能被公司的其他团队依赖或者使用吗？
        - 项目是否会从外来者以原始团队无法预料的方式进行扩展中获益？
      - 项目是否可以从其他团队贡献的缺陷修复以及重构工作中获益？
      - 外部开发者是否可以贡献有用的代码和建议呢？
      - 外部开发者会愿意加入项目做贡献吗？
    - 代码成熟度
      - 项目模块化程度是否足以使代码变得容易和安全吗？
      - 代码的文档健全吗？
    - 现有过程
      - 可以频发发布吗？
      - 是否有持续测试和集成机制？
      - 是否所有的代码都存储在使得分支请求和集成变得容易的版本控制库中，比如GitHub？
  - 团队
    - 团队成员准备好面对实施内源带来的挑战了吗？
      - 接受来自外部开发者的代码变更
      - 对外部开发者提供的不太完美的代码负责
      - 让外部开发人员看到自己不完美的代码
      - 不得不与外部开发人员进行关于接受和拒绝他们贡献的沟通
      - 指导或者学习如何指导新人
    - 团队成员是否清楚推行一个内源项目的需求？（成员如果有开源项目的开发经验的话会好很多）
      - 为外来贡献者创建和维护文档
      - 参与论坛和耐心回答问题的心理准备
      - 使用论坛进行讨论，而不是走廊上的对话。因为论坛提供了每个人都能看到的历史记录。（可选地，在现场会议期间使用抄写员做笔记，保证所有决定和解释都记录在案）
      - 愿意审核外部开发
      - 维护缺陷追踪
      - 轮流承担Trusted Commiter的职责
    - 你们有选举出Trusted Commiter吗？
      - 他们是否清楚自身肩负的职责？
        - 编辑并维护CONTRIBUTING.md文件
        - 审核提交的代码变更（Pull request）
        - 指导外来开发人员
        - 合并代码提交
        - 作为主力参与重构和模块化工作
        - 参与讨论并积极回答问题
        - 发布公告
        - 密切关注并发起协作
      - 他们知道担任Trusted Commiter带来的潜在回报吗？
        - 对代码产生深入的理解
        - 提高团队代码的质量
        - 通过更好的集成提高组织内代码的质量
        - 作为一名开发人员，通过看到许多引入的代码示例来学习和成长
        - 了解如何更好地重构和模块化代码以鼓励外部贡献
        - 通过指导和与外部进行协商，培养人际交往和领导能力
        - 通过指导和与客人贡献者进行协商，培养人际交往和领导能力
      - 他们是否有足够的时间精力去做以往工作要求中没有提到的事情？
    - 团队成员的工作日程中是否为这些新职责留出了时间？
    - 团队成员是否接受过处理这些职责的培训？
    - 有没有一种机制可以让组织中的任何人都可以跟踪和搜索？（例如：Slack、email）
    - 是否有一个记录下来的讨论机制，以便所有外来贡献者的问题和内部团队决策都可以被人搜索？（例：Slack，在线论坛）
  - 公司
    - CxO级管理人员
      - 管理人员是否了解推行内源项目的目的和价值？
        - 在整个组织中传播部门知识的价值
        - 让团队消除他们自己的外部障碍和瓶颈的价值
        - 一个联系更加紧密的组织的价值
        - 拥有对代码库的许多分支有更深入理解的高级团队成员的价值
        - 内源鼓励基本的良好开发实践，帮助开发和传播更好的代码和开发实践
        - 内源提高单个开发人员的学习和开发技能
      - 他们是否愿意支持灵活的工作要求和跨部门贡献的时间？
      - 他们能接受实验失败和重新定位吗？
      - 他们是否愿意支持不需要管理的职业发展道路？
      - 执行团队是否支持内源的主动性？
      - 公司目标和关键绩效指标是否明确规定并共享？
      - 公司基于内源的愿景和使命是否相关、实时、清晰、受到开发人员的尊重和遵循？
    - 人力资源
      - 是否有基于内源价值的奖励和晋升标准？
        - 对为其他部门的项目做出贡献的人的奖励
        - 对处理其他部门贡献的开发人员的奖励
      - 需要一条基于社区角色、与管理层无关的晋升途径
    - 组织机构设置
      - 中央协调小组
        - 团队成立了吗？
        - 它是否准备好与有兴趣推行内源的项目进行沟通？它能应用这个检查表中的标准来确保项目和团队准备好了吗？
        - 项目如何成为内源项目？
      - 员工有时间为外部项目做贡献吗？
      - 员工是否有资源来衡量和展示团队的得失？
      - 工作人员能否根据他们的专业知识和动机选择从事哪些项目？
      - 有没有一种精英哲学可以不问出处的欣赏好的贡献？
    - 开发者
      - 公司的开发人员是否了解他们可以为内源项目做出贡献？
      - 他们了解为其他项目做贡献的价值吗？
        - 移除瓶颈
        - 构建与其他工具的集成
        - 了解其他团队如何构建代码并从中学习
      - 他们是否了解为其他项目做贡献的流程？
        - 加入讨论
        - 阅读贡献要求
        - 阅读并向Help Wanted文件做贡献
        - 关注公告
      - 他们知道如何使用工具吗？
        - 版本控制
        - 程序设计语言
        - 测试开发
      - 他们知道如何支持他们的团队在内源中的角色吗？
        - 他们能有效地参与论坛讨论吗？
          - 回答贡献者的问题
          - 以清晰的方式描述选择背后的原因
          - 给予建设性的反馈
        - 他们能参加关于他们代码评审的对话吗？
      - 他们是否被允许为部门外的项目贡献？
        - 他们是否了解如何获得产品所有者和经理的支持？
2. 仓库
  - 是否设置了辅助资源，例如：
    - 文档
    - 讨论论坛
    - 缺陷追踪系统
    - Wiki
  - 以下文档是否到位
    — README.md
      - 项目名称
      - 此项目的任何早期名称和代号
      - 项目描述
      - 团队领导和PM/PMO联系方式
      - 搜索关键字
        - 满足通过名字找到这个项目
        - 满足通过它的功能找到这个项目
      - 如何注册公告列表
      - 论坛链接
      - 其他相关仓库的链接（例如：JIRA、Rally、Confluence）
    — CONTRIBUTING.md
      - 必须项
        - 目录
        - TCs的姓名和联系方式
        - TCs的时间表
      - 可选项
        - 社区指南
        - 代码公约
        - 测试公约
        - 分支公约
        - Commit Message公约
        - 创建好的Pull Request的步骤
        - 如何提交功能请求
        - 如何提交缺陷报告
        - 如何提交安全问题报告
        - 如何编写文档
        - 依赖关系
        - 构建过程计划
        - 冲刺计划
        - 路线图
        - 有用的链接、信息和文档
        - 代码库对贡献关闭的时间
    - HELPWANTED.md
      - 最初可以为空
      - 可以链接到发布请求和响应的论坛
      - 可以包含请求和响应的列表
    - GETTINGSTARTED.md
      - 任何贡献者需要用来启动和运行应用程序才能开始编码的东西
      - 可以由实习生填写，或者在一些贡献者开始工作后，根据对他们开始工作有帮助的反馈意见填写
  - 谁审阅代码库中的文档？      
3. 工具
  - 版本控制
  - 持续集成
  - 测试
4. 后备支撑
  - 冲刺
  - 代码马拉松，特别是工具
  - 教育
  - 测试
  - 游戏化
  - 报告
    - 最近的Pull requests
      - 数量
      - 大小（按代码行）
      - 类型
      - Pull requests提交者
    - 基本量度
    - 持续跟踪
      - 资源
        - 成本
      - 时间
    - 度量结果给谁看？向社区展示？
  - 缺陷修复
5. 产品所有者

