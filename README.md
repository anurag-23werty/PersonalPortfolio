# anurag@outr:~/portfolio

My personal portfolio, styled as a terminal. Live at **https://personal-portfolio-swart-pi-92.vercel.app**.

The look is inspired by [billpwchan/profile-terminal](https://github.com/billpwchan/profile-terminal): one panel grid, one monospace face (IBM Plex Mono), an amber accent and a ticker tape.

## What's on it

- **Hero:** my name as block ASCII art next to an animated ASCII Earth with an orbiting satellite. Every few seconds the satellite's telemetry readout flags a drift, a nod to SatPred.
- **F1 WORK:** four featured builds, each with a small chart drawn from numbers in its README:
  - [SQL Data Warehouse](https://github.com/anurag-23werty/sql-data-warehouse-project): PostgreSQL medallion warehouse with a [live dashboard](https://sql-data-analytics-project.vercel.app/)
  - [SatPred / sathealth](https://github.com/anurag-23werty/SatPred): explainable satellite health monitoring on NASA SMAP/MSL telemetry
  - [FastFrame](https://github.com/anurag-23werty/FastFrame): finds and safely rewrites slow pandas/NumPy code (`pip install fastframe-pandas`)
  - [VulnGraph](https://github.com/anurag-23werty/VulnGraph): graph-aware vulnerability triage agent on FalkorDB ([live demo](https://vulngraph-oit9.onrender.com))
- **F2 LOG:** about me and a timeline
- **F3 STACK:** tools and languages
- **F4 SHELL:** a small interactive shell. Try `help`, `projects`, `open fastframe`, `contact`.

Press `F1` to `F4` (or `1` to `4`) to jump between sections.

## Run locally

It's a single static `index.html` with no build step:

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```
