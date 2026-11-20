# DEEPSOLVER

Independent Windows software for prompt-assisted Ansys MAPDL automation through Python.

**Created by Deep Chatterjee, Research Scholar, IIT (ISM) Dhanbad.**

## Download

Download [DEEPSOLVER-Online-Setup-0.8.exe](https://github.com/chatjees/DEEPSOLVER/releases/download/v0.8.0-preview/DEEPSOLVER-Online-Setup-0.8.exe). The installer prepares a private Python runtime and installs pinned dependencies automatically. Internet is needed during installation; no system Python or ChatGPT account is required. See [all release assets](https://github.com/chatjees/DEEPSOLVER/releases).

Legacy offline fragments are not required by the online installer.

## Current preview

- Local model interpretation of supported requests; no ChatGPT/Codex/OpenAI credentials or runtime required.
- Composite DCB specimen setup with explicit-input checks and a fixed-crack, elastic 2D APDL template.
- Reviewed execution of imported APDL inputs through PyMAPDL.
- Configured mesh iterations, solver logs, convergence plots, CSV, Excel and study summaries.
- Signed, device-bound activation files and a 10-day initial trial recorded by an operator-side issuer.

General free-form Ansys/APDL generation is not implemented. The DCB preview does not establish ASTM compliance, determine GIc or validate arbitrary fracture models.

## Requirements

Windows x64, a separately installed/licensed Ansys MAPDL solver, a local Ollama service with a suitably licensed model, and a signed activation file for solver access. Python is bundled. Ansys and model licences are separate from DEEPSOLVER access.

## Trial and subscriptions

The trial starts at first activation, not download. In this engineering preview, activation files are operator-issued. **Public automatic activation and checkout are not live.**

Planned INR period totals: monthly ₹1,999; quarterly ₹4,999; semiannual ₹9,999; annual ₹19,999. Razorpay is the selected provider. No payment is collected by this repository.

## Installation and support status

Read [INSTALL.md](INSTALL.md) and [RELEASE_NOTES.md](RELEASE_NOTES.md). The application is an unsigned engineering preview and has not been validated on a clean second computer or across a supported Ansys version matrix.

This repository distributes release binaries and documentation. Application source, licence-signing private keys, merchant credentials, research data and model weights are not included.

## Company website

A separately deployable website is being prepared. A custom company domain has not been registered or connected. GitHub Releases is the current independent download route.
