<p align="center">
  <img src="https://github.com/NetBreaker-org/NetBreaker/blob/main/assets/logowhite.svg" width="100%" />
</p>

<h1 align="center">NetBreaker</h1>

<p align="center">
  An open-source project focused on reverse proxying,
  load balancing, and server management.
</p>

<p align="center">
  <strong>Under Development</strong>
</p>

---

## About

NetBreaker is an open-source server management platform designed to simplify traffic routing, backend management, and infrastructure orchestration.

Its architecture is being developed around a modular runtime and independently installable execution engines, allowing different implementations to serve different workloads.

## Architecture

NetBreaker is designed around a central runtime that manages configurations, orchestration, and communication with execution engines.

Individual engines are maintained as separate repositories and can be installed and selected independently.

## Repositories

| Repository                                                               | Description                    |
| ------------------------------------------------------------------------ | ------------------------------ |
| [netbreaker-engine](https://github.com/NetBreaker-org/netbreaker-engine) | Main runtime and orchestration |
| [netbreaker-oldfox](https://github.com/NetBreaker-org/netbreaker-oldfox) | TypeScript-based proxy engine  |

_More repositories and engines may be added as development progresses._

## Naming Conventions

- Repository names use lowercase kebab-case.
- All project repositories use the `netbreaker-` prefix.
- The main runtime uses the `netbreaker-engine` name.
- Individual execution engines use distinct codenames.
- Implementation languages and engine capabilities are documented in their respective repositories.

## Project Links

- [Website](https://netbreaker.maywill.online)
- [Documentation](https://netbreaker.maywill.online/docs)
- [GitHub Organization](https://github.com/NetBreaker-org)

## Development Status

NetBreaker is undergoing major architectural development. Its interfaces, features, and internal components may change considerably.

It is not yet a stable release, and using it in production is not recommended.

---

<p align="center">
  Copyright © 2026 NetBreaker contributors
</p>
