# Culture Skills Library

**Open-source culture skills for humans and AI agents.**

These folder names intentionally use company-neutral identifiers so teams can fork, adapt, and teach the skills inside their own organizations without making the library feel exclusive to any single company.

Culture skills are modular, self-contained packages that encode how an organization works — its values, communication norms, decision frameworks, and operational philosophies. Unlike a static handbook, each skill is designed to be actionable by both humans and AI agents.

## Skills

| Skill | Description |
|-------|-------------|
| **[culture-os](./culture-os)** | Master index — LEET-AI values framework, 30 operating principles, and routing guide to all micro-skills |
| **[manager-of-one](./manager-of-one)** | Self-management, time-boxing, the 6-step system, and autonomy framework |
| **[ai-first](./ai-first)** | AI integration in daily workflows, prompting excellence, and the 4 AI agent archetypes |
| **[async-first](./async-first)** | 3x Rule, Slack norms, non-linear workday, and energy mapping |
| **[artifact-first](./artifact-first)** | Three golden rules of documentation, meeting hygiene, and the Osmosis Signal |
| **[culture-hiring](./culture-hiring)** | 5-stage hiring process, LEET-AI scoring rubric, and candidate archetypes |
| **[leadership-collaboration](./leadership-collaboration)** | Architect/Coach/Editor leadership model, DACI framework, and team agreements |
| **[employment-wellbeing](./employment-wellbeing)** | Fractional/advisory employment models, Rest Ethic, and sustainable high performance |

## Architecture

The library uses a **micro-skills architecture**: one master index skill (`culture-os`) provides the values framework and routes to seven specialized micro-skills. Each micro-skill is self-contained — you can read and use it independently without the others.

```
culture-os (master index)
├── manager-of-one
├── ai-first
├── async-first
├── artifact-first
├── culture-hiring
├── leadership-collaboration
└── employment-wellbeing
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
