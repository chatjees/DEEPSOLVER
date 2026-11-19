# Install DEEPSOLVER 0.8 preview

1. Download the Windows x64 preview ZIP from this repository's Releases page.
2. Extract the complete ZIP. Run `DEEPSOLVER/DEEPSOLVER.exe`, or run the supplied `Install.ps1` with PowerShell to install for the current Windows user.
3. Open **AI / ANSYS settings**. Select your local model service, installed model name and Ansys executable.
4. Open **Trial / subscription** to see your activation device code and import an operator-issued signed activation JSON file.
5. Create a DCB study or import an APDL input. Review inputs and model assumptions before executing the solver.

The download does not automatically start the trial. The initial 10-day period starts when the operator activates the device. Automated customer activation and Razorpay checkout are not available yet.

## Local data

Application settings, study files and activation live in `%LOCALAPPDATA%/DEEPSOLVER`. Installation does not include data from the developer's research workspace. Keep backups of your own studies.

## Prerequisites

The application bundles Python and PyMAPDL. It does not include Ansys, an Ansys licence or AI model weights. Configure a local Ollama model with appropriate terms. No ChatGPT subscription, OpenAI API key, Codex installation or Node.js is required.

## Verification and limits

The installer is unsigned. This is an engineering preview. DCB modelling is fixed-crack and elastic, with idealized fixtures. Successive mesh stability is not proof of physical accuracy. Review actual solver logs and independently validate models/results.
