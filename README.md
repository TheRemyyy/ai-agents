<div align="center">

# Elite AI Agents

**Professional System Prompts That Actually Work**

[![Agents](https://img.shields.io/badge/Agents-5-blueviolet?style=flat-square)](/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

*Crafted prompts that turn generic AI into elite specialists.*

[Agents](#agents) • [Usage](#usage) • [Principles](#core-principles)

</div>

---

## Overview

Elite AI Agents is a collection of battle-tested system prompts that transform AI assistants into specialized professionals. Unlike generic prompts that produce "AI slop", these agents are engineered with strict protocols for quality, accuracy, and completeness.

### Key Features

- **🎯 Zero-Placeholder Policy** — No `// TODO` comments. Complete, production-ready implementations only.
- **🛡️ Anti-Hallucination** — Strict verification before action. When uncertain, agents ask instead of guessing.
- **🧠 Domain Expertise** — Deep specialization in software, security, DevOps, design, and data science.
- **🌍 Language Adaptation** — Automatically responds in your language (English, Czech, etc.).
- **⚡ High Thinking Mode** — Plans before executing. Breaks down complex tasks into atomic steps.
- **📦 Self-Contained Output** — Generated code compiles without missing dependencies.

## Agents

| Agent | Role | Archetype | Specialty |
|-------|------|-----------|-----------|
| **Aether** | Software Architect | ♍♎ | Full-stack, modern tech stacks, security-first |
| **Sentinel** | Security Specialist | ♏ | Pentesting, crypto, anti-RE, code review |
| **Nexus** | DevOps Engineer | ♒ | CI/CD, Kubernetes, IaC, cloud |
| **Prism** | UI/UX Designer | ♎♓ | Modern design, accessibility, design systems |
| **Oracle** | Data Scientist | ♑ | ML pipelines, statistics, visualization |

### 🏛️ Aether — Software Architect

Elite architect combining analytical precision (Virgo ♍) with aesthetic harmony (Libra ♎).

```
Specialization:
├── Full-stack application architecture
├── Production-grade code with zero shortcuts
├── Modern stacks (TypeScript, React, Tailwind)
├── Security-first development (SQLi/XSS prevention)
└── STEALTH mode for security-critical code
```

### 🛡️ Sentinel — Security Specialist

Cybersecurity expert with paranoia as a core feature.

```
Specialization:
├── Penetration testing methodology
├── Secure code review & static analysis
├── Cryptography (AES-256-GCM, Argon2, proper standards)
├── Anti-reverse engineering techniques
└── No toy-crypto — real security only
```

### ⚙️ Nexus — DevOps Engineer

Infrastructure and automation specialist for scalable systems.

```
Specialization:
├── CI/CD (GitHub Actions, GitLab CI, Jenkins)
├── Container orchestration (Docker, Kubernetes)
├── Cloud infrastructure (AWS, GCP, Azure)
├── Infrastructure as Code (Terraform, Ansible)
└── Cost optimization & disaster recovery
```

### 🎨 Prism — UI/UX Designer

Creative designer focused on beautiful, functional interfaces.

```
Specialization:
├── Modern UI design (NO Bootstrap defaults)
├── User experience optimization
├── Design systems & tokens
├── Accessibility (WCAG 2.1 AA)
└── No gratuitous glassmorphism
```

### 📊 Oracle — Data Scientist

Data analysis and machine learning specialist.

```
Specialization:
├── Statistical analysis & hypothesis testing
├── Machine learning pipelines (training → production)
├── Data visualization & storytelling
├── Business intelligence
└── Skeptical of spurious correlations
```

## <a id="usage"></a>📦 Usage

### With Claude/GPT/Gemini

1. Copy the agent prompt from `agents/[name].md`
2. Paste as system prompt or at conversation start
3. The agent responds in your language automatically

### Quick Selection Guide

| Task | Agent | Why |
|------|-------|-----|
| Building full-stack apps | **Aether** | Architecture + clean code |
| Security audit/pentesting | **Sentinel** | Offensive + defensive security |
| CI/CD & infrastructure | **Nexus** | Automation + cloud expertise |
| UI/UX design work | **Prism** | Aesthetics + usability |
| Data analysis & ML | **Oracle** | Statistics + production ML |

## <a id="core-principles"></a>🧠 Core Principles

All agents share these core behaviors:

### High Thinking Mode

```
Never generate output without a PLAN.
Before writing a single line of code, break down the task into atoms.
Look for edge cases that could occur.
```

### Anti-Hallucination Protocol

```
The 1% Uncertainty Rule:
If 99% sure but missing 1% — DON'T GUESS. STOP. ASK.

Never use libraries or methods without 100% certainty they exist.
```

### Zero-Placeholder Policy

```
FORBIDDEN:
  - "// TODO: Implement logic here"
  - "// rest of the code is similar"
  - "// add your implementation"

Complete implementation or nothing.
```

### Self-Contained Output

```
Generated code must be compilable/runnable without needing
to add external utilities not mentioned in the response.
```

## Project Structure

```
ai-agents/
├── README.md              # This file
├── agents/
│   ├── aether.md          # Software Architect prompt
│   ├── sentinel.md        # Security Specialist prompt
│   ├── nexus.md           # DevOps Engineer prompt
│   ├── prism.md           # UI/UX Designer prompt
│   └── oracle.md          # Data Scientist prompt
└── LICENSE
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
<sub>Built with 🧠 by TheRemyyy</sub>
</div>
