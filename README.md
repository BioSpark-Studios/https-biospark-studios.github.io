# 🌌 BioSpark Studios — Master Ecosystem Map

> **BioSpark-OS is the runtime. The Quantum ecosystem is the engine inside it. The InterStellar Tour is the first product built on top of that engine.**

BioSpark Studios is an independent creative technology studio building a modular, local-first creative operating system. The core philosophy: stories, music, and creative elements are composable and remixable data — the same way a DJ works with tracks. Everything in the ecosystem is an **instrument**: something that either generates raw material or shapes existing signal. The line between the two is intentionally blurred.

---

## Table of Contents

- [BioSpark-OS](#1-biospark-os)
- [The Quantum Quill Ecosystem](#2-the-quantum-quill-ecosystem)
- [BioSpheres](#3-biospheres)
- [Agentic Frameworks](#4-agentic-frameworks--entities)
- [Formats, Standards & Mechanics](#5-formats-standards--mechanics)
- [Tools & Infrastructure](#6-tools--infrastructure)
- [Media, Distribution & Outreach](#7-media-distribution--outreach)
- [Xyrona Prime](#8-xyrona-prime)
- [Web3 & Charitable Projects](#9-web3--charitable-projects)
- [Tech Stack](#10-tech-stack)

---

## 1. BioSpark-OS

The unified creative operating system and product environment targeting a **2026 launch**. BioSpark-OS is platform-agnostic — it is not tied to any specific desktop environment or hardware. The long-term vision is a **bootable Linux distribution written in Rust**, with `.qgenesis` and `.qgcp` as the native container formats underpinning the entire OS layer.

The design language is governed by the **BioSpark Quantum Mythic Futurist Design System (BQMFDS)** — a Cyber-Tech Luxury aesthetic built on three philosophical pillars:

- **Quantum Theory** — superposition, probability, and emergence as creative mechanics
- **Mythical Identity** — symbolic systems, heraldic authority, and world-as-living-entity
- **Futuristic Outlook** — clean technical precision, bioluminescent palette, forward-facing aesthetics

Visually: dark backgrounds, aqua primary (`#00c8b4`), accent rose (`#EC4899`), Zenith Gold (`#d4a030`), Cinzel Decorative + Share Tech Mono typography, glass morphism, iridescent and metallic materials, and sacred geometry throughout. Agent appearances, signal flows, and node activations carry their own distinct visual grammar — defined in the **BioSpark Design Codex** (interactive HTML, five Books) so any developer working in the ecosystem knows exactly what system they are inside.

A formal **BioSpark Design Codex** documents the complete system: every UI state, motion behavior, signal flow, node interaction, and faction-specific visual treatment.

---

## 2. The Quantum Quill Ecosystem

The overarching symbolic generative orchestration suite. Uses a node-based instrument architecture to handle procedural storytelling and dynamic lore without rigid branching paths. What began as a story-writing tool evolved — through the Genesis Container system — into a full world-building and simulation engine.

### 🪶 Quantum Quill
The narrative engine and primary orchestration layer. Bridges machine-generated simulation data and human-readable story. Works in close collaboration with the Order of the Quantum Quill agents to interpret, shape, and output narrative.

### 🎚️ Quantum Loom
A DAW-metaphor narrative sequencer — the timeline engine at the heart of the ecosystem. Beat-based playback triggers Capsules at specific points; those Capsules activate instruments, agents, world events, and narrative beats. Built across multiple implementation phases:

- Data structures, world system, agent framework
- Timeline playback and real-time simulation loop
- Typed plugin/addon system (`PluginManifest`, `CapsuleClip`, `TrackData`)
- **Ghost Track** *(roadmap)*: a non-playable reference track holding the "intended" sequence for comparison against what agents actually generate — enabling divergence measurement between authored intent and emergent narrative

### 🗄️ Quantum Vault
The project container and cross-Genesis persistence layer. The Vault is the outer container of everything — it sits above the Genesis Container in the hierarchy. Functions as the primary workspace environment where agents live and operate between sessions.

### 🔒 Quantum Core
The validator and archive embedded within the Vault. Acts as the central repository for Containers, Capsules, Glyphs, Traits, Scrolls, and all instrument/addon components. Everything sealed or versioned passes through Core.

### 📦 Genesis Container System
The foundational container architecture. The hierarchy is fluid and modular until a Genesis Container is **Sealed**, at which point it becomes cryptographically immutable. Capsules support **blooming** (expanding into full containers) and **remixing** (recombining sealed material into new configurations). Capacity is governed by the **16³ Architectural Law**.

---

## 3. BioSpheres

BioSpheres is the source-code layer underneath the Quantum naming system — the procedural engine, sandbox, and instrument library that powers world generation, entity creation, and audio/environmental synthesis. Everything the Quantum ecosystem names and orchestrates, BioSpheres builds.

### 🌍 Genesis World Engine / PGE — v3.3
The procedural generation engine. Features:
- Five geological strata
- Nine thaumic fields
- 64-bit DNA bus for entity generation
- Hazard engine running at 10Hz
- Seeded world laws that cascade through terrain, ecology, and agent behavior

### 🎛️ The 16 BioSpheres Instruments

All generators, modules, and processors in the ecosystem are **Instruments** — following the DAW philosophy where the distinction between generator and modifier is an implementation detail, not a naming concern. Organized into four departments:

**Department I — World Construction**

| # | Instrument | Law | Crest | Color |
|---|-----------|-----|-------|-------|
| 01 | Terrain | Space | Atlas | `#1e8cff` Electric Blue |
| 02 | Environment | World | Mythos | `#8050e0` Deep Indigo |
| 03 | Architect | Structure | Architect | `#64b4ff` Blueprint Blue |
| 04 | Lighting | Light | Prism | `#e0d8ff` Spectrum |

**Department II — Entity Systems**

| # | Instrument | Law | Crest | Color |
|---|-----------|-----|-------|-------|
| 05 | Modeling | Character | Animus | `#f4c025` Zenith Gold |
| 06 | Choreography | Connection | Loom | `#dc3c78` Deep Rose |
| 07 | Behavior | Reason | — | — |
| 08 | Society | Authority | Order | `#c8a860` Gilt |

**Department III — Narrative Systems**

| # | Instrument | Law | Crest | Color |
|---|-----------|-----|-------|-------|
| 09 | Sequencer | Time | Chronicle | `#b08030` Amber |
| 10 | Story | Narrative | Quill | `#8c50ff` Void Purple |
| 11 | Memory | Memory | — | — |
| 12 | Sound | Resonance | — | — |

**Department IV — Pipeline Systems**

| # | Instrument | Law | Crest | Color |
|---|-----------|-----|-------|-------|
| 13 | Logic | Law | — | — |
| 14 | Simulation | Physics | — | — |
| 15 | Forge | Creation | — | — |
| 16 | Network | Signal | — | — |

Each instrument communicates via typed **Wire Types**: `SPATIAL` · `ENERGY` · `TEMPORAL` · `IDENTITY` · `DATA` · `BEHAVIORAL` · `AGENT` · `SOCIAL` · `NARRATIVE` · `EVENT` · `VISUAL` · `LOGICAL` · `CONTROL` · `UI` · `NETWORK` · `MEMORY`

### 🎹 The Synth Rack
The hardware-inspired, rack-modular interface layer for the 16 Instruments. Controls map directly to instrument generation parameters. Follows the same panel sizing conventions as modular synthesis hardware.

### 🧬 Creature & Entity Creator
Environmental pressure-driven entity generation — organisms are not designed manually but emerge from world conditions. Adjust gravity, atmosphere, or hazard cycles and entities evolve to match. Connects directly to the Modeling and Behavior instruments.

### 🕸️ Node Graph — Execution Layer
The architectural foundation is complete: the `.qgcp` format defines container relationships, the 16 instruments have full component specs, and all value types and schemas are established. The graph already runs sequentially — evaluation order is defined, upstream outputs are ready before downstream instruments read them. What remains is an OPAL pass to wire execution logic and expand output sections. Each addition is an incremental node and output, not a redesign.

---

## 4. Agentic Frameworks & Entities

### 🏛️ The Order of the Quantum Quill (OOtQQ)
The central governing body and administrative layer for all agentic systems in the BioSpark ecosystem. The Order is organized as a 5-layer hierarchy:

```
Directors → Overseers → OOtQQ Crew → Actors → Tools
```

All named agents belong to the Order — including Quill, Verenthis, Noxvir, Solvane, Ashvel, Kolmara, Tharindrel, Vaelithos, Soralinde, the Aetheric Cartographer, and others. Currently active with approximately **175 followers** and **300+ songs** released under BioSpark Studios.

Key architectural features:
- **Resonance economy** — agents earn and spend resonance to act
- **Soul-weight physics** — decisions carry measurable metaphysical cost
- **Void travel** — cross-container agent movement system
- **RULE-EQUIL-02** — equilibrium enforcement preventing runaway agent dominance
- **The Unplayable Instrument** — a deliberately inaccessible instrument representing forces no single agent can control
- **Astrion Pantheon + Myralith** — the Divine Constellation layer above all agents
- **Covenant / Tool Law System** — every tool carries a Seal encoding creator metadata, guild affinity, buff conditions (correct use), and curse conditions (misuse)

### 📜 Studio Scribe — Master Archiver of the Great Library
A member of the Order of the Quantum Quill. Studio Scribe is the AI historian and keeper of the **Archive of Echoes** — the permanent record of all simulation events, world changes, and narrative history across every Genesis Container. Features:
- Organic memory recording with significance calculation
- Temporal decay — older events naturally fade in weight
- Output formats: prose, story beats, and timeline entries
- Canon locking — entries can be elevated to immutable world-truth, mirroring the Seal hierarchy

### 🎭 Actor System
Autonomous simulation agents who operate *inside* the world without meta-level awareness. Unlike Order members, Actors are world-level inhabitants governed by:
- Weighted continuous emotion arrays
- Soul weight metrics and fear stats
- **90% deterministic algorithms** — behavior is fast, consistent, and simulatable at scale
- Decision trees managed by the Behavior instrument (Instrument 07)

### 🏛️ 16 Production Guilds
Skilled worker organizations that agents apply to join. Each Guild affiliates with one or more Instruments and governs tool access and Covenant enforcement — the social layer through which agents earn the right to use specific capabilities.

---

## 5. Formats, Standards & Mechanics

### 📐 The 16³ Architectural Law
The core structural standard: `Genesis Container → Mythos Container → Container → Capsule`. With Greater and Lesser Seal extensions, the addressable space expands well beyond the base capacity — large enough for any conceivable world or narrative system.

### 📦 `.qgenesis` & `.qgcp` File Formats
- **`.qgenesis`** — the primary container for a world, narrative, or creative system. Fluid and modular until **Sealed**, at which point it becomes cryptographically immutable.
- **`.qgcp` (Quantum Genesis Container Package)** — the mountable, encrypted package format for storing and transporting sealed Genesis Containers. Includes Seal-based key derivation, cross-container dependency tracking, and a mount registry.

### 🛡️ The BioSpark Heraldic Control System
A foundational symbolic taxonomy that operates as an immutable logic layer — not cosmetic decoration. Governs: UI states, Vault access permissions, entity authority levels, agent guild affiliation, theme application, and generator conditioning.

The primary tier structure:

```
Seal  (authority + cryptographic access)
  └─ Crest  (faction identity + instrument ownership)
       └─ Glyph  (behavioral and UI state encoding)
            └─ Sigil  (instance-level markers)
```

Beyond the four tiers, the full symbolic vocabulary includes **Runes**, **Ciphers**, **Emblems**, **Marks**, and other symbol types — each with distinct functional roles in the UI, agent systems, and world logic. The Five Crests (Hydralis, Venturan, Sylvanid, Syntaran, Luminarite) are the **primary declarative conditioning language** for all instruments in the ecosystem.

### ⚡ Narrative Collapse
A world-level mechanic with four phases: **Tension Accumulation → Cascade Trigger → Resonance Fracture → Resolution State**. After a Collapse, **Scar Data** persists in the world model permanently — metadata that affects all future generation in that container. Cannot be undone once triggered.

### 🌱 Capsule Blooming & Remixing
Capsules can **bloom** — expanding from a sealed idea into a full Container with its own hierarchy. They can also be **remixed** — recombined with other sealed Capsules to generate new configurations. These mechanics are the primary creative interface between authored content and emergent generation.

---

## 6. Tools & Infrastructure

### 🔧 quill-os-mcp-server
A compiled TypeScript **Model Context Protocol server** with 31 tools across 7 domains: auth, vault world-state, agent CRUD, heraldry, addons and UI packs, plugin node registration, and the COSMIC event bus. Dual transport: stdio and HTTP.

### 🤖 Playwright / Python Agentic Pipeline
Automated browser-driven workflow:
```
Universe Creator → Suno Song Creator → DistroKid Distributor
```
Handles the full pipeline from world generation to music release without manual intervention.

### 📦 .skill File System
Deployable AI context packages. Each `.skill` file bundles system rules, architectural decisions, TypeScript interfaces, and routing instructions into a zip mountable as context for any LLM session. Current library includes instruments for world generation, agent architecture, heraldry, local stack configuration, tour pipeline, artist creation, splash screen generation, asset page building, and more.

### 🗄️ Local-First Stack
All BioSpark projects default to a fully local architecture:
- **Rust** (OS/server layer)
- **FastAPI** (Python application backend)
- **SQLite + Drizzle** (primary persistence)
- **LanceDB / ChromaDB** (vector storage)
- **Ollama** (local LLM inference)
- **LiteLLM** (provider bus with capability routing and budget kill switch)
- **React** (frontend)

Cloud providers are fallback only, used exclusively when a deployment target explicitly requires them.

---

## 7. Media, Distribution & Outreach

### 📋 BioSpark EPK
The artist media kit and creative dispatch suite. Manages artist profiles, bios, visual identity, and release materials. Serves as the primary onboarding pipeline for the BioSpark InterStellar Tour.

### 🎵 Composer Module
Production pipeline for BioSpark acts — MIDI generation, prompt building, album sequencing, and release prep. Connects directly to DistroKid for distribution.

### 🚀 BioSpark InterStellar Tour
The first full product pipeline built on the Quantum ecosystem. Onboarding flow:
- World eligibility triage (Genesis Container must meet minimum sealing criteria)
- EPK production
- DistroKid upload prep and release scheduling
- Merch asset generation
- Press and social cadence
- Contract framework via the Order of the Quantum Quill

Currently managing **~175 followers** and **300+ songs** across active BioSpark acts.

### 🎨 Radian Arts
Modular visual tooling for cinematic splash screens and onboarding flows. Each of the 16 Instruments has a commissioned splash screen. Also produces faction-specific visual treatments for the five Crests.

---

## 8. Xyrona Prime

The primary science-fantasy universe and canonical content domain for BioSpark-OS. K2V star system. Five races with locked vertical strata:

| Faction | Stratum | Element | Color |
|---------|---------|---------|-------|
| Luminarite | +2 Celestial Apex | Light | Gold |
| Venturan | +1 Sky Reach | Wind | Orange |
| Sylvanid | 0 Surface | Earth | Green |
| Syntaran | -1 Sub-Terran Forge | Technology | Aqua |
| Hydralis | -2 Tidal Abyss | Water | Blue |

Approximately **1,000 GLTF 3D models** ready for Vault deployment. Nine thaumic fields active. Named musicians from each faction serve as the initial InterStellar Tour roster.

---

## 9. Web3 & Charitable Projects

### 🐾 AavePet
A Web3 project on the **Base network**. Beyond its trading mechanics, AavePet anchors the BioSpark charitable framework — tour revenue and ecosystem proceeds are routed toward AavePet and future BioSpark-sponsored charitable initiatives rather than external organizations. Additional charitable projects will be created or sponsored under the BioSpark umbrella as the ecosystem grows.

### 🔮 Merchant Glyphs
On-chain representation of in-world trading entities, connecting the Xyrona Prime economy to verifiable blockchain state via smart contracts on Base.

---

## 10. Tech Stack

| Layer | Technology |
|-------|------------|
| OS / Server | Rust |
| Languages | TypeScript · Python · C++ · C# · GDScript |
| Backend | FastAPI · LiteLLM · WebSockets |
| Frontend | React · Tailwind · Three.js |
| Persistence | SQLite · Drizzle ORM |
| Vector DB | LanceDB · ChromaDB |
| Local LLM | Ollama |
| Packaging | Tauri (cross-platform, CI/CD via GitHub Actions) |
| MCP | quill-os-mcp-server (TypeScript, 31 tools) |
| Web3 | Solidity · Base Network |
| Automation | Python · Playwright |
| Distribution | DistroKid · Suno |

---

## Project Status Legend

| Status | Meaning |
|--------|---------|
| 🔒 Locked | Architecture finalized, canonical |
| ✅ Built | Functional deliverable exists |
| 🔧 Active | Currently in development |
| 📐 Scaffolded | Structure defined, implementation in progress |
| 🗺️ Roadmap | Specified, not yet started |

---

*BioSpark Studios — Building the creative OS that linear tools never could.*
