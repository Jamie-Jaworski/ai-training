# AI Training Series — Curriculum

**First Hawaiian Bank | Cybersecurity Team**

---

## Program Overview

This training series equips the First Hawaiian Bank cybersecurity and technology team with practical, hands-on knowledge of Generative AI, Agentic AI, AI Security, and emerging AI productivity tools.

The program is organized into four tracks, each covering a distinct domain. Recommended delivery order: Track 1 → Track 2 → Track 3 → Track 4.

---

## 🤖 Track 1: Generative AI Foundations

### Session 1.1 — How LLMs Work

- How LLMs work (transformers, tokens, embeddings)
- Attention mechanisms and why they enable language understanding
- Tokenization — how text becomes numbers the model can process
- Embeddings and semantic similarity: meaning encoded as vectors
- Context windows: why size and position of information matter
- Temperature and sampling — why the same prompt yields different answers

---

### Session 1.2 — Prompt Engineering Best Practices

- Prompt engineering best practices
- Anatomy of an effective prompt: context, instruction, format, and constraints
- Zero-shot vs. few-shot prompting — when to include examples
- Chain-of-thought and step-by-step reasoning techniques
- Using XML tags and structured output formats for consistent results
- Role framing and system prompts: shaping model behavior upstream
- Building reusable prompt templates for common security and compliance tasks

---

### Session 1.3 — Evaluating GenAI Outputs

- Evaluating GenAI outputs — when to trust, verify, or reject
- The trust spectrum: when AI is a drafting assistant vs. a subject-matter authority
- Common failure modes: hallucination, sycophancy, outdated knowledge
- Subtle errors in security and compliance contexts — where mistakes cost most
- Verification strategies: cross-referencing, source tracing, structured critique
- High-stakes domains requiring extra scrutiny: legal, security, financial advice
- Building team norms around AI output review and escalation

---

## 🦾 Track 2: Agentic AI

### Session 2.1 — What Makes AI Agentic

- What makes an AI "agentic" — tools, memory, planning, and multi-step reasoning
- The four pillars: Tools, Memory, Planning, and Multi-Step Reasoning
- Tool use: how models call APIs, execute code, search the web, and read files
- Memory types: in-context, external databases, and episodic memory patterns
- Planning patterns: ReAct, chain-of-thought, tree-of-thought
- Human-in-the-loop: when to require approval vs. allow full autonomy
- Failure modes: loops, hallucinated tool calls, permission escalation

---

### Session 2.2 — Agentic AI Architectures

- Agentic AI architectures
- Single-agent loops vs. multi-agent orchestration
- Parallel vs. sequential agent workflows — when each is appropriate
- Orchestrator–subagent patterns and delegation
- Banking use cases: document review automation, compliance monitoring, ticket triage
- Evaluation criteria: cost, latency, accuracy, auditability, and explainability
- Design patterns for regulated environments: audit trails and rollback capabilities

---

### Session 2.3 — MCP and Tool Integration Ecosystems

- MCP (Model Context Protocol) and tool integration ecosystems
- What the Model Context Protocol (MCP) is and why it matters
- Standardizing tool access: how MCP eliminates custom integrations
- Available connectors: Slack, Jira, Google Drive, Notion, Miro, and more
- Authentication and authorization: OAuth, scopes, and credential handling
- Security model for MCP: what data is exposed and to whom
- Governance considerations for FHB's environment
- Hands-on lab: configuring and testing an MCP connector

---

## 🔒 Track 3: AI Security

### Session 3.1 — Threat Modeling for AI Systems (OWASP LLM Top 10)

- Threat modeling for AI systems (OWASP LLM Top 10)
- OWASP LLM Top 10 walkthrough with banking-specific scenarios
- LLM01: Prompt Injection — LLM02: Insecure Output Handling — LLM03: Training Data Poisoning
- LLM04: Model Denial of Service — LLM05: Supply Chain Vulnerabilities
- LLM06: Sensitive Information Disclosure — LLM07–10: Authorization and Plugin risks
- STRIDE threat modeling adapted for LLM applications
- Attack surface mapping: user inputs, APIs, integrations, and training pipelines
- Lab: threat model a hypothetical AI deployment at FHB

---

### Session 3.2 — Prompt Injection Attacks

- Prompt injection attacks — direct and indirect
- Direct injection: user manipulates the model through conversation input
- Indirect injection: malicious content in documents, emails, or web pages hijacks agent actions
- The "confused deputy" problem in agentic systems
- Real-world examples from production deployments
- Defensive patterns: input sanitization, instruction hierarchy, output validation
- Lab: identify and exploit injection vulnerabilities in a demo application

---

### Session 3.3 — Data Leakage and Training Data Poisoning Risks

- Data leakage and training data poisoning risks
- How LLMs can surface sensitive training data through targeted prompting
- Data classification requirements: what can and cannot be sent to AI APIs
- Training data poisoning: how adversaries corrupt model behavior at scale
- Supply chain risks: third-party models, fine-tuning providers, and API dependencies
- Vendor risk in AI: evaluating model providers for data handling and security
- Data governance policy requirements for AI deployments at FHB

---

### Session 3.4 — AI Governance Frameworks

- AI governance frameworks (NIST AI RMF, ISO/IEC 42001)
- NIST AI Risk Management Framework: Govern, Map, Measure, Manage functions
- ISO/IEC 42001 AI Management System — key requirements and applicability
- Regulatory landscape: OCC guidance, FFIEC expectations, emerging state laws
- Model Risk Management (SR 11-7) and its applicability to GenAI systems
- Acceptable use policies: drafting and enforcing them at FHB
- Shadow AI: how employees use unauthorized tools and how to manage it

---

## 🛠️ Track 4: Cool Tools

### Session 4.1 — Claude Code

**Using Claude Code for Software Development**

- Code generation: scaffolding, boilerplate, and rapid prototyping
- Refactoring, debugging, and code explanation
- Writing tests and documentation with AI assistance
- IDE integration and workflow best practices
- When to rely on AI vs. require human code review

**Using Claude Code for Security Assessments**

- Automated code security review: OWASP Top 10 vulnerability patterns
- Threat modeling from code: data flow diagrams and attack surface analysis
- Security control validation: authentication, authorization, input handling
- Generating security findings reports and remediation guidance
- Lab: security assessment on a sample application

---

### Session 4.2 — Claude Cowork

**Automating Day-to-Day Security Tasks**

- Alert summarization: turning SIEM noise into actionable triage summaries
- Policy document drafting: generating and updating security policies from frameworks
- Ticket management: enriching, categorizing, and drafting responses to security tickets
- Building repeatable AI-powered task pipelines

**Using Projects to Maintain Context Across Long-Running Work**

- What Claude Projects are and how context persists across sessions
- Setting up a Project for an ongoing security initiative
- Attaching documents, policies, and reference materials to a Project
- Best practices for long-running agentic work

---

### Session 4.3 — Claude.ai and Prompt Workflows

**Building Reusable Skills for Recurring Security Tasks**

- What Skills are in Claude's ecosystem and how to author them
- Creating Skills for recurring workflows: vendor assessments, risk summaries, policy reviews
- Sharing and governing Skills across the team

**Deep Research Workflows**

- Vendor security assessments: structuring multi-source research with Claude
- Regulatory research: staying current on AI and cybersecurity guidance
- Threat intelligence gathering: synthesizing threat actor profiles and TTPs
- Lab: conduct a vendor security assessment using Claude's deep research capabilities

---

### Session 4.4 — MCP Connectors and Integrations

**Connecting Claude to External Tools**

- Overview of available MCP connectors: Slack, Jira, Google Drive, Notion, Miro
- Authentication and authorization: how MCP handles credentials securely
- Demo: Claude reading a Jira ticket queue and drafting response summaries
- Demo: Claude searching Google Drive and synthesizing findings

**Building Lightweight AI-Powered Workflows**

- Designing multi-tool workflows: connecting inputs, processing, and outputs
- Practical example: automated daily security briefing pulling from Slack, Jira, and threat feeds
- Governance and risk considerations: which integrations are appropriate for FHB
- Lab: design and prototype a workflow using two or more MCP connectors

---
