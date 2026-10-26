# skeptical-content-trend-triangulation (Grok skill)

A daily topic-selection procedure: triangulate Google Trends RSS, Techmeme and trade press, never trust one AI search tool's denial, and log runner-ups.

## Install

This repo is the skill folder: `SKILL.md` sits at the top level. Clone it into a skills directory.

User scope (all your projects), macOS or Linux:

    mkdir -p ~/.grok/skills
    git clone https://github.com/skeptical-agency/skeptical-content-trend-triangulation.git ~/.grok/skills/skeptical-content-trend-triangulation

User scope, Windows PowerShell (assumes Grok reads skills from `$HOME\.grok\skills`):

    New-Item -ItemType Directory -Force "$HOME\.grok\skills"
    git clone https://github.com/skeptical-agency/skeptical-content-trend-triangulation.git "$HOME\.grok\skills\skeptical-content-trend-triangulation"

Project scope (shared via git):

    mkdir -p .grok/skills
    git clone https://github.com/skeptical-agency/skeptical-content-trend-triangulation.git .grok/skills/skeptical-content-trend-triangulation

No git? Download the repo as a zip from GitHub and unzip it into a folder named `skeptical-content-trend-triangulation` inside the skills directory.

More skills: [skeptical-agency/grok-skills](https://github.com/skeptical-agency/grok-skills).

## Requirements

- `curl` (included on macOS, current Windows 10 and 11, and most Linux systems)

## Use

Ask Grok things like:

> pick today's top 2 topics for my tech shorts channel using the triangulation stack and log the runner-ups

SKILL.md has a plain-English intro, a worked example, the exact commands and the known pitfalls.

## Responsible use

Use public feeds politely and follow each source's terms. Verify stories against the primary source before publishing.

## License

MIT, see LICENSE.
