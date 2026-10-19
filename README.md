<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="Reloading: threat intelligence, Certificate Transparency, and the things that turn up in logs" src="assets/header-light.svg" width="100%">
</picture>

I work in threat intelligence. Most of my attention goes to Certificate Transparency:
every publicly trusted TLS certificate gets logged, which makes CT one of the earliest
places a phishing domain becomes visible, often before it serves a single page.
I write the tooling for that in Rust.

### Projects

**[certstream-server-rust](https://github.com/Reloading01/certstream-server-rust)**
A Rust implementation of certstream-server. It watches CT logs and streams newly issued
certificates over WebSocket in real time. Packaged for Homebrew, APT and DNF.

```sh
brew install reloading01/tap/certstream-server-rust
```

**[threat-intelligence-dataset](https://github.com/Reloading01/threat-intelligence-dataset)**
A source-grounded, fact-checked instruction-tuning dataset for cyber threat intelligence.
12k examples across 42 CTI categories, built from MITRE ATT&CK, CVE/KEV, CWE, CAPEC,
D3FEND and live threat feeds.

**[toolmark](https://github.com/Reloading01/toolmark)**
Forensic timelines and detectors for the artifacts AI coding agents leave behind on a machine.

### Contact

[reloading799@gmail.com](mailto:reloading799@gmail.com)
