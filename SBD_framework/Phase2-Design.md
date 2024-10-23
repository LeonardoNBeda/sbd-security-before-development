# Phase 2: Design Review and Threat Modeling

**Category**: SSDLC Process Enhancement  
**Version**: 1.0  
**Last Updated**: October 2024  
**Author**: Leonardo Beda

## Overview - Phase 2: Design Review and Threat Modeling

The **Design Review and Threat Modeling** phase is critical for identifying potential security risks in the system architecture before development begins. This phase involves a comprehensive review of the application's design to uncover any threats or vulnerabilities that may arise from the architecture, components, or integration points. By thoroughly conducting design reviews and threat modeling, teams can ensure that security considerations are seamlessly integrated into the design process.

## Goals of the Design Review and Threat Modeling Phase

The primary objectives of this phase are to:

1. **Review System Architecture**: Analyze the application architecture to identify security weaknesses and ensure alignment with security requirements.
2. **Conduct Threat Modeling**: Identify potential threats, vulnerabilities, and attack vectors specific to the application’s design and architecture.
3. **Mitigate Security Risks**: Develop strategies and controls to address identified security risks prior to the start of development.

## Key Questions for Development and AppSec Teams

The following questions guide teams in addressing security concerns during the design review and threat modeling phase:

### 1. **System Architecture Review**
- **Required**: How does the architecture align with the secure coding guidelines established in the previous phase?
- **Required**: What are the critical components and data flows within the architecture?
- **Optional**: Are there any third-party services or components integrated into the design, and how are they secured?
- **Optional**: How is user data segregated and protected within the application architecture?

### 2. **Threat Modeling**
- **Required**: What potential threats have been identified for this architecture? (e.g., unauthorized access, data breaches)
- **Required**: What attack vectors have been considered in the threat model?
- **Optional**: Have threat actors and their motivations been taken into account?
- **Optional**: Are there specific threats related to regulatory compliance that need addressing?

### 3. **Security Controls and Mitigations**
- **Required**: What security controls are in place to mitigate identified threats?
- **Required**: How will authentication and authorization be managed within the application?
- **Optional**: Are there specific tools or technologies being considered to enhance security (e.g., Web Application Firewalls, IDS/IPS)?
- **Optional**: What monitoring and logging capabilities will be implemented to detect security incidents?

### 4. **Secure Architecture**
- **Required**: How are security zones defined within the architecture, and what measures are in place to protect sensitive zones?
- **Required**: Are redundancies established to ensure availability and security, such as load balancers or failover systems?
- **Optional**: How are data retention and disposal handled within the architecture?

### 5. **Authentication and Authorization**
- **Required**: What authentication mechanisms are being utilized (e.g., multi-factor authentication, single sign-on)?
- **Required**: How is user access to resources managed, and what role-based access controls (RBAC) are implemented?
- **Optional**: How are session management and timeout policies structured?

### 6. **Data Protection**
- **Required**: How is sensitive data classified, and what specific controls are in place to protect it throughout its lifecycle?
- **Required**: What measures ensure data is encrypted at rest, in transit, and during processing?
- **Optional**: Are there mechanisms for data masking or tokenization in place to safeguard sensitive information?

### 7. **Secure Development Practices**
- **Required**: How are third-party libraries and dependencies evaluated for security before being integrated into the application?
- **Required**: Are secure coding practices enforced through automated tools, and what is the process for reviewing exceptions?
- **Optional**: What mechanisms are in place for regular security training for developers?

### 8. **Incident Response and Logging**
- **Required**: What logging and monitoring practices are implemented in the design? How is log data protected?
- **Required**: How are security incidents identified, reported, and managed within the architecture?
- **Optional**: Are there processes for regular audits of logs and monitoring alerts?

### 9. **Integration and API Security**
- **Required**: What security controls are implemented for APIs, such as rate limiting, throttling, and input validation?
- **Required**: How are third-party integrations secured, and what measures are in place to monitor their security posture?
- **Optional**: Are there guidelines for secure communication protocols when integrating with external services?

### 10. **Compliance and Regulatory Considerations**
- **Required**: How is compliance with relevant regulations (e.g., GDPR, CCPA) ensured in the architecture?
- **Required**: What mechanisms are in place to demonstrate compliance during audits?
- **Optional**: Are there specific controls for handling personally identifiable information (PII)?

## Artifacts to Provide

During the **Design Review and Threat Modeling** phase, the following artifacts must be provided to the AppSec team to ensure a comprehensive review of the application design and the identification of security risks:

### ✅ **1. Architecture Diagram**
   - **Required**: A high-level diagram illustrating the system architecture, including components, data flows, and interactions between services.  
   **Responsible Party**: Development Team & System Architect

### ✅ **2. Threat Model Document**
   - **Required**: A document detailing identified threats, vulnerabilities, and potential mitigations associated with the design, including a list of threats and the corresponding risk assessment.  
   **Responsible Party**: AppSec Team & Development Team

### ✅ **3. Security Control Plan**
   - **Required**: A plan outlining the security controls implemented to mitigate identified threats, including details about authentication, authorization, data protection, and incident response strategies.  
   **Responsible Party**: Security Architect & AppSec Team

### ✅ **4. Risk Assessment Report**
   - **Required**: A report assessing the risks identified during the threat modeling process, including the likelihood and impact of each risk.  
   **Responsible Party**: Risk Management Team & AppSec Team

### ✅ **5. Design Review Checklist**
   - **Required**: A checklist to ensure all security considerations have been addressed in the design, including compliance requirements, secure design principles, and identified risks.  
   **Responsible Party**: AppSec Team & Development Team

## Conclusion

The **Design Review and Threat Modeling** phase is essential for identifying and mitigating potential security risks in the application design. By conducting thorough reviews and implementing security controls early in the development process, teams can significantly reduce the likelihood of vulnerabilities being introduced during implementation. By the end of this phase, developers and security teams should have a clear understanding of the application's security posture and the measures necessary to address any identified risks.

[Go to Previous page](./Phase1-Requirements.md) | [Go to next page](./Phase3-Development.md)