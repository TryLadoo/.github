<p align="center">
  <a href="https://tryladoo.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/ladoo-wordmark-on-dark.svg">
      <img src="assets/ladoo-wordmark.svg" alt="Ladoo" width="220">
    </picture>
  </a>
</p>

<p align="center">
  <b>The AI receptionist for local service businesses.</b><br>
  Ladoo answers the phone and website chat, books the appointment, takes the message and updates the CRM.<br>
  Start from a template or one sentence, then shape every step of the call yourself.
</p>

<p align="center">
  <a href="https://tryladoo.com">Website</a> ·
  <a href="https://tryladoo.com/docs/developers">Developer docs</a> ·
  <a href="https://tryladoo.com/docs/developers/api-reference">API reference</a> ·
  <a href="https://tryladoo.com/docs/developers/changelog">Changelog</a> ·
  <a href="https://tryladoo.com/status">Status</a>
</p>

---

### Build on Ladoo

Everything you can do in the Ladoo dashboard, you can do from code: read calls and transcripts, manage agents and their workflows, fill knowledge bases, buy numbers, run agencies' client workspaces, and get signed webhooks when a call ends or a booking lands. Your own HTTP endpoints can become tools the agent calls mid-conversation, and a pre-call webhook can look a caller up before the agent says hello.

| Project | What it's for |
|---|---|
| [**ladoo-node**](https://github.com/TryLadoo/ladoo-node) | TypeScript SDK. Typed client, auto-pagination, retries and webhook signature checks that run anywhere: Node, Bun, Deno and edge runtimes. `npm i ladoo` |
| [**ladoo-python**](https://github.com/TryLadoo/ladoo-python) | Python SDK, sync and async, with typed models. `pip install ladoo` |
| [**ladoo-mcp**](https://github.com/TryLadoo/ladoo-mcp) | MCP server. Ask Claude, Cursor or ChatGPT about your calls, bookings and callers. `npx -y ladoo-mcp` |
| [**workflows**](https://github.com/TryLadoo/workflows) | The open `.lassi-workflow.json` format, its JSON Schema, and ready-made call workflows for plumbers, dentists, law firms, salons and more. |

### Try it in one request

```sh
curl https://api.tryladoo.com/v1/calls?limit=5 \
  -H "Authorization: Bearer $LADOO_API_KEY"
```

Create a key under **Settings → Developers**, then follow the [ten-minute quickstart](https://tryladoo.com/docs/developers/quickstart). The full OpenAPI 3.1 document is at [`api.tryladoo.com/openapi.json`](https://api.tryladoo.com/openapi.json).

### Get in touch

Questions and ideas: open an issue on the project, or email [support@tryladoo.com](mailto:support@tryladoo.com).
Security reports: see our [disclosure policy](https://tryladoo.com/security#disclosure).
