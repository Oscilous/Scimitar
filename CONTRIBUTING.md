# Contributing to Scimitar V2

Thanks for your interest in improving **Scimitar**! We welcome fixes, edits, and enhancements to CAD, BoM, and documentation.

## Workflow
1. **Fork** the repo and create a feature branch.
2. Make your changes (see file conventions below).
3. **Update docs/BoM** relevant to your change.
4. Open a **Pull Request** with a short description and before/after notes.

If unsure, open a **Discussion/Issue** first—small PRs are welcome!

## File conventions

**Hardware (CAD)**
- Preferred “source” is native, editable CAD (e.g., Fusion 360 **.F3Z** with components).
- Also export **STEP (.step/.stp)** for interoperability.
- Meshes (3MF) are welcome as print outputs but are not a substitute for source.

**BoM**
- Edit `bom/bom.csv`; include part name, material/spec, qty, and notes (e.g., ISO/DIN for fasteners).

**Printing**
- Add per-part settings to `docs/printing-settings.csv`.
- Keep human-readable guidance in `docs/printing.md` (link images from `docs/gallery/`).

**Docs**
- Keep `README.md` newcomer-friendly (what/why/how, quick start links).
- Add photos/renders to `docs/gallery/` and reference them with relative paths.

## Review checklist (maintainers)
- Source CAD present/updated (native + STEP).
- BoM updated if parts/materials changed.
- Printing/assembly notes updated if relevant.
- Licenses unchanged and headers intact.

## Licenses and sign-off
By contributing, you agree that:
- **Hardware contributions** are provided under **CERN-OHL-P v2.0**.
- **Documentation contributions** (text/images) are provided under **CC BY 4.0**.

If you include third-party content, ensure it’s compatible and **properly attributed** (for docs: use CC-BY TASL).