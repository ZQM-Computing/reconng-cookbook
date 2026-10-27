# Recon-ng Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **Recon-ng cookbook** for modular reconnaissance workspaces and resource scripts. Patterns are drawn from the ZQM fleet's Recon-ng work, including the trap that resource scripts must end with `exit` or the framework hangs at the prompt, and its crt.sh demo. It is intended for OSINT practitioners who run structured, module-based reconnaissance. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** Recon-ng patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. Intended to provide geospatial data feeds (POI, weather, satellite imagery, geocoding) for the ZQM game platform. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

OSINT practitioners who run structured, module-based reconnaissance.

## Prerequisites

- Recon-ng in the fleet tooling
- Python 3.11+
- An in-scope target you own or are authorized to research

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-workspace` | Workspaces, modules, and options |
| 02 | `02-resource-scripts` | Writing resource scripts that end with exit |
| 03 | `03-crtsh-demo` | Certificate-transparency enumeration with crt.sh |

## Repository layout

```text
reconng-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [theharvester-cookbook](https://github.com/ZQM-Computing/theharvester-cookbook) — Passive reconnaissance: domains, emails, and hosts from public sources
- [amass-cookbook](https://github.com/ZQM-Computing/amass-cookbook) — Passive subdomain enumeration and graph output
- [spiderfoot-cookbook](https://github.com/ZQM-Computing/spiderfoot-cookbook) — Passive OSINT automation as a service
