# think-like-WHH

A Claude Code plugin that reproduces the analytical framework, conceptual vocabulary, investment method, and prose voice of WHH (William H. Hurt), portfolio manager at Capital Group Companies from 1972 to 2019.

## What it does

Invoke `/think-like-WHH` with any investment, economic, or strategic question and get an analysis in WHH's distinctive style:

- **Multi-factor framework** — eight domains (Economics, Financial, International, Political, Psychological, Supply/Demand, Technical, Valuation) with directional ratings
- **Historical-analogical reasoning** — deep parallels from prior cycles, developed in detail, with limits noted
- **Original conceptual vocabulary** — Mama Market, Accumulation vs. Maintenance Societies, CROWDING, SQUARING, Time/Place Utility, Options Access Utility, the Iron Box of Returns, Form vs. Substance, Multi-Sigma
- **Scenario-based thinking** — "No Facts About the Future But Some Speculations"
- **The WHH voice** — confessional openings, question cascades, anecdote-to-framework leaps, self-correcting closes, the parenthetical mind, trailing ellipses, and "folks," "stuff," "wherewithal"

## Installation

```bash
# Add as a plugin directory
claude --plugin-dir /path/to/think

# Or install via marketplace (if added to one)
/plugin marketplace add https://github.com/doctorwes/think
/plugin install think-like-WHH@think
```

## Usage

```
/think-like-WHH analyze the current AI capex boom
/think-like-WHH write a quarterly review for Q1 2026
/think-like-WHH assess China's semiconductor buildout
/think-like-WHH what would you make of the current bond market
```

## Registers

The skill adapts to the type of analysis requested:

| Register | Description |
|----------|-------------|
| **Quarterly Review** | Full systematic assessment with cover letter, eight-factor ratings, speculations |
| **Standalone Memo** | Big-idea piece organized around a single thesis |
| **Cover Letter** | Personal, discursive, confessional positioning |
| **Investment Analysis** | Specific company, sector, or asset class assessment |
| **Strategic Assessment** | Geopolitical, technological, or structural analysis |
| **Mentoring/Teaching** | Explaining frameworks and investment philosophy |

## Source material

Built from a comprehensive style guide derived from 23 WHH memos spanning 1987–2019, covering quarterly reviews, standalone memos, and the autobiographical "Working Model for Investing" (2019).

## License

MIT
