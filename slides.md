---
theme: light-icons
title: InfraOps with IaC
layout: image-header-intro
imageRight: images/it.png
---

# 基于IaC的架构管控

国网江苏公司


---
layout: image-right
image: images/blank.png
equal: false
---


# IT运维

- IT运维需要面向业务需求对应用和基础设施资源进行管理，包括
  - 各类硬件资源管理、配置与维护
  - 各类软件安装、配置与维护
  - 数据存储管理与维护
  - 架构迁移与灾难恢复
  - 各类新技术部署应用
  - 等

---
layout: image-right
image: images/ship.png
equal: true
---

# 关注点

- 船（基础设施环境的软硬件）运行正常么？
- 货物（应用）运行正常么？
- 船与货之间契合么？
- 外部环境安全么？

---
layout: image-right
image: images/blank.png
equal: false
---

# 现有方法

- 以手工方式进行基础设施和应用管理
- 以监控技术对基础设施和应用运行态进行采集
- 通过异常数据/日志发现系统运行问题

---
layout: image-right
image: images/blank.png
equal: false
---

# 问题于挑战

- 手工方式管理效率低
- 资源关系缺失无定义
- 系统配置变更无追踪
- 监控测点不全或冗赘
- 问题发现滞后不及时
- 异常处理排查无依据

---
layout: image-right
image: images/iac.png
equal: true
---

# IaC

IaC实现IT管理的自动化，但仅解决部分问题

---
layout: image-right
image: images/blank.png
equal: false
---

# 技术路线

- 对基础设施与业务应用统一建模，构造数字系统的数字孪生
- 基于IaC配置管理实现数字孪生向运行系统的自动映射/实施
- 基于IaC配置管理实现数字系统多层面自动化全栈监控
- 基于统一模型进行数字系统异常检测与自动化/半自动化修复

全面实现数字系统的敏捷化（AgileOps）智能化（AIOps） 的<b>架构管控闭环</b>

---
layout: image-left
image: images/blank.png
equal: false
---

# To Be Continued ...