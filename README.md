### Hi, I'm Enzo

I'm a Mechanical & Energy Engineering student at Polytech Marseille. Outside of school, I like building my own software and 3D-printing tools rather than just using off-the-shelf ones. This repo's README is basically a home page for that side of what I do.

I post my 3D-printed designs on [printables.com/@TFD_5012172](https://www.printables.com/@TFD_5012172).

## What I build

I taught myself full-stack development and lean heavily on AI-assisted workflows (Claude Code) to design, build, and ship real, working software rather than toy demos. Two projects here are actually in daily use:

- **[orca-profile-manager](https://github.com/enzoprt/orca-profile-manager)** — a companion app for OrcaSlicer (3D-printing slicer software). It organizes filament spools, nozzles, and presets by print objective, and locks hand-calibrated settings (flow ratio, pressure advance, temperatures) per spool/nozzle pair so they don't get lost when switching between print profiles. Stack: FastAPI (Python) backend, React/Vite frontend, SQLite for local data, packaged as a native macOS app.
- **[finance-tracker](https://github.com/enzoprt/finance-tracker)** — a personal finance aggregator pulling data from Saxo, LCL, and N26 into a single local dashboard, since none of those platforms talk to each other. Python backend scripts, static JSON output, no data leaves the machine.

Tools I use regularly: Python, FastAPI, React, Git, and browser/OS automation (Playwright, AppleScript) for smaller day-to-day scripting.
