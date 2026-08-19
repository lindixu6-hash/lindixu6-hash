# Production AI Agent Engineering

Full-stack AI Agent developer building executable evals, tool-security
boundaries, context systems, and human-gated workflows.

全栈 AI Agent 开发者，专注可执行评估、工具安全、上下文工程与人在回路工作流。

[![Awesome Agentic Engineering](https://img.shields.io/github/stars/lindixu6-hash/awesome-agentic-engineering?style=flat-square&label=awesome-agentic-engineering&logo=github)](https://github.com/lindixu6-hash/awesome-agentic-engineering)
[![Release](https://img.shields.io/github/v/release/lindixu6-hash/awesome-agentic-engineering?style=flat-square)](https://github.com/lindixu6-hash/awesome-agentic-engineering/releases/latest)
[![CI](https://github.com/lindixu6-hash/awesome-agentic-engineering/actions/workflows/ci.yml/badge.svg)](https://github.com/lindixu6-hash/awesome-agentic-engineering/actions/workflows/ci.yml)

## [Awesome Agentic Engineering](https://github.com/lindixu6-hash/awesome-agentic-engineering)

**Not another resource list:** an executable production-readiness gate for AI
agents, maintained in English and Simplified Chinese.

**不是另一份资源清单：** 一套可执行、可审查、完整中英文同步的 AI Agent
生产就绪门禁。

| Current evidence / 当前证据 | Verified result / 已验证结果 |
| --- | --- |
| Release | [`v0.18.2`](https://github.com/lindixu6-hash/awesome-agentic-engineering/releases/tag/v0.18.2) |
| Deterministic tests | `151` total: `148` pass, `0` fail, `3` optional integrations skipped |
| Prompt-injection fixtures | `8/8` across reference, LangGraph.js, and OpenAI Agents SDK runtimes |
| Provenance | Separate producer + SHA-pinned verifier, authority-policy digests, GitHub OIDC/Sigstore attestation |
| Starter supply chain | Generated workflows pin `actions/checkout` to the reviewed v7.0.1 commit SHA |
| Governance | CFF 1.2 citation, CODEOWNERS, funding boundaries, protected `main` |
| Distribution | Verified npm tarball contract; npm publication remains explicitly pending |

| Try / 使用 | Integrate / 接入 | Inspect evidence / 查看证据 | 中文 |
| --- | --- | --- | --- |
| [Web scorecard](https://lindixu6-hash.github.io/awesome-agentic-engineering/) | [Five-minute fail-closed setup](https://github.com/lindixu6-hash/awesome-agentic-engineering/blob/main/docs/quickstart.md) | [Attested eval provenance](https://github.com/lindixu6-hash/awesome-agentic-engineering/blob/main/docs/evidence-provenance.md) | [中文 README](https://github.com/lindixu6-hash/awesome-agentic-engineering/blob/main/README.zh-CN.md) |
| [OpenAI Agents SDK eval](https://lindixu6-hash.github.io/awesome-agentic-engineering/openai-agents-eval/) | [Public JSON Schemas](https://lindixu6-hash.github.io/awesome-agentic-engineering/schema/agent-card.schema.json) | [Source-linked incidents](https://github.com/lindixu6-hash/awesome-agentic-engineering/blob/main/docs/production-incidents.md) | [中文 Schema 指南](https://github.com/lindixu6-hash/awesome-agentic-engineering/blob/main/schema/README.zh-CN.md) |

### Adoption status / 采用状态

- [AI Content Workflow Skills](https://github.com/lindixu6-hash/ai-content-workflow-skills)
  is a same-maintainer consumer. Its score gate passes at 12/20, while its
  `draft-only` profile and three launch blockers remain visibly failing.
- [PaperSage #149](https://github.com/0verL1nk/PaperSage/pull/149) is an
  independent Agent Card adoption PR under maintainer review. It is not counted
  as adoption unless merged.

### Upstream contribution / 上游贡献

- [mac-developer-bridge #4](https://github.com/alexanderradahl/mac-developer-bridge/pull/4):
  a poisoned-repository adversarial harness merged after the upstream owner
  reproduced the evidence and CI passed. This is a merged upstream contribution,
  not adoption or endorsement of Awesome Agentic Engineering.

### Open-source maintenance / 开源维护

- Invited as a Write collaborator for
  [`tickernelz/opencode-mem`](https://github.com/tickernelz/opencode-mem), a
  1.3k+ Star local-first memory plugin for coding agents.
- Independently reviewed, verified, and merged
  [#248](https://github.com/tickernelz/opencode-mem/pull/248),
  [#256](https://github.com/tickernelz/opencode-mem/pull/256), and
  [#260](https://github.com/tickernelz/opencode-mem/pull/260). Exact merge or
  cumulative `main` commits passed six-platform package smoke on Ubuntu,
  Windows, and macOS Intel/Apple Silicon.
- Authored fixes [#257](https://github.com/tickernelz/opencode-mem/pull/257)
  and [#258](https://github.com/tickernelz/opencode-mem/pull/258) are clean,
  mergeable, and six-platform green, but remain explicitly pending independent
  review. This is Collaborator evidence, not a Maintainer or ownership claim.

### Independent validation / 独立验证

- [EvalRepro #31](https://github.com/seva9523/EvalRepro/pull/31) merged a
  pinned-revision, hash-only reproduction of the `v0.15.0` to `v0.16.0`
  eight-file release contract. The external workflow detected exactly the three
  intended generated-workflow changes, with its standard matrix and public-source
  reproduction passing. This records public design-partner validation, not
  adoption or endorsement.

### External positioning / 外部定位

- [awesome-ai-security-tools #52](https://github.com/scadastrangelove/awesome-ai-security-tools/pull/52)
  merged the project into its 1k+ Star Watchlist and explicitly classified it
  as a broader, self-declared readiness gate rather than a security scanner or
  enforcement control. The entry also records that the project is new, has
  minimal adoption, and its listed consumer is author-operated. This is
  Watchlist inclusion and external positioning review, not adoption,
  certification, or endorsement.

## Open Source Focus / 开源方向

- Agent evaluation and reliability / Agent 评估与可靠性
- MCP and tool security / MCP 与工具安全
- Human-in-the-loop workflow design / 人在回路的工作流设计
- Context engineering and multi-agent systems / 上下文工程与多智能体系统
