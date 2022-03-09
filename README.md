# 1-the-not-fake-company
This is used for my totally not "fake" company


```
main         o-----\---o--------------/------------------/-------------------------------/----
staging             +----o-\----o----/-----------/---o--/----\---------------------/--o-/
feature/branch              +------------o------/---o---x     \                   /
feature/branch2                                                +---o--o--o---o---/
```

## Company as Code
So what is this term? Company as Code is a term that I'm started to adopt more. This highlights a company that is capable of running their operations 100% from code. This makes for all services like provitioning, maintaining updates and patches, change of configs, automated security and vulnerability remidiation.

This new sight will replace the need for repetative tasks like tedious "Click 'n DragOps" with automated systems that removes a lot of human errors. Company as Code will automate tasks that before was repetative and routine tasks. We all know that routine tasks is prone to errors (e.g. forgetting a step in the process).

### Infrastructure as Code
Utilizing the provtioning power of tools like e.g. Terraform and the like. Provitioning VMs and hardware have never been easier, Terraform is the leading at current date [09.03.2022] - Terraform can provition to self-hosted solutions (e.g. ProxMox, VMware etc.), aswell as Cloud (e.g. Azure, AWS, GCP, Linode etc.). This makes Terraform really powerful!

### Configuration as Code
Ansible! Ansible is a automated configuration utility written in Python3, this tool and configure the provitioned systems per. request. E.g. Default and fresh server tanking, re-config massive amount of servers, configure serverfarms etc.

### Security as Code
Automated CI/CD pipelines that scan, evaluate and notify about outdated, vulnerable or unhealthy servers, services and softwares to a platform like (e.g. Mattermost, Discord, Slack, Teams etc...)