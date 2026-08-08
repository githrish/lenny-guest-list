# Interviewed by Lenny's Guests: PM Mock Interviews

[![Platforms](https://img.shields.io/badge/works%20with-ChatGPT%20%7C%20Claude%20%7C%20Hermes%20%7C%20Codex-blue)]()

**Get interviewed BY Lenny's Podcast guests. Not just study their advice.**

Shreyas Doshi grills your product strategy through his 3 levels of product
work. Brian Chesky tears apart your design instincts. Nikita Bier demands
your growth numbers. April Dunford makes you defend your positioning.

300+ Lenny's Podcast guests. Every PM interview round. Their actual voice,
built from their actual transcripts. Works with ChatGPT, Claude, Hermes,
Codex, or any AI agent that loads a SKILL.md.

## Quick Start

```bash
git clone https://github.com/githrish/lenny-guest-list.git
git clone https://github.com/ChatPRD/lennys-podcast-transcripts.git
```

Point your AI agent to `lenny-guest-list/SKILL.md`. Done.

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

## Supported platforms

| Platform | How to use |
|----------|-----------|
| **ChatGPT** | Upload SKILL.md as a custom instruction or project file |
| **Claude** | Add SKILL.md to your project context |
| **Hermes Agent** | Place skill in `~/.hermes/skills/` or load via `skill_view` |
| **OpenAI Codex** | Reference SKILL.md in your project |
| **Any agent** | If it reads markdown files, it works |

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