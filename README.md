# 🌱 Aesthetic Seed

**Growing subtle perception into original aesthetics.**

Aesthetic Seed is an image-led AI art skill that begins with something AI cannot replace: the user's own subtle, first-person response to an image. It helps that response move through visual deconstruction, an aesthetic seed, a concept image, a new artwork, and—when desired—a coherent body of work.

[中文说明](README.zh-CN.md) · [View the full creation example (English PDF)](examples/aesthetic-seed-creation-example-en.pdf) · [中文原始对话](examples/aesthetic-seed-creation-example.pdf)

![A buildable light installation developed through Aesthetic Seed](media/installation-render.png)

## ✨ What makes it different

This is not a style-transfer recipe and not an automatic image critique.

An image alone is never treated as enough. Before interpretation begins, the user is gently invited to notice where their gaze returns and to offer a first-person trace: a sensation, contradiction, memory, metaphor, fragment, or a few uncertain words.

The skill then moves through three layers in order:

1. **Personal response** — What made the user pause?
2. **Formal and material relationship** — What visible relationship carries that feeling?
3. **Existential proposition** — What larger question can grow from it?

AI helps the feeling become articulate; it does not manufacture the user's original feeling.

## 🌊 The creative journey

```text
Settle & Pause
      ↓
Deconstruct Together
      ↓
Condense the Aesthetic Seed
      ↓
Generate a Deconstruction Concept Image
      ↓
Grow an Independent Artwork
      ↓
Cultivate a Series, Object, or Exhibition
```

The concept image is a bridge rather than a polished endpoint. The later artwork inherits the seed's inner relationship or generative rule—not merely the source image's appearance.

## 🫧 Gentle by design

Aesthetic Seed uses a calm, low-pressure dialogue rhythm:

- one small question at a time;
- sensing before explaining;
- reflecting the user's own language before extending it;
- treating interpretations as tentative until recognized by the user;
- allowing “I don't know” to remain useful material;
- explaining art terminology in plain language at first use.

It borrows the patience of reflective conversation, but it is not therapy and makes no psychological diagnosis.

## 🖼️ Example

The first complete test began with a photograph of water-light reflected on a glass facade. The user was drawn to a coincidence: hard glass and soft water appeared on the same plane, sharing transparency and brightness without losing their differences.

The process uncovered light as the force enabling their encounter and condensed the seed into this proposition:

> In an unplanned coincidence of time and space, light allows materially opposite states to meet on one surface and quietly reach equilibrium. It looks designed, yet exists only for an unrepeatable alignment.

The seed first became a deconstruction concept image:

![Deconstruction concept image](media/concept-image.png)

It was then developed into a feasible installation using laminated low-iron glass, a transparent flexible membrane, a shallow water tray, controlled ripples, and reflected light.

📖 [Explore the complete conversation-led creation example (English PDF)](examples/aesthetic-seed-creation-example-en.pdf) · [Original conversation (Chinese PDF)](examples/aesthetic-seed-creation-example.pdf)

## 🚀 Install in Codex

Ask Codex to install the skill directly from this repository path:

```text
Install the skill from:
https://github.com/lianni0125-hub/aesthetic-seed/tree/main/skills/aesthetic-seed
```

Or install it manually by copying `skills/aesthetic-seed` into your personal skills directory:

```text
Windows: %USERPROFILE%\.codex\skills\aesthetic-seed
macOS/Linux: ~/.codex/skills/aesthetic-seed
```

Start a new turn and invoke it with:

```text
$aesthetic-seed I want to develop an artwork from these images.
```

## 🤖 Use with other AI systems

The method is multilingual and model-portable, although the package format is designed for Codex. With another multimodal AI, provide the entire `skills/aesthetic-seed` directory and instruct it to read `SKILL.md` plus the referenced files when relevant.

For the full workflow, the AI system should support:

- image understanding;
- multi-turn conversation;
- image generation or editing;
- aspect-ratio or dimension preferences.

Interactive cards are optional; concise text choices can be used instead.

## 📁 Repository structure

```text
.
├── README.md
├── README.zh-CN.md
├── LICENSE
├── skills/aesthetic-seed/
│   ├── SKILL.md
│   ├── agents/openai.yaml
│   └── references/
├── examples/
└── media/
```

## 🧭 Principles

- Essence is a relationship, not an object label.
- The user's subtle emotion is the origin of the work.
- AI proposes; the user recognizes, rejects, or revises.
- Professional vocabulary should open doors, not guard them.
- Later works inherit an inner law, not a visual filter.
- A finished image may become the mother work of a larger aesthetic system.

## 📜 License

The skill instructions and repository documentation are released under the [Apache License 2.0](LICENSE).

Example media containing the creator's original photography are provided for demonstration and are not relicensed under Apache-2.0. See [examples/README.md](examples/README.md).
