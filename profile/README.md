# grekt

The open artifact manager for AI tools.

grekt treats AI configurations (system prompts, rules, agents, skills, hooks, MCPs) as first-class artifacts with versioning, integrity checks, and a plugin-based sync system. It supports current and emerging AI tools, if a new agent or coding assistant appears tomorrow, grekt is ready.

## Get Started

```bash
curl -fsSL https://grekt.com/install.sh | sh
```

```bash
npm i -g @grekt/cli
```

```bash
grekt init            # initialize a project
grekt add @scope/name # add an artifact from the registry
grekt sync            # sync artifacts to your AI tools
```

[Documentation](https://docs.grekt.com) | [Explore artifacts](https://explore.grekt.com)

## Repositories

| Repo | Description |
|------|-------------|
| [cli](https://github.com/grekt-labs/cli) | The grekt CLI |
| [engine](https://github.com/grekt-labs/engine) | Core engine powering the CLI and integrations |
| [docs](https://github.com/grekt-labs/docs) | [Documentation](https://grekt.com/en-US/docs/guide/introduction.html) |
| [docs-dev](https://github.com/grekt-labs/docs-dev) | [Developer docs](https://developer.grekt.com/en-US/docs/guide/introduction.html) for building integrations |

## Roadmap

This roadmap reflects our current direction. It's not a promise — priorities shift as we learn.

### Now

What we're actively building and refining.
- **Artifact evals** - Testing your artifacts with deterministic evals or through LLM-as-judge (for non deterministic components)
- **Self-hosted control dashboard** - Following our principles we are creating a dashboard to allow you see all your projects easily, fully self-hosted. We do not track/store anything. You will be the owner of your data :)

### Next

What's coming after current work stabilizes.

- **Focus on auditability** - Look for integrations or features that will allow teams to trust it's own AI stack.
- **Private artifacts** - publish private artifacts to the grekt registry, visible only to you or your organization
- **Organizations and teams** - shared artifact ownership, access control, team workspaces
- **Verified publishers** - trust signals for artifact authors and organizations
- **Granular capability policies** - leverage declared capabilities for fine-grained access control and auditing
- **Registry hardening** - improving the publish/download flow, error handling, and edge
- **Artifact kits** - curated collections for team onboarding and standardization

### Later

Directions we're exploring. No timelines.

- **Discovery and insights** - compatibility matrix, trending artifacts, usage analytics

> Have ideas or feedback? [Open an issue](https://github.com/grekt-labs/cli/issues) or start a [discussion](https://github.com/grekt-labs/cli/discussions).

## License

grekt is source-available under [BSL 1.1](https://github.com/grekt-labs/cli/blob/main/LICENSE). You can use it freely for any purpose personal, commercial, internal tooling, as long as you don't use the code to build a competing product. Each version converts to MIT after two years. [Learn more](https://github.com/grekt-labs/cli/blob/main/LICENSING.md).
