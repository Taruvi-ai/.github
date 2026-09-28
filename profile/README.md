<div align="center">

# TaruviBase

### Enterprise infrastructure at modern speed.

Build secure, multi-tenant SaaS and AI applications without assembling
and operating your backend infrastructure from scratch.

[Website](https://taruvibase.com/) ·
[Documentation](https://docs.taruvibase.com/) ·
[Get Started](https://docs.taruvibase.com/docs/introduction/) ·
[Quickstarts](https://github.com/Taruvi-ai/taruvi-quickstarts)

</div>

---

## Build with Taruvi

TaruviBase provides the backend capabilities needed to build production applications:
data, authentication and authorization, storage, serverless functions, analytics,
secrets, events, APIs, and AI-native development through MCP.

| | SDK / Integration | Latest | Install | Start here |
|---|---|---|---|---|
| 🟨 | **JavaScript / TypeScript SDK** | ![npm](https://img.shields.io/npm/v/@taruvi/sdk?label=version) | `npm install @taruvi/sdk` | [SDK docs](https://docs.taruvibase.com/docs/sdk/overview/) |
| 🐍 | **Python SDK** | ![PyPI](https://img.shields.io/pypi/v/taruvi?label=version) | `pip install taruvi` | [SDK docs](https://docs.taruvibase.com/docs/sdk/overview/) |
| ⚛️ | **Refine Providers** | ![npm](https://img.shields.io/npm/v/@taruvi/refine-providers?label=version) | `npm install @taruvi/refine-providers` | [Refine docs](https://docs.taruvibase.com/docs/refine-providers/overview/) |
| 🔎 | **React Filter Builder** | ![npm](https://img.shields.io/npm/v/@taruvi/react-filters?label=version) | `npm install @taruvi/react-filters` | Examples coming soon |
| 🧭 | **NavKit** | ![npm](https://img.shields.io/npm/v/@taruvi/navkit?label=version) | `npm install @taruvi/navkit` | Examples coming soon |

> Package badges show the currently published version from npm or PyPI.

---

## What can you build?

| Capability | What Taruvi gives you |
|---|---|
| **Database & schemas** | Managed datatables, relationships, filtering, search, and schema evolution |
| **Authentication** | Application users, sessions, and identity management |
| **Authorization** | Fine-grained policy-based access control |
| **Storage** | Managed buckets, objects, uploads, and file delivery |
| **Functions** | Serverless backend logic and scheduled execution |
| **Analytics** | Parameterized, secure analytical queries |
| **Secrets** | Managed application secrets and configuration |
| **Events** | Event-driven workflows and function triggers |
| **APIs & SDKs** | REST APIs plus JavaScript/TypeScript and Python SDKs |
| **MCP** | Let AI coding agents understand and work with your Taruvi backend |

[Explore the platform →](https://taruvibase.com/platform)

---

## Start building

### JavaScript / TypeScript

```bash
npm install @taruvi/sdk
```

```ts
import { Client } from "@taruvi/sdk";

const client = new Client({
  apiKey: process.env.TARUVI_API_KEY,
  appSlug: "my-app",
  baseUrl: "https://your-site.taruvi.cloud",
});
```

### Python

```bash
pip install taruvi
```

```python
from taruvi import Client

client = Client(
    api_url="https://api.taruvi.cloud",
    app_slug="my-app",
)
```

Follow the full [SDK Quickstart](https://docs.taruvibase.com/docs/sdk/quickstart/).

---

## Quickstarts

Learn Taruvi by running focused examples.

| Quickstart | What you'll learn |
|---|---|
| **Database** | Create, read, update, delete, filter, and paginate records |
| **Authentication** | Sign in users and protect application flows |
| **Storage** | Upload, list, download, and delete files |
| **Authorization** | Enforce fine-grained access policies |
| **Functions** | Execute backend functions from your application |
| **Analytics** | Run secure analytical queries |
| **Refine** | Build a CRUD application using Taruvi Refine providers |
| **Filter Builder** | Turn visual filters into Taruvi queries |
| **MCP & AI Agents** | Build and manage Taruvi backends with AI coding agents |

[Browse Taruvi Quickstarts →](https://github.com/Taruvi-ai/taruvi-quickstarts)

---

## Build frontend applications faster

### Refine + Taruvi

Taruvi provides first-party Refine providers for database CRUD, storage,
functions, authentication, users, analytics, and access control.

```bash
npm install @taruvi/refine-providers @taruvi/sdk @refinedev/core
```

[Refine integration docs →](https://docs.taruvibase.com/docs/refine-providers/overview/)

### Taruvi starter

Start from a working React + Refine application rather than a blank project.

[Open the Taruvi Refine Starter →](https://github.com/Taruvi-ai/refine-starter-template)

---

## Build with AI

Taruvi is designed to work with modern AI-assisted development workflows.

### MCP

Connect supported AI development tools to TaruviBase so agents can understand
and work with your backend resources.

[Learn about Taruvi MCP →](https://docs.taruvibase.com/)

### Agent tooling

- [**Taruvi Skills**](https://github.com/Taruvi-ai/taruvi-skills) — reusable Taruvi knowledge for AI coding agents
- [**Taruvi Agents Plugin**](https://github.com/Taruvi-ai/taruvi-agents-plugin) — Taruvi development tooling for supported coding agents

---

## Developer tools

| Project | Purpose |
|---|---|
| [`@taruvi/sdk`](https://www.npmjs.com/package/@taruvi/sdk) | JavaScript / TypeScript SDK |
| [`taruvi`](https://pypi.org/project/taruvi/) | Python SDK |
| [`@taruvi/refine-providers`](https://www.npmjs.com/package/@taruvi/refine-providers) | Refine integration |
| [`@taruvi/react-filters`](https://www.npmjs.com/package/@taruvi/react-filters) | Visual filter builder |
| `@taruvi/navkit` | Application navigation components |
| [`taruvi-skills`](https://github.com/Taruvi-ai/taruvi-skills) | Skills for AI coding agents |
| [`taruvi-agents-plugin`](https://github.com/Taruvi-ai/taruvi-agents-plugin) | Agent development integration |
| [`taruvi-action`](https://github.com/Taruvi-ai/taruvi-action) | GitHub Actions deployment tooling |

---

## Featured repositories

### [`taruvi-quickstarts`](https://github.com/Taruvi-ai/taruvi-quickstarts)
Focused, runnable examples for Taruvi platform capabilities.

### [`refine-starter-template`](https://github.com/Taruvi-ai/refine-starter-template)
A ready-to-use React + Refine starter connected to Taruvi.

### [`taruvi-python-sdk`](https://github.com/Taruvi-ai/taruvi-python-sdk)
Official Python SDK for TaruviBase.

### [`taruvi-skills`](https://github.com/Taruvi-ai/taruvi-skills)
Official Taruvi skills for AI-assisted development.

### [`taruvi-agents-plugin`](https://github.com/Taruvi-ai/taruvi-agents-plugin)
Agent integration tooling for Taruvi development workflows.

---

## Documentation

- [Introduction](https://docs.taruvibase.com/docs/introduction/)
- [SDK Overview](https://docs.taruvibase.com/docs/sdk/overview/)
- [SDK Quickstart](https://docs.taruvibase.com/docs/sdk/quickstart/)
- [Refine Providers](https://docs.taruvibase.com/docs/refine-providers/overview/)
- [Platform Overview](https://taruvibase.com/platform)

---

## Contributing & support

Each Taruvi repository contains its own contribution and issue guidance.

For product information and support:

- [TaruviBase](https://taruvibase.com/)
- [Documentation](https://docs.taruvibase.com/)

---

<div align="center">

**Build the product. Taruvi runs the backend.**

[Get started](https://docs.taruvibase.com/) ·
[Explore TaruviBase](https://taruvibase.com/)

</div>
