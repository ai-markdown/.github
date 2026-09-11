<p align="center">
  <img src="https://raw.githubusercontent.com/ai-markdown/.github/main/assets/banner.png" alt="ai-markdown — Markdown for AI, built for the stream." width="100%" />
</p>

<p align="center">
  <strong>From the first token to the final footnote.</strong><br />
  Open-source Markdown rendering for AI applications.<br />
  Incremental streaming, rich content, and thoughtful multilingual typography.
</p>

<p align="center">
  <a href="https://ai-markdown.github.io/">Website</a> ·
  <a href="https://ai-markdown.github.io/examples/">Examples</a> ·
  <a href="https://github.com/ai-markdown/ai-markdown">Source</a> ·
  <a href="https://ai-markdown.github.io/docs/">Documentation</a> ·
  <a href="https://ai-markdown.github.io/docs/guides/framework-transition/">Migration guide</a> ·
  <a href="https://github.com/ai-markdown/ai-markdown/discussions">Discussions</a>
</p>

---

### Made for answers that arrive one token at a time

AI output is a document in motion: a code fence may still be open, a formula unfinished, or a footnote definition yet to arrive. **ai-markdown** brings parsing, document coordination, and framework rendering together to handle those intermediate states.

- **Streaming, with continuity.** Incremental parsing where safe, reusable rendered blocks, and smooth text reveal in React and Vue.
- **Rich answers.** GFM tables and task lists, KaTeX math, and optional Mantine presentation for highlighted code and Mermaid diagrams.
- **Multilingual by design.** CJK-aware delimiter parsing and optional spacing between CJK and Latin text.
- **Room for your UI.** Typed component overrides, typography tokens, and configurable sanitization and URL policies.

### Choose your starting point

| Package                                                                                         | What it brings                                                                            |
| ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| [**@ai-markdown/react**](https://ai-markdown.github.io/docs/react/)                             | React components, hooks, streaming, and document coordination. Start here for React apps. |
| [**@ai-markdown/vue**](https://ai-markdown.github.io/docs/vue/)                                 | Vue components, composables, streaming, and document coordination.                        |
| [**@ai-markdown/react-mantine**](https://ai-markdown.github.io/docs/react/mantine/)             | Mantine typography, code controls, syntax highlighting, and diagrams.                     |
| [**@ai-markdown/core**](https://ai-markdown.github.io/docs/core/)                               | Framework-independent sessions, block plans, and document contributions.                  |
| [**@ai-markdown/engine**](https://ai-markdown.github.io/docs/engine/)                           | Markdown parsing, transforms, and incremental processing.                                 |
| [**@ai-markdown/remark-mark-highlight**](https://ai-markdown.github.io/docs/plugins/highlight/) | A standalone remark plugin for `==highlight==` syntax.                                    |

**Release status:** React, Vue, Mantine, core, and engine are on the stable **v3** train. Follow each package’s documentation for installation, peer dependencies, and styles. The highlight plugin has its own release line.

New to the project? Start with the [React installation guide](https://ai-markdown.github.io/docs/react/#installation). Moving from `@ai-react-markdown`? Follow the [package migration guide](https://ai-markdown.github.io/docs/guides/framework-transition/) — the old React `core` package is now `@ai-markdown/react`; the new `@ai-markdown/core` is the shared runtime.

### Explore the details

[Streaming & performance](https://ai-markdown.github.io/docs/guides/streaming-and-performance/) ·
[Smooth streaming](https://ai-markdown.github.io/docs/guides/smooth-streaming/) ·
[Document coordination](https://ai-markdown.github.io/docs/guides/cross-chunk-coordination/) ·
[CJK typography](https://ai-markdown.github.io/docs/guides/cjk-typography/) ·
[Architecture](https://ai-markdown.github.io/docs/guides/architecture/)

### Build with us

Questions and ideas belong in [Discussions](https://github.com/ai-markdown/ai-markdown/discussions). For bugs, [open an issue](https://github.com/ai-markdown/ai-markdown/issues/new/choose) with the package version, a minimal Markdown sample, and the exact sequence of streaming updates when relevant.

Ready to contribute? Read the [contributor guide](https://github.com/ai-markdown/ai-markdown/blob/main/CONTRIBUTING.md) and [code of conduct](https://github.com/ai-markdown/ai-markdown/blob/main/CODE_OF_CONDUCT.md). For vulnerabilities, follow the [security policy](https://github.com/ai-markdown/ai-markdown/blob/main/SECURITY.md).

<details>
<summary><strong>About the other repositories</strong></summary>

The [`rehype-raw`](https://github.com/ai-markdown/rehype-raw), [`hast-util-raw`](https://github.com/ai-markdown/hast-util-raw), and [`hast-util-from-parse5`](https://github.com/ai-markdown/hast-util-from-parse5) repositories are forks of upstream unified ecosystem utilities. They support dependency maintenance; the main project, packages, and documentation live in [`ai-markdown/ai-markdown`](https://github.com/ai-markdown/ai-markdown).

</details>

---

<p align="center">Markdown rendering for AI applications · Streaming · Math · CJK typography<br /><sub>Open source · MIT licensed · Built with the unified ecosystem</sub></p>
