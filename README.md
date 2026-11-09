# Jason Wood

Senior backend engineer and senior development team member with 15+ years in .NET, Azure and cloud-native services.

## Day job

I work in a small development team for a fortune 1000 company and act as technical consultant to other departments, helping them move to the cloud and integrate services.

- **Cloud-native .NET**: I design, deploy and monitor C# / .NET microservices on Azure in production, with safer deployment practices and proper lifecycle management.
- **DevOps**: reusable GitHub Actions workflows and CI/CD pipelines that make rapid, repeatable releases the default.
- **AI adoption**: I help lead the integration of AI tools (Claude, Copilot, ChatGPT) and AI APIs into production software, and recommend the best practices our teams follow.
- **Mentoring and architecture**: code review, dependency injection, agile practice, and architectural decisions that other people can understand and maintain.

## On my own time

Personally, I'm building a community platform and sharpening my skills on the fast-moving front of AI agentic development.

![.NET](https://img.shields.io/badge/.NET-10_LTS-512BD4?logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-18-4169E1?logo=postgresql&logoColor=white)
![Modules](https://img.shields.io/badge/modules-25-555)
![ADRs](https://img.shields.io/badge/ADRs-110-555)

A pre-launch community and creator platform: social feeds, a multi-vendor marketplace, events, courses and real-time messaging, on a modular monolith with 25 feature modules.

- **Backend**: .NET 10, Clean Architecture with CQRS (MediatR), deployed as separate API and worker hosts.
- **Frontend**: Nx monorepo of Vite + React + TypeScript apps sharing a hand-written, Zod-validated API client, plus a Next.js public site.
- **Data and infra**: PostgreSQL with TimescaleDB, Redis in two durability classes, RabbitMQ with MassTransit, OpenSearch, Quartz, Docker, a CDN and edge-scripting layer, DigitalOcean.
- **Accessible by default**: WCAG-minded UI, checked with axe-core and eslint-plugin-jsx-a11y.

## Technology

**Languages and frameworks**

<img src="https://skillicons.dev/icons?i=cs,dotnet,ts,js,python,react,nextjs,nodejs,tailwind,vite" alt="C#, .NET, TypeScript, JavaScript, Python, React, Next.js, Node.js, Tailwind CSS, Vite" />

**Cloud, data and platform**

<img src="https://skillicons.dev/icons?i=azure,postgres,mysql,redis,rabbitmq,docker,nginx,linux,terraform" alt="Azure, PostgreSQL, MySQL, Redis, RabbitMQ, Docker, NGINX, Linux, Terraform and OpenTofu" />

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?logo=microsoftsqlserver&logoColor=white)
![Bunny.net](https://img.shields.io/badge/Bunny.net-FF8A00?logo=bunnydotnet&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?logo=digitalocean&logoColor=white)
![Azure Bicep](https://img.shields.io/badge/Azure_Bicep-0078D4?logo=microsoftazure&logoColor=white)

**DevOps and quality**

<img src="https://skillicons.dev/icons?i=githubactions,github,vitest,k6,prometheus,grafana" alt="GitHub Actions, GitHub, Vitest, k6, Prometheus, Grafana" />

![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D4?logo=azuredevops&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white)

**AI and accessibility**

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?logo=claude&logoColor=white)
![OpenAI Codex](https://img.shields.io/badge/Codex_CLI-412991?logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-555)
![WCAG](https://img.shields.io/badge/ADA_%2F_WCAG-axe--core_%2B_jsx--a11y-005A9C?logo=w3c&logoColor=white)

## Open source

- **[dotnet-agent-radar](https://github.com/jangolath/dotnet-agent-radar)**: a hand-reviewed shortlist of .NET, SQL Server
  and Azure AI-agent tooling (MCP servers, Roslyn, T-SQL linters), each with a use / watch / avoid verdict and the reason,
  kept fresh by a weekly check.
- **[lanqueue](https://github.com/jangolath/lanqueue)**: a .NET global tool that sends builds, tests and headless agent
  jobs to the idle machines on your own network over key-only SSH, routed by capability, with safe defaults enforced by
  tests. Built after one busy dev PC became the bottleneck for AI-assisted work.
- **[lanq-makeready](https://github.com/jangolath/lanq-makeready)**: lanqueue's companion. A read-only readiness check
  for an old PC (Windows, Linux or macOS) before it joins the pool: what is missing, what is too old, and what would
  break an overnight job, plus a ready-to-paste worker entry. No admin, no network, nothing installed.

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

## Earlier experience

<img src="https://skillicons.dev/icons?i=wordpress,php,mysql,angular,bootstrap,jquery,aws" alt="WordPress, PHP, MySQL, Angular, Bootstrap, jQuery, AWS" />

![VB.NET](https://img.shields.io/badge/VB.NET-512BD4?logo=dotnet&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?logo=salesforce&logoColor=white)
![Entity Framework](https://img.shields.io/badge/EF_%2F_nHibernate_%2F_OData-512BD4)
![WCF](https://img.shields.io/badge/WCF_%2F_ASP.NET_MVC_%2F_Web_API-512BD4)

I started out building WordPress and BuddyBoss plugins and multisite installs: media offloading to a CDN, gamification,
location search, theming. That work paid for the education that took me into enterprise .NET, distributed systems and
the engineering practices above.

Along the way: modernising legacy VB.NET and MVC applications to async C# on .NET Core, service-oriented work with WCF and
REST/OData APIs, AngularJS, Aurelia and React front-ends, SQL Server and Oracle back ends, and platform migrations in
financial services, healthcare and association software.
