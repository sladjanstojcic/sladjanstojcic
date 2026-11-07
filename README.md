# Hi, I'm Sladjan 👋

**Full-Stack Engineer · AI-native workflow · Infrastructure & DevOps**

I build full-stack products in TypeScript, from the React UI down to the server it runs on. Every day I work with Claude Code and Codex in a multi-agent setup I designed myself: a written spec, then a plan, then agents that implement each task in their own git worktree, with a second model reviewing every change before it lands.

<a href="https://www.linkedin.com/in/sladjan-stojcic-b68063165/"><img alt="Open to full-time and contract work, remote US and EU" src="https://img.shields.io/badge/Open_to-Full--time_%26_Contract_%C2%B7_Remote_US%2FEU-2ea44f?style=flat-square"></a>
<a href="https://www.linkedin.com/in/sladjan-stojcic-b68063165/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Let's_talk-0A66C2?style=flat-square"></a>

## What I bring

- **Full-stack product work.** Next.js and React apps backed by Supabase/Postgres, SQLite or PocketBase: multi-tenant SaaS, internal dashboards, marketplace tooling and e-commerce.
- **Infrastructure I run myself.** Hetzner servers built with cloud-init and hardened (key-only SSH, fail2ban, firewalls), self-hosted apps on Coolify, a private Tailscale network, DNSSEC, backups I have test-restored, and bringing a dev server back from a Docker and memory-exhaustion outage.
- **AI-native engineering.** Guardrails that keep coding agents honest: hooks, strict type-checked lint, import boundaries, Playwright smoke tests and CI gates. I also write the working agreements my agents follow.

## Projects

- **[triage](https://github.com/sladjanstojcic/triage)**: one local dashboard for everything running on your Mac and remote hosts. It groups dev servers by project and shows ports, Docker containers, SSH tunnels, Tailscale and VPS resources. I built it for the mess that comes from several agents and terminals starting their own servers. React 19, Vite, TypeScript, Tailwind.

**In the works**

- **next-harness**: a Next.js starter with guardrails for building with Claude Code and Codex. A single `pnpm check` runs typed lint, import boundaries, dead-code checks, unit tests, the build and Playwright smoke tests, with matching git hooks, agent hooks and CI.
- **devco**: "Coolify for development". It gives every project and git worktree its own isolated environment on a dev server (ports, Supabase stacks, tunnels) and watches the server's health.
- **poirot**: a traceroute for web requests. It follows one request through DNS, TCP, TLS and HTTP and grades its security.

## Stack

<p>
<img alt="Build" src="https://img.shields.io/badge/BUILD-30363d?style=flat-square">
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
<img alt="React" src="https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white">
<img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white">
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">
<img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
<img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white">
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
<img alt="pnpm" src="https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white">
</p>

<p>
<img alt="Run" src="https://img.shields.io/badge/RUN-30363d?style=flat-square">
<img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img alt="Hetzner" src="https://img.shields.io/badge/Hetzner-D50C2D?style=flat-square&logo=hetzner&logoColor=white">
<img alt="Coolify" src="https://img.shields.io/badge/Coolify-6B16ED?style=flat-square&logo=coolify&logoColor=white">
<img alt="Tailscale" src="https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white">
<img alt="Caddy" src="https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white">
<img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
</p>

<p>
<img alt="AI" src="https://img.shields.io/badge/AI-30363d?style=flat-square">
<img alt="Claude Code" src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white">
<img alt="Codex" src="https://img.shields.io/badge/Codex-10A37F?style=flat-square">
<img alt="Anthropic SDK" src="https://img.shields.io/badge/Anthropic_SDK-191919?style=flat-square&logo=anthropic&logoColor=white">
<img alt="MCP" src="https://img.shields.io/badge/MCP-555555?style=flat-square">
</p>
