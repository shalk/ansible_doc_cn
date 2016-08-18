

# Ansible Documentation(CN)

## About Ansible

Welcome to the Ansible documentation!
欢迎查看Ansible 文档

Ansible is an IT automation tool. It can configure systems, deploy software, and orchestrate more advanced IT tasks such as continuous deployments or zero downtime rolling updates.
Ansible是一种IT自动化工具。它可以配置系统，部署软件和编排高级的IT任务，如持续部署，0宕机滚动升级。

Ansible’s main goals are simplicity and ease-of-use. It also has a strong focus on security and reliability, featuring a minimum of moving parts, usage of OpenSSH for transport (with an accelerated socket mode and pull modes as alternatives), and a language that is designed around auditability by humans–even those not familiar with the program.
Ansible的主要目标是简化和易用。它也强烈关注安全性和可靠性，它具有最少的[移动组件](https://en.wikipedia.org/wiki/Moving_parts)，这些组件包括使用OpenSSH用于传输（包括加速socket模式和pull模式也作为选择）和一种基于可审阅而设计的语言，这种语言对于不熟悉编程的人也可以审阅。


We believe simplicity is relevant to all sizes of environments, so we design for busy users of all types: developers, sysadmins, release engineers, IT managers, and everyone in between. Ansible is appropriate for managing all environments, from small setups with a handful of instances to enterprise environments with many thousands of instances.
我们相信简化是与各种规模的环境相关的，


Ansible manages machines in an agent-less manner. There is never a question of how to upgrade remote daemons or the problem of not being able to manage systems because daemons are uninstalled. Because OpenSSH is one of the most peer-reviewed open source components, security exposure is greatly reduced. Ansible is decentralized–it relies on your existing OS credentials to control access to remote machines. If needed, Ansible can easily connect with Kerberos, LDAP, and other centralized authentication management systems.

This documentation covers the current released version of Ansible (2.0.1) and also some development version features (2.1). For recent features, we note in each section the version of Ansible where the feature was added.

Ansible, Inc. releases a new major release of Ansible approximately every two months. The core application evolves somewhat conservatively, valuing simplicity in language design and setup. However, the community around new modules and plugins being developed and contributed moves very quickly, typically adding 20 or so new modules in each release.

- Introduction
- Quickstart Video
- Playbooks
- Playbooks: Special Topics
- About Modules
- Module Index
- Detailed Guides
- Developer Information
- Ansible Tower
- Community Information & Contributing
- Ansible Galaxy
- Testing Strategies
- Frequently Asked Questions
- Glossary
- YAML Syntax
- Porting Guide
- Porting plugins
- Hybrid plugins
- Porting custom scripts

