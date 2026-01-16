# 🏢 Enterprise Agents - Starter Kit

**Track**: Battle #3 - Enterprise Agents with M365 Agents Toolkit  
**Date**: Friday, February 19, 2026 - 8am Pacific Time

Welcome to the Enterprise Agents track! In this challenge, you will build intelligent agents that extend **Microsoft 365 Copilot** to address real-world enterprise scenarios. Your goal is to create agents that seamlessly integrate with Microsoft 365 workloads, leveraging the power of AI to automate tasks, enhance productivity, and deliver exceptional user experiences within the enterprise ecosystem.

---

## 💡 Project Ideas

In this track, we encourage you to create agents that extend **Microsoft 365 Copilot** using one of the following development approaches:

### Development Approaches

1. **Microsoft 365 Agents Toolkit (ATK) + Visual Studio Code** - Build **Declarative Agents** using the ATK extension in VS Code. This approach allows you to define agent capabilities, actions, and behaviors through declarative configurations, enabling rapid development and iteration of enterprise-grade agents.

2. **Copilot Studio** - Leverage Microsoft Copilot Studio to create powerful agents with a low-code/no-code experience. Copilot Studio provides a visual designer for building conversational agents that can be easily extended and customized to meet specific business needs.

### Real-World Enterprise Scenarios

If you like, take inspiration from the following real-world enterprise scenarios to guide your project:

- **Human Resources (HR) Agent**: Build an agent that helps employees navigate HR policies, submit time-off requests, access benefits information, onboard new hires, or manage performance reviews. The agent could integrate with HR systems to provide personalized responses and automate routine HR tasks.

- **Research & Development (R&D) Agent**: Create an agent that assists R&D teams in accessing research documentation, managing intellectual property, tracking project milestones, or collaborating on innovation initiatives. The agent could help researchers find relevant prior work, summarize technical documents, or coordinate cross-functional teams.

- **Supply Chain Management Agent**: Develop an agent that provides visibility into supply chain operations, tracks inventory levels, monitors supplier performance, or predicts potential disruptions. The agent could help procurement teams make data-driven decisions and optimize logistics operations.

- **Finance & Accounting Agent**: Design an agent that assists with expense reporting, budget tracking, financial forecasting, or compliance reporting. The agent could automate data extraction from invoices, provide spending insights, or alert stakeholders to anomalies.

- **IT Helpdesk Agent**: Build an agent that handles IT support tickets, troubleshoots common issues, guides users through self-service resolutions, or escalates complex problems to human agents. The agent could integrate with IT service management systems to provide contextual assistance.

- **Legal & Compliance Agent**: Create an agent that helps legal teams review contracts, identify compliance risks, track regulatory changes, or manage legal document workflows. The agent could leverage AI to extract key terms and flag potential issues.

- **Sales Enablement Agent**: Develop an agent that provides sales teams with real-time access to product information, competitive intelligence, customer insights, or sales playbooks. The agent could help prepare for meetings and track deal progress.

Feel free to combine multiple scenarios or create entirely new use cases that address specific challenges within your organization or industry.

---

## 🚀 Quick Start

Get started quickly by exploring the following resources that provide step-by-step guidance for building enterprise agents:

### Copilot Dev Camp

The **Copilot Dev Camp** is your one-stop destination for learning how to build agents that extend Microsoft 365 Copilot. Access comprehensive tutorials, hands-on labs, and sample code to accelerate your development journey.

🔗 **Main Portal**: [https://aka.ms/copilotdevcamp](https://aka.ms/copilotdevcamp)

### Building with Copilot Studio

Learn how to create powerful agents using Microsoft Copilot Studio's visual designer and low-code capabilities:

🔗 **Copilot Studio Guide**: [https://microsoft.github.io/copilot-camp/pages/make/copilot-studio/](https://microsoft.github.io/copilot-camp/pages/make/copilot-studio/)

### Extending Microsoft 365 Copilot

Discover how to extend Microsoft 365 Copilot with custom agents, plugins, and connectors:

🔗 **Extend M365 Copilot**: [https://microsoft.github.io/copilot-camp/pages/extend-m365-copilot/](https://microsoft.github.io/copilot-camp/pages/extend-m365-copilot/)

### Agent Academy

The **Agent Academy** provides structured learning paths and expert-led training to help you master agent creation with Microsoft Copilot Studio. Whether you're new to building agents or looking to enhance your skills, Agent Academy offers curated content to guide you through the entire development lifecycle in Copilot Studio.

🔗 **Agent Academy**: [https://aka.ms/agentacademy](https://aka.ms/agentacademy)

### Getting Started Checklist

1. ✅ Visit the Copilot Dev Camp portal and review the available learning paths
2. ✅ Set up your development environment (VS Code + ATK or Copilot Studio)
3. ✅ Explore the sample projects and templates provided in the documentation
4. ✅ Identify your target enterprise scenario and define your agent's capabilities
5. ✅ Start building and iterating on your solution

---

## 🛡️ Security & Best Practices

Security is paramount when building enterprise agents that handle sensitive organizational data and integrate with Microsoft 365 services. When writing custom code, follow these guidelines to ensure your solution meets enterprise security standards:

### Microsoft 365 Security Integration

- **Microsoft Entra ID (formerly Azure Active Directory)**: Your agent **must** leverage Microsoft Entra ID for user authentication and authorization. This ensures that users are properly authenticated before accessing agent capabilities and that authorization policies are enforced consistently across the enterprise.

- **User Authentication**: Implement proper authentication flows that require users to sign in with their organizational credentials. Use OAuth 2.0 and OpenID Connect protocols to securely authenticate users and obtain access tokens for downstream API calls.

- **Authorization & Permissions**: Define granular permissions for your agent based on the principle of least privilege. Ensure that users can only access data and perform actions that are appropriate for their role and responsibilities within the organization.

- **Conditional Access Policies**: Design your agent to respect organizational Conditional Access policies, including multi-factor authentication (MFA) requirements, device compliance checks, and location-based access controls.

### Best Practices

- **Data Protection**: Handle sensitive data responsibly by implementing proper data encryption, avoiding unnecessary data storage, and following data residency requirements.

- **Audit & Logging**: Implement comprehensive logging to track agent interactions and support security audits. Ensure logs capture relevant metadata without exposing sensitive information.

- **Secure Development Lifecycle**: When writing code, follow secure coding practices throughout development, including input validation, output encoding, and protection against common vulnerabilities.

- **Token Management**: Store and handle access tokens securely. Never expose tokens in logs, URLs, or client-side code.

---

## 📋 Requirements & Evaluation

Your solution will be evaluated based on the following requirements and criteria. Meeting these requirements will position your project for success in the competition:

### Core Requirements

#### 1. External MCP Server Integration (Required)

Your agent **must** integrate with an external **Model Context Protocol (MCP) server** to read and write specific content. The MCP server acts as a bridge between your agent and external data sources or services, enabling your agent to:

- **Read Operations**: Retrieve data from external systems, databases, or APIs through the MCP server
- **Write Operations**: Create, update, or modify content in external systems through the MCP server

This requirement ensures that your agent demonstrates real-world integration capabilities and can interact with enterprise systems beyond the Microsoft 365 ecosystem.

#### 2. OAuth Security for MCP Server (Highly Valued)

Implementing **OAuth-based authentication and authorization** when consuming the MCP server will be **highly appreciated** and will positively impact your evaluation score. Secure MCP server integration should include:

- Proper OAuth 2.0 token acquisition and management
- Secure storage and handling of client credentials
- Token refresh mechanisms to maintain continuous access
- Proper error handling for authentication failures

### Bonus Criteria

#### 3. Adaptive Cards for UI/UX (Plus)

Using **Adaptive Cards** for rendering your agent's user interface and user experience will be considered a **plus** in your solution. Adaptive Cards provide:

- Rich, interactive card-based interfaces that render natively across Microsoft 365 applications
- Consistent user experiences across different platforms and devices
- Support for user input, actions, and dynamic content updates
- Accessibility features built into the card framework

Leverage Adaptive Cards to create engaging, intuitive interactions that enhance user productivity.

#### 4. Connected Agents Architecture (Higher Rating)

A solution that implements **connected agents** (multi-agent architecture) will be **rated higher** than single-agent architectures. Connected agents demonstrate:

- **Orchestration**: Multiple specialized agents working together to accomplish complex tasks
- **Collaboration**: Agents that can delegate work, share context, and coordinate responses
- **Scalability**: An architecture that can be extended with additional agents as needs evolve
- **Specialization**: Each agent focuses on specific capabilities, leading to better overall performance

Consider designing your solution with multiple agents that collaborate to address different aspects of your enterprise scenario.

### Evaluation Summary

| Criterion | Impact |
|-----------|--------|
| External MCP Server Integration (Read/Write) | **Required** |
| OAuth Security for MCP Server | **Highly Valued** |
| Adaptive Cards for UI/UX | **Plus** |
| Connected Agents Architecture | **Higher Rating** |

---

## 📚 Resources

Explore the following resources to deepen your knowledge and accelerate your development:

### Copilot Dev Camp

Your comprehensive learning destination for building agents that extend Microsoft 365 Copilot:

🔗 [https://aka.ms/copilotdevcamp](https://aka.ms/copilotdevcamp)

### Agent Academy

Structured learning paths and expert-led training for mastering agent development with Microsoft Copilot Studio:

🔗 [https://aka.ms/agentacademy](https://aka.ms/agentacademy)

### Microsoft Learn

Access official Microsoft documentation, tutorials, and learning paths:

- **Microsoft 365 Copilot Documentation**: [https://learn.microsoft.com/microsoft-365-copilot/](https://learn.microsoft.com/microsoft-365-copilot/)
- **Copilot Studio Documentation**: [https://learn.microsoft.com/microsoft-copilot-studio/](https://learn.microsoft.com/microsoft-copilot-studio/)
- **Microsoft Entra ID Documentation**: [https://learn.microsoft.com/entra/identity/](https://learn.microsoft.com/entra/identity/)
- **Adaptive Cards Documentation**: [https://learn.microsoft.com/adaptive-cards/](https://learn.microsoft.com/adaptive-cards/)
- **Model Context Protocol (MCP)**: [https://learn.microsoft.com/azure/ai-services/agents/](https://learn.microsoft.com/azure/ai-services/agents/)

### Additional Resources

- **Microsoft 365 Agents Toolkit for VS Code**: [https://learn.microsoft.com/en-us/microsoft-365/developer/overview-m365-agents-toolkit](https://learn.microsoft.com/en-us/microsoft-365/developer/overview-m365-agents-toolkit)
- **Microsoft Graph API**: [https://learn.microsoft.com/graph/](https://learn.microsoft.com/graph/)
- **Microsoft 365 Developer Program**: [https://developer.microsoft.com/microsoft-365/dev-program](https://developer.microsoft.com/microsoft-365/dev-program)

---

Questions? Join [Discord](https://aka.ms/agentsleague/discord) #enterprise-agents channel
