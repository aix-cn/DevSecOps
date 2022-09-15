# DevSecOps

#### 定义
DevSecOps-让业务,开发,安全,运维, 同病相怜, 肝胆相照, 荣辱与共。

DevSecOps是DevOps的理念的扩展。DevSecOps的目标是将安全嵌入到DevOps的流水线之中，满足从需求，设计，开发，测试到运维等全过程的安全整合，实现安全的完全嵌入和左移，让所有的人为安全负责，主动的承担安全责任，最终让团队能更快，更高效的开发更安全的产品。
![输入图片说明](0.DevSecOps%20Overview/Image-for-devsecops-lifecycle-devsecopswebpage-17.jpg)


#### DevSecOps Overview
1.  [Zero-to-DevSecOps](https://github.com/lab-mj/DevSecOps/raw/master/0.DevSecOps%20Overview/Zero-to-DevSecOps.pdf)
2.  [DevSecOps-What-Why-And-How](https://github.com/lab-mj/DevSecOps/blob/master/0.DevSecOps%20Overview/DevSecOps-What-Why-And-How.pdf) 
3.  [Devsecops-Security-Test-automation](https://github.com/lab-mj/DevSecOps/blob/master/0.DevSecOps%20Overview/Devsecops-Security-Test-automation-briefing.pdf) 

https://github.com/lab-mj/DevSecOps/blob/main/1.DoD%20Enterprise%20DevSecOps/DoD-Enterprise-DevSecOps-2.0-Fundamentals.pdf

#### DOD DevSecOps 

1. [DoD-Enterprise-DevSecOps-2.0-Fundamentals](https://github.com/lab-mj/DevSecOps/blob/master/1.DoD%20Enterprise%20DevSecOps/DoD-Enterprise-DevSecOps-2.0-Fundamentals.pdf) 
2. [DoD-Enterprise-DevSecOps-2.0-Playbook](https://github.com/lab-mj/DevSecOps/blob/master/1.DoD%20Enterprise%20DevSecOps/DoD-Enterprise-DevSecOps-2.0-Playbook.pdf) 
3. [DoD-Enterprise-DevSecOps-2.0-Strategy-Guide](https://github.com/lab-mj/DevSecOps/blob/master/1.DoD%20Enterprise%20DevSecOps/DoD-Enterprise-DevSecOps-2.0-Strategy-Guide.pdf) 
4. [DoD-Enterprise-DevSecOps-2.0-Tools-and-Activities](https://github.com/lab-mj/DevSecOps/blob/master/1.DoD%20Enterprise%20DevSecOps/DoD-Enterprise-DevSecOps-2.0-Tools-and-Activities-Guidebook.pdf) 
5. [DoD-Enterprise-DevSecOps-Reference-Design-v2.0-CNCF-Kubernetes](https://github.com/lab-mj/DevSecOps/blob/master/1.DoD%20Enterprise%20DevSecOps/DoD-Enterprise-DevSecOps-Reference-Design-v2.0-CNCF-Kubernetes.pdf) 

#### DevSecOps-大厂的视角
1. [devsecops.org](https://www.devsecops.org/) 
2. [synopsys 定义的DevSecOps](https://www.synopsys.com/glossary/what-is-devsecops.html)
3. [redhat-DevSecOps](https://www.redhat.com/en/topics/devops/what-is-devsecops)
4. [IBM-DevSecOps](https://www.ibm.com/cloud/learn/devsecops)
5. [dynatrace-DevSecOps](https://www.dynatrace.com/news/blog/what-is-devsecops/)    
6. [atlassian-DevSecOps](https://www.atlassian.com/devops/devops-tools/devsecops-tools)
7. [csoonline-DevSecOps](https://www.csoonline.com/article/3245748/what-is-devsecops-developing-more-secure-applications.html) 
8. [techtarget-DevSecOps](https://www.techtarget.com/searchitoperations/definition/DevSecOps)
9. [jfrog-DevSecOps](https://jfrog.com/devops-tools/what-is-devsecops/) 
10. [snyk-DevSecOps](https://snyk.io/series/devsecops/) 
11. [plutora-DevSecOps](https://www.plutora.com/blog/devsecops-guide)


#### DevSecOps 工具
1.  [DevSecOps-Toolchain](https://github.com/zemmali/DevSecOps-Toolchain) 
2.  [DevSecOps tools](https://github.com/hahwul/DevSecOps/tree/main/tools)


| Type | Name | Description |
| ---------- | :---------- | :----------: |
| Build/SAST  | [SonarQube](https://www.sonarqube.org/) |  SonarQube 是一个开源的代码分析平台, 用来持续分析和评测项目源代码的质量。 通过SonarQube我们可以检测出项目中重复代码, 潜在bug, 代码规范,安全性漏洞等问题；|![](https://img.shields.io/static/v1?label=&message=it's%20not%20github&color=gray)|![](https://img.shields.io/static/v1?label=&message=it's%20not%20github&color=gray)
| Build/SAST | [codeql](https://github.com/github/codeql) | CodeQL 是一个语义代码分析引擎，它可以扫描发现代码库中的漏洞。使用 CodeQL，可以像对待数据一样查询代码。编写查询条件以查找漏洞的所有变体，并处理，同时可以分享个人查询条件。| ![](https://img.shields.io/github/stars/github/codeql) | ![](https://img.shields.io/github/languages/top/github/codeql) |
| Build/SAST | [semgrep](https://github.com/returntocorp/semgrep) | Semgrep 是一个快速、开源的静态分析工具，用于在编辑、提交和 CI 时查找错误并执行代码标准。 | ![](https://img.shields.io/github/stars/returntocorp/semgrep) | ![](https://img.shields.io/github/languages/top/returntocorp/semgrep) |
| Build/SAST | [sonarcloud-github-action](https://github.com/SonarSource/sonarcloud-github-action) | 将SonarCloud代码分析集成到GitHub Actions | ![](https://img.shields.io/github/stars/SonarSource/sonarcloud-github-action) | ![](https://img.shields.io/github/languages/top/SonarSource/sonarcloud-github-action) |
| Build/SECRET-MANAGE | [kamus](https://github.com/Soluto/kamus) | Kamus 能自动将零信任加密和解密合并到你的 GitOps 工作流中。与 Git-Secret 结合使用，你可以在不减慢 CI/CD 周期的情况下增强整个管道的安全性。 | ![](https://img.shields.io/github/stars/Soluto/kamus) | ![](https://img.shields.io/github/languages/top/Soluto/kamus) |
| Build/SECRET-MANAGE | [secrets-sync-action](https://github.com/google/secrets-sync-action) | 以将一个存储库中的机密同步到其他存储库中。通过此操作，维护人员可以在单个存储库中定义和旋转机密，并将其同步到Github组织或更高版本中的所有其他存储库。 | ![](https://img.shields.io/github/stars/google/secrets-sync-action) | ![](https://img.shields.io/github/languages/top/google/secrets-sync-action) |
| Build/SECRET-MANAGE | [vault-action](https://github.com/hashicorp/vault-action) |秘钥管理工具 | ![](https://img.shields.io/github/stars/hashicorp/vault-action) | ![](https://img.shields.io/github/languages/top/hashicorp/vault-action) |
| Design/THREAT | [owasp-threat-dragon-desktop](https://github.com/mike-goodwin/owasp-threat-dragon-desktop) | Threat Dragon是一款免费的开源跨平台应用程序，包括系统图表和自动生成威胁/缓解措施的规则引擎。 这是一个。 该项目的重点是出色的UX，功能强大的规则引擎以及与其他开发生命周期工具的集成。 | ![](https://img.shields.io/github/stars/mike-goodwin/owasp-threat-dragon-desktop) | ![](https://img.shields.io/github/languages/top/mike-goodwin/owasp-threat-dragon-desktop) |
| Design/THREAT | [pytm](https://github.com/izar/pytm) | Pytm是一款Python风格的威胁建模框架，它可以帮助我们以Python语言风格的形式并使用pytm框架中的元素和属性来定义你的系统。根据我们的定义参数，pytm可以针对你的系统生成数据流图（DFD）、序列图以及威胁模型。 | ![](https://img.shields.io/github/stars/izar/pytm) | ![](https://img.shields.io/github/languages/top/izar/pytm) |
| Design/THREAT | [seasponge](https://github.com/mozilla/seasponge) | 威胁建模工具 | ![](https://img.shields.io/github/stars/mozilla/seasponge) | ![](https://img.shields.io/github/languages/top/mozilla/seasponge) |
| Design/THREAT | [threagile](https://github.com/Threagile/threagile) | 敏捷威胁建模工具| ![](https://img.shields.io/github/stars/Threagile/threagile) | ![](https://img.shields.io/github/languages/top/Threagile/threagile) |
| Operate and Monitor/COMPONENT-ANALYSIS | [dependency-track](https://github.com/DependencyTrack/dependency-track) | Dependency-Track是一个智能组件分析平台，允许组织识别和降低软件供应链中的风险。Dependency-Track通过利用软件材料清单（SBOM）的功能，采取了一种独特且非常有益的方法。这种方法提供了传统软件组合分析（SCA）解决方案无法实现的功能。Dependency-Track监控其投资组合中每个应用程序所有版本的组件使用情况，以便主动识别整个组织的风险。该平台采用API优先设计，非常适合在CI/CD环境中使用。 | ![](https://img.shields.io/github/stars/DependencyTrack/dependency-track) | ![](https://img.shields.io/github/languages/top/DependencyTrack/dependency-track) |
| Operate and Monitor/K8S | [kube-hunter](https://github.com/aquasecurity/kube-hunter) | 寻找 Kubernetes 集群中可利用的安全弱点。Kube-hunter 更有用的功能之一是能够利用它发现的漏洞来寻找进一步的漏洞。 | ![](https://img.shields.io/github/stars/aquasecurity/kube-hunter) | ![](https://img.shields.io/github/languages/top/aquasecurity/kube-hunter) |
| Test/DAST | [action-baseline](https://github.com/zaproxy/action-baseline) | 运行OWASP ZAP 以查找Web应用程序中的漏洞的GitHub操作。 ZAP基线操作会扫描目标URL中的漏洞，并在GitHub存储库中维护已标识警报的问题。 | ![](https://img.shields.io/github/stars/zaproxy/action-baseline) | ![](https://img.shields.io/github/languages/top/zaproxy/action-baseline) |
| Test/DAST | [action-dalfox](https://github.com/hahwul/action-dalfox) | DalFox是一款功能强大的XSS参数分析和扫描工具,该工具基于Golang开发,可以帮助广大研究人员通过分析参数,来寻找XSS漏洞,并基于DOM解析器来对找到的XSS漏洞进行验证。 | ![](https://img.shields.io/github/stars/hahwul/action-dalfox) | ![](https://img.shields.io/github/languages/top/hahwul/action-dalfox) |
| Test/DAST | [action-full-scan](https://github.com/zaproxy/action-full-scan) | A运行OWASPZAP完整扫描的GitHub操作,ZAP动作全扫描运行OWASPZAP以执行动态应用程序安全测试(DAST)的GitHub操作。 | ![](https://img.shields.io/github/stars/zaproxy/action-full-scan) | ![](https://img.shields.io/github/languages/top/zaproxy/action-full-scan) |
| Test/DAST | [zaproxy](https://github.com/zaproxy/zaproxy) | 寻找Web应用程序漏洞的综合性渗透测试工具| ![](https://img.shields.io/github/stars/zaproxy/zaproxy) | ![](https://img.shields.io/github/languages/top/zaproxy/zaproxy) |
| Test/PENTEST | [faraday](https://github.com/infobyte/faraday) | 渗透测试工具和漏洞管理平台 | ![](https://img.shields.io/github/stars/infobyte/faraday) | ![](https://img.shields.io/github/languages/top/infobyte/faraday) |
| Test/PENTEST | [metasploit-framework](https://github.com/rapid7/metasploit-framework) | 渗透测试框架 | ![](https://img.shields.io/github/stars/rapid7/metasploit-framework) | ![](https://img.shields.io/github/languages/top/rapid7/metasploit-framework) |
| Test/PENTEST | [monkey](https://github.com/guardicore/monkey) | 自动化的渗透测试工具 | ![](https://img.shields.io/github/stars/guardicore/monkey) | ![](https://img.shields.io/github/languages/top/guardicore/monkey) |
| Test/PENTEST | [ptf](https://github.com/trustedsec/ptf) | 渗透测试框架 | ![](https://img.shields.io/github/stars/trustedsec/ptf) | ![](https://img.shields.io/github/languages/top/trustedsec/ptf) |                                                                                |


#### DevSecOps Labs

1. [Practical DevOps-The Lab](https://www.rohitsalecha.com/#projects)    
2. [DevSecOps bootcamp](https://github.com/devsecops/bootcamp) 

#### DevSecOps 培训

1.  [dsosec.com](https://www.dsosec.com/)

---------------------------------------------------------------------------------------------------------------------
欢迎加群讨论：

![输入图片说明](0.DevSecOps%20Overview/k9cw9whc0wkrn4f5w4ie.jpg)
