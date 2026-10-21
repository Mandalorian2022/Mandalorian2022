# Reza Faraji

Systems administrator for a university computer science department, finishing an M.S. in Cybersecurity.
I run the kind of infrastructure attackers like — GPU clusters, research servers, an identity migration
in flight — and spend the rest of my time on the detection side of the same problem.

## What I work on

- **Detection engineering.** Sigma rules, correlation, behavioural analytics, and evaluation against
  labeled data rather than gut feel.
- **Research infrastructure.** Proxmox, FreeIPA, Slurm GPU fleets, storage, monitoring and log pipelines
  for a department that runs its own hardware.
- **Security research.** CTFs (National Cyber League), hardware tooling, reverse engineering.

## Featured work

| Project | What it is |
|---|---|
| [siem-detection-lab](https://github.com/farajisec/siem-detection-lab) | A Sigma rule engine with correlation rules, behavioural analytics (beaconing, impossible travel, DGA, exfiltration volume), risk-based incident grouping and a measured evaluation harness, run against a synthetic week of identity and network telemetry with labeled attacks and benign look-alikes. |
| [log-anomaly-triage](https://github.com/farajisec/log-anomaly-triage) | Unsupervised anomaly detection on service metrics that produces a ranked, advisory triage queue for a human — it decides what to look at, never what to do. |
| [csflow](https://github.com/farajisec/csflow) | A privacy-first fleet status pipeline: aggregation, a publish delay and a fail-closed privacy gate so a public status page cannot leak a single hostname. |

Every project is synthetic and reproducible: no real hosts, accounts or logs, and the numbers in each
README come from running the code in that repository.

## Toolbox

`Python` `Bash` `PowerShell` `Linux` `Windows Server` `Proxmox` `FreeIPA` `Slurm` `Splunk` `Sigma` `Git`

## Elsewhere

Resume and project write-ups: **[farajisec.github.io](https://farajisec.github.io)**.

Aviation and air-traffic control nerd. Open to conversations about detection engineering and research
infrastructure — reach me through GitHub.
