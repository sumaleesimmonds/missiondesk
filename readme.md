# MissionDesk

An AI-powered platform that combines grant matching, loan readiness scoring,
and impact storytelling into one workspace for nonprofits and small businesses.

Built in alignment with Pacific Community Ventures and the International
Rescue Committee. Powered by the Anthropic Claude API.

Read the full impact statement: IMPACT.md

---

## Important note on this demo

This is a frontend MVP. The Claude API integration is fully coded but
requires an API key to function live. For security reasons, no key is
included in this public repository.

To run it with live AI responses:

  1. Clone this repo
  2. Open index.html in a text editor
  3. Set up your own backend or proxy to securely call the Anthropic API
     with your own key (never hardcode a key directly into client-side
     JavaScript in a public repository)
  4. Open index.html in a browser

Without an API connection, the interface and navigation are fully
explorable, but the "Find my grants," "Check my readiness," and
"Write my story" buttons will return an error instead of a generated result.

---

## What it does

MissionDesk brings together three tools that nonprofits and small business
owners would otherwise need separate specialists, software, or consultants for:

  GRANT MATCHING AND DRAFTING
    Describe your organization and get matched to realistic grant
    opportunities, with reasoning for each match.

  LOAN READINESS ADVISOR
    Get a readiness score, strengths and gaps, and realistic funding
    program types for underserved small business owners.

  IMPACT STORY GENERATOR
    Turn program data into a donor email, annual report section, or
    social media caption, ready to copy and use.

---

## How it's built

A single self-contained index.html file containing:

  - A marketing landing page with hero section, tool showcase, and
    "how it works" walkthrough
  - A demo sign-in flow (no real authentication — name and organization
    only, for demonstration purposes)
  - A full app shell with sidebar navigation and a live dashboard
  - Three tool pages, each with a form that calls the Claude API directly
    and renders the generated result inline

No frameworks, no build step. Plain HTML, CSS, and JavaScript.

---

## Design choices

The visual direction uses a warm paper background, deep moss green, and
clay orange accents rather than a typical cold tech-startup palette,
intentionally evoking trust, groundedness, and community rather than
venture-backed Silicon Valley aesthetics. Serif headlines (Lora) paired
with a clean sans-serif body (Inter) signal credibility without feeling
corporate or sterile.

---

## Why one platform instead of three separate tools

Nonprofits and small business owners do not experience their challenges
in isolation. The same overworked executive director who needs grant
funding also needs to write a compelling annual report. The same small
business owner applying for a CDFI loan also needs to communicate their
impact to potential lenders. Combining these tools into one workspace
reflects how the work actually happens.

---

## Project structure

  missiondesk/
  |__ index.html      Full application (marketing site, login, app, tools)
  |__ README.md        This file
  |__ IMPACT.md         Humanitarian and ethical impact statement

---

## Tags

ai anthropic claude saas nonprofit small-business social-impact
cdfi grant-writing pacific-community-ventures economic-justice llm

---

## License

MIT — free to use and adapt. Built to demonstrate what's possible when
AI tools are designed specifically for under-resourced organizations.
