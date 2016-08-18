 

# Ansible Documentation(CN)

## About Ansible

Welcome to the Ansible documentation!
欢迎查看Ansible 文档

Ansible is an IT automation tool. It can configure systems, deploy software, and orchestrate more advanced IT tasks such as continuous deployments or zero downtime rolling updates.
Ansible是一种IT自动化工具。它可以配置系统，部署软件和编排高级的IT任务，如持续部署，0宕机滚动升级。

Ansible’s main goals are simplicity and ease-of-use. It also has a strong focus on security and reliability, featuring a minimum of moving parts, usage of OpenSSH for transport (with an accelerated socket mode and pull modes as alternatives), and a language that is designed around auditability by humans–even those not familiar with the program.
Ansible的主要目标是简化和易用。它也强烈关注安全性和可靠性，它具有最少的[移动组件](https://en.wikipedia.org/wiki/Moving_parts)，这些组件包括使用OpenSSH用于传输（包括加速socket模式和pull模式也作为选择）和一种基于可审阅而设计的语言，这种语言对于不熟悉编程的人也可以审阅。


We believe simplicity is relevant to all sizes of environments, so we design for busy users of all types: developers, sysadmins, release engineers, IT managers, and everyone in between. Ansible is appropriate for managing all environments, from small setups with a handful of instances to enterprise environments with many thousands of instances.
我们相信简化是与各种规模的环境相关的，所以我们为各种类型的繁忙用户而设计，包括开发者，系统管理员，发布工程师，IT经理 以及所有介于这之间的人。Ansible是适合管理所有这些环境的，从少量实例的小装置到数以千计的实例的企业环境。


Ansible manages machines in an agent-less manner. There is never a question of how to upgrade remote daemons or the problem of not being able to manage systems because daemons are uninstalled. Because OpenSSH is one of the most peer-reviewed open source components, security exposure is greatly reduced. Ansible is decentralized–it relies on your existing OS credentials to control access to remote machines. If needed, Ansible can easily connect with Kerberos, LDAP, and other centralized authentication management systems.
Ansible采用无代理的方式管理机器。如何更新远程deamons或者无法管理系统这种问题是不存在的，因为deamons并没有安装。
因为OpenSSH是一种广泛评审的开源组件，安全缺陷得到了极大的减少。Ansible是去中心化的-它依靠存在的OS证书去控制远程机器的访问。如果需要，Ansible可以很容易的连通Kerberos、LDAP和其他的中心化认证管理系统。


This documentation covers the current released version of Ansible (2.0.1) and also some development version features (2.1). For recent features, we note in each section the version of Ansible where the feature was added.
这个文档覆盖当前发行版本的Ansible（2.0.1）和一些开发版本的功能（2.1）。对于最近的功能，我们在每个章节标注了功能添加时Ansible的版本。

Ansible, Inc. releases a new major release of Ansible approximately every two months. The core application evolves somewhat conservatively, valuing simplicity in language design and setup. However, the community around new modules and plugins being developed and contributed moves very quickly, typically adding 20 or so new modules in each release.
Ansible 公司 大约每两个月发布一个主版本更新的Ansible。核心应用演进的有些保守，并重视语言设计和安装的简化。尽管如此，社区对于新模块和插件的持续开发和贡献推进的非常的快，一般每个release会增加大约20个新模块。

- Introduction
- 介绍
- Quickstart Video
- 快速开始 视频
- Playbooks
- Playbooks: Special Topics
- Playbooks: 特定话题
- About Modules
- 关于模块
- Module Index
- 模块索引
- Detailed Guides
- 细节指南
- Developer Information
- 开发者信息
- Ansible Tower
- Ansible Tower
- Community Information & Contributing
- 社区信息和贡献
- Ansible Galaxy
- Ansible Galaxy
- Testing Strategies
- 测试策略
- Frequently Asked Questions
- 常见问答
- Glossary
- 词汇表
- YAML Syntax
- YAML 语法
- Porting Guide
- Porting 指南
- Porting plugins
- Porting 插件
- Hybrid plugins
- Hybird 插件
- Porting custom scripts
- Porting 定制脚本

