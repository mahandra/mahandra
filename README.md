Python/Django engineer working on platform automation, APIs, and AI integrations: RAG pipelines, MCP servers, and LLM features that have to behave predictably once real users depend on them, with cited answers, evaluations, guarded actions, and audit trails.

Based in Florida, working remotely. Outside of application work I build smart home and IoT systems with Home Assistant, ESPHome, and Zigbee, which is where several of my projects come from.

### Projects

**[DocQA](https://github.com/mahandra/docsearcher)**: A Django app for asking questions about your own documents (PDF, DOCX). Files are parsed, chunked, and embedded in a Celery worker and stored in PostgreSQL/pgvector; each question runs a hybrid search (vectors + full-text), and Claude answers from the retrieved passages with citations. Answer quality is measured by an eval suite with an LLM judge, and every reply is traced in Langfuse.

**[HA Insights MCP](https://github.com/mahandra/ha-insights-mcp)**: An MCP server that gives LLM agents analytics, diagnostics, and guarded actions for Home Assistant. It is read-only by default; actions are opt-in and pass through an allowlist, value bounds, a preview, human confirmation, and an audit log. Runs over stdio or authenticated Streamable HTTP in Docker.

**[HVAC Maintenance Tracker](https://github.com/mahandra/hvac)**: A Django + HTMX app for tracking air-conditioner maintenance at rental properties: per-address visit history with checklists and photos, PDF reports, and read-only share links. Designed to be used from a phone on site.

**[dj-mcp](https://github.com/mahandra/dj_mcp)**: A Django REST API with an MCP server on top, so AI assistants such as Claude can query and manage its data. Runs under ASGI with async streaming endpoints.

### Stack

Python, Django, Django REST Framework, PostgreSQL / pgvector, Celery, Redis, HTMX, Docker, Anthropic API, MCP. Currently learning Rust.

### Open to work

I'm open to fully remote roles centered on Python and Django development.

More at **[makhotin.net](https://makhotin.net)**.
