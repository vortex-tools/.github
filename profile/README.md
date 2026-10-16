<p align="center">
  <a href="https://vx.tools"><img src="vortex-logo.svg" width="72" height="72" alt="Vortex"></a>
</p>

<h3 align="center">Vortex runs a Solana validator and measures how validators perform.</h3>

<p align="center">
  The tools Vortex built to run and study its own validator live here, published as they are ready for other operators. See the
  <a href="https://vx.tools">Vortex validator</a> they run on.
</p>

<p align="center">
  <a href="https://app.vx.tools"><b>app.vx.tools</b></a> ·
  <a href="https://vx.tools">vx.tools</a> ·
  <a href="https://api.vx.tools/llms.txt">API</a>
</p>

## Tools

| Tool | What it does | Status |
| --- | --- | --- |
| **[vortex-dashboard](https://app.vx.tools)** | The validator explorer at app.vx.tools: vote quality and block income across the cluster, epoch by epoch, served from a public read-only API with no key. | Live at [app.vx.tools](https://app.vx.tools) · source coming soon |
| **vortex-cli** | Operator shell for an Agave validator: versioned builds with rollback, service control, identity switching and cross-host handoff, a self-checking config. | Coming soon |
| **vortex-monitor** | Log monitor and TUI that knows what your build can report (agave, jito, instrumented), with operator alerts and a read-only HTTP/MCP interface for agents. | Coming soon |
| **vortex-ansible** | Ansible playbooks that turn a fresh Ubuntu machine into a validator host, with read-only inspection first and a report of what is left to do. | Coming soon |
| **vortex-execution** | Interactive timeline of how one block ran: a lane per thread, load and execute bars per transaction, and the account dependencies between them. | In development |

Each tool gets its own repository here as it is published, under the Apache-2.0 license.

## The data is open now

The dashboard and its API are public today, no account needed:

```sh
curl https://api.vx.tools/epochs/current
```

The endpoints are documented in [api.vx.tools/llms.txt](https://api.vx.tools/llms.txt), written so assistants and agents can query them directly.
