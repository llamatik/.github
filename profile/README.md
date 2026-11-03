# Llamatik

### Open AI. Your devices. Your rules.

**An open-source ecosystem for private, efficient, and distributed AI — built with Kotlin Multiplatform.**

[Website](https://llamatik.com) · [Documentation](https://docs.llamatik.com) · [Discord](https://discord.gg/vHB3qASbg)

---

## Our Mission

We believe AI should be **accessible, private, sustainable, and owned by the people who use it**.

Today, most AI applications depend on centralized cloud services. Llamatik explores a different approach: bringing intelligence closer to users, running models directly on their devices, and enabling those devices to work together.

Our goal is to make AI development easier for everyone, from developers building their first local AI application to teams creating autonomous agents and distributed AI systems.

**Local by default. Connected when needed. Open by design.**

## What We're Building

Llamatik is more than an inference library. It's a growing collection of open-source technologies and applications designed to make local and distributed AI practical.

### Llamatik — Kotlin Multiplatform AI SDK

Our core project provides the building blocks for developing AI-powered applications across Android, iOS, Desktop, and WebAssembly.

Powered by established native inference engines, it includes:

- **LLM inference** — local text generation, streaming, structured output, and embeddings using llama.cpp.
- **Multimodal AI** — image understanding with vision-language models.
- **Speech recognition** — offline speech-to-text using whisper.cpp.
- **Image generation** — text-to-image and image-to-image using stable-diffusion.cpp.
- **Agent framework** — tools, memory, workflows, and autonomous task orchestration.
- **Application SDK** — model management, RAG, chat sessions, and reusable AI components.

The SDK is organized into three layers: `core`, `sdk`, and `sdk-agent`.

**[Explore Llamatik SDK](https://github.com/llamatik/Llamatik)**

### Llamatik App — Your Personal AI Companion

A cross-platform application that puts local AI directly into users' hands.

Our vision is an assistant that can:

- Run language models directly on supported devices.
- Help users through natural conversations.
- Work offline without mandatory cloud accounts.
- Use tools and workflows to perform useful actions with appropriate permissions.
- Offer customizable assistant and companion experiences.

The application also serves as a real-world showcase for the Llamatik SDK.

*The next generation of Llamatik App and its agent features are under active development.*

### 💻 Llamatik Code — AI-Powered Development

A local-first AI coding assistant for IntelliJ-based IDEs.

Llamatik Code brings AI assistance directly into the development workflow, including:

- Project-aware conversations and coding assistance.
- Agent-driven development workflows.
- Code analysis and assisted changes.
- Integration with external tools through MCP.
- Local inference options that give developers more control over their source code.

**Built for developers who want AI assistance without giving up control over their tools and data.**

### Llamatik Network — Distributed AI

*An ongoing research and development initiative.*

What if the devices we already own could work together to run AI?

We're exploring a decentralized inference network where devices can discover available peers and share computing resources.

The long-term vision is to enable:

- **Peer discovery** — find available inference nodes on local networks and, eventually, beyond.
- **Shared computing** — use suitable devices to execute inference requests.
- **Hardware reuse** — give existing and older devices a useful role in AI workloads.
- **Streaming inference** — return generated responses to the requesting device.
- **Decentralized infrastructure** — reduce dependence on centralized AI providers.

Think of it as exploring a **BitTorrent-inspired network for AI inference**.

This work is experimental; decentralized scheduling, trust, security, and resource-sharing capabilities are part of the longer-term vision, not established production features.

## Our Principles

**🔐 Privacy First**

AI should run where your data lives whenever possible. Local inference keeps sensitive information under user control.

**🌍 Sustainability**

AI should make better use of existing hardware. We want to explore efficient inference and distributed computing as alternatives to unnecessary centralized resource consumption.

**🧩 Open Source and Transparency**

We believe in open development, reusable components, accessible knowledge, and community contributions.

**📱 Multiplatform by Design**

AI shouldn't be limited to one operating system or device category. Kotlin Multiplatform helps us build shared technology across different environments.

**🛠 Developer Driven**

Llamatik is built by developers, for developers, with practical APIs, extensible architecture, and real-world applications.

## 🏗️ The Ecosystem

| Project | Purpose |
|---|---|
| **[Llamatik SDK](https://github.com/llamatik/Llamatik)** | On-device inference, multimodal AI, RAG, and agent development |
| **[Llamatik App](https://github.com/llamatik/Llamatik)** | Personal AI assistant and SDK showcase |
| **[Llamatik Code](https://github.com/llamatik/Llamatik-Code)** | AI coding assistant for IntelliJ-based IDEs |
| **[Llamatik Server / Node](https://github.com/llamatik/Llamatik-Server)** | Infrastructure for serving inference requests and connecting devices |
| **Llamatik Mesh** *(vision)* | Peer-to-peer discovery and distributed AI inference |

These projects share a common objective: make AI more accessible, private, and independent of centralized infrastructure.

## 🧑‍💻 Join the Community

Llamatik is a developer-driven open-source initiative, and contributions are welcome.

Whether you're interested in Kotlin Multiplatform, on-device inference, agent systems, native AI engines, or distributed computing, there are opportunities to get involved.

You can contribute through code, bug reports, documentation, testing, design, and ideas.

Start by exploring the [main repository](https://github.com/llamatik/Llamatik), opening an issue, or joining a technical discussion.

---

### Let's build a more open and sustainable AI ecosystem.

**Run locally. Build freely. Connect intelligently.**

[llamatik.com](https://llamatik.com) · [Documentation](https://docs.llamatik.com) · [Discord](https://discord.gg/vHB3qASbg)
