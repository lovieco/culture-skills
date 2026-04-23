# Culture Skills Library

**Open-source culture skills for humans and AI agents.**

Culture skills are modular, self-contained packages that encode how an organization works — its values, communication norms, decision frameworks, and operational philosophies. Unlike a static handbook, each skill is designed to be actionable by both humans and AI agents.

## Skills

| Skill | Description |
|-------|-------------|
| **[lovie-culture-os](./lovie-culture-os)** | Master index — LEET-AI values framework, 30 operating principles, and routing guide to all micro-skills |
| **[lovie-manager-of-one](./lovie-manager-of-one)** | Self-management, time-boxing, the 6-step system, and autonomy framework |
| **[lovie-ai-first](./lovie-ai-first)** | AI integration in daily workflows, prompting excellence, and the 4 AI agent archetypes |
| **[lovie-async-first](./lovie-async-first)** | 3x Rule, Slack norms, non-linear workday, and energy mapping |
| **[lovie-artifact-first](./lovie-artifact-first)** | Three golden rules of documentation, meeting hygiene, and the Osmosis Signal |
| **[lovie-culture-hiring](./lovie-culture-hiring)** | 5-stage hiring process, LEET-AI scoring rubric, and candidate archetypes |
| **[lovie-leadership-collaboration](./lovie-leadership-collaboration)** | Architect/Coach/Editor leadership model, DACI framework, and team agreements |
| **[lovie-employment-wellbeing](./lovie-employment-wellbeing)** | Fractional/advisory employment models, Rest Ethic, and sustainable high performance |

## Architecture

The library uses a **micro-skills architecture**: one master index skill (`lovie-culture-os`) provides the values framework and routes to seven specialized micro-skills. Each micro-skill is self-contained — you can read and use it independently without the others.

```
lovie-culture-os (master index)
├── lovie-manager-of-one
├── lovie-ai-first
├── lovie-async-first
├── lovie-artifact-first
├── lovie-culture-hiring
├── lovie-leadership-collaboration
└── lovie-employment-wellbeing
```

## Usage

### For HR and Culture Teams

Each skill is a standalone Markdown file (`SKILL.md`) that can be used directly for onboarding, training, hiring, and team alignment. Download individual skills or fork the entire repository to customize for your organization.

### For AI Agents

Feed these skills to your AI agents so they understand your culture, values, and operating norms. Each skill includes explicit agent behavioral instructions in its "For AI Agents" section. Compatible with any AI agent framework that supports Markdown-based skill files.

## Getting Started

1. **Browse** — Read the skills directly on GitHub
2. **Download** — Clone or download individual `SKILL.md` files
3. **Fork** — Fork this repository to customize for your organization
4. **Train** — Feed skills to your AI agents as context

## Learn More

Visit [lovie.co/culture/skills](https://www.lovie.co/culture/skills) for the full interactive experience.

## License

This work is shared openly as part of the [Future of Work 2.0](https://www.lovie.co/culture) movement.
