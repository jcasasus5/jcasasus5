# Joaquín Casasús

**AI Engineer · Generative & Agentic AI · Full-stack product development**

I build AI systems and the applications around them: agents, APIs, user interfaces, data models and deployment workflows. Alongside my professional work, I develop personal products that turn practical problems and interests into working software.

[LinkedIn](https://www.linkedin.com/in/joaquin-casasus) · [Public repositories](https://github.com/jcasasus5?tab=repositories)

## Personal projects at a glance

Some projects have public source code; others are developed in private repositories. The descriptions below explain what each project does, my contribution and who I built it with.

| Project | What it does | My involvement | Source |
| --- | --- | --- | --- |
| [iFlySEO](https://iflyseo.com) | AI content generation, SEO workflows and scheduled publishing | Built with [Javier Lucía Marco](https://github.com/JLM-2000) | Private |
| iFlyWeb | AI-assisted website creation, editing and publishing | Personal development within the iFlySEO ecosystem | Private |
| Arista | Marketplace connecting clients with professional mountain guides | Built with [Javier Lucía Marco](https://github.com/JLM-2000) | Private |
| [Climber Indoor Cycling](https://github.com/jcasasus5/cycling-app) | Browser-based indoor training using real climbing profiles and smart trainers | Personal project, from application to deployment | Public |
| Tutoría | Joint project maintained in a separate GitHub organization | Built with [Manuel San Román García](https://github.com/manuelsanroman) | Organization repository |
| [World Cup 2026 Prediction Pool](https://github.com/jcasasus5/porra-mundial-2026) | Match predictions, automated results and shared rankings | Personal project, from application to deployment | Public |
| [Arturito Casasus](https://github.com/arturitoCasasus) | My personal OpenClaw AI agent, with its own GitHub account | Personal agent setup and ongoing development | Public profile |

## iFlySEO — AI content and publishing

Built with [Javier Lucía Marco](https://github.com/JLM-2000), iFlySEO helps customers generate SEO content, manage their websites and schedule publication. The product combines a backend and background workers with a WordPress plugin, an embeddable browser SDK and a commercial account portal.

My contributions include the hosted panel and portal experience, administration tools, account and billing workflows, and fixes to scheduling and publishing behavior. I have also worked on an admin assistant with scoped, read-only account queries and on deployment isolation and reliability improvements.

This project brings together the parts of AI product development that interest me most: generation workflows, usable interfaces, account boundaries and visibility into usage and costs.

**Stack:** Python · FastAPI · Celery · PostgreSQL · Redis · PHP / WordPress · JavaScript · Next.js · TypeScript · Docker

[Product website](https://iflyseo.com)

## iFlyWeb — guided website creation

A website builder I develop within the iFlySEO ecosystem. It turns a business brief into a structured, multi-page website that users can edit through blocks or natural-language instructions.

My work covers the generation flow, reusable templates, responsive previews, image uploads, editing and publishing. Draft revisions and published versions are separate, and the builder uses a shared renderer for editing and public pages. The service also includes account access, signed integrations, custom-domain verification and subscription-based hosting controls.

**Stack:** Next.js · React · TypeScript · PostgreSQL · LLM APIs · Docker

## Arista — mountain guide marketplace

Built with [Javier Lucía Marco](https://github.com/JLM-2000), Arista connects people with professional mountain guides. The application includes activity discovery, maps, guide profiles, booking workflows and separate spaces for clients, guides and administrators.

My contributions include multilingual routes and interface copy, profile photos, messaging usability, application rebranding, database access hardening and dependency security fixes. I also work on the configuration and checks needed to maintain the application across environments.

**Stack:** Python · FastAPI · PostgreSQL / PostGIS · Next.js · TypeScript · MapLibre · Stripe Connect · Docker

## Climber Indoor Cycling — real climbs on a smart trainer

A personal project combining cycling with software and AI. Climber runs in the browser and connects to a compatible smart trainer through Web Bluetooth and FTMS. As the rider progresses through a route, the app sends the corresponding gradient to the trainer and records speed, cadence and power.

I built the route editor and training interface, Bluetooth integration, activity history and deployment workflow. Routes can be imported from elevation-profile images using a vision model, kept private or shared with other users. The application also implements Strava OAuth and activity uploads, plus TCX export.

**Stack:** Python · FastAPI · JavaScript · Web Bluetooth / FTMS · OpenAI Vision · Supabase · PostgreSQL · Vercel

[Source code](https://github.com/jcasasus5/cycling-app) · [Web app](https://cycling-app-xi.vercel.app)

## Tutoría — collaboration with Manuel San Román

A project I built with [Manuel San Román García](https://github.com/manuelsanroman), maintained in a separate GitHub organization. It is part of my personal project work beyond the repositories hosted on this account.

## World Cup 2026 Prediction Pool

A personal web application for running a World Cup prediction pool. Participants predict scores and the tournament winner; administrators manage entries, fixtures and results.

I built the participant and admin flows, scoring rules, rankings and automated result synchronization. Predictions close at kickoff and stay hidden from other participants until the match closes. Database access policies enforce user boundaries, while result corrections trigger score recalculation.

**Stack:** Next.js · React · TypeScript · Tailwind CSS · Supabase Auth · PostgreSQL · Vercel

[Source code](https://github.com/jcasasus5/porra-mundial-2026) · [Web app](https://porra-mundial-2026-topaz.vercel.app)

## Arturito Casasus — my personal OpenClaw agent

[Arturito](https://github.com/arturitoCasasus) is my personal AI agent built on OpenClaw, with its own GitHub identity. I use it to explore practical agent workflows for research, coding, automation, documentation and maintaining context between tasks.

This is my own agent configuration and ongoing experimentation on top of OpenClaw. Its separate account makes the agent's identity and activity visible alongside my own work.

[Arturito's GitHub profile](https://github.com/arturitoCasasus)

## Professional background

I work as an **AI Engineer at VASS**, developing generative and agentic AI solutions. My experience includes AI architecture projects for **Bankinter** and **Abante Asesores**, covering multi-tenant platforms, RAG pipelines, autonomous workflows and custom AI tools.

I hold a **Bachelor in Computer Science & Artificial Intelligence from IE University**.

- **AI:** LLM applications, agents, multi-agent systems, RAG, LangChain, LangGraph and MCP.
- **Application development:** Python, FastAPI, JavaScript, TypeScript, React and Next.js.
- **Data and infrastructure:** SQL, PostgreSQL, vector databases, Docker and CI/CD.
- **Cloud experience:** Azure, AWS and Google Cloud.

Outside of software, I enjoy skiing, cycling, teaching and traveling. Several of these projects started with a problem I wanted to solve myself.

Feel free to [connect with me on LinkedIn](https://www.linkedin.com/in/joaquin-casasus) to discuss AI engineering, product development or any of these projects.
