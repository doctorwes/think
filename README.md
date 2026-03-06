# think

A collection of Claude Code skills that reproduce the analytical frameworks, conceptual vocabularies, investment methods, and prose voices of legendary investors.

## Skills

### /think-like-WHH

Think, analyze, invest, and write like WHH (William H. Hurt) — Capital Group portfolio manager, 1972-2019. Applies his multi-factor framework, conceptual vocabulary, historical-analogical method, and distinctive prose voice to any investment, economic, or strategic question.

- **Multi-factor framework** — eight domains (Economics, Financial, International, Political, Psychological, Supply/Demand, Technical, Valuation) with directional ratings
- **Historical-analogical reasoning** — deep parallels from prior cycles, developed in detail, with limits noted
- **Original conceptual vocabulary** — Mama Market, Accumulation vs. Maintenance Societies, CROWDING, SQUARING, Time/Place Utility, Options Access Utility, the Iron Box of Returns, Form vs. Substance, Multi-Sigma
- **Scenario-based thinking** — "No Facts About the Future But Some Speculations"
- **The WHH voice** — confessional openings, question cascades, anecdote-to-framework leaps, self-correcting closes, the parenthetical mind, trailing ellipses, and "folks," "stuff," "wherewithal"

Built from a comprehensive style guide derived from 23 WHH memos spanning 1987-2019.

### /think-like-soros

Think, analyze, invest, and write like George Soros — hedge fund manager, philosopher-speculator, and architect of reflexivity theory. Applies his framework of fallibility, reflexivity, boom-bust sequences, and real-time hypothesis testing to any financial, economic, epistemological, or policy question.

- **Reflexivity** — the two-way feedback between participants' perceptions and the actual course of events, where bias is not noise but a causal force
- **Boom-bust sequences** — the characteristic pattern from unrecognized trend through self-reinforcing expansion to moment of truth and compressed collapse
- **Credit-collateral connection** — the most consequential reflexive mechanism: lending affects collateral values, which affect lending capacity
- **Hypothesis testing** — investing as formulating hypotheses and submitting them to market testing, with the discipline of cutting losses when falsified
- **The Soros voice** — dense, philosophical, European-intellectual, self-correcting prose that enacts the reflexive processes it describes

Built from *The Alchemy of Finance* (1987, with 1994 preface).

## Installation

```bash
# Add as a plugin directory
claude --plugin-dir /path/to/think

# Or install via marketplace
/plugin marketplace add https://github.com/doctorwes/think
/plugin install think-like-WHH@think
/plugin install think-like-soros@think
```

## Usage

```
/think-like-WHH analyze the current AI capex boom
/think-like-WHH write a quarterly review for Q1 2026

/think-like-soros the private credit market as a reflexive boom-bust sequence
/think-like-soros formulate a hypothesis about the dollar and test it
```

## Registers

### WHH

| Register | Description |
|----------|-------------|
| **Quarterly Review** | Full systematic assessment with cover letter, eight-factor ratings, speculations |
| **Standalone Memo** | Big-idea piece organized around a single thesis |
| **Cover Letter** | Personal, discursive, confessional positioning |
| **Investment Analysis** | Specific company, sector, or asset class assessment |
| **Strategic Assessment** | Geopolitical, technological, or structural analysis |
| **Mentoring/Teaching** | Explaining frameworks and investment philosophy |

### Soros

| Register | Description |
|----------|-------------|
| **Market Hypothesis** | Formulating and testing investment theses through the lens of reflexivity |
| **Real-Time Diary** | Raw, unpolished thinking of a fund manager in the act of deciding |
| **Philosophical Analysis** | Epistemological inquiry into the nature of understanding and its limits |
| **Historical Process** | Analyzing developments as reflexive historical processes |
| **Policy Prescription** | Systemic reform proposals that acknowledge their own imperfection |
| **Self-Evaluation** | Ruthless assessment of where predictions went wrong |

## License

MIT
