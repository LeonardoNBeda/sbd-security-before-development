# Extra: Tooling for Each Phase

**Category**: SSDLC Process Enhancement  
**Version**: 1.0  
**Last Updated**: October 2024  
**Author**: Leonardo Beda

## Overview - Tooling for Each Phase

This document presents a curated selection of open-source tools and frameworks designed to support teams throughout the Security Before Development (SBD) process. By incorporating these tools, organizations can strengthen their security posture, streamline security assessments, and ensure adherence to best practices.

Beyond just tools, this documentation underscores the necessity of a comprehensive security strategy. This includes elements such as threat modeling, secure coding guidelines, and continuous monitoring. Leveraging these resources fosters better collaboration between development and security teams, ultimately leading to more secure applications.

## Phase 0: Business Reconnaissance
- **[Draw.io](https://app.diagrams.net/)**: Create diagrams to visualize business processes and architecture effectively.
- **[Google Docs / Notion](https://www.notion.so)**: Collaborative tools for gathering insights, brainstorming, and documenting business requirements and stakeholder interviews.
- **[Miro](https://miro.com/)**: An online whiteboard platform for collaborative brainstorming and mapping out business needs and user journeys.

## Phase 1: Requirements
- **[OWASP Dependency-Check](https://owasp.org/www-project-dependency-check/)**: A software composition analysis tool that identifies project dependencies and checks them for known vulnerabilities.
- **[SonarQube](https://www.sonarqube.org/)**: An open-source platform that evaluates code quality and security vulnerabilities, ensuring compliance with secure coding standards.
- **[OWASP SAMM (Software Assurance Maturity Model)](https://owasp.org/www-project-software-assurance-maturity-model/)**: A framework for assessing and enhancing security practices within the software development lifecycle.

## Phase 2: Design Review and Threat Modeling
- **[OWASP Threat Dragon](https://owasp.org/www-project-threat-dragon/)**: A threat modeling tool that aids in visualizing, analyzing, and mitigating threats during the design phase.
- **[Microsoft Threat Modeling Tool](https://github.com/microsoft/threat-modeling-tool)**: A free tool for creating data flow diagrams and identifying potential security issues based on architecture.
- **[OWASP Risk Rating Methodology](https://owasp.org/www-community/OWASP_Risk_Rating_Methodology)**: Guidelines for assessing risks and prioritizing security efforts based on their impact and likelihood.

## Phase 3: Development
- **[ESLint](https://eslint.org/)**: A static code analysis tool that identifies and addresses problematic patterns in JavaScript code, supporting secure coding practices.
- **[Brakeman](https://brakemanscanner.org/)**: A static analysis tool tailored for Ruby on Rails applications, focusing on identifying security vulnerabilities.
- **[OWASP Security Coding Practices](https://owasp.org/www-project-secure-coding-practices-quick-reference-guide/)**: A collection of secure coding guidelines applicable across various programming languages.

## Phase 4: Testing
- **[OWASP ZAP (Zed Attack Proxy)](https://www.zaproxy.org/)**: A widely-used penetration testing tool that uncovers security vulnerabilities in web applications during testing.
- **[Arachni](https://www.arachni-scanner.com/)**: An open-source web application security scanner that identifies vulnerabilities through automated testing.
- **[Burp Suite Community Edition](https://portswigger.net/burp/communitydownload)**: A free version of a popular web application security testing tool, ideal for both manual and automated assessments.
- **[Snyk Open Source](https://snyk.io/)**: A tool designed to discover and remediate vulnerabilities in open-source libraries utilized in applications.

## Phase 5: Deployment
- **[OpenVAS](https://www.openvas.org/)**: An open-source vulnerability scanning tool that assesses the security of applications and their environments prior to deployment.
- **[Prometheus](https://prometheus.io/)**: An open-source monitoring tool that tracks application performance and detects anomalies or security incidents in real time.
- **[Kube-bench](https://github.com/aquasecurity/kube-bench)**: A tool for evaluating Kubernetes clusters against the CIS Kubernetes Benchmark to ensure compliance.

## Bonus Tools
- **[Metasploit Community Edition](https://www.metasploit.com/)**: A comprehensive penetration testing framework for assessing application and network security.
- **[OWASP Amass](https://owasp.org/www-project-amass/)**: A tool for network mapping of attack surfaces and discovering external assets.

## Conclusion
Integrating these open-source tools and frameworks can significantly enhance security practices throughout each phase of the SBD. By emphasizing OWASP resources, organizations can align their security initiatives with industry best practices, paving the way for more secure and resilient applications. The ideal combination of tools will vary depending on the specific needs and technologies employed by the development and security teams.

[Go to Previous page](./Phase5-Deployment.md)