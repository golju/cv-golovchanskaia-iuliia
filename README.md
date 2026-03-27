<div align="center">

# Iuliia Golovchanskaia

**Senior C++ Developer** · Cyprus

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iuliia-golovchanskaia)
[![GitHub](https://img.shields.io/badge/GitHub-golju-181717?style=for-the-badge&logo=github)](https://github.com/golju)

Game development · Computer vision · Performance · Modern C++

<img src="https://readme-typing-svg.demolab.com?font=Source+Sans+Pro&size=22&duration=3000&pause=1000&color=5C6BC0&center=true&vCenter=true&width=600&lines=Lead+Programmer+at+Playrix+%7C+Fishdom;C%2B%2B17%2F20+%7C+Live+ops+%7C+AI-assisted+dev" alt="Typing intro" />

</div>

---

## About

> About **eight years** bridging **mobile games** and **classical computer vision**. I own **game event** features end-to-end at **Playrix** on **Fishdom** — from **architecture** through shipping to **live-ops** delivery — with earlier work on **industrial CV / 3D** and **traffic analytics**. I care about **performance**, **engineering quality**, and **AI-assisted workflows** that actually help teams ship.

| | |
|:---|:---|
| **Now** | Lead Programmer @ Playrix · Fishdom · Cyprus |
| **Focus** | **Game event systems** & **live-ops** in C++ (architecture → shipping); **performance** & reliability; team standards, **reviews**, **mentoring** |
| **Also** | Public speaking (C++ Russia, YaTalks, …) · SPIE publications |

---

## What’s in the CV

Source → **`Golovchanskaia_CV.tex`** → PDF **`Golovchanskaia_CV.pdf`**

| Section | Contents |
|:---:|:---|
| **Summary** | Experience in games + computer vision; **Fishdom** context (reach / MAU); owning **game event** features end-to-end; architecture through **live-ops**; quality and **AI-assisted** engineering |
| **Skills** | Strong **C++** for shipping (perf, concurrency, tooling); **CMake** / **Linux** / **tests** / **CI**; **AI-assisted** workflow (**Cursor**); **games** + **computer vision** background |
| **Experience** | Playrix → HSE (C++ teaching) → **Computer Vision Systems** → Simicon |
| **Education** | ITMO (MSc) · SPbU (BSc) |
| **Certifications** | e.g. **NEBIUS** — AI-Assisted Programming |
| **Speaking** | C++ Russia, PiterPy, YaTalks, … |
| **Publications** | **SPIE** proceedings (2021) — full citations & publisher links in the CV |

Certificate notes & PDF naming → [`certificates/README.md`](certificates/README.md)

---

## Tech snapshot

*Not the full skills table — that lives in **`Golovchanskaia_CV.pdf**. These are the pillars that show up across games + CV work.*

![C++](https://img.shields.io/badge/C%2B%2B-17%2F20-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-AI--assisted%20workflow-181717?style=flat-square&logo=cursor&logoColor=white)
![Game dev](https://img.shields.io/badge/Game%20dev-6A1B9A?style=flat-square)

<sub>Also in the CV: **OpenCV** (computer-vision roles), **Qt** (earlier roles), multithreading & profiling, **CUDA** / SIMD where it mattered, **Windows**, **TeamCity**, **Google Test**, …</sub>

---

## This repository

LaTeX source with two build modes: **public** (GitHub-safe stubs + NDA-soft achievements) and **private** (real contacts & full bullets via local files).

### Build

```bash
pdflatex -interaction=nonstopmode Golovchanskaia_CV.tex
```

Run **twice** if you need clean hyperref metadata. Needs **pdfLaTeX** + **fontawesome5**, **hyperref**, **tabularx**, **enumitem**, **etoolbox**.

<details>
<summary><strong>Public vs full CV — which files?</strong></summary>

| File | In git? | Purpose |
|:---:|:---:|:---|
| `Golovchanskaia_CV.tex` | yes | Main document |
| `cv-contact-public.tex` | yes | Placeholder contacts in PDF header |
| `cv-contact.local.tex` copy | **gitignored** | Real email / phone / Telegram |
| `cv-achievements-public.tex` | yes | Safe bullet text |
| `cv-achievements.local.tex` copy | **gitignored** | Detailed achievements |

Copy from `*.example` → fill → compile. **Do not commit** `*.local.tex`.

**Public build:** temporarily move or omit the two `.local.tex` files.

</details>

**Tree (main pieces)**

```
Golovchanskaia_CV.tex
cv-contact-public.tex      +  cv-contact.local.tex.example
cv-achievements-public.tex +  cv-achievements.local.tex.example
certificates/
docs/                      # optional notes (e.g. résumé / ATS research)
```

Optional note (not needed to compile): [`docs/senior_cpp_resume_format_research.md`](docs/senior_cpp_resume_format_research.md) — résumé format / ATS research.

---

**About the LaTeX template:** The CV is based on **autoCV** (open source, MIT license, author Jitin Nair). In `Golovchanskaia_CV.tex` at the very top there is a short comment with that credit — if someone copies this project, that line should stay, as the license asks.
