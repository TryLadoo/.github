<p align="center">
  <a href="https://tryladoo.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/ladoo-wordmark-on-dark.svg">
      <img src="assets/ladoo-wordmark.svg" alt="Ladoo" width="200">
    </picture>
  </a>
</p>

<p align="center">
  Ladoo answers the phone and website chat for local service businesses.<br>
  It books the appointment, takes the message and updates the CRM.
</p>

<p align="center">
  <a href="https://tryladoo.com">tryladoo.com</a> ·
  <a href="https://tryladoo.com/docs/developers">Developer docs</a> ·
  <a href="https://tryladoo.com/docs/developers/api-reference">API reference</a> ·
  <a href="https://tryladoo.com/status">Status</a>
</p>

---

The Ladoo API covers what the dashboard does: calls and transcripts, agents and their workflows, knowledge bases, phone numbers, bookings and agency client workspaces. Webhooks are signed. Your own endpoints can be tools the agent calls during a call, and a pre-call webhook can look up the caller before the agent picks up.

| Repo | |
|---|---|
| [ladoo-node](https://github.com/TryLadoo/ladoo-node) | TypeScript client and webhook helpers. Node, Bun, Deno and edge runtimes. |
| [ladoo-python](https://github.com/TryLadoo/ladoo-python) | Python client, sync and async. |
| [ladoo-mcp](https://github.com/TryLadoo/ladoo-mcp) | MCP server for Claude, Cursor and other MCP clients. |
| [workflows](https://github.com/TryLadoo/workflows) | The workflow file format, its JSON Schema, and workflows you can import. |

```sh
curl "https://api.tryladoo.com/v1/calls?limit=5" \
  -H "Authorization: Bearer $LADOO_API_KEY"
```

Keys are under **Settings → Developers**. The [quickstart](https://tryladoo.com/docs/developers/quickstart) covers your first request and webhook, and the OpenAPI document is at [api.tryladoo.com/openapi.json](https://api.tryladoo.com/openapi.json).

### Roadmap

- [ ] Publish `ladoo` to npm and PyPI, and `ladoo-mcp` to npm. Until then, install from GitHub (each README shows how).
- [ ] List `ladoo-mcp` in the MCP registry.
- [ ] More workflows, contributed by the people who run them.

Questions go in an issue on the relevant repo, or to [support@tryladoo.com](mailto:support@tryladoo.com). For security reports, see the [disclosure policy](https://tryladoo.com/security#disclosure).
