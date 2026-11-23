### Hi, I'm Enzo

I'm a Mechanical & Energy Engineering student at Polytech Marseille, bridging energy engineering into naval engineering and the decarbonization of shipping. Outside of school, I like building my own software and 3D-printing tools rather than just using off-the-shelf ones. This repo's README is basically a home page for that side of what I do.

I post my 3D-printed designs on [printables.com/@TFD_5012172](https://www.printables.com/@TFD_5012172).

## Featured: Gronflad

**[gronflad](https://github.com/enzoprt/gronflad)** (from the Danish *grønne flåde*, "green fleet") is an open source voyage energy model for low carbon shipping. It answers one question: how much energy does a ship need on a given route, and how much can wind assistance and alternative fuels save?

**Live demo: [gronflad.streamlit.app](https://gronflad.streamlit.app)**

- Hull resistance (Holtrop and Mennen) and a Wageningen B-series propeller, predicting shaft power from the hull alone within 0.1 % of the published reference case
- Hull geometry read straight from the official IGES file of the KCS benchmark ship, hydrostatics recovered within 0.2 % and resistance compared with the published model test
- Interactive Streamlit app, [online](https://gronflad.streamlit.app), to explore hull, propeller and speed, including the propeller open water diagram, with warnings outside the method's validity range
- Alternative fuels (ammonia, methanol, LNG, hydrogen, e-fuels) compared on bunker volume, lost container slots, well-to-wake emissions and FuelEU Maritime compliance
- Flettner rotor sails sailed along real routes with a year of ERA5 wind, showing savings of a few percent at 25 knots and up to a third at slow steaming on the North Atlantic

## What I build

I taught myself full-stack development and lean heavily on AI-assisted workflows (Claude Code) to design, build, and ship real, working software rather than toy demos. Two projects here are actually in daily use:

- **[orca-profile-manager](https://github.com/enzoprt/orca-profile-manager)**: a companion app for OrcaSlicer (3D-printing slicer software). It organizes filament spools, nozzles, and presets by print objective, and locks hand-calibrated settings (flow ratio, pressure advance, temperatures) per spool/nozzle pair so they don't get lost when switching between print profiles. Stack: FastAPI (Python) backend, React/Vite frontend, SQLite for local data, packaged as a native macOS app.
- **[finance-tracker](https://github.com/enzoprt/finance-tracker)**: a personal finance aggregator pulling data from Saxo, LCL, and N26 into a single local dashboard, since none of those platforms talk to each other. Python backend scripts, static JSON output, no data leaves the machine.

Tools I use regularly: Python, FastAPI, React, Streamlit, Git, and browser/OS automation (Playwright, AppleScript) for smaller day-to-day scripting.
