# 浙江大学超算队章程

## 第一章 总则

 - **第一条** 浙江大学超级计算机竞赛队（简称超算队）是由浙江大学计算机学院于 2014 年成立的学生超算竞赛队伍。通过参与国际、国内等各级别高性能计算大赛，提高学生程序设计、工程优化能力，强化学生创新实践素质，提升人才培养质量。

 - **第二条** 目标
    1. 超算队总目标为在国际大学生超级计算机竞赛（ASC/SC/ISC）中夺冠；
    2. 超算队阶段性目标为在国际大学生超级计算机竞赛（ASC/SC/ISC）、各大高性能优化大赛（CPC/PAC/IPCC）中获得金、银、铜等奖励。

## 第二章 队员选拔
 - **第一条** 超算队队员选拔对象原则上要求为浙江大学在读本科生。

 - **第二条** 超算队通过面试考核的形式选拔优秀学生进入预备队，通过训练、竞赛成绩和项目考核的形式选拔优秀队员进入正式队伍，参加国家级、国际级的竞赛。

## 第三章 训练管理

 - **第一条** 所有超算队队员每周须向队内汇报本周工作，形式为周报或是周会汇报。

 - **第二条** 对于队内布置的训练任务，应当按时、认真完成，并及时给出反馈。

## 第四章 项目管理

### mirrors 项目管理

#### 人员配置与职责
   - 一人作为总负责人
   - 两人作为镜像源维护者，与总负责人一起负责镜像源的日常维护与灾情处置
   - 三个人中一人主要负责硬件，两人主要负责软件
   - 一人运营镜像源的反馈邮箱，并对收到的用户反馈邮件进行处理
   - 一人作为财务人员，管理经费并撰写财务报告
#### 管理规则
   - 每日至少进行一次镜像源同步
   - 每月至少对上游仓库进行检查与评估一次，保持上游仓库可信
   - 若有新增镜像列表的需求，在对版权等风险进行检查之后上报学校，经过许可后再进行第一次维护
   - 每周至少进行服务器硬件维护一次
   - 用户反馈不论能否处理都在一周内进行回复，若用户提出的问题或是需求合理，则需给出预期解决时间并保持后续通告
   - 若服务器需停机维护则至少提前 3 天发布通告

### git server 项目管理

#### 人员配置与职责
  - 总负责人 1 名——负责和上级部门的交流对接，负责内部事务的决策，优先考虑技术人员担任
  - 技术人员 2-3 名——负责新服务的开发，服务器运维，管理硬件的使用
  - 外宣与审核 1 名——对外联系组织交流，发布公告与推文，负责审核 Git 上的公开项目内容
  - 技术候补 3-5 名——招收新人作为技术候补，辅助进行审核，辅助技术人员进行运维工作，接受技术培训，交接技术人员毕业或离开后的工作
  - 财务人员 1 名——负责管理财务的收支，撰写财务报告，管理捐款等专用款项并公开

#### 管理规则
  - 财务规则
    - 接受校内师生与学校上级单位的监督和质询。
    - 相关负责⼈应当根据运营情况和学校相关规定，建⽴独⽴透明的会计、审计制度。财务⼯工作应当完全透明，相关负责⼈有详尽记录财务使⽤用情况并定期公开发表财务报告的义务。
    - 经费主要来源于上级部门的活动经费，维护人员自筹的经费，来自于校内或社会的捐款。
    - 重大活动经费支出需经全体协商，总负责人同意后支出。
    - 捐款需转款专用，公开每一笔捐款的具体去向，存储在指定的公共账户上接受监管。
  - 人事变动
    - 原则上每年组织两次纳新，每位新成员需经至少3位面试官考核通过，纳新过程应当留档记录，记录至少保存3年。
    - 总负责人由内部推举决定。
    - 若成员有重大失误或过错，经内部 2/3 多数决议后，可以对成员进行撤职或开除。
    - 原则上应当维持内部健康的年龄结构，确保长期工作的交接稳定。
  - 技术事项
    - 每日均需有专人排班检视服务器运行状态，建立完善的服务报警机制，出现问题能及时通知到技术人员进行修复。
    - 每月至少一次组织对硬件运行状态的检查，讨论下一步的发展方向。
    - 用户反馈的问题需要在一周内进行处理和答复，若非短期问题则需要给出答复，将问题列入工作日程。
    - 对高热度高访问量的公开内容进行内容审核，防止出现危险敏感内容，接受用户的举报与监督并及时处理。
    - 建立用户使用情况的自动监视报警机制，防止用户恶意使用服务器资源造成公共资源的浪费。
  - 外部事项
    - 定期组织与校内/友校其它技术社团组织的交流，不定期与社会企业交流，不定期举办公开的技术交流讲座。

## 第五章 竞赛管理

### 人员配置与职责

- 一人作为总负责人，即超算队队长
- 优化方向两人负责，机器学习方向一人，运维方向一人
- 各负责人同时承担人才选拔任务
- 原则上优先选择有参赛、科研经验的队员参与国际比赛

### 管理规则

#### 人才选拔
超算队定期从 mirror 和 git 的技术人员中选出技术出众者参与相关竞赛，进入竞赛方向的人员必须经过单独面试。
#### 内部培训
选入参与竞赛的队员需按时参与内训，并每周提交周报对学习进步进行汇报。
#### 内部权益
  1. 选入参与竞赛的队员拥有使用队内超算机器的资格。
  2. 每年竞赛最突出的三名队员享有竞赛保研资格。
#### 考核机制
  1. 对于长期缺席内训或不进行汇报的队员，将失去参与竞赛资格
  2. 在竞赛中长期划水拖累队友的队员，失去参赛资格
  3. 各负责人应每季度对参赛队员进行考核，发现上述两点的队员应及时剔除，并免去相关权益。

## 第六章 奖惩管理
### 奖励方案
1. 对于每年积极参加比赛、并取得优异成绩的队员，可以参与保研资格的分配。
2. 超算队保研资格需要在每年学科竞赛保研申请期间由队员自己主动提出申请，交由指导老师审核，根据队内贡献和获奖情况由队内讨论得出名单，逾期不候。
3. 超算队队内正式成员参赛所得奖金由队内讨论后统一按照队员贡献进行分配。
4. 超算队对外学生在超算队带领下参加比赛获奖所得校内外奖金在进行分配时，需考虑超算队指导老师及超算队机器维护费用等情况，经讨论后进行分配。
5. 超算队外出参加比赛所得的校内外奖金在分配时，观摩队员可以按照贡献以一定比例参与奖金分配，用于鼓励协助主力队员进行比赛的同学。

### 惩罚方案
1. 集训队队员要兼顾日常训练和专业课程学习，不能以日常训练为借口旷课、挂科等。集训通常安排在周末和寒暑假，一般不与课程冲突。如果遇到外出参赛和参加集训的时间与上课或者考试时间冲突，必须向相关任课教师说明情况，并向学院申请批准请假或者考试缓考。旷课、挂科情况严重的队员，将视情况做出相应惩罚处理。
2. 对于平时训练或是比赛中消极怠工、拖累队友的队员，直接丧失超算队竞赛保研资格。

## 第七章 年度工作计划

1. 积极参与各类超算竞赛。
2. 维护好浙江大学镜像站及校内 git 服务。
3. 组织相关技术交流活动，增加校内影响力。

## 第八章 杂项

### 集群使用

1. 集群使用原则上优先供给竞赛任务和日常训练；当竞赛和队员训练有需求时，其他无关的计算任务应当主动停止。
2. 参加竞赛的队员可以在不通知使用者的情况下关闭无关的计算任务，腾出计算资源。
3. 队员应当使用自己的账号登录集群进行操作，严禁外借自己的账号，如有发现吊销账号。
4. 严禁使用集群进行炼丹等无意义的计算行为，或是直接或间接贩卖集群算力，如有发现吊销账号。

### 书籍借阅

1. 512 书架上的书籍可供队员借用学习，借用和归还时需在书架上的本子上登记。
2. 如有需求可以使用经费购置书籍，审批后予以报销。
