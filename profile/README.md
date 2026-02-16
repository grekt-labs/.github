# grekt

The open artifact manager for AI tools.

grekt treats AI configurations (system prompts, rules, agents, skills, hooks, MCPs) as first-class artifacts with versioning, integrity checks, and a plugin-based sync system. It supports current and emerging AI tools — if a new agent or coding assistant appears tomorrow, grekt is ready.

## Get Started

```bash
curl -fsSL https://grekt.com/install.sh | sh
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
| [cli-engine](https://github.com/grekt-labs/cli-engine) | Core engine powering the CLI and integrations |
| [docs](https://github.com/grekt-labs/docs) | Documentation |
| [docs-dev](https://github.com/grekt-labs/docs-dev) | Developer docs for building integrations |

## Roadmap

This roadmap reflects our current direction. It's not a promise — priorities shift as we learn.

### Now

What we're actively building and refining.

- **Registry hardening** — improving the publish/download flow, error handling, and edge cases
- **Monorepo workflows** — batch operations, selective publishing, workspace management
- **Artifact kits** — curated collections for team onboarding and standardization

### Next

What's coming after current work stabilizes.

- **Private artifacts** — publish private artifacts to the grekt registry, visible only to you or your organization
- **Organizations and teams** — shared artifact ownership, access control, team workspaces
- **Verified publishers** — trust signals for artifact authors and organizations
- **Security preview** — warnings and transparency for untrusted or unverified artifacts before installation
- **Granular capability policies** — leverage declared capabilities for fine-grained access control and auditing

### Later

Directions we're exploring. No timelines.

- **Artifact composability** — combine and extend artifacts at runtime
- **CI/CD integration** — automate artifact publishing and policy validation in pipelines
- **Discovery and insights** — compatibility matrix, trending artifacts, usage analytics

> Have ideas or feedback? [Open an issue](https://github.com/grekt-labs/cli/issues) or start a [discussion](https://github.com/grekt-labs/cli/discussions).

## License

grekt is source-available under [BSL 1.1](https://github.com/grekt-labs/cli/blob/main/LICENSE). You can use it freely for any purpose — personal, commercial, internal tooling — as long as you don't use the code to build a competing product. Each version converts to MIT after two years. [Learn more](https://github.com/grekt-labs/cli/blob/main/LICENSING.md).
