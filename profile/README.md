<p align="center">
  <img src="https://raw.githubusercontent.com/obtraceai/.github/main/banner.png" alt="Obtrace" width="960" />
</p>

# Obtrace

SDK-first observability for modern applications. AI-powered root cause analysis, auto-fix PRs, session replay, and cost attribution.

## Documentation

- https://docs.obtrace.ai/

## SDKs

| Language | Repository |
|----------|------------|
| JavaScript / Node.js | [obtrace-sdk-js](https://github.com/obtraceai/obtrace-sdk-js) |
| Browser | [obtrace-sdk-browser](https://github.com/obtraceai/obtrace-sdk-browser) |
| Go | [obtrace-sdk-go](https://github.com/obtraceai/obtrace-sdk-go) |
| Python | [obtrace-sdk-python](https://github.com/obtraceai/obtrace-sdk-python) |
| Java | [obtrace-sdk-java](https://github.com/obtraceai/obtrace-sdk-java) |
| .NET | [obtrace-sdk-dotnet](https://github.com/obtraceai/obtrace-sdk-dotnet) |
| PHP | [obtrace-sdk-php](https://github.com/obtraceai/obtrace-sdk-php) |
| Ruby | [obtrace-sdk-ruby](https://github.com/obtraceai/obtrace-sdk-ruby) |

## Auto-Instrumentation

| Tool | Purpose | Repository |
|------|---------|------------|
| **Obtrace Zero** `NEW` | Zero-touch K8s operator — auto-detects language, injects SDK or eBPF sidecar, no code changes | [obtrace-zero](https://github.com/obtraceai/obtrace-zero) |

> `obtrace-zero install --api-key=obt_live_xxx` — one command, full cluster observability. Supports Node.js, Python, Java, .NET, PHP, Ruby via SDK injection and Go, Rust, C++ via eBPF kernel tracing. [Docs](https://docs.obtrace.ai/docs/obtrace-zero) · [Quickstart](https://docs.obtrace.ai/docs/obtrace-zero/quickstart)

## Infrastructure Agents

| Agent | Purpose | Repository |
|-------|---------|------------|
| Kubernetes | Cluster, pod, and node metrics | [obtrace-sdk-k8s-integration](https://github.com/obtraceai/obtrace-sdk-k8s-integration) |
| Database | Postgres, MySQL, MongoDB, Redis, Cassandra, Elasticsearch, ClickHouse, CockroachDB, SQLite | [obtrace-db-agent](https://github.com/obtraceai/obtrace-db-agent) |

## MCP (Model Context Protocol)

Obtrace supports [MCP](https://modelcontextprotocol.io/) for AI-assisted development and debugging. Connect your AI coding assistant to your observability data.

| Resource | Description |
|----------|-------------|
| [MCP Server](https://docs.obtrace.ai/docs/mcp) | Connect obtrace to AI coding assistants (Cursor, Claude, Copilot) |
| `docs/mcp.md` | MCP integration guide available in each SDK repo |
| `llm.txt` | LLM-readable context file available in each SDK repo |
