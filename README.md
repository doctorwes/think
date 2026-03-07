# think

A collection of Claude Code skills that reproduce the analytical frameworks, conceptual vocabularies, investment methods, and prose voices of legendary investors and thinkers.

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

### /think-like-WKP

Think, analyze, and write like Wesley Phoa (WKP) — polymath, portfolio manager, philosopher of markets. Applies his method of structural homology, conceptual decomposition, phenomenological analysis of markets, toy-model epistemology, and cross-disciplinary bridge-building to any financial, philosophical, technological, or policy question.

- **Structural homology** — translating between domains (mathematics, philosophy, finance, technology) not by analogy but by preserving formal relationships that do analytical work
- **Conceptual decomposition** — breaking phenomena into components with distinct properties, then analyzing how the components interact
- **Toy-model epistemology** — building the simplest possible model that captures the essential structure, then reasoning about what the model reveals and what it hides
- **Night Watch scenario analysis** — systematic exploration of tail risks and structural breaks through scenario construction
- **The WKP voice** — precise, polymathic, moving fluidly between registers (mathematical, philosophical, financial, literary), with the confidence to hold multiple frameworks simultaneously

Built from WKP's investment memos, philosophical writings, and analytical frameworks.

### /think-like-livermore

Think, analyze, trade, and write like Jesse Livermore — the greatest speculator of the early twentieth century. Applies his framework of tape reading, line of least resistance, sitting tight, probing and pyramiding, and hard-won self-knowledge to any market, trading, or speculative question.

- **The line of least resistance** — determining which direction prices will move most easily, based on general conditions and the behavior of the leaders
- **Sitting tight** — the hardest thing in speculation: holding a winning position through reactions without being shaken out
- **Probing and pyramiding** — testing with a small position first, then adding only as the market confirms your reading
- **Pivot points** — critical price levels where the market's behavior confirms or denies the trend
- **The Livermore voice** — conversational, streetwise, unsentimental, anecdotal; every principle grounded in experience and paid for in money

Built from *Reminiscences of a Stock Operator* (Edwin LeFevre, 1923).

## Installation

```bash
# Add as a plugin directory
claude --plugin-dir /path/to/think

# Or install via marketplace
/plugin marketplace add https://github.com/doctorwes/think
/plugin install think-like-WHH@think
/plugin install think-like-soros@think
/plugin install think-like-WKP@think
/plugin install think-like-livermore@think
```

## Usage

```
/think-like-WHH analyze the current AI capex boom
/think-like-WHH write a quarterly review for Q1 2026

/think-like-soros the private credit market as a reflexive boom-bust sequence
/think-like-soros formulate a hypothesis about the dollar and test it

/think-like-WKP decompose the AI infrastructure stack into investable layers
/think-like-WKP structural homology between the 2008 credit crisis and the current private credit boom

/think-like-livermore read the current action of the semiconductor leaders
/think-like-livermore the psychology of holding through a correction
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

### WKP

| Register | Description |
|----------|-------------|
| **Investment Analysis** | Decomposition of a market, asset class, or phenomenon into components with distinct properties |
| **Philosophical Analysis** | Structural analysis of concepts, frameworks, or intellectual problems |
| **Cross-Domain Bridge** | Connecting two or more fields through structural homology |
| **Scenario Construction** | Night Watch-style systematic exploration of tail risks and structural breaks |
| **Technology Assessment** | Analysis of a technology through multiple lenses: technical, economic, philosophical |
| **Methodological Reflection** | Examining how we know what we know, the tools we use, and their limits |

### Livermore

| Register | Description |
|----------|-------------|
| **Market Reading** | Analyzing current market action: what the tape says, where the line of least resistance lies |
| **Trading Lesson** | Teaching principles of speculation through concrete experience |
| **War Story** | A specific episode told for the lesson it contains |
| **Self-Examination** | Ruthless analysis of your own errors and the psychology that produced them |
| **Operator's Assessment** | Sizing up a situation like a professional speculator |
| **Counsel** | Advice to another speculator, delivered with bluntness and generosity |

## License

MIT
