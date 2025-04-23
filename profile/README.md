# the Learning&Training Hub of OS Kernel

## [2025春夏季开源操作系统训练营：2025.3.30~2025.6.22](https://github.com/LearningOS/rust-based-os-comp2025/blob/main/2025-spring-summary.md)

- 2025.3.30：[2025年春夏季开源操作系统训练营启动仪式回放](https://meeting.tencent.com/crm/NbwaVE759c)
- 2025.3.19: 2025年春夏季开源操作系统训练营发布[**重要信息**](https://github.com/LearningOS/rust-based-os-comp2025/blob/main/2025-spring-summary.md)，请仔细阅读。
- 2025.3.15: 2025年春夏季开源操作系统训练营准备中。

## [以往信息](./log.md)

## 自学自练&定期交流

### 榜样
- [浙江大学本科生徐文浩2020开源操作系统训练营的过程记录](https://github.com/LearningOS/record)
- [湖南大学本科生肖政杭的自学ucore for x86的过程记录](https://kiprey.github.io/tags/uCore/)

### Self Learning
- **Easy --> Normal  --> Hard**
  - [**Rust Programming** --> **RISC-V & OS** --> **Advanced OS proj&researchs**](https://github.com/LearningOS/rust-based-os-comp2025/blob/main/relatedinfo.md)
 
### Self Training
**入门 --> 进阶 --> 提升 --> 实战**

#### 入门：Rust Language
**（第一阶段）目标：了解并掌握基于Rust语言的编程**

##### 学习：相关课程与资源
- [opencamp课程-基础阶段 - Rust编程](https://opencamp.cn/os2edu/camp/2025spring/stage/1)
- [Easy ：stage1: Rust-lang & RISC-V arch training](https://github.com/LearningOS/rust-based-os-comp2025/blob/main/2025-spring-scheduling-1.md)
##### 任务：完成实验练习
- [创建rustling练习教室](https://classroom.github.com/a/S8vP0lDr) 点击后按提示可以建立自己的rustling实验专用仓库，并完成练习
##### 成绩：排行榜
- [**rustling练习排行榜**](https://opencamp.cn/os2edu/camp/2025spring/stage/1?tab=rank) 可以查看自己的rusting实验的排名情况

#### 进阶：Rust base Simple OS Kernel
**（第二阶段）目标：了解并掌握如何设计实现一个简单的操作系统内核**

##### 学习：相关课程与资源：
rCore Tutorial来自清华大学计算机系本科操作系统课实验
- [opencamp课程-专业阶段 - OS设计实现](https://opencamp.cn/os2edu/camp/2025spring/stage/2)
- [Normal ：stage2: Rust-based OS kernel Training](https://github.com/LearningOS/rust-based-os-comp2025/blob/main/2025-spring-scheduling-2.md)
##### 任务：完成实验练习
- [创建 rCore Tutorial练习教室](https://classroom.github.com/a/pTgmDIG6) 点击后按提示可以建立自己的rCore Tutorial实验专用仓库，并完成实验
##### 成绩：排行榜
- [**rCore Tutorial练习排行榜**](https://opencamp.cn/os2edu/camp/2025spring/stage/2?tab=rank) 可以查看自己的rCore Tutorial实验的排名情况


#### 提升：Foundation of Component OS Kernel Design & Implementation
**（第三阶段）目标：打好设计实现组件化OS的基础，理解如何基于组件来组合出多种构型的操作系统内核**

##### 学习：相关课程与资源
- [opencamp课程-项目基础阶段 - 组件化操作系统的视频](https://opencamp.cn/os2edu/camp/2025spring/stage/3?tab=video)
  - 学习视频，并重现[视频中的tutorial例子](https://github.com/arceos-org/oscamp/tree/main/arceos/tour) 
- [Normal -- Hard  ：Design OS Components -- OS Kernel Framework -- Apps](https://github.com/rcore-os/arceos)
  - [arceos tutorial文档一](https://oslearning365.github.io/arceos-tutorial-book/)
  - [arceos tutorial文档二](https://oslearning365.github.io/arceos-tutorial-book/)
  - 注:这两个文档有进一步更新计划，欢迎想一起写文档的学员直接微信联系助教或导师欢迎合作者联系我们，我们一起共建训练营。

##### 任务：完成实验练习
- 根据[opencamp课程-项目基础阶段 - 组件化操作系统的视频](https://opencamp.cn/os2edu/camp/2025spring/stage/3?tab=video)中每节课最后的练习说明，完成[课程练习](https://github.com/arceos-org/oscamp/tree/main/arceos/exercises)。
- [**创建"实现组件化 unikernel/monolithickernel/Hypervisor"练习教室**](https://classroom.github.com/a/BaLc7UDP) 点击后按提示可以建立自己的["实现组件化OS/Hypervisor"](https://github.com/arceos-org/oscamp/)实验专用仓库
  - ["实现组件化unikernel/monolithickernel//Hypervisor"练习教室模板](https://github.com/LearningOS/arceos-classroom-2025s-arceos-2025s-oscamp-stage3) 
##### 成绩：排行榜
- [**"实现组件化OS/Hypervisor"练习题排行榜**](https://opencamp.cn/os2edu/camp/2025spring/stage/3?tab=rank)这个是课后练习的排行榜，一共6题，共600分，可以查看自己的的排名情况。
- [**"实现组件化OS/Hypervisor"挑战题排行榜**](https://opencamp.cn/os2edu/camp/2025spring/stage/5?tab=rank)这个是挑战题目的排行榜，满分设置的是373分，可以查看自己的的排名情况。 
- 注：感谢徐堃元、殷金钰和周屿涵建立的三阶段排行榜！

**第四阶段：实战1~3**  
#### 实战1：OS Kernel Design&Implementation
**（第四阶段）目标：用组件化开发方法，基于单体内核组件扩展出宏内核组件，设计并实现直接支持Linux应用的轻量组件化宏内核**


实战挑战：类似全国大学生操作系统比赛内核赛道实战，构造支持linux syscalls的OS kernel on RV64/LA64/AARCH64/X64，
##### 学习建议
1. 先完成[Rust base Simple OS Kernel](#进阶rust-base-simple-os-kernel)和[Foundation of Component OS Kernel Design & Implementation](#提升foundation-of-component-os-kernel-design--implementation)的学习
2. 小步快跑，学习[指导书](https://azure-stars.github.io/Starry-Tutorial-Book/)，观察[主线进展](https://github.com/oscomp/starry-next/)和[挑战者的进步](https://learningos.cn/oscomptest-grading)，查找[资源](https://github.com/oscomp/os-competition-info/blob/main/ref-info.md),有问题就发[issues](https://github.com/oscomp/starry-next/issues),有想法就发[discussion](https://github.com/oscomp/starry-next/discussions)，鼓励贡献并[提交PR](https://github.com/oscomp/starry-next/pulls)
3. 所有的开发、合作、交流基于下面列出的建立在github上的 classroom，CI, issues, PR, discussions
##### 参考资源
- [opencamp课程-项目一：基于ArceOS组件的宏内核- Starry-Next](https://opencamp.cn/os2edu/camp/2025spring/stage/5)
- [Hard ：Design OS Kernel to run linux apps](https://github.com/LearningOS/learningos-classroom-oscomp) 2025年开源操作系统训练营 oskernel训练仓库模板
- [Starry-Next实验指导书](https://azure-stars.github.io/Starry-Tutorial-Book/) 欢迎提交PR，一起来写

##### 任务：完成实验练习
**设计实现支持Linux App的宏内核**
- [四阶段实战一具体小任务列表](https://github.com/orgs/rcore-os/discussions/15)

**一个具体任务的参考步骤：扩展Linux Syscall**

1. [创建OS kernel Comp练习教室](https://classroom.github.com/a/END-WGn8) 点击后按提示可以建立自己的OS kernel Comp实验专用仓库
1. 把[Starry-next](https://github.com/oscomp/starry-next)作为基线宏内核参考，并阅读[starry-next编程指导书(撰写中)](https://azure-stars.github.io/Starry-Tutorial-Book/)
1. 进一步分析[支持Linux App宏内核的编程排行榜](https://learningos.cn/oscomptest-grading)中有成绩的repo项目，学习他们是如何逐步实现对Linux Syscalls的支持，并进一步通过测试用例的。注:上榜的宏内核不仅仅是Starry Next，还有ByteOS等
1. 对自己的OS kernel Comp实验专用仓库进行编程，逐步实现对各种Linux Syscall的支持。有问题就发[issues](https://github.com/oscomp/starry-next/issues)，并可在四阶段项目一群中交流。在自己的的OS kernel Comp实验专用仓库中撰写周报告，总结自己如何逐步提升的。
1. 争取登顶[支持Linux App宏内核的编程排行榜](https://learningos.cn/oscomptest-grading)
   
##### 成绩：排行榜
- [**OS kernel Comp练习排行榜**](https://learningos.cn/oscomptest-grading) 可以查看自己的OS kernel Comp实验的排名情况
   1. 测试逻辑：每测例1分，同时通过四种架构测试才能得到该测例的分数
   1. 排名逻辑：按总分排名，总分排名相同则按git commit的push时间排名
   1. Linux测试用例来自[全国大学生OS比赛内核赛道的测例](https://github.com/oscomp/testsuits-for-oskernel/tree/2025_multiarch)
- 注：感谢黄熙涵建立的宏内核排行榜！

##### 交流与贡献
- [给Starry-Next宏内核提问题](https://github.com/oscomp/starry-next/issues) 关于Starry-Next的bug信息等
- [给Starry-Next宏内核贡献PR](https://github.com/oscomp/starry-next/pulls) 关于Starry-Next的各种改进/修复bug的提交
- [Starry-Next宏内核讨论](https://github.com/oscomp/starry-next/discussions) 关于周报告、想法等
- [全国大学生OS比赛内核实现赛道相关的资源信息](https://github.com/oscomp/os-competition-info/blob/main/ref-info.md) 相关硬件手册，驱动组件，文件系统组件，网络协议栈组件，获奖操作系统，操作系统参考例子等。
  
#### 实战2：Hypervisor Design & Implementation
**（第四阶段）目标：用组件化开发方法，基于单体内核组件扩展出系统虚拟化组件，设计并实现直接支持运行Linux和其他OS内核的轻量组件化Hypervisor**

实战挑战：基于RV64/LA64/AARCH64/X64的硬件辅助虚拟化，设计轻量组件化的Hypervisor

##### 参考资源
- [opencamp课程-项目二：基于ArceOS组件的Hypervisor- AxVisor](https://opencamp.cn/os2edu/camp/2025spring/stage/6)
- [Normal -- Hard  ：Design Hypervisor小例子](https://github.com/LearningOS/RVM-Tutorial)
  - [RVM-Tutorial 文档](https://github.com/equation314/RVM-Tutorial/wiki)

##### 任务：完成实验练习
**设计实现组件化Hypervisor**
- [四阶段实战二具体小任务列表](https://github.com/orgs/rcore-os/discussions/13)


#### 实战3：OS kernel/driver based on the asynchronous mechanism of coroutines
**（第四阶段）目标：基于 Rust 语言的异步机制 future 对设备驱动和调度器等内核模块进行异步改造核心问题**

##### 参考资源
- [opencamp课程-项目三：基于协程异步机制的操作系统/驱动](https://opencamp.cn/os2edu/camp/2025spring/stage/7)
- 基础阶段：学习相关博客
  - [200行实现绿色线程](https://zjp-cn.github.io/os-notes/green-thread.html)
  - [与协程相关的博客](https://without.boats/tags/async/)
- 进阶阶段：阅读 tokio 源码，形成文档
  - 参考资料：[tokio中文](https://tokio-zh.github.io/document/)
- [嵌入式异步框架embassy中文文档](https://lighklife.github.io/embassy-cn/) 
- [2024春夏季OS训练营实习：embassy preempt开发总结文档](https://kmsorsms.github.io/embassy_preempt/)
- [2024秋冬季OS训练营实习总结：异步协程相关1](https://systemxlabs.github.io/blog/green-threads-in-200-lines-of-rust/)
- [2024秋冬季OS训练营实习总结：异步协程相关2](https://github.com/wahoooooooo/os_blog)
##### 任务：完成实验练习
**设计实现异步协程相关机制和内核相关组件**
- [四阶段实战三具体小任务列表](https://github.com/orgs/rcore-os/discussions/36)

**注1：有感兴趣改进各阶段的排行榜的学员，请在直接微信联系助教或导师，我们一起共建训练营。**
  
**注2：如果对（Option）训练内容或定制培训内容感兴趣，请联系LearningOS开源社区负责人李明老师（微信id：limingth）。**

**注3：如果想继续实习/训练的学生和工程师，请在完成四阶段OS实习后，请与助教和老师联系。这些项目和其它OS相关项目属于有一定创新性的题目，得到了国家实验室、国家创新中心、头部企业和高校研究生导师的直接支持，在就业和学业发展上有新的挑战和机会。**

## 开展新的探索
- [开源实验小项目招新](https://github.com/orgs/rcore-os/discussions/categories/ideas)，可作为本科或研究生毕设课题，欢迎报名并参加！

## 相关开源社区
- [内核组件汇聚中心](https://github.com/kern-crates) 汇聚了各种各样的内核组件，并进行分析、测试和管理
- [ArceOS开源社区](https://github.com/arceos-org/arceos) 探索多构型内核组件化设计
- [唐图(rCoreOS)开源社区](https://github.com/rcore-os) 开展多构型内核组件化设计与实现的教学与科研探索
- [OS比赛开源社区](https://github.com/oscomp) 面向全国高校学生的OS比赛
- [syswonder开源社区](https://syswonder.org/) 面向泛在技术的操作系统探索
- [智能网联汽车创新中心训练营:开源操作系统](https://github.com/cicvedu) 面向智能驾驶领域的系统软件开发培训
