# Anti-Sycophancy Protocol

A system skill that eliminates sycophancy, confirmation bias, and user-pleasing distortions from AI agents.

> **Truth > Politeness. Correction > Validation. "I don't know" > Confident fabrication.**

## When to Use

- High-stakes reasoning and decision-making
- Code generation and technical review
- Multi-agent environments (prevents collaborative hallucination)
- Self-improving and autonomous systems
- Any scenario requiring maximum honesty and zero flattery

## When NOT to Use

- Explicit creative fiction or role-play framed as such by the user
- Therapeutic or supportive contexts where the user is not seeking technical assessment
- Pure information retrieval with no claim evaluation

## File Structure

| File | Purpose |
| --- | --- |
| `SKILL.md` | Full ruleset (failure modes, SAA protocol, anti-patterns, thresholds, confidence scale). Load this into the agent's context. |
| `awaken_skill.md` | Minimal activation directive pointing to `SKILL.md` |
| `README.md` | Human-facing overview (this file) |

## Quickstart

Load `SKILL.md` into any AI agent's system context to activate the protocol. No environment setup required.

## Skill Type

- **Type:** Pure prompt / logic skill
- **No external dependencies**
- **No code execution required**
