# Antonio De Gaetano

**Biological Scientist (B.Sc. Hons) · Bioinformatician · Scientific Systems Engineer**

[Portfolio & CV](https://antux912012.github.io/) · [Imladris Workbench](https://antux912012.github.io/imladris/) · [Imladris on Web](https://github.com/Antux912012/imladris-on-web)

---

## Background & Research Focus

I hold a **B.Sc. (Hons) in Biological Sciences** and work at the intersection of **life sciences, bioinformatics, and systems software engineering**.

My focus is on building practical, reproducible computational infrastructure for biological and clinical research:

- **Reproducible Bioinformatics & Provenance**: Connecting upstream genomic and structural biology platforms (Galaxy Project, AlphaFold DB, Ensembl, UniProtKB) directly to literate manuscripts (Quarto, R Markdown, Jupyter) with cryptographic SHA-256 provenance lockfiles.
- **Clinical Biostatistics & Regulated R&D**: Implementing transparent, auditable statistical workflows (ICH E9 sample size/power models, CDISC ADSL/ADTTE code generation, air-gapped and PHI-locked execution policies).
- **Collaborative Academic Tooling**: Designing self-hosted, institutional-grade authoring and execution environments where research groups and universities can co-author, review inline, and track revision history without surrendering data sovereignty.
- **Efficient Scientific Environments**: Replacing heavy Electron/JVM desktop overhead with compiled native Linux tooling (Vala, Rust, C, GTK4) and immutable OS images so workstation memory and GPU capacity remain available for statistical modeling and local inference.

---

## Selected Projects

### [Imladris](https://github.com/Antux912012/imladris) (`v0.42.1`) · [Landing Page](https://antux912012.github.io/imladris/) · [Wiki](https://github.com/Antux912012/imladris/wiki)
Native Linux scientific workbench and polyglot notebook studio (`Vala`, `GTK4`, `Libadwaita`, `GtkSourceView 5`, `WebKitGTK 6.0`, `Apache-2.0`).
- **Domain Bridges**: **Elbereth** (ICH E9 statistical power & CDISC tables), **Arekyer** (Galaxy Project `usegalaxy.eu`/`.org` provenance loader with `libsecret-1`), **Taniquetil** (AlphaFold DB / PDB pLDDT inspection), and **Yavanna** (UniProtKB, Ensembl GRCh38, and RT-qPCR oligo calculator).
- **Reproducibility & Governance**: 1:1 `.Rproj` and lossless `.ipynb` (`nbformat 4.5`) parity, `.mallorn` project bundles, `<doc>.provenance.lock.json` SHA-256 manifests, Air-Gapped Mode, PHI/PII Data Lock, and MCP D-Bus audit controls.

### [Imladris on Web](https://github.com/Antux912012/imladris-on-web) (`v0.1.0`)
Self-hosted collaborative sister project to native Imladris (`TypeScript`, `React 19`, `CodeMirror 6`, `Fastify 5`, `Yjs CRDT`, `FastAPI`, `Apache-2.0`).
- **Lab & University Collaboration**: Real-time multi-user editing, line-anchored inline comment threads, git-like revision checkpoints with line diffs and restore, and scoped RBAC invite tokens (`OWNER`, `EDITOR`, `REVIEWER`, `VIEWER`).
- **Self-Hosting**: Deployable via Docker Compose, rootless Podman Compose, or Kubernetes (`deploy/k8s/`) with `SHARED` vs `PERSONAL` execution kernels and `AIR_GAPPED_MODE`.

### [Kepler OS](https://github.com/Antux912012/kepler-os)
Immutable `x86-64-v3` Linux distribution tailored for computational biology and scientific computing, using atomic OSTree updates and Secure Boot.

### Supporting Linux Systems Utilities
- **[Mithrandir](https://github.com/Antux912012/mithrandir)**: GNU/Linux system maintenance, kernel scheduler/CPU governor tuning, and diagnostics utility (`Rust`, `GTK4`, `Libadwaita`).
- **[RecGo](https://github.com/Antux912012/RecGo)**: Native Wayland screen, window, and V4L2 webcam recorder using PipeWire and GStreamer (`Vala`, `GTK4`).

---

## Technical Stack

- **Life Sciences & Data Science**: R (`tidyverse`, `ggplot2`, `bio3d`, `renv`), Python (`numpy`, `pandas`, `matplotlib`, `biotite`), Quarto, R Markdown, Jupyter (`nbformat 4.5`), LaTeX/BibTeX, Galaxy REST API.
- **Systems & Desktop**: Vala, Rust, C, GTK4, Libadwaita, GtkSourceView 5, WebKitGTK 6.0, Meson, Flatpak, OSTree.
- **Web & Infrastructure**: TypeScript, Node.js, Fastify, Yjs/Hocuspocus, SQLite/Drizzle, FastAPI, Docker, Podman, Kubernetes, Caddy.

---

## Links

- **Portfolio & CV**: [antux912012.github.io](https://antux912012.github.io/)
- **GitHub**: [@Antux912012](https://github.com/Antux912012)
