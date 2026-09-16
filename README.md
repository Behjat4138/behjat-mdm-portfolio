# BehjatOS

A portfolio website disguised as an operating system. Instead of scrolling through sections, visitors boot into a desktop, click icons to open draggable windows, and interact with a working terminal.

**Live:** [behjat4138.github.io/behjat-mdm-portfolio](https://behjat4138.github.io/behjat-mdm-portfolio/)

---

## What happens when you visit

1. A boot sequence loads with progress messages
2. You land on an illustrated desk scene — mini-B sitting at her computer, coffee steaming, sun through the window
3. Click the monitor to zoom *into* the screen
4. You're now on a desktop with icons, a menu bar, a running clock, and a draggable sticky note

Every section of the portfolio is an app:

| Icon | App | What it does |
|------|-----|-------------|
| 📄 | About.txt | Who I am, in a TextEdit window |
| 🗂️ | Projects | Finder-style sidebar with 6 case studies, each with its own animated diagram |
| 🔬 | Research | Document viewer with venue stamps (CHI 2027, SIGCHI 2027) |
| 🗺️ | Journey | Timeline of roles and internships |
| ⌨️ | Terminal | Actually works — type `help`, `hire`, `open projects`, `curtains`, `sudo` |
| ✉️ | Contact | Pre-written mail compose window with email/LinkedIn/GitHub |

## The details that make it

- **Theater curtains** — every window opens with red velvet curtains parting to reveal the content. Switching projects in the Finder triggers a full stage transition: curtains close, set changes, curtains reopen on the new project
- **Per-project animations** — data dots flowing through an agent graph (BoA Complaint Analyzer), queries routing down three paths (MedHop-Agent), a typing indicator in a phone UI (PTSDCare), a car lapping a racing line (LapZero), a rotating wireframe (SMVG), a scan line over a text corpus (Low-Resource NLP)
- **Working terminal** with commands: `whoami`, `projects`, `research`, `certs`, `visa`, `contact`, `open <app>`, `curtains`, `desk`, `hire`, `sudo`, `ls`, `clear`
- **Mini-B** — a mascot that sits in the corner, comments once per app you open, and cycles through hints when clicked
- **Live desktop scene** — drifting clouds, a breathing sun, a bird that flaps across the sky, layered green hills
- **Draggable everything** — windows, sticky note, all with proper z-index stacking

## Tech

One self-contained `index.html`. No build step, no framework, no dependencies beyond two Google Fonts.

- Vanilla JS for window management, drag system, terminal, project switching, curtain choreography
- CSS transitions and keyframe animations for all motion (curtains, desk zoom, stage reveals, project diagrams)
- SVG for the desk scene, mascot, project visualizations, clouds, bird, hills
- Deploys to GitHub Pages as a static file

## Run locally

```bash
git clone https://github.com/Behjat4138/behjat-mdm-portfolio.git
cd behjat-mdm-portfolio
open index.html
```

No install, no build, no server needed.

## Who

**Behjat Riyaz** — MS Computer Science, Emory University (3.945 GPA, December 2026). Builds multi-agent LLM systems, retrieval pipelines, and production apps.

- [Email](mailto:fnu.behjat.riyaz@emory.edu)
- [LinkedIn](https://linkedin.com/in/behjat-riyaz28)
- [GitHub](https://github.com/Behjat4138)
