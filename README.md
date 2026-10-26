# Claude skills

A collection of Claude Code skills, collected from the skills installed in my Claude sessions.

## Install

```bash
git clone https://github.com/lakshmant006-code/claude-skills.git
cp -r claude-skills/skills/instagram/ig-* ~/.claude/skills/
cp -r claude-skills/skills/anthropic/* ~/.claude/skills/
cp -r claude-skills/skills/brag/brag ~/.claude/skills/
cp -r claude-skills/skills/remotion/remotion-motion-graphics ~/.claude/skills/
```

Copy only the folders you want. Each folder with a `SKILL.md` is one skill.

## Instagram (`skills/instagram/`)

From [Jakeschincariol/instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill), MIT license (see `skills/instagram/LICENSE`). Copy `voice.template.md` to `~/.claude/instagram/voice.md` and fill it in.

| skill | what it does |
| --- | --- |
| `ig-audit` | Post-mortem on what the user has already posted - which reels actually worked, why, and what to stop making |
| `ig-caption` | Write the Instagram caption - the line that survives the "... more" cut, the body, the single ask, the search terms and the three hashtags - and lint it before it goes out |
| `ig-carousel` | Build an Instagram carousel - the cover that earns the swipe, slide-by-slide copy, and the 1080x1350 files to upload |
| `ig-comment` | Write comments on other people's Instagram posts and reels that read as a person with an opinion, not a bot |
| `ig-dm` | Write Instagram DMs that get replies - the keyword delivery, the first message to someone who engaged, the collab pitch, and the two follow-ups |
| `ig-human` | Strip the machine fingerprint out of any draft - em dashes, AI slop words, invisible watermark characters - and score it against a five-check detection panel before it goes out |
| `ig-plan` | Build the week on Instagram - what to post, which format, when, and who to engage with |
| `ig-profile` | Score an Instagram profile out of 100 against a 12-part rubric and rewrite the parts that lose points - name field, bio, link, highlights, pinned three, grid |
| `ig-reel` | Write an Instagram Reel from a raw idea - hook options off 26 formulas, the spoken script, the on-screen text, and a timed beat sheet - in the user's own voice and scored before they shoot it |
| `ig-reply` | Handle the comments under the user's own reels and posts - draft replies to the ones worth answering, sorted by which ones are |
| `ig-repurpose` | Turn one long asset - a YouTube video, podcast, livestream, newsletter, blog post or client call - into a week of reels and carousels |
| `ig-story` | Write the day's Instagram Stories - the frame-by-frame sequence, which stickers to use where, and the one that moves people into the DMs |
| `ig-viral` | Go and find the reels that are actually working right now in the user's niche, rank them by how far each beat its own account, name the hook formula each one used, and turn that into a swipe file they can shoot from |

## Brag (`skills/brag/`)

From [latent-spaces/brag](https://github.com/latent-spaces/brag) v0.5.0, MIT license (see `skills/brag/LICENSE`). Bundled music is "Happy Beats / Business Moves" by Sascha Ende, ende.app (CC BY 4.0). Sound effects are from [Kenney](https://kenney.nl/). Needs Node for `npx hyperframes`.

| skill | what it does |
| --- | --- |
| `brag` | Turn the current project website into a short, polished, shareable launch video using Hyperframes |

## Remotion (`skills/remotion/`)

From [haidrrrry/claude-remotion-skill](https://github.com/haidrrrry/claude-remotion-skill), MIT license (see `skills/remotion/LICENSE`). Needs Node and a Remotion project (`npm install remotion @remotion/cli react react-dom`).

| skill | what it does |
| --- | --- |
| `remotion-motion-graphics` | Create and edit professional motion graphics videos with Remotion (React-based video) |

## Anthropic example skills (`skills/anthropic/`)

Anthropic's skills released under Apache 2.0. Each folder keeps its own `LICENSE.txt`.

| skill | what it does |
| --- | --- |
| `algorithmic-art` | Creating algorithmic art using p5.js with seeded randomness and interactive parameter exploration |
| `benepass-reimbursement` | Submit expense reimbursements through Benepass (app.getbenepass.com) |
| `brand-guidelines` | Applies Anthropic's official brand colors and typography to any sort of artifact that may benefit from having Anthropic's look-and-feel |
| `call-to-book` | Make a phone call to book an appointment or reservation |
| `cancel-unsubscribe` | Cancel a subscription or unsubscribe from a service |
| `canvas-design` | Create beautiful visual art in .png and .pdf documents using design philosophy |
| `event-planning` | Help plan an event — from a birthday dinner to a wedding |
| `file-expenses` | Help submit an expense or reimbursement on any platform |
| `file-form` | Handle small bureaucratic tasks — jury duty responses, parking tickets, passport renewals, DMV forms, permit applications, and other government or administrative paperwork |
| `financial-calculator` | Run financial calculations and scenario comparisons — tax estimates, loan comparisons, retirement projections, rent vs. buy, investment scenarios, and more |
| `frontend-design` | Guidance for distinctive, intentional visual design when building new UI or reshaping an existing one |
| `grocery-shopping` | Help order groceries for delivery |
| `hire-help` | Help find and book a service provider for a task — cleaning, handyman, moving, assembly, yard work, errands, etc |
| `internal-comms` | A set of resources to help me write all kinds of internal communications, using the formats that my company likes to use |
| `learn` | Use this skill when the user wants intellectual understanding — learning how or why something works, not getting a task done or soliciting Claude's judgment |
| `mcp-builder` | Guide for creating high-quality MCP (Model Context Protocol) servers that enable LLMs to interact with external services through well-designed tools |
| `meal-delivery` | Help order food timed to arrive at a specific time |
| `paint` | Paint an original image in a watercolor style by writing code, not by calling an image model |
| `prescription-refill` | Refill a prescription at a pharmacy |
| `return-refund` | Help return an item or request a refund from any retailer |
| `skill-creator` | Create new skills, modify and improve existing skills, and measure skill performance |
| `slack-gif-creator` | Knowledge and utilities for creating animated GIFs optimized for Slack |
| `theme-factory` | Toolkit for styling artifacts with a theme |
| `web-artifacts-builder` | Suite of tools for creating elaborate, multi-component claude.ai HTML artifacts using modern frontend web technologies (React, Tailwind CSS, shadcn/ui) |

## Not included

Anthropic's proprietary skills (docx, pdf, pptx, xlsx, file-reading, pdf-reading, computer-use, chrome-browser, built-in-browser, artifact-emulator) don't allow copies outside Anthropic's services. Skills with no license file (deep-research, docs, google-workspace, import-memory, morning, motion-design, doc-coauthoring, setup-writing-style, product-self-knowledge, session-start-hook) aren't included either. Skills built into Claude Code itself have no source files to copy. All of them are still available in Claude.
