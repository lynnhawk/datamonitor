# 数据监控平台

监控管理系统是数据中心工作人员的信息化工具，系统架构设计应考虑与数据中心组织管理架构相对应，以便相关人员履行岗位职责，系统功能必须满足数据中心工作人员对数据中心进行监控、维护与管理的需要。

监控管理系统应用计算机软件技术、网络通信技术、数据库技术、工业自动控制技术、传感技术等，通过采集、处理数据中心各种智能型和非智能型的设备或系统的运行状态、参数及信息，对数据中心基础设施进行全面监控，并通过分析处理监控信息驱动管理与决策，从而及时高效地做好运行维护，保证数据中心的可用性。

监控管理系统首先是一个多系统集成的综合系统，这是由它监控的对象及其特征所决定的。数据中心的监控对象包括：数据中心供配电动力状况及其相关设备、机房环境状况及其相关设备、机房空间物理安全状况及其相关设备。这些在数据中心承担不同功能的设备，类型多，数量多，参数多，连接多；而且它们自身也可以组成一个个相对独立的硬件系统。因此，通过一个统一的监控管理平台，集成这些系统，就可以组成一个完整的监控管理系统。

监控管理系统也是一个数据采集、加工处理、统计分析的数据管理平台。系统监测的数据，一方面用来实时反映基础设施当前的运行状态指标，以便数据中心机房维护管理人员第一时间发现问题，及时消除，避免对数据中心所支撑的各个业务应用的影响；

另一方面，按照一定的原则和要求，保存历史监控数据，用于日后事故追踪、查询统计和趋势分析。监测的数据经过加工，驱动管理。

以下分别从逻辑架构、物理架构、系统部署架构三个方面介绍监控管理系统的整体架构。

系统逻辑架构

逻辑架构描述了监控管理系统软件由哪些逻辑构件组成、以及这些逻辑构件之间的关系。系统逻辑架构由以下四大逻辑构件组成：监控系统，运行管理系统，总控中心系统，基础服务系统。如下图

