<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,10:1a0533,30:6D28D9,50:8B5CF6,70:A855F7,90:EC4899,100:F97316&height=250&section=header&text=OCTAVIAN&fontSize=100&fontColor=ffffff&animation=twinkling&fontAlignY=36&desc=Software%20Engineer%20%E2%80%A2%20Linux%20Systems%20Administrator%20%E2%80%A2%20Security%20Practitioner%20%E2%80%A2%20Performance%20Architect&descSize=15&descAlignY=58&descColor=c4b5fd" />

<a href="https://octaviantweaking.com">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=2600&pause=700&color=A855F7&center=true&vCenter=true&width=820&height=45&lines=If+it+runs%2C+it+can+run+faster+%E2%80%94+and+safer.;Polyglot+engineer.+Infrastructure+custodian.+Adversarial+thinker.;From+interrupt+affinity+to+hardened+production+fleets.;Architect+of+the+Octavian+Tweaking+Utility+%E2%9A%A1" alt="Typing SVG" />
</a>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3500&pause=1000&color=EC4899&center=true&vCenter=true&width=820&height=26&lines=%E2%96%B8+Software+Engineering+%E2%80%A2+Full-Stack+Architecture+%E2%80%A2+Systems+Programming;%E2%96%B8+Multi-Distribution+Linux+Administration+%E2%80%A2+Infrastructure+Orchestration;%E2%96%B8+Game-Hosting+Platform+Engineering+%E2%80%A2+High-Availability+Topologies;%E2%96%B8+Defensive+Security+%E2%80%A2+Hardening+%E2%80%A2+Threat+Mitigation;%E2%96%B8+Low-Latency+Windows+Optimization+%E2%80%A2+Frame-Pacing+Forensics" alt="Subtitle" />

<br/>

<img src="https://komarev.com/ghpvc/?username=OctavianAdv&color=6D28D9&style=for-the-badge&label=PROFILE+VIEWS" alt="views" />
<a href="https://github.com/OctavianAdv?tab=followers"><img src="https://img.shields.io/github/followers/OctavianAdv?style=for-the-badge&color=A855F7&labelColor=0d1117&logo=github&label=FOLLOWERS" /></a>
<a href="https://octaviantweaking.com"><img src="https://img.shields.io/badge/OCTAVIANTWEAKING.COM-F97316?style=for-the-badge&labelColor=0d1117&logo=googlechrome&logoColor=white" /></a>
<a href="https://davidenko.ro"><img src="https://img.shields.io/badge/DAVIDENKO.RO-A855F7?style=for-the-badge&labelColor=0d1117&logo=googlechrome&logoColor=white" /></a>

</div>

<img width="100%" src="./assets/divider.svg" />

## 🧬 Manifesto

I am a **polymathic software engineer, multi-distribution Linux systems administrator, game-hosting platform architect, security practitioner, and performance engineer** from Romania 🇷🇴 — operating at the confluence where source code, operating-system internals, network infrastructure, and adversarial threat models intersect.

My professional ethos rests upon a deliberately uncompromising premise: **every system — whether a competitive gaming workstation, a production web platform, or a fleet of multiplayer game servers — can be rendered faster, leaner, more deterministic, and more resilient than its default state permits.** Vendor defaults are, by necessity, calibrated for the lowest common denominator; my discipline is the systematic, evidence-based transcendence of those defaults.

I refuse to treat engineering as a collection of isolated specialisms. Performance without security is recklessness; security without availability is paralysis; availability without observability is blind faith. I therefore approach every undertaking **holistically** — conceiving, implementing, deploying, hardening, monitoring, and continuously refining the entire lifecycle, from the first line of code to the last packet traversing the wire.

> *"If it runs, it can run faster."*
> — and if it runs faster, it must also run **safer, steadier, and longer**.

<img width="100%" src="./assets/divider.svg" />

## ⚡ `whoami`

```typescript
interface Engineer {
  readonly identity:    string;
  readonly origin:      string;
  readonly disciplines: Record<string, readonly string[]>;
  readonly doctrine:    string;
}

export const octavian: Engineer = {
  identity: "Octavian",
  origin:   "Romania 🇷🇴",
  disciplines: {
    softwareEngineering: ["C", "C++", "C#/.NET", "TypeScript", "Python", "PowerShell", "Bash"],
    webArchitecture:     ["Next.js", "React", "Angular", "Node.js", "Express", "PostgreSQL", "MySQL"],
    linuxAdministration: ["Ubuntu", "Debian", "Rocky Linux", "AlmaLinux", "Fedora", "Arch Linux"],
    hostingPlatforms:    ["Dedicated & virtualized servers", "Control panels", "Game-server orchestration"],
    cyberSecurity:       ["System hardening", "Network defense", "DDoS mitigation", "Incident response"],
    performance:         ["Windows internals", "Interrupt topology", "Latency & frame-pacing forensics"],
  },
  doctrine: "Measure. Isolate. Harden. Automate. Validate. Never assume.",
};
```

<img width="100%" src="./assets/divider.svg" />

## 🗺️ Domains of Mastery

<div align="center">

| | Domain | Scope of Expertise |
|:--:|:--|:--|
| 💻 | **Software Engineering** | Systems programming, desktop tooling, full-stack web platforms, automation and scripting across heterogeneous runtimes |
| 🐧 | **Linux Systems Administration** | Provisioning, configuration, hardening, and lifecycle stewardship across Debian-based, RHEL-based, and rolling-release distributions |
| 🎮 | **Game-Hosting Platform Engineering** | Architecting, deploying, and operating multiplayer infrastructure with emphasis on tick-rate stability and availability |
| 🛡️ | **Cyber Security** | Defensive architecture, attack-surface reduction, threat mitigation, vulnerability assessment, and incident response |
| 🌐 | **Infrastructure & Networking** | Reverse proxies, TLS termination, DNS, CDN integration, firewalling, and traffic engineering |
| ⚙️ | **Performance Engineering** | Low-latency Windows optimization, scheduler heuristics, interrupt topology, and frame-pacing analysis |

</div>

<img width="100%" src="./assets/divider.svg" />

## 🏛️ Infrastructure Philosophy — Reference Architecture

```mermaid
flowchart TB
    U([🌍 Clients & Players]) --> CF[☁️ Edge Layer<br/>CDN • WAF • DDoS Scrubbing]
    CF --> FW{🛡️ Host Firewall<br/>nftables • rate limiting}
    FW --> RP[🔀 Reverse Proxy<br/>Nginx • TLS termination]
    FW --> GS[🎮 Game-Server Nodes<br/>isolated • containerized]
    RP --> APP[⚙️ Application Tier<br/>Node.js • Next.js]
    APP --> DB[(🗄️ Data Tier<br/>PostgreSQL • MySQL)]
    GS --> BK[(💾 Automated Backups<br/>versioned • off-site)]
    DB --> BK
    APP & GS & DB --> MON[📈 Observability<br/>metrics • logs • alerting]
    MON -.->|anomaly| IR[🚨 Incident Response]

    style U fill:#1a0533,stroke:#A855F7,color:#fff
    style CF fill:#0d1117,stroke:#F97316,color:#fff
    style FW fill:#0d1117,stroke:#EC4899,color:#fff
    style MON fill:#6D28D9,stroke:#A855F7,color:#fff
    style IR fill:#0d1117,stroke:#EC4899,color:#fff
```

**Defense in depth, layered by design.** Each tier presumes the compromise of the tier preceding it, constraining blast radius and ensuring that no single failure — accidental or adversarial — cascades into systemic collapse.

<img width="100%" src="./assets/divider.svg" />

## 🐧 Linux Systems Administration

<div align="center">

<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
<img src="https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white" />
<img src="https://img.shields.io/badge/Rocky_Linux-10B981?style=for-the-badge&logo=rockylinux&logoColor=white" />
<img src="https://img.shields.io/badge/AlmaLinux-000000?style=for-the-badge&logo=almalinux&logoColor=white" />
<img src="https://img.shields.io/badge/CentOS-262577?style=for-the-badge&logo=centos&logoColor=white" />
<img src="https://img.shields.io/badge/Fedora-51A2DA?style=for-the-badge&logo=fedora&logoColor=white" />
<img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white" />

</div>

Fluency across distribution families is not merely a matter of memorizing divergent package managers — it is an intimate understanding of their **differing philosophies of stability, release cadence, default security posture, and init-system conventions**.

<details>
<summary><b>📦 Distribution Families & Operational Nuance</b></summary>
<br/>

| Family | Representatives | Package Ecosystem | Operational Character |
|:--|:--|:--|:--|
| **Debian-based** | Debian, Ubuntu | `apt` / `dpkg` | Conservative stability (Debian) or predictable LTS cadence (Ubuntu); AppArmor by default |
| **RHEL-based** | Rocky Linux, AlmaLinux, CentOS | `dnf` / `rpm` | Enterprise longevity, binary compatibility, SELinux enforcing by default |
| **Fedora** | Fedora Server / Workstation | `dnf` / `rpm` | Upstream-proximate innovation; proving ground for enterprise technologies |
| **Rolling-release** | Arch Linux | `pacman` / AUR | Bleeding-edge currency; demands disciplined, deliberate maintenance |

</details>

<details>
<summary><b>⚙️ Core Administrative Competencies</b></summary>
<br/>

| Discipline | Instruments | Objective |
|:--|:--|:--|
| **Service Orchestration** | `systemd` units, timers, dependency ordering | Deterministic, self-healing service lifecycles |
| **Storage Engineering** | LVM, RAID, ext4, XFS, mount-option tuning | Resilient, performant, and extensible storage layouts |
| **Kernel Tuning** | `sysctl`, I/O schedulers, network buffers, file-descriptor limits | Calibrating the kernel for the specific workload rather than the generic case |
| **Web Serving** | Nginx, Apache, reverse proxying, TLS via ACME | Secure, efficient, horizontally composable HTTP delivery |
| **Databases** | PostgreSQL, MySQL/MariaDB — tuning, replication, backup | Durable, consistent, and performant persistence |
| **Containerization** | Docker, Compose, resource constraints, network isolation | Reproducible deployments with bounded blast radius |
| **Automation** | Bash, cron, systemd timers, scripted provisioning | Eradicating toil and human error through idempotent automation |
| **Observability** | Journald, log rotation, resource metrics, alerting | Perceiving degradation before it becomes an outage |
| **Control Panels** | HestiaCP and comparable hosting panels | Multi-tenant web, mail, and DNS administration at scale |

</details>

<img width="100%" src="./assets/divider.svg" />

## 🎮 Game-Hosting Platform Engineering

In multiplayer environments, infrastructure quality is **directly perceptible** to every player. A dropped tick, a garbage-collection pause, or a volumetric flood is not an abstract incident — it is a ruined match. I engineer hosting environments accordingly.

<details>
<summary><b>🕹️ Platform Architecture & Operations</b></summary>
<br/>

| Dimension | Approach | Rationale |
|:--|:--|:--|
| **Bare-Metal Provisioning** | Dedicated servers with calibrated CPU governors and kernel parameters | Game servers are frequently single-thread-bound; clock stability eclipses core count |
| **Server Software** | Paper/PaperMC and performance-oriented forks, proxy layers for networks | Asynchronous chunk processing and optimized tick loops sustain higher player density |
| **JVM Engineering** | Heap sizing, garbage-collector selection and flag calibration | Minimizes stop-the-world pauses that manifest as in-game lag spikes |
| **Tenant Isolation** | Containerization, per-instance resource quotas, dedicated users | Prevents a single misbehaving instance from starving its neighbors |
| **Management Panels** | Web-based game-server panels with daemon-per-node topology | Delegated, auditable administration without granting shell access |
| **Network Resilience** | Upstream DDoS scrubbing, protocol-aware filtering, connection throttling | Game protocols are prime volumetric and state-exhaustion targets |
| **Data Durability** | Scheduled, versioned, off-site world and database backups | Recovery objectives measured in minutes, not days |
| **Performance Profiling** | Tick-time analysis, TPS/MSPT monitoring, plugin profiling | Pinpointing the precise code path responsible for degradation |

</details>

<img width="100%" src="./assets/divider.svg" />

## 🛡️ Cyber Security & Defensive Engineering

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&duration=2400&pause=900&color=EC4899&center=true&vCenter=true&width=760&height=30&lines=Assume+breach.+Minimize+privilege.+Verify+everything.;Attack+surface+is+a+liability+%E2%80%94+reduce+it+relentlessly.;Think+like+the+adversary.+Defend+like+the+architect." alt="Security" />

</div>

Security is not a product one installs; it is an **emergent property of disciplined architecture**. I practice it through the lens of the adversary — anticipating reconnaissance, enumerating attack vectors, and dismantling them before they can be weaponized.

<details>
<summary><b>🔐 Host Hardening</b></summary>
<br/>

| Control | Implementation | Threat Neutralized |
|:--|:--|:--|
| **SSH Hardening** | Key-only authentication, root login disabled, non-default exposure, restricted ciphers | Credential brute-forcing and opportunistic scanning |
| **Principle of Least Privilege** | Granular `sudo` policies, dedicated service accounts, restrictive permissions | Lateral movement and privilege escalation |
| **Mandatory Access Control** | SELinux / AppArmor enforcement profiles | Post-exploitation containment |
| **Patch Governance** | Disciplined update cadence, unattended security updates | Exploitation of publicly disclosed vulnerabilities |
| **Service Minimization** | Disabling and removing every non-essential daemon | Attack-surface proliferation |
| **Integrity & Auditing** | `auditd`, file-integrity monitoring, centralized logging | Undetected tampering and persistence |

</details>

<details>
<summary><b>🌐 Network Defense</b></summary>
<br/>

| Control | Implementation | Threat Neutralized |
|:--|:--|:--|
| **Stateful Firewalling** | nftables / iptables / UFW with default-deny ingress | Unsolicited exposure of internal services |
| **Intrusion Prevention** | Fail2ban / CrowdSec behavioral banning | Automated brute-force and abusive clients |
| **DDoS Mitigation** | Edge scrubbing, rate limiting, SYN cookies, connection caps | Volumetric, protocol, and application-layer floods |
| **Web Application Firewall** | Edge and reverse-proxy rule sets | Injection, traversal, and automated exploitation attempts |
| **Transport Security** | Modern TLS configuration, HSTS, certificate automation | Interception and downgrade attacks |
| **Origin Concealment** | Proxied DNS, origin firewalled to edge ranges only | Direct-to-origin attacks bypassing protection |

</details>

<details>
<summary><b>🔎 Assessment, Detection & Response</b></summary>
<br/>

| Phase | Practice | Outcome |
|:--|:--|:--|
| **Reconnaissance Awareness** | Port and service enumeration of one's own perimeter | Seeing the infrastructure exactly as an attacker would |
| **Vulnerability Assessment** | Configuration audits, dependency scrutiny, benchmark alignment | Identifying weaknesses before they are exploited |
| **Application Security** | Input validation, parameterized queries, secure session handling, secret management | Eliminating OWASP-class vulnerabilities at the source |
| **Log Analysis** | Correlating authentication, web, and system logs | Early detection of anomalous and malicious behavior |
| **Incident Response** | Containment, eradication, recovery, post-mortem | Minimized dwell time and institutionalized lessons |
| **Resilience Engineering** | Tested backups, documented recovery procedures | Survivability even under worst-case compromise |

</details>

<img width="100%" src="./assets/divider.svg" />

## ⚙️ Flagship — Octavian Tweaking Utility

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&duration=2200&pause=900&color=F97316&center=true&vCenter=true&width=700&height=30&lines=Max+FPS.;Lowest+latency.;Zero+bloat.;Engineered%2C+not+guessed." alt="OTU" />

**A comprehensive, holistic performance-orchestration suite for Windows** — consolidating system-level, network-level, and input-level optimization into a single, coherent, meticulously engineered instrument.

<a href="https://octaviantweaking.com"><img src="https://img.shields.io/badge/Website-F97316?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
<a href="https://discord.gg/BBtwEREjmj"><img src="https://img.shields.io/badge/Join_the_Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>

</div>

| Subsystem | Intervention Vector | Engineering Objective |
|:--|:--|:--|
| 🧠 **Processor & Scheduler** | Quantum configuration, core-parking suppression, idle-state governance | Maximize foreground responsiveness and eradicate wake-up latency |
| ⏱️ **Timers & Interrupts** | Timer-resolution coercion, MSI delivery, interrupt-affinity pinning | Deterministic interrupt servicing with minimal DPC/ISR jitter |
| 🎮 **Graphics Pipeline** | Presentation-model optimization, driver debloating | Low-variance frame delivery and reduced render-queue depth |
| 🧮 **Memory Subsystem** | Standby-list governance, paging-policy calibration | Eliminate cache-eviction stutter and allocation stalls |
| 🌐 **Network Stack** | Nagle neutralization, RSS balancing, adapter power-saving eradication | Minimize packet-coalescing delay and real-time jitter |
| 🖱️ **Input Path** | Raw-input validation, acceleration removal, USB power-policy correction | Faithful, one-to-one, latency-minimized peripheral input |
| 🧹 **Operating System** | Telemetry suppression, service rationalization, task pruning | Reclaim cycles, I/O bandwidth, and memory from background entropy |

```mermaid
flowchart LR
    A([📊 Baseline<br/>Telemetry]) --> B{🔍 Bottleneck<br/>Isolation}
    B -->|CPU-bound| C[🧠 Scheduler &<br/>Power Policy]
    B -->|Latency-bound| D[⏱️ Timers &<br/>Interrupts]
    B -->|GPU-bound| E[🎮 Render<br/>Pipeline]
    B -->|Network-bound| F[🌐 Stack &<br/>Adapter]
    C & D & E & F --> G[🧪 Empirical<br/>Validation]
    G -->|Regression| B
    G -->|Improvement| H([✅ Documented,<br/>Reversible State])

    style A fill:#1a0533,stroke:#A855F7,color:#fff
    style B fill:#0d1117,stroke:#EC4899,color:#fff
    style G fill:#0d1117,stroke:#F97316,color:#fff
    style H fill:#6D28D9,stroke:#A855F7,color:#fff
```

<details>
<summary><b>📚 The Performance Doctrine — Windows Internals Compendium</b></summary>
<br/>

#### 🧠 Processor, Scheduler & Power Management

| Parameter | Mechanism | Rationale |
|:--|:--|:--|
| `Win32PrioritySeparation` | Quantum length, variability, and foreground boost | Shapes how aggressively the foreground process is favored |
| **Core Parking** | Consolidates load onto fewer active cores | Unparking eliminates the penalty of re-awakening dormant cores |
| **C-states** | Progressively deeper idle states | Deep states impose exit latency; constraining them yields snappier wake-ups |
| **Energy Performance Preference** | Hints the CPU's internal frequency governor | Expedites frequency ramp-up under burst loads |

#### ⏱️ Timers & Interrupts

| Parameter | Mechanism | Rationale |
|:--|:--|:--|
| **Timer Resolution** | `NtSetTimerResolution` — default ≈15.6 ms | Finer granularity tightens sleep precision and frame-limiter accuracy |
| **Dynamic Tick** | `disabledynamictick` | Prevents tick coalescing during perceived idleness |
| **MSI / MSI-X** | Message-signaled interrupts | Reduces interrupt-sharing contention and servicing overhead |
| **Interrupt Affinity** | Pins device interrupts to designated cores | Isolates GPU, NIC, and USB servicing from critical game threads |

#### 🎮 Graphics & Frame Pacing

| Parameter | Mechanism | Rationale |
|:--|:--|:--|
| **Presentation Model** | Flip-model / independent flip | Bypasses composition overhead |
| **Render Queue Depth** | Low-latency modes, Reflex, Anti-Lag | Curtails input latency by shrinking frame buffering |
| **HAGS / MPO** | GPU scheduling, hardware overlays | Evaluated per configuration — never applied dogmatically |

#### 🌐 Network & 🖱️ Input

| Parameter | Mechanism | Rationale |
|:--|:--|:--|
| **Nagle's Algorithm** | `TcpAckFrequency` / `TCPNoDelay` | Removes small-packet coalescing delay |
| **Interrupt Moderation / RSS** | NIC batching and multi-core distribution | Balances throughput against per-packet responsiveness |
| **Pointer Acceleration** | Enhance Pointer Precision | Removal restores one-to-one, muscle-memory-consistent input |
| **USB Selective Suspend** | Per-port power management | Prevents mid-session peripheral power transitions |

#### 📐 Validation Protocol

| Step | Procedure |
|:--:|:--|
| **01** | Establish a controlled baseline — identical scene, settings, and thermal equilibrium |
| **02** | Capture frametimes with PresentMon / CapFrameX across multiple passes |
| **03** | Profile DPC/ISR latency with LatencyMon and Windows Performance Analyzer |
| **04** | Apply exactly **one** intervention — never confound variables |
| **05** | Re-capture and compare averages, 1% lows, 0.1% lows, and variance |
| **06** | Retain only statistically meaningful improvements; document and guarantee reversibility |

</details>

<img width="100%" src="./assets/divider.svg" />

## 🚀 Additional Engineering

<table>
<tr>
<td width="50%" valign="top">

### 🖱️ MouseFix
A **low-level input-path remediation utility** operating at the kernel-driver layer — engineered to guarantee unadulterated, acceleration-free, one-to-one mouse input with no smoothing artifacts.

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Kernel](https://img.shields.io/badge/Kernel_Mode-1a0533?style=for-the-badge&logo=windows&logoColor=white)

</td>
<td width="50%" valign="top">

### 🎮 NEXON
A **full-stack e-commerce platform** for bespoke controllers and competitive gaming peripherals — integrated payment orchestration, contemporary design language, and performance-first architecture.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

</td>
</tr>
</table>

<img width="100%" src="./assets/divider.svg" />

## 🛠️ Technological Arsenal

<div align="center">

**Systems & Scripting Languages**<br/>
<img src="https://skillicons.dev/icons?i=c,cpp,cs,py,js,ts,bash,powershell&theme=dark&perline=8" />

**Frontend & Backend Frameworks**<br/>
<img src="https://skillicons.dev/icons?i=nextjs,react,angular,nodejs,express,dotnet,tailwind&theme=dark&perline=8" />

**Operating Systems & Infrastructure**<br/>
<img src="https://skillicons.dev/icons?i=linux,ubuntu,debian,arch,fedora,windows,docker,nginx,cloudflare&theme=dark&perline=9" />

**Data & Persistence**<br/>
<img src="https://skillicons.dev/icons?i=postgresql,mysql,supabase,redis&theme=dark&perline=8" />

**Engineering Toolchain**<br/>
<img src="https://skillicons.dev/icons?i=vscode,visualstudio,git,github,githubactions,figma&theme=dark&perline=8" />

</div>

<img width="100%" src="./assets/divider.svg" />

## 📊 Telemetry

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=OctavianAdv&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=A855F7&icon_color=EC4899&text_color=c9d1d9&ring_color=A855F7&rank_icon=percentile" />
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=OctavianAdv&layout=compact&langs_count=8&hide_border=true&bg_color=0d1117&title_color=A855F7&text_color=c9d1d9" />

<img src="https://streak-stats.demolab.com/?user=OctavianAdv&hide_border=true&background=0d1117&ring=A855F7&fire=EC4899&currStreakLabel=A855F7&sideLabels=c9d1d9&currStreakNum=EC4899&sideNums=F97316&dates=555555" />

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=OctavianAdv&theme=react-dark&hide_border=true&bg_color=0d1117&color=A855F7&line=EC4899&point=F97316&area=true&area_color=6D28D9" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/OctavianAdv/OctavianAdv/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/OctavianAdv/OctavianAdv/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/OctavianAdv/OctavianAdv/output/github-snake-dark.svg" />
</picture>

</div>

<img width="100%" src="./assets/divider.svg" />

## 🌐 Transmission Channels

<div align="center">

<a href="https://instagram.com/octaviantweaks"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
<a href="https://tiktok.com/@octavianxoc"><img src="https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white" /></a>
<a href="https://youtube.com/@octavianxoc"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
<a href="https://kick.com/octavianxoc"><img src="https://img.shields.io/badge/Kick-53FC18?style=for-the-badge&logo=kick&logoColor=black" /></a>
<a href="https://discord.gg/BBtwEREjmj"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=3000&pause=1000&color=A855F7&center=true&vCenter=true&width=760&lines=Performance+is+not+an+accident.+It+is+engineered.;Security+is+not+a+feature.+It+is+a+discipline.;Thanks+for+visiting+%E2%80%94+now+go+build+something+formidable.+%E2%9A%A1" alt="Outro" />

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,10:1a0533,30:6D28D9,50:8B5CF6,70:A855F7,90:EC4899,100:F97316&height=140&section=footer&animation=twinkling" />
