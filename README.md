# Nodelex

**AI-Assisted, Node-Based Dialogue & Scenario Editor for Games and Interactive Stories**

Nodelex is a visual, node-based editor for designing branching NPC dialogue
trees, conversation logic, and interactive scenarios — with an AI assistant
(powered by Gemini, Claude, or OpenAI) to help you draft branches, suggest
lines, and flesh out characters as you go.

🔗 **[nodelex.online](https://www.nodelex.online)** — website, docs & free web editor
📥 **[Download](https://www.nodelex.online/launch)** — Web Editor, Lite Editor, Desktop App, and Unity Package

<p align="center">
  <img src="docs/images/hero-canvas.gif" alt="Building a branching dialogue tree on the Nodelex node canvas" width="800">
</p>

---

## What is Nodelex?

Writing branching dialogue directly in code or flat script files makes it
hard to see the overall shape of a conversation, and easy to create dead
ends or broken branches. Nodelex turns that structure into something you
can see and edit directly — drag, connect, and reorder nodes to build NPC
conversations the way you'd sketch them on a whiteboard.

It's built for game developers and writers working on:

- NPC dialogue systems
- Branching narrative / interactive fiction
- Visual novel scripts
- Tabletop or scenario planning docs
- Any project that needs structured, branching conversation logic

## Features

- **Visual node-based canvas** — Dialogue, Statement, Event, and End nodes,
  connected to map out exactly how a conversation can unfold
- **AI assistant built in** — draft dialogue branches, generate lines, or
  flesh out character personalities using Gemini, Claude, or OpenAI
- **Engine-agnostic by design** — works as a standalone tool with JSON/CSV
  export for custom pipelines
- **Unity export** — available now via a dedicated Unity Package (Unity 6
  ready), exporting trees as `DialogueTreeSO` / `DialogueNodeSO`
  ScriptableObjects with a lightweight `DialogueRunner` and C# events
- **Unreal Engine export** — coming soon

<p align="center">
  <img src="docs/images/ai-assistant.gif" alt="Nodelex AI assistant suggesting a dialogue branch" width="800">
</p>

## Unity Integration

Export any dialogue tree directly into Unity 6 as ScriptableObject assets —
no manual data wiring, no singleton pattern to fight against. Each tree
becomes a `DialogueTreeSO`, each node a `DialogueNodeSO`, and characters
become `CharacterSO` assets, all driven by a lightweight `DialogueRunner`
using C# events.

<p align="center">
  <img src="docs/images/unity-export.png" alt="Nodelex-exported DialogueTreeSO assets shown in the Unity Inspector" width="800">
</p>

## Ways to use Nodelex

| | |
|---|---|
| 🌐 **[Web Editor](https://editor.nodelex.online)** | Full-featured browser-based editor — projects, characters, event library. No install required. |
| ⚡ **[Lite Editor](https://www.nodelex.online/editor)** | Free, in-browser editor for quickly sketching a conversation flow. No sign-up. |
| 💻 **Desktop App** | The full Nodelex experience with AI-assisted dialogue generation and one-click Unity export. [Download here](https://www.nodelex.online/launch). |
| 🎮 **Unity Package** | Import dialogue trees directly into Unity 6 as ScriptableObjects. [Download here](https://www.nodelex.online/launch). |

## How it compares

Nodelex sits alongside tools like [Yarn Spinner](https://www.yarnspinner.dev/),
[Ink](https://www.inklestudios.com/ink/), Articy:Draft, the Dialogue System
for Unity, and [Twine](https://twinery.org/) — but is built around a visual,
node-based canvas with AI assistance and a direct path to Unity (and soon
Unreal) export.

## Documentation

Full docs, guides, and the Unity Package integration walkthrough are at
**[nodelex.online/docs](https://www.nodelex.online/docs)**.

## Report a Bug / Get in Touch

Found an issue or have feedback? [Contact us](https://www.nodelex.online/contact)
or open an issue in this repository.

---

⭐ If Nodelex is useful for your project, consider starring this repo — it
helps other developers find it.
