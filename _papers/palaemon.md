---
title: "Trust Management as a Service: Enabling Trusted Execution in the Face of Byzantine Stakeholders"
authors: Franz&nbsp;Gregor, Wojciech&nbsp;Ozga, Sébastien&nbsp;Vaucher, Rafael&nbsp;Pires, Do&nbsp;Le&nbsp;Quoc, Sergei&nbsp;Arnautov, André&nbsp;Martin, Valerio&nbsp;Schiavoni, Pascal&nbsp;Felber, Christof&nbsp;Fetzer
conference_short: DSN 2020
conference_long: 50th IEEE/IFIP International Conference on Dependable Systems and Networks, València, Spain
conference_website: https://dsn2020.webs.upv.es/
date: 2020-06-29
arxiv: 2003.14099
doi: 10.1109/DSN48063.2020.00063
---
Trust is arguably the most important challenge for critical services both deployed as well as accessed remotely over the network.
These systems are exposed to a wide diversity of threats, ranging from bugs to exploits, active attacks, rogue operators, or simply careless administrators.
To protect such applications, one needs to guarantee that they are properly configured and securely provisioned with the “secrets” (*e.g.* encryption keys) necessary to preserve not only the confidentiality, integrity and freshness of their data but also their code.
Furthermore, these secrets should not be kept under the control of a single stakeholder---which might be compromised and would represent a single point of failure---and they must be protected across software versions in the sense that attackers cannot get access to them via malicious updates.
Traditional approaches for solving these challenges often use *ad hoc* techniques and ultimately rely on a hardware security module (HSM) as root of trust.
We propose a more powerful and generic approach to trust management that instead relies on trusted execution environments (TEEs) and a set of stakeholders as root of trust.
Our system, PALÆMON, can operate as a managed service deployed in an untrusted environment, *i.e.*, one can delegate its operations to an untrusted cloud provider with the guarantee that data will remain confidential despite not trusting any individual human (even with root access) nor system software.
PALÆMON addresses in a secure, efficient and cost-effective way five main challenges faced when developing trusted networked applications and services.
Our evaluation on a range of benchmarks and real applications shows that PALÆMON performs efficiently and can protect secrets of services without any change to their source code.
