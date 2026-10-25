# Open-source contributions: ashokram-si

I fix real, reported bugs in open-source developer tools and AI infrastructure, mostly in Rust, C++ and Python. Every fix starts with a reproduction on the project's latest code and ships with a regression test that fails without it. I follow each project's own contribution process, including its rules on AI-assisted work.

_Last updated: 2026-10-26_

## At a glance

| Metric | Count |
|---|---|
| Pull requests opened | **2** |
| Merged | 0 |
| Under review | 2 |
| Issue investigations posted | 1 |
| Fixes ready locally, awaiting submission | 2 |
| Projects tracked | 10 |

## Contributions

| Date | Project | Contribution | Link | Status |
|---|---|---|---|---|
| 2026-10-25 | [Tauri](https://github.com/tauri-apps/tauri) | `tauri dev` stopped watching the whole app when `.taurignore` contained `/*`. Fixed to match `.gitignore` semantics, with a unit test and an end-to-end check | [tauri-apps/tauri#16398](https://github.com/tauri-apps/tauri/pull/16398) (fixes #9163) | 🟡 In review |
| 2026-10-25 | [PhotoCraft](https://github.com/storytold/photocraft) | Crash-safety: a panic in a command's pre-checks or bookkeeping crashed the app; now caught and reported as an error, with a regression test | [storytold/photocraft#9516](https://github.com/storytold/photocraft/pull/9516) (fixes #8604) | 🟡 In review |
| 2026-10-25 | [VectorCraft](https://github.com/storytold/vectorcraft) | Root-caused "Offset Path resets 0.1 mm to 1 mm": decimal-comma input is rejected and the field silently keeps its old value. Proposed three fixes for the maintainers to choose from | [comment on #3837](https://github.com/storytold/vectorcraft/issues/3837#issuecomment-6401739771) | 🔵 Awaiting maintainer decision |

Status key: 🟢 merged · 🟡 in review · 🔵 waiting on maintainers · 🔴 closed

## Projects I contribute to

| Area | Projects |
|---|---|
| Developer tooling (Rust) | [Tauri](https://github.com/tauri-apps/tauri), [Biome](https://github.com/biomejs/biome) |
| AI infrastructure | [llama.cpp](https://github.com/ggml-org/llama.cpp), [Hugging Face Transformers](https://github.com/huggingface/transformers), [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) |
| Creative apps in Rust (ArtCraft) | [PhotoCraft](https://github.com/storytold/photocraft), [VectorCraft](https://github.com/storytold/vectorcraft), [FilmCraft](https://github.com/storytold/filmcraft), [EffectCraft](https://github.com/storytold/effectcraft), [LightCraft](https://github.com/storytold/lightcraft) |

## How I work

- **Confirmed bugs only.** I pick issues maintainers have triaged, check nobody else is working on them, and reproduce them on current `main` before writing code.
- **Tested.** Each fix has a test that fails before and passes after, plus the project's own lint/format/test gates run locally.
- **Small and focused.** One issue per PR, minimal diff, the project's PR template filled in completely.
- **Respect each project's rules.** Branch targets, changesets/change files, commit-title conventions and AI policies differ per project and are followed exactly.
- **Transparent about AI.** I use AI assistance (Claude Code) where a project allows it and disclose it as the project asks.
- **Learn from every outcome.** Rejections and process mistakes become written rules I follow on every later contribution.

## Projections

| Horizon | Goal |
|---|---|
| **Nov 2026** | First merged PRs in Tauri and PhotoCraft · submit the llama.cpp and Biome fixes · fix VectorCraft #3837 once the maintainers choose an approach |
| **Dec 2026** | First Hugging Face Transformers contribution · an assigned MCP Python SDK issue · first EffectCraft / LightCraft fixes · **8 merged PRs across 5+ projects** |
| **H1 2027** | **20+ merged PRs** · regular contributor in 2 projects (reviews, triage, repeat fixes) · a feature-level contribution after maintainer discussion |

Progress against these goals is updated as PRs land.
