<p align="center">
  <a href="https://vx.tools"><img src="vortex-logo.svg" width="72" height="72" alt="Vortex"></a>
</p>

<h3 align="center">Vortex runs a Solana validator and measures how validators perform.</h3>

<p align="center">
  The tools Vortex built to run and study its own validator live here, published as they are ready for other operators.
</p>

<p align="center">
  <a href="https://app.vx.tools"><b>app.vx.tools</b></a> ·
  <a href="https://vx.tools">vx.tools</a> ·
  <a href="https://api.vx.tools/llms.txt">API</a> ·
  <a href="https://blog.vx.tools">Blog</a>
</p>

## Tools

| Tool | What it does | Links |
| --- | --- | --- |
| **[vortex-dashboard](https://github.com/vortex-tools/vortex-dashboard)** | The validator explorer at app.vx.tools: vote quality and block income across the cluster, epoch by epoch, served from a public read-only API with no key. | [app.vx.tools](https://app.vx.tools) · [source](https://github.com/vortex-tools/vortex-dashboard) |

Released under the Apache-2.0 license.

## Open data

The dashboard and its API are public today, no account needed:

```sh
curl https://api.vx.tools/epochs/current
```

The endpoints are documented in [api.vx.tools/llms.txt](https://api.vx.tools/llms.txt), written so assistants and agents can query them directly.
