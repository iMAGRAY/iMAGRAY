<!--
Profile README for @iMAGRAY (Amir Tlinov)
Style: businesslike; no emojis; SVG icons only (Tabler + Simple Icons); consistent 20px.
Tip: for maximum reliability, vendor icons into assets/icons/ and use relative paths.
-->

<div align="center">

<h1>Amir Tlinov — iMAGRAY</h1>

<strong>AI Developer & Software Engineer</strong>

<p><em>Designing deterministic AI tooling, Rust/Python systems, and MCP-compatible servers. Production first.</em></p>

<!-- Contact -->
<p>
  <a href="https://imagray.dev" target="_blank" rel="noopener">
    <img src="https://raw.githubusercontent.com/tabler/tabler-icons/master/icons/icon-link.svg" alt="Website" width="20" height="20" style="vertical-align:text-bottom;"> imagray.dev
  </a>
</p>

</div>

<hr/>

<h2>
  <img src="https://raw.githubusercontent.com/tabler/tabler-icons/master/icons/icon-target.svg" alt="Focus" width="20" height="20" style="vertical-align:text-bottom;">
  Focus
</h2>

- AI agents & developer tooling (Claude / GPT / Gemini). Offline-friendly workflows when possible.
- Systems programming in Rust and Python. Predictable performance and safety by default.
- Model Context Protocol (MCP): practical tool servers and strict interface contracts.
- Distributed architecture & observability: metrics, logs, traces; p95/p99 and budget gates in CI.

<hr/>

<h2>
  <img src="https://raw.githubusercontent.com/tabler/tabler-icons/master/icons/icon-briefcase.svg" alt="Projects" width="20" height="20" style="vertical-align:text-bottom;">
  Selected Projects
</h2>

<table>
  <thead>
    <tr>
      <th align="left">Project</th>
      <th align="left">What it is</th>
      <th align="left">Highlights</th>
      <th align="left">Tech</th>
    </tr>
  </thead>
  <tbody>

    <tr>
      <td><a href="https://github.com/iMAGRAY/ASTSentinel">ASTSentinel</a></td>
      <td>Deterministic AST hooks & checks for AI coding agents (pre/post tool-use; prompt/contract scaffolding).</td>
      <td>Perf budgets (p50/p95/p99), “no panic in prod” policy, structured logs, offline modes.</td>
      <td>
        <img src="https://cdn.simpleicons.org/rust" alt="Rust" width="20" height="20"/>
      </td>
    </tr>

    <tr>
      <td><a href="https://github.com/iMAGRAY/ArchLens">ArchLens</a></td>
      <td>Architecture analysis with AI-assisted insights.</td>
      <td>Code smell/antipattern detection, MCP-compatible workflow, Mermaid exports.</td>
      <td>
        <img src="https://cdn.simpleicons.org/rust" alt="Rust" width="20" height="20"/>
        <img src="https://cdn.simpleicons.org/mermaid" alt="Mermaid" width="20" height="20"/>
      </td>
    </tr>

    <tr>
      <td><a href="https://github.com/iMAGRAY/MAGRAY_Cli">MAGRAY_Cli</a></td>
      <td>Developer automation CLI with agent tooling.</td>
      <td>Task matrix, performance gates, local/offline model support.</td>
      <td>
        <img src="https://cdn.simpleicons.org/rust" alt="Rust" width="20" height="20"/>
      </td>
    </tr>

    <tr>
      <td><a href="https://github.com/iMAGRAY/PSQL_SSH_API_MCP">PSQL_SSH_API_MCP</a></td>
      <td>Compact MCP server for PostgreSQL, SSH and HTTP APIs.</td>
      <td>Service-layer DI design, shorter tool names, security hardening (SQL/command/SSRF protection).</td>
      <td>
        <img src="https://cdn.simpleicons.org/nodedotjs" alt="Node.js" width="20" height="20"/>
        <img src="https://cdn.simpleicons.org/postgresql" alt="PostgreSQL" width="20" height="20"/>
        <img src="https://cdn.simpleicons.org/gnubash" alt="SSH" width="20" height="20"/>
      </td>
    </tr>

    <tr>
      <td><a href="https://github.com/iMAGRAY/CogniVault">CogniVault</a></td>
      <td>High-performance, pluggable memory hub for embeddings, blobs and vector search.</td>
      <td>Signed plugin system (cdylib/WASI), runtime-agnostic core, Prometheus metrics.</td>
      <td>
        <img src="https://cdn.simpleicons.org/rust" alt="Rust" width="20" height="20"/>
      </td>
    </tr>

    <tr>
      <td><a href="https://github.com/iMAGRAY/70B-1q-to-70B-lang">SIGLA</a></td>
      <td>Local vector memory & retrieval for agents.</td>
      <td>HNSW with NumPy fallback, SQLite+FTS5, clean Python API & HTTP server.</td>
      <td>
        <img src="https://cdn.simpleicons.org/python" alt="Python" width="20" height="20"/>
        <img src="https://cdn.simpleicons.org/sqlite" alt="SQLite" width="20" height="20"/>
      </td>
    </tr>

    <tr>
      <td><a href="https://github.com/iMAGRAY/TelegramVoice">TelegramVoice</a></td>
      <td>Telegram Mini App for multi-party voice rooms.</td>
      <td>WebRTC audio, WebSocket signaling, CI/CD deploy scripts.</td>
      <td>
        <img src="https://cdn.simpleicons.org/telegram" alt="Telegram" width="20" height="20"/>
        <img src="https://cdn.simpleicons.org/typescript" alt="TypeScript" width="20" height="20"/>
        <img src="https://cdn.simpleicons.org/webrtc" alt="WebRTC" width="20" height="20"/>
      </td>
    </tr>

    <tr>
      <td><a href="https://github.com/iMAGRAY/-24-">-24-</a></td>
      <td>MCP remote-control server for secure operations on local machines via AI interfaces.</td>
      <td>SSH/WebSocket tunneling, filesystem/exec/system tools, sandboxing and audit logging.</td>
      <td>
        <img src="https://cdn.simpleicons.org/python" alt="Python" width="20" height="20"/>
        <img src="https://cdn.simpleicons.org/gnubash" alt="Shell" width="20" height="20"/>
      </td>
    </tr>

    <tr>
      <td><a href="https://github.com/iMAGRAY/Axiom">Axiom</a></td>
      <td>LLM-First Language (docs-only mode).</td>
      <td>Release workflows, PDF/MD bundling, strict doc tests and link checks; wiki/pages sync.</td>
      <td>
        <img src="https://cdn.simpleicons.org/python" alt="Python" width="20" height="20"/>
        <img src="https://cdn.simpleicons.org/jupyter" alt="Jupyter" width="20" height="20"/>
      </td>
    </tr>

  </tbody>
</table>

<hr/>

<h2>
  <img src="https://raw.githubusercontent.com/tabler/tabler-icons/master/icons/icon-stack-2.svg" alt="Stack" width="20" height="20" style="vertical-align:text-bottom;">
  Core Stack
</h2>

<p>
  <img src="https://cdn.simpleicons.org/rust" alt="Rust" width="20" height="20"/>
  <img src="https://cdn.simpleicons.org/python" alt="Python" width="20" height="20"/>
  <img src="https://cdn.simpleicons.org/typescript" alt="TypeScript" width="20" height="20"/>
  <img src="https://cdn.simpleicons.org/nodedotjs" alt="Node.js" width="20" height="20"/>
  <img src="https://cdn.simpleicons.org/react" alt="React" width="20" height="20"/>
  <img src="https://cdn.simpleicons.org/nextdotjs" alt="Next.js" width="20" height="20"/>
  <img src="https://cdn.simpleicons.org/docker" alt="Docker" width="20" height="20"/>
  <img src="https://cdn.simpleicons.org/githubactions" alt="GitHub Actions" width="20" height="20"/>
  <img src="https://cdn.simpleicons.org/postgresql" alt="PostgreSQL" width="20" height="20"/>
  <img src="https://cdn.simpleicons.org/redis" alt="Redis" width="20" height="20"/>
  <img src="https://cdn.simpleicons.org/webassembly" alt="WebAssembly" width="20" height="20"/>
</p>

<sub>Also used as required: Prometheus/Grafana, Sentry, OpenTelemetry, Playwright, Terraform.</sub>

<hr/>

<h2>
  <img src="https://raw.githubusercontent.com/tabler/tabler-icons/master/icons/icon-compass.svg" alt="Principles" width="20" height="20" style="vertical-align:text-bottom;">
  Engineering Principles
</h2>

- Design docs first; clear API contracts; docs co-located with code.
- Small PRs; trunk-based delivery; feature flags; zero-downtime migrations.
- Observability by design: metrics/logs/traces, tracked p95/p99, performance gates in CI.
- Security first: least privilege, secrets management, input validation, idempotent operations.
- Reduce accidental complexity; pay down tech debt regularly.

<hr/>

<h2>
  <img src="https://raw.githubusercontent.com/tabler/tabler-icons/master/icons/icon-folder.svg" alt="Repos" width="20" height="20" style="vertical-align:text-bottom;">
  Where to look
</h2>

- <strong>Pinned</strong>: ASTSentinel • ArchLens • MAGRAY_Cli • PSQL_SSH_API_MCP • CogniVault • SIGLA (70B-1q-to-70B-lang)
- For MCP work: PSQL_SSH_API_MCP, -24-, ArchLens.
- For AI tooling & memory: CogniVault, SIGLA.
- For real-time app work: TelegramVoice.

<hr/>

<h2>
  <img src="https://raw.githubusercontent.com/tabler/tabler-icons/master/icons/icon-mail.svg" alt="Contact" width="20" height="20" style="vertical-align:text-bottom;">
  Contact
</h2>

- Website: <a href="https://imagray.dev" target="_blank" rel="noopener">imagray.dev</a>
- For collaboration or questions: open an Issue in the relevant repository.

<hr/>

<sub>
Colophon — SVG icons only (Tabler + Simple Icons), single size 20px.  
To avoid CDN dependency, vendor icons into <code>assets/icons/</code> and switch links to relative paths.
</sub>

