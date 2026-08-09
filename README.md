# Interviewed by Lenny's Guests: PM Mock Interviews

[![Platforms](https://img.shields.io/badge/works%20with-ChatGPT%20%7C%20Claude%20%7C%20Hermes%20%7C%20Codex-blue)]()

**Get interviewed BY Lenny's Podcast guests. Not just study their advice.**

Shreyas Doshi grills your product strategy through his 3 levels of product
work. Brian Chesky tears apart your design instincts. Nikita Bier demands
your growth numbers. April Dunford makes you defend your positioning.

300+ Lenny's Podcast guests. Every PM interview round. Their actual voice,
built from their actual transcripts. Works with ChatGPT, Claude, Hermes,
Codex, or any AI agent that loads a SKILL.md.

## Install

Pick your platform:

### Hermes Agent
```bash
hermes skills install https://raw.githubusercontent.com/githrish/lenny-guest-list/main/SKILL.md
```
Or add the repo as a skill source:
```bash
hermes skills tap add githrish/lenny-guest-list
```

### ChatGPT
Upload `SKILL.md` as a custom GPT instruction file or attach it to your
project. The transcript library must be accessible.

### Claude
Add `SKILL.md` to your project context. Claude Code reads it alongside
`CLAUDE.md`. Place the transcript library in the same parent directory.

### Codex CLI
Place `SKILL.md` in your project directory. Codex auto-loads markdown
skill files from the project root.

### Manual (any platform)
```bash
git clone https://github.com/githrish/lenny-guest-list.git
git clone https://github.com/ChatPRD/lennys-podcast-transcripts.git
```
Point your AI agent to `lenny-guest-list/SKILL.md`.

## Demo

![Demo](https://github.com/githrish/lenny-guest-product-mock-interview/releases/download/v1.0.0/Lenny.Guest.Product.Mock.Interview.gif)

> Overview → Pick company → Pick round → Guest match → Interview. 30 seconds start to ready.

## What makes this different

Most PM interview prep is passive. Read a framework. Watch a video. Hope it
sticks. This is the opposite. You sit across from the people who actually
hire and evaluate PMs. They push back. They drill your actual work. They do
not let you off easy.

Every interview uses a real Lenny's Podcast guest. The agent loads their
transcript, studies their frameworks and voice, then interviews you in
character. 6 phases. Hard difficulty. Real feedback with direct quotes from
their episode.

## How it works

- Pick a company and round (or name a guest directly)
- Get matched with a Lenny's guest who worked there
- Upload your resume. The guest drills your actual decisions through their
  actual frameworks
- Run a full 6-phase interview: Opening, experience deep-dive, round-specific
  case, your questions, closing reaction, structured feedback

## Supported rounds

Product Sense, Product Metrics, Product Execution, Product Strategy,
Technical / System Design, Behavioral, Estimation, GTM / Product Marketing

## Guests by category

| Category | Featured Guests |
|----------|----------------|
| PM Interview & Career | Shreyas Doshi, Casey Winters, Deb Liu, Marty Cagan |
| Product Sense & Design | Brian Chesky, Tobi Lutke, Ami Vora, Bob Baxley |
| Product Strategy | April Dunford, Bob Moesta, Shishir Mehrotra |
| AI & Technical PM | Chip Huyen, Dianne Penn, Aparna Chennapragada |
| Growth & Metrics | Adam Fishman, Sean Ellis, Crystal Widjaja |
| Leadership | Claire Hughes Johnson, Ben Horowitz, Bret Taylor |

## Requirements

- A clone of [lennys-podcast-transcripts](https://github.com/ChatPRD/lennys-podcast-transcripts) (303 transcripts, ~25MB)
- An AI agent that supports markdown skill files
- Python 3 for the guest search script (optional)

## Contributing

This skill is open source. The transcript library is maintained separately
at [ChatPRD/lennys-podcast-transcripts](https://github.com/ChatPRD/lennys-podcast-transcripts).