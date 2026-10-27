<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.png">
    <img alt="Dr. Bashar Al Agha. Research, methods and software." src="assets/banner-light.png" width="100%">
  </picture>
</p>

<p align="center">
  <a href="https://orcid.org/0009-0004-5178-2345"><img alt="ORCID 0009-0004-5178-2345" src="https://img.shields.io/badge/ORCID-0009--0004--5178--2345-1E3A5F?style=flat-square&logo=orcid&logoColor=A6CE39"></a>
  <a href="https://www.linkedin.com/in/dr-bashar-al-agha"><img alt="LinkedIn dr-bashar-al-agha" src="https://img.shields.io/badge/LinkedIn-dr--bashar--al--agha-1E3A5F?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYTIuMDYyIDIuMDYyIDAgMSAxIDAtNC4xMjUgMi4wNjIgMi4wNjIgMCAwIDEgMCA0LjEyNXpNNy4xMTkgMjAuNDUySDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+"></a>
  <a href="https://bashar-portfolio-six.vercel.app"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-Research%2C%20Practice%20%26%20Technology-1E3A5F?style=flat-square&logo=vercel&logoColor=white"></a>
  <a href="mailto:ba8160@srmist.edu.in"><img alt="Academic email ba8160@srmist.edu.in" src="https://img.shields.io/badge/SRMIST-ba8160%40srmist.edu.in-1E3A5F?style=flat-square&logo=googlescholar&logoColor=white"></a>
  <a href="mailto:basharalagha21@gmail.com"><img alt="Email basharalagha21@gmail.com" src="https://img.shields.io/badge/Email-basharalagha21%40gmail.com-1E3A5F?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

## About

I am a doctoral researcher in Management Studies at the Faculty of Management, SRM Institute of Science and Technology (SRMIST), Chennai, India. My doctoral research (PhD in Healthcare Management and Evidence-Based Decision Making, 2025–2028) focuses on international healthcare systems and strategic expansion models: global healthcare strategy, health service internationalization and healthcare ecosystem development. My background bridges the clinical and management sciences: **BDS** (Damascus University), **BPharm** (Marwadi University), **Master in Pharmacology** (Saurashtra University) and **PGDM** (BIMTECH).

Alongside the research I build software: tools that make rigorous quantitative analysis faster and reproducible, and web platforms for education, health services and scholarly publishing.

<table>
  <tr>
    <th align="left" width="33%">Research</th>
    <th align="left" width="33%">Methods</th>
    <th align="left" width="34%">Engineering</th>
  </tr>
  <tr>
    <td valign="top">Global healthcare strategy<br>Health service internationalization<br>Healthcare ecosystem development<br>Evidence-based healthcare management<br>One Health<br>Healthcare management and marketing</td>
    <td valign="top">PLS-SEM and CB-SEM<br>fsQCA and NCA<br>Data envelopment analysis<br>Panel data and causal inference<br>Time-series econometrics<br>Meta-analysis and bibliometrics</td>
    <td valign="top">TypeScript, React, Next.js, Angular<br>Go, PHP (Laravel), Python, R<br>PostgreSQL, MySQL, Elasticsearch, Redis<br>Docker, Vercel, Cloudflare Workers<br>AI-agent and research-automation pipelines</td>
  </tr>
</table>

## Flagship: Arwad

<a href="https://github.com/bashar-al-agha/arwad"><b>Arwad: R, compiled.</b></a> A statistical programming language that keeps R's syntax and the CRAN ecosystem, and compiles numerical work to native code with deterministic, garbage-collection-free memory (built on the [Goose](https://github.com/aardappel/goose) systems language). The `arwad` R package compiles loop-heavy R functions to native code on their first call. Its results are bit-identical to GNU R across a 201-function equivalence corpus, checked on Linux, macOS and Windows, with no memory errors under AddressSanitizer. On one laptop, compiled loops ran 11–33× faster than R's byte code, a Gibbs sampler 20× faster, and a bootstrapped regression 11.7× faster (2.1× against idiomatic vectorised R). Its first statistical engines, compiled bootstraps of linear and logistic regression, return R's own coefficients bit for bit and ran 43.7× and 10.8× faster than the `lm()` and `glm()` loops researchers usually write (1.9× and 3.25× against hand-optimised R; [report](https://github.com/bashar-al-agha/arwad/blob/main/bench/phase2/REPORT.md)). Its PLS-SEM engine reproduces `seminr::bootstrap_model()` bit for bit and runs a 10,000-resample bootstrap 5.1× faster (41 s instead of 212 s).

<p align="center">
  <a href="https://github.com/bashar-al-agha/arwad/blob/main/bench/phase2/REPORT.md">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/bashar-al-agha/arwad/main/docs/assets/results-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/bashar-al-agha/arwad/main/docs/assets/results-light.svg">
      <img alt="Arwad Phase 2 results: the same answers as R, bit for bit, from native code; 43.7 times faster than an lm() loop, 10.8 times faster than a glm() loop, 5.1 times faster than seminr for 10,000 PLS-SEM resamples." src="https://raw.githubusercontent.com/bashar-al-agha/arwad/main/docs/assets/results-light.svg" width="100%">
    </picture>
  </a>
</p>

[Arwad at Langwi](https://langwi.com/arwad) &middot; [Design](https://github.com/bashar-al-agha/arwad/blob/main/docs/ARCHITECTURE.md) &middot; [Roadmap](https://github.com/bashar-al-agha/arwad/blob/main/docs/ROADMAP.md) &middot; [Benchmark report](https://github.com/bashar-al-agha/arwad/blob/main/bench/phase1/REPORT.md) &middot; MIT licence

## Ecosystem

| Platform | Role |
|---|---|
| [**Langwi**](https://langwi.com) | The compiler and open-source lab: home of [Arwad](https://langwi.com/arwad), its benchmark reports and my open-source developer projects |
| [**Palmyra Academic Press**](https://palmyrapub.org) | Academic publisher: journals, monographs and the methods papers behind my software |
| [**PalmyraDoor**](https://palmyradoor.tech) | Research portal in development: point-and-click statistical engines (PLS-SEM, DEA, panel models) running in the browser on Arwad |

## Open-source standard

New open-source projects start from [`mit-project-template`](https://github.com/bashar-al-agha/mit-project-template): MIT licence, a `CITATION.cff` file for GitHub's *Cite this repository* button and Zenodo DOIs, continuous integration, Dependabot, and the shared community files in [`.github`](https://github.com/bashar-al-agha/.github).

## Contact

- **Academic:** [ba8160@srmist.edu.in](mailto:ba8160@srmist.edu.in)
- **Personal:** [basharalagha21@gmail.com](mailto:basharalagha21@gmail.com) &middot; [alaghabashar0@gmail.com](mailto:alaghabashar0@gmail.com)
- **Alumni (BIMTECH):** [bashar.agha25@bimtech.ac.in](mailto:bashar.agha25@bimtech.ac.in)
- **ORCID:** [0009-0004-5178-2345](https://orcid.org/0009-0004-5178-2345) &middot; **LinkedIn:** [dr-bashar-al-agha](https://www.linkedin.com/in/dr-bashar-al-agha) &middot; **Portfolio:** [bashar-portfolio-six.vercel.app](https://bashar-portfolio-six.vercel.app)

Open to collaboration on research software, quantitative methods and health-systems analytics.

<sub>Related accounts: <a href="https://github.com/connexdotz">@connexdotz</a> (product engineering) &middot; <a href="https://github.com/Drbash6">@Drbash6</a> (research instruments and study materials)</sub>
