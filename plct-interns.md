# PLCT实验室对实习生开放的岗位

最后更新：2020年7月3日，有效期4周。

这里是实习生的岗位页面。全职校招及社招请前往 [Jobs.md](Jobs.md)。

**来一起做点有意思有难度的事情吧！**

## 软件所PLCT实验室简介

PLCT全称是程序语言与编译技术实验室，隶属于中科院软件所智能软件研究中心（ISRC），致力于成为编译技术领域的开源领导者，推进开源工具链及运行时系统等软件基础设施的技术革新，具备主导开发和维护重要基础设施的技术及管理能力。与此同时，努力成为编译领域培养尖端人才的黄埔军校，推动先进编译技术在国内的普及和发展。

中科院软件所（ISCAS）智能软件研究中心（ISRC）的使命是以智能驱动软件发展，以软件支撑智能创新。面向智能计算发展趋势，瞄准高性能、高安全、低功耗、低延时等需求，研究智能基础理论与模型、软件新结构与编译构造方法、内核和运行时环境等，打造适配通用处理器、智能芯片和开放指令集的操作系统和编译工具链，建设开源软件可靠供应链和安全漏洞平台，研发智能无人系统仿真测试环境，支撑智能计算生态和重要行业应用。

中心目前有研究员 3 人，兼职研究员 3 人，副研究员/高级工程师 7 人，目前承担多项国家级的重点项目或课题，以及华为、腾讯、阿里等企业横向课题，近年来在国内外顶级会议和期刊上发表多篇论文，已成为国内在智能和系统软件交叉领域有影响力的团队。

## 我们需要什么样的实习生

### 所有PLCT实习生共性要求

入职要求：

0. 良好的沟通理解能力、能够观察和感知他人的态度和观点。
1. 能够主动沟通、遇到计划外或坏消息能够大声的说出来。
2. 知道如何陈述bugs/issues以及向其他人求助，如何不浪费同事的时间，将复现bug需要的信息提供完整。
3. 能力值评定一般要求达到LV3级别及以上，对于某些特定岗位可以放宽。 **同时，PLCT对于家在湖北省内的同学以及在湖北高校念书的同学，自2020年4月1日开始至2020年9月30日，实习生招募中进行特殊名额分配，不设置准入LV等级。欢迎同学们来PLCT实习。开源项目的实习全部是远程的，并不要求在北京或南京坐班。**
4. 热爱编程，经常写代码。C/C++/Java/JavaScript 都可以。
5. 熟练使用 Linux 命令行；会一点 Python/Bash 脚本进行自动化测试等工作。
6. 熟练使用 Google 搜索引擎；能够自我驱动，朝着目标不断尝试不同的路径。
7. 熟练使用 Git，能够发送 patch set，能够自己 rebase 或解决 conflicts。
8. （加分项）自学了 RISC-V 指令集，包括 RV32GC 和 RV64GC。在自己的电脑上部署运行起来QEMU-RISCV64以及Spike模拟器。
9. （加分项）对于网络知识有基本了解并熟练使用，例如SSH任意端口登陆、Port Forwarding、反向链接、ProxyCommand 等配置自行掌握。

### 实习结束后可以得到什么

1. 技术能力变强。
2. 开始在开源技术社区积累自己的名望。
3. LV4+可以入职软件所PLCT实验室。
4. LV3+可以内推各大公司（华为、今日头条、阿里、腾讯等）的编译器相关团队。

### PLCT的实习生不能得到什么

1. 现金。我们目前隶属在中科院，属于事业单位，能够开出来的实习工资不会像BAT那么高，LV2一般标准是 1500RMB/mo，LV3 一般是 2500RMB/mo，可以些许上浮。如果需要赚钱贴补日常开销，那么PLCT并不是合适的实习场所，可以努力变强，拿到offer，以员工身份加入PLCT。
2. 安稳。我们不保证稳定。我们每个月1号和16号会进行交付物评估，并发布《PLCT开源进展》刊物。新加入实习生有3～4周时间证明自己，并允许有2次观测点交付物不达标。之后如果达不到标准实习会被终止。连续两周没有交付物会被劝退。

### 如何正确的投递简历

请认真阅读。不符合条件邮件不会收到回复。

有意者请投递简历至：
**吴老师 wuwei2016@iscas.ac.cn**

邮件标题请注明：
**实习生 - 岗位编号 - 姓名 - 学校 - 手机号码**

邮件正文请:
**进行跟应聘职位相关的自我介绍，不超过300字。**

邮件必须附带简历。没有PDF格式简历的邮件不保证会收到回复。

## 开放实习生岗位

### BJ33 Firefox/Spidermonkey 开发实习生，porting to RISC-V

工作内容：

1. 就像将 V8 移植到 RISC-V 平台一样，将 Spidermonkey 移植到 RISC-V 平台。
2. 在这个过程中，写文章普及 Spidermonkey 和 RISC-V 的知识，做技术分享。就像是PLCT一贯以来做的那样。
3. 跟 mentor 一起跟 Mozilla 上游交流，将移植工作 upstream。

入职要求：

1. 第一位同学需要LV4的能力；第二位开始需要LV3。目前PLCT实验室还没有mentor在做这块，所以要求第一个实习生能够自行展开，要求会高一些。
2. 加分：最好的自己的英语有自信。
3. 加分：看过 Dart 或任何一个虚拟机的代码实现或架构。写过 Dart。

### BJ32 Dart for RISC-V 开发实习生

工作内容：

1. 就像将 V8 移植到 RISC-V 平台一样，将 Dart 移植到 RISC-V 平台。
2. 在这个过程中，写文章普及 Dart 和 RISC-V 的知识，做技术分享。就像是PLCT一贯以来做的那样。
3. 负责跟 Dart 上游交流，将移植工作 upstream。

入职要求：

1. 第一位同学需要LV4的能力；第二位开始需要LV3。目前PLCT实验室还没有mentor在做这块，所以要求第一个实习生能够自行展开，要求会高一些。
2. 加分：最好的自己的英语有自信。
3. 加分：看过 Dart 或任何一个虚拟机的代码实现或架构。写过 Dart。

### BJ18 Clang/LLVM 开发实习生，主要做 RISC-V 支持

工作内容：

1. 参与PLCT实验室 Clang/LLVM 相关项目的开发，包括但不限于 rvv-llvm、玄铁C910相关实现。
2. 负责撰写学习技术报告、对开发内容进行讲解、就自己所学所写进行技术报告。
3. 负责PLCT实验室相关的国家纵向课题开发及文档工作。

入职要求：

0. 满足PLCT实习生共性要求。
1. 在自己的电脑上编译通过Clang/LLVM的源代码和回归测试集。
2. 对于LLVM的IR和架构有了解。什么都不知道就投简历会在电话面试初筛中被刷。

### BJ17 V8 开发实习生，主要做 RISC-V 支持

工作内容：

1. 参与PLCT实验室 V8 for RISC-V 相关项目的开发。
2. 负责撰写学习技术报告、对开发内容进行讲解、就自己所学所写进行技术报告。

入职要求：

0. 满足PLCT实习生共性要求。
1. 在自己的电脑上编译通过V8的源代码和回归测试集。
2. 观看过V8团队的技术报告，对于编译原理、虚拟机原理、V8的架构有初步了解。
什么都不知道就投简历会在电话面试初筛中被刷。

### BJ15 Spike 开源模拟器开发实习生

工作内容：

1. 参与PLCT实验室在QEMU、Spike等相关开源项目的开发。
2. 负责撰写学习技术报告、对开发内容进行讲解、就自己所学所写进行技术报告。

入职要求：

0. 满足PLCT实习生共性要求。
1. 从源代码编译并运行起来 QEMU-RISCV64、Spike。
2. 对于编译原理和模拟器初步了解。什么都不知道就投简历会在电话面试初筛中被刷。

### BJ14 QEMU 开源模拟器开发实习生（2名）

工作内容：

1. 参与PLCT实验室在QEMU等相关开源项目的开发。
2. 负责撰写学习技术报告、对开发内容进行讲解、就自己所学所写进行技术报告。

入职要求：

0. 满足PLCT实习生共性要求。
1. 从源代码编译并运行起来 QEMU-RISCV64、Spike。
2. 对于编译原理和模拟器初步了解。什么都不知道就投简历会在电话面试初筛中被刷。


### BJ31 OpenROAD 开发实习生（as 代码分析员）

工作内容：

1. PLCT实验室希望建立对EDA工具链OpenROAD进行维护、开发的能力，并成为OpenROAD活跃贡献者。目前OpenROAD工具链的英文资料质量有限，并且缺少中文资料。我们希望招募以为LV4级别的实习生，阅读OpenROAD代码，完善中英文资料，理解各个工具的作用，优化或开发新的工具。
2. 输出分为编写文档和代码贡献。编写文档方面，通过理解OpenROAD源代码，优化OpenROAD英文文档，并且编写中文文档。代码贡献方面，根据源代码研究情况，选择OpenROAD开放项目进行开发工作。（开放项目参考： https://openroad.readthedocs.io/en/latest/contrib/getting-involved.html ）在编写文档和代码贡献的过程中，完成技术报告分享（公开技术报告形式可以参考 [PLCT OpenDay 2019](https://www.bilibili.com/video/BV1PJ41147Ek)）。
3. 负责作为联络员在社区中观察社区动态、形成每周社区动态报告。在需要的时候代表PLCT通过英文邮件跟社区讨论。

入职要求：

0. 满足PLCT实习生共性要求，级别达到 LV4（也就是要求能够独立展开）。
1. 成功构建 OpenROAD 工具链，并实现一种开源芯片的 RTL to GDS 全流程。观看过PLCT的OpenROAD[文章](https://zhuanlan.zhihu.com/p/141713099)及[报告](https://www.bilibili.com/video/BV17C4y1a7Pv/)。（利益相关：这不仅是PLCT的自卖自夸，作者也是你入职之后的直接伙伴，可以通过文章和报告看下风格是否相合。）
2. 对计算机体系结构、芯片设计、EDA工具链的知识有一定了解。
3. 熟练使用 C++，会 Verilog 程序设计语言。
4. 有强烈的动机。

### BJ30 QEMU 代码分析员

工作内容：

1. PLCT实验室希望能够在2020年9月之前建立对 QEMU 进行维护、定制、魔改的能力。而目前PLCT在这个领域还是很多空白。相关的技术资料（不管是中文还是英文）也缺少。目前我们还没有具备在1～3个月快速培养新人投入相关开发工作的培训能力。我们希望招募一位LV3+级别的实习生，阅读 QEMU 的代码，理解细节实现、跟架构设计对应起来。
2. 输出主要是将 undocumented details 文档化，实现细节的文档、进行技术报告分享、并通过PLCT实验室开源（具体开源采用的协议可能需要遵守分析的软件本身文档使用的开源协议）。
3. 在项目的分析过程中，有可能会有部分开发类或 code hacking。
4. 负责作为联络员在社区中观察社区动态、形成每周社区动态报告。在需要的时候代表PLCT通过英文邮件跟社区讨论。

入职要求：

0. 满足PLCT实习生共性要求。
1. 高度自律。
2. 有强烈的动机，以后在开源社区担任 maintainer 或 core contributor。（否则，可能坚持不下来。 Code Analyst 日常都是很枯燥的。）

### BJ29 跟BJ15重复

### BJ28 Valgrind RISC-V 移植开发

工作内容：

1. PLCT实验室希望能够在2021年6月之前建立对 Valgrind 进行维护、定制、魔改的能力。而目前PLCT在这个领域还是空白的状态。相关的技术资料（不管是中文还是英文）也缺少。目前我们还没有具备在1～3个月快速培养新人投入相关开发工作的培训能力。我们希望招募一位LV3+级别的实习生，阅读 Valgrind 的代码，理解细节实现、跟架构设计对应起来。
2. 输出主要是将 undocumented details 文档化，实现细节的文档、进行技术报告分享、并通过PLCT实验室开源（具体开源采用的协议可能需要遵守分析的软件本身文档使用的开源协议）。
3. 在项目的分析过程中，有可能会有部分开发类或 code hacking。
4. 负责作为联络员在社区中观察社区动态、形成每周社区动态报告。在需要的时候代表PLCT通过英文邮件跟社区讨论。

入职要求：

0. 满足PLCT实习生共性要求。
1. 高度自律。
2. 有强烈的动机，以后在开源社区担任 maintainer 或 core contributor。（否则，可能坚持不下来。 Code Analyst 日常都是很枯燥的。）

### BJ27 HotSpot VM 代码分析员，以及特别强的话可以尝试给 RISC-V 做移植

工作内容：

1. PLCT实验室希望能够在2022年1月之前建立对 HotSpot VM 进行魔改以增加 RISC-V 后端的能力。而目前PLCT在这个领域还是空白的状态。相关的技术资料（不管是中文还是英文）也缺少。目前我们还没有具备在1～3个月快速培养新人投入相关开发工作的培训能力。我们希望招募一位LV3+级别的实习生，阅读 HotSpot 的代码，理解细节实现、跟架构设计对应起来。
2. 输出主要是将 undocumented details 文档化，实现细节的文档、进行技术报告分享、并通过PLCT实验室开源（具体开源采用的协议可能需要遵守分析的软件本身文档使用的开源协议）。
3. 在项目的分析过程中，有可能会有部分开发类工作或 code hacking。
4. 负责作为联络员在社区中观察社区动态、形成每周社区动态报告。在需要的时候代表PLCT通过英文邮件跟社区讨论。

入职要求：

0. 满足PLCT实习生共性要求。
1. 高度自律。
2. 有强烈的动机，以后在开源社区担任 maintainer 或 core contributor。（否则，可能坚持不下来。 Code Analyst 日常都是很枯燥的。）

### BJ26 FIRRTL 代码分析员，以及成为上游 maintainer

工作内容：

1. PLCT实验室希望能够在2021年6月之前建立对围绕 FIRRTL 的相关的进行维护、定制、魔改的能力。而目前PLCT在这个领域还是空白的状态。相关的技术资料（不管是中文还是英文）也缺少。目前我们还没有具备在1～3个月快速培养新人投入相关开发工作的培训能力。我们希望招募一位LV3+级别的实习生，阅读 FIRRTL项目的代码，理解细节实现、跟架构设计对应起来。
2. 输出主要是将 undocumented details 文档化，实现细节的文档、进行技术报告分享、并通过PLCT实验室开源（具体开源采用的协议可能需要遵守分析的软件本身文档使用的开源协议）。
3. 在项目的分析过程中，有可能会有部分开发类工作或 code hacking。
4. 负责作为联络员在社区中观察社区动态、形成每周社区动态报告。在需要的时候代表PLCT通过英文邮件跟社区讨论。

入职要求：

0. 满足PLCT实习生共性要求。
1. 高度自律。
2. 有强烈的动机，以后在开源社区担任 maintainer 或 core contributor。（否则，可能坚持不下来。 Code Analyst 日常都是很枯燥的。）

### BJ25 glibc 代码分析员，耐得住寂寞

工作内容：

1. PLCT实验室希望能够在2021年6月之前建立对 GLibC 进行维护、定制、魔改的能力。而目前PLCT在这个领域还是空白的状态。相关的技术资料（不管是中文还是英文）也缺少。目前我们还没有具备在1～3个月快速培养新人投入相关开发工作的培训能力。我们希望招募一位LV3+级别的实习生，阅读 glibc 的代码，理解细节实现、跟架构设计对应起来。
2. 输出主要是将 undocumented details 文档化，实现细节的文档、进行技术报告分享、并通过PLCT实验室开源（具体开源采用的协议可能需要遵守分析的软件本身文档使用的开源协议）。
3. 在项目的分析过程中，有可能会有部分开发类工作或 code hacking。
4. 负责作为联络员在社区中观察社区动态、形成每周社区动态报告。在需要的时候代表PLCT通过英文邮件跟社区讨论。

入职要求：

0. 满足PLCT实习生共性要求。
1. 高度自律。
2. 有强烈的动机，以后在开源社区担任 maintainer 或 core contributor。（否则，可能坚持不下来。 Code Analyst 日常都是很枯燥的。）


### BJ24 verilator 代码分析员（我还不知道这是什么）

工作内容：

1. PLCT实验室希望能够在2021年12月之前建立对 verilator 进行维护、定制、魔改的能力。而目前PLCT在这个领域还是空白的状态。相关的技术资料（不管是中文还是英文）也缺少。目前我们还没有具备在1～3个月快速培养新人投入相关开发工作的培训能力。我们希望招募一位LV3+级别的实习生，阅读 verilator 的代码，理解细节实现、跟架构设计对应起来。
2. 输出主要是将 undocumented details 文档化，实现细节的文档、进行技术报告分享、并通过PLCT实验室开源（具体开源采用的协议可能需要遵守分析的软件本身文档使用的开源协议）。
3. 在项目的分析过程中，有可能会有部分开发类工作或 code hacking。
4. 负责作为联络员在社区中观察社区动态、形成每周社区动态报告。在需要的时候代表PLCT通过英文邮件跟社区讨论。

入职要求：

0. 满足PLCT实习生共性要求。
1. 高度自律。
2. 有强烈的动机，以后在开源社区担任 maintainer 或 core contributor。（否则，可能坚持不下来。 Code Analyst 日常都是很枯燥的。）

### BJ23 被 BJ31 覆盖

### BJ22 LLVM lld 代码分析员，以及 RISC-V port 支持

工作内容：

1. PLCT实验室希望能够在2021年1月之前建立对 LLVM lld 进行维护、定制、魔改的能力。而目前PLCT在这个领域还是空白的状态。相关的技术资料（不管是中文还是英文）也缺少。目前我们还没有具备在1～3个月快速培养新人投入相关开发工作的培训能力。我们希望招募一位LV3+级别的实习生，阅读 lld 的代码，理解细节实现、跟架构设计对应起来。
2. 输出主要是将 undocumented details 文档化，实现细节的文档、进行技术报告分享、并通过PLCT实验室开源（具体开源采用的协议可能需要遵守分析的软件本身文档使用的开源协议）。
3. 在项目的分析过程中，有可能会有部分开发类工作或 code hacking。
4. 负责作为联络员在社区中观察社区动态、形成每周社区动态报告。在需要的时候代表PLCT通过英文邮件跟社区讨论。

入职要求：

0. 满足PLCT实习生共性要求。
1. 高度自律。
2. 有强烈的动机，以后在开源社区担任 maintainer 或 core contributor。（否则，可能坚持不下来。 Code Analyst 日常都是很枯燥的。）

### BJ21 LLVM lldb，以及 RISC-V port 支持

工作内容：

1. PLCT实验室希望能够在2021年1月之前建立对 lldb 进行维护、定制、魔改的能力。而目前PLCT在这个领域还是空白的状态。相关的技术资料（不管是中文还是英文）也缺少。目前我们还没有具备在1～3个月快速培养新人投入相关开发工作的培训能力。我们希望招募一位LV3+级别的实习生，阅读 lldb 的代码，理解细节实现、跟架构设计对应起来。
2. 输出主要是将 undocumented details 文档化，实现细节的文档、进行技术报告分享、并通过PLCT实验室开源（具体开源采用的协议可能需要遵守分析的软件本身文档使用的开源协议）。
3. 在项目的分析过程中，有可能会有部分开发类工作或 code hacking。
4. 负责作为联络员在社区中观察社区动态、形成每周社区动态报告。在需要的时候代表PLCT通过英文邮件跟社区讨论。

入职要求：

0. 满足PLCT实习生共性要求。
1. 高度自律。
2. 有强烈的动机，以后在开源社区担任 maintainer 或 core contributor。（否则，可能坚持不下来。 Code Analyst 日常都是很枯燥的。）

### BJ20 GNU gdb，以及 RISC-V port 支持

工作内容：

1. PLCT实验室希望能够在2021年6月之前建立对 GNU GDB 进行维护、定制、魔改的能力。而目前PLCT在这个领域还是空白的状态。相关的技术资料（不管是中文还是英文）也缺少。目前我们还没有具备在1～3个月快速培养新人投入相关开发工作的培训能力。我们希望招募一位LV3+级别的实习生，阅读 GDB 的代码，理解细节实现、跟架构设计对应起来。
2. 输出主要是将 undocumented details 文档化，实现细节的文档、进行技术报告分享、并通过PLCT实验室开源（具体开源采用的协议可能需要遵守分析的软件本身文档使用的开源协议）。
3. 在项目的分析过程中，有可能会有部分开发类工作或 code hacking。
4. 负责作为联络员在社区中观察社区动态、形成每周社区动态报告。在需要的时候代表PLCT通过英文邮件跟社区讨论。

入职要求：

0. 满足PLCT实习生共性要求。
1. 高度自律。
2. 有强烈的动机，以后在开源社区担任 maintainer 或 core contributor。（否则，可能坚持不下来。 Code Analyst 日常都是很枯燥的。）

### BJ19 RISC-V IDE 开发实习生

工作内容：

1. 参与PLCT实验室 IDE for RISC-V 相关项目的开发。
2. 负责撰写学习技术报告、对开发内容进行讲解、就自己所学所写进行技术报告。
3. 负责PLCT实验室相关的国家纵向课题开发及文档工作。

入职要求：

0. 满足PLCT实习生共性要求。
1. 在自己的电脑上编译通过Clang/LLVM的源代码和回归测试集。
2. 事先搜索和阅读过 Eclipse 或 VSCode 的架构。什么都不知道就投简历会在电话面试初筛中被刷。

### BJ16 方舟开源编译器开发实习生

工作内容：

1. 参与PLCT实验室 方舟编译器以及 Toy Runtime 相关项目的开发。
2. 负责撰写学习技术报告、对开发内容进行讲解、就自己所学所写进行技术报告。

入职要求：

0. 满足PLCT实习生共性要求。
1. 在自己的电脑上编译通过 OpenArkCompiler 的源代码和回归测试集。
2. 对于编译原理初步了解。什么都不知道就投简历会在电话面试初筛中被刷。