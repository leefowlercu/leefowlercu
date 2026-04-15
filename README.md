# Lee Fowler

I'm a Software Engineer focused on AI systems, building the runtimes, control
planes, SDKs, and orchestration layers that make model-driven workflows usable
in practice.

Most of my recent work is in Go and TypeScript across agent harnesses,
multi-agent orchestration, protocol integrations, and developer-facing tooling.
I tend to build with a strong bias toward typed configuration, testable
interfaces, runtime observability, and operationally clear systems.

## Current Focus

- AI runtime and harness development
- Agent orchestration and workflow automation
- MCP and A2A protocol integrations
- Web and CLI control planes for long-running AI workflows
- Developer tooling for safe, observable AI systems

## Selected Work

- [`sigil`](https://github.com/leefowlercu/sigil) - a Go-based RLM harness with
  example-driven configuration, indexed run summaries, and token accounting
  surfaces.
- [`sigil-web`](https://github.com/leefowlercu/sigil-web) - a TypeScript web UI
  for the `sigil` app-server with live run inspection, step-level views, and
  operator workflows.
- [`project-sigil`](https://github.com/leefowlercu/project-sigil) - the
  superproject coordinating the `sigil` ecosystem, specifications, and
  multi-repo delivery flow.
- [`go-contextforge`](https://github.com/leefowlercu/go-contextforge) - a Go
  SDK for the IBM ContextForge MCP Gateway, covering tools, resources, prompts,
  gateways, and agent management.
- [`go-symphony`](https://github.com/leefowlercu/go-symphony) - a Go
  orchestration service for running coding-agent sessions against issue queues
  in isolated workspaces.
- [`nomad-mcp-pack`](https://github.com/leefowlercu/nomad-mcp-pack) - a Go-based 
  orchestration system for translating MCP Server definitions into HashiCorp Nomad Packs.
- [`agent-skills`](https://github.com/leefowlercu/agent-skills) - agent skills
  and plugin work that supports AI-assisted developer workflows.

## Background

My background in distributed systems engineering shapes how I build AI-focused software
today. I approach runtimes, agent orchestration, protocol integrations, and
control planes as distributed systems problems: explicit interfaces, observable
state transitions, fault tolerance, coordination boundaries, and infrastructure
that remains understandable under real operational pressure.

- [More about me](https://voxmachina.io/me)
