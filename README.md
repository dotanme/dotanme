### Hi, I'm Dotan 👋

Full-stack .NET engineer in Israel who builds **AI agent systems** that real teams use every day.

At [Issta](https://www.issta.co.il) I'm one of three engineers building the company's AI agents platform, which departments across the organization plug into to automate their work, and I designed and built the company's first MCP server.

#### What I'm working on

- **AI agents platform:** multi-agent orchestration, RAG over team knowledge bases, memory, and agents on web chat, voice, SMS/WhatsApp and email. I led the visual workflow engine (drag-and-drop designer, triggers, human-in-the-loop steps, hundreds of runs a day), and I own its infrastructure and production operations: LLM tracing, token tracking and cross-region model failover.
- **MCP + REST gateway:** a multi-tenant gateway that lets AI assistants and outside partners search travel products, manage orders and pull BI data. MCP and REST share one handler layer, behind per-tenant, fail-secure tool and route allow-lists.
- **AI-first engineering:** most of that code was written by LLMs (Claude Code, GitHub Copilot), with my team steering them through specs, project docs written for the models, high test coverage and E2E checks on every deploy. I also built agentic GitHub workflows for daily change reports, vulnerability-fix PRs and release changelogs.
- **[issue-triage-agent](https://github.com/dotanme/issue-triage-agent)** (side project, in progress): a repo-agnostic agent that classifies GitHub issues, finds duplicates and answers from the docs, with offline evals in CI.

Before the AI work I spent three years building backend services for travel bookings: a multi-tenant booking API (Clean Architecture, CQRS), an event-sourced order-processing service with sagas, and a credit card payment integration.

#### Tech

**Languages & frameworks:** C#, .NET 10, ASP.NET Core, JavaScript  
**AI:** Microsoft Agent Framework, Microsoft.Extensions.AI, Azure OpenAI, Azure AI Search, MCP, A2A  
**Data & messaging:** SQL Server, PostgreSQL (Marten), Redis, MassTransit, Azure Service Bus  
**Cloud & delivery:** Azure, Docker, GitHub Actions, Azure DevOps  
**Testing:** xUnit, NUnit, Playwright

#### Find me

[LinkedIn](https://www.linkedin.com/in/dotanm)
