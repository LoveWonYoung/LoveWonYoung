<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&height=300&color=0:030712,22:111827,45:06B6D4,72:22C55E,100:FB7185&text=LoveWonYoung&fontColor=F8FAFC&fontSize=72&fontAlignY=38&desc=Automotive%20Embedded%20Software%20%C2%B7%20Diagnostics%20%C2%B7%20Bootloader%20%C2%B7%20Automation&descAlignY=58&descSize=18&animation=twinkling" alt="LoveWonYoung banner" />

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=24&duration=2300&pause=650&color=22C55E&center=true&vCenter=true&width=980&lines=diagnostic.session+%3D+extended;%3E+CAN+%2F+LIN+%2F+UDS+tooling;%3E+Bootloader+flash+pipeline;%3E+Go+%2B+Rust+%2B+Python;%3E+Make+vehicle+software+observable" alt="Typing animation" />

<br />
<br />

<a href="https://github.com/LoveWonYoung">
  <img src="https://img.shields.io/badge/GitHub-LoveWonYoung-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
<img src="https://img.shields.io/badge/Domain-Automotive%20Embedded-06B6D4?style=for-the-badge" alt="Domain" />
<img src="https://img.shields.io/badge/Stack-Go%20%7C%20Rust%20%7C%20Python-22C55E?style=for-the-badge" alt="Stack" />
<img src="https://img.shields.io/badge/Mode-Diagnostics%20Online-FB7185?style=for-the-badge" alt="Mode" />

<br />
<br />

<img src="https://komarev.com/ghpvc/?username=LoveWonYoung&style=for-the-badge&color=06B6D4&label=CONTROL+ROOM+VISITS" alt="Profile views" />

</div>

---

<table>
<tr>
<td width="52%" valign="top">

## Operator

我是 **lm**，专注于 **汽车电子、车载诊断、Bootloader、工程自动化**。

I build tools that make low-level vehicle software easier to inspect, test, flash, and ship.

```text
identity.boot()
├─ role       : automotive embedded software developer
├─ protocols  : CAN / LIN / UDS / DTC
├─ focus      : diagnostics, flashing, validation
├─ languages  : Go / Rust / Python / C
└─ principle  : observable, repeatable, reliable
```

</td>
<td width="48%" valign="top">

## Live Telemetry

<img width="100%" src="https://github-readme-stats.vercel.app/api?username=LoveWonYoung&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&bg_color=00000000&custom_title=Runtime%20Telemetry" alt="GitHub stats" />

</td>
</tr>
</table>

## Control Matrix

<table>
<tr>
<td width="25%" align="center">

**Bus Layer**

`CAN` `LIN`

Message trace, decoding, timing, signal inspection.

</td>
<td width="25%" align="center">

**Diagnostic Layer**

`UDS` `DTC`

Session control, security access, routine control.

</td>
<td width="25%" align="center">

**Flash Layer**

`Bootloader`

Erase, download, transfer, verify, reset.

</td>
<td width="25%" align="center">

**Automation Layer**

`CLI` `Scripts`

Regression, logs, reports, repeatable workflows.

</td>
</tr>
</table>

## Tool Arsenal

<div align="center">

<img src="https://skillicons.dev/icons?i=go,rust,python,c,git,github,linux,vscode,bash,docker&theme=dark" alt="Skill icons" />

</div>

| Zone | What I Care About | Output |
| --- | --- | --- |
| Embedded | deterministic behavior, clear state machines | firmware workflow that can be reasoned about |
| Diagnostics | service flow, error recovery, traceability | UDS tooling and test automation |
| Bootloader | security access, transfer reliability, validation | stable flashing pipeline |
| Engineering | reproducible scripts, useful logs, fast feedback | tools that reduce manual debugging |

## Signal Route

```mermaid
flowchart LR
    A["ECU / Vehicle"] --> B["CAN / LIN Frames"]
    B --> C["Protocol Decode"]
    C --> D["UDS Services"]
    D --> E["Security Access"]
    E --> F["Flash / Routine / DTC"]
    F --> G["Logs"]
    G --> H["Reports + Regression"]
```

## Build Modes

<table>
<tr>
<td width="33%" valign="top">

### Diagnostic Console

- UDS service verification
- DTC read / clear workflows
- Message trace analysis
- Negative response handling

</td>
<td width="33%" valign="top">

### Flash Pipeline

- Session transition
- Seed-key access
- Block transfer
- Verify and reset strategy

</td>
<td width="33%" valign="top">

### Automation Rig

- CLI tooling
- Batch validation
- Log parsing
- Regression reports

</td>
</tr>
</table>

## Repository Radar

<div align="center">

<a href="https://github.com/LoveWonYoung?tab=repositories">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=LoveWonYoung&repo=LoveWonYoung&theme=tokyonight&hide_border=true&bg_color=00000000" alt="Profile repository" />
</a>
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LoveWonYoung&layout=compact&theme=tokyonight&hide_border=true&bg_color=00000000&langs_count=8" alt="Top languages" />

</div>

<details>
<summary><strong>Open the diagnostics terminal</strong></summary>

```text
ecu.attach --bus can0 --protocol uds

[OK] default_session        -> extended_session
[OK] security_access        -> unlocked
[OK] routine_control        -> running
[OK] request_download       -> accepted
[OK] transfer_data          -> verified
[OK] ecu_reset              -> completed

report.write("observable_vehicle_software.md")
```

</details>

## Activity Grid

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=LoveWonYoung&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=6&margin-w=12" alt="GitHub trophies" />

<br />
<br />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=LoveWonYoung&theme=tokyo-night&hide_border=true&bg_color=00000000&color=22C55E&line=06B6D4&point=FB7185" alt="GitHub activity graph" />

<br />
<br />

<img src="https://github-readme-streak-stats.herokuapp.com?user=LoveWonYoung&theme=tokyonight&hide_border=true&background=00000000" alt="GitHub streak" />

</div>

## Contribution Stream

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LoveWonYoung/LoveWonYoung/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LoveWonYoung/LoveWonYoung/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/LoveWonYoung/LoveWonYoung/output/github-contribution-grid-snake.svg" />
</picture>

</div>

## Current Packet

```go
type Packet struct {
    Name      string
    Domain    string
    Protocols []string
    Mission   string
}

packet := Packet{
    Name:      "lm",
    Domain:    "Automotive Embedded Software",
    Protocols: []string{"CAN", "LIN", "UDS", "DTC"},
    Mission:   "Build reliable tools for vehicle software workflows",
}
```

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:06B6D4,45:22C55E,100:FB7185" alt="Divider" />

**Vehicle software should be testable, traceable, and calm under pressure.**

<br />
<br />

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:030712,45:06B6D4,100:22C55E" alt="Footer wave" />

</div>
