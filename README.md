# Jason Wood

I build a large-scale community and creator platform, and I build it AI-first: agents and humans working together under strict review and test gates.

![.NET](https://img.shields.io/badge/.NET-10_LTS-512BD4?logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-18-4169E1?logo=postgresql&logoColor=white)
![Modules](https://img.shields.io/badge/modules-25-555)
![ADRs](https://img.shields.io/badge/ADRs-110-555)

<img src="https://skillicons.dev/icons?i=dotnet,cs,postgres,redis,rabbitmq,docker,react,ts,nextjs,nodejs,tailwind,vite,nginx,githubactions,linux" alt="Tech stack icons" />

## Currently building

A pre-launch community and creator platform: social feeds, a multi-vendor marketplace, events, courses and real-time messaging, on a modular monolith with 25 feature modules.

- **Backend**: .NET 10, Clean Architecture with CQRS (MediatR), deployed as separate API and worker hosts.
- **Frontend**: Nx monorepo of Vite + React + TypeScript apps sharing a hand-written, Zod-validated API client, plus a Next.js 16 public site.
- **Data and infra**: PostgreSQL with TimescaleDB, Redis in two durability classes, RabbitMQ with MassTransit, OpenSearch, Quartz, Docker, a CDN/edge layer, DigitalOcean.

## How we build

- **AI-first, human-gated**: AI agents draft, test and review code alongside engineers; independent review, triaged findings and automated gates decide what lands. The rules are written down so agents and people follow the same ones.
- **ADR-driven**: every architectural decision is a written record (110 so far), referenced from the code it governs.
- **Architecture tests**: module boundaries, data ownership and authorization coverage are enforced by reflection tests, not convention.
- **Layered testing**: architecture, unit and PostgreSQL-backed integration tests, happy and failure paths; a regression test must fail on the unfixed code first.
- **Warnings are errors**: .NET analyzers on; builds must be 0 warnings.
- **Privacy by design**: data minimisation, no card or government-ID data stored (provider-hosted tokenization only), per-module erasure and export handlers.
- **Scale posture**: cached reads, batched write-behind for high-volume writes, fail-closed money paths, clustered scheduled jobs.

## Interested in joining the team?

Experienced developers who are comfortable shipping with AI tooling, and who care about clear boundaries, written decisions and tests that mean something: .NET, PostgreSQL, React/TypeScript and DevOps all matter here. Get in touch: [LinkedIn](https://www.linkedin.com/in/jason-wood-52246a56)

## Early days

<img src="https://skillicons.dev/icons?i=wordpress,php,mysql" alt="WordPress, PHP, MySQL" />

I started out building WordPress and BuddyBoss plugins and multisite installs: media offloading to a CDN, gamification,
location search, theming. That work paid for the education that took me into enterprise .NET, distributed systems and
the engineering practices above.
