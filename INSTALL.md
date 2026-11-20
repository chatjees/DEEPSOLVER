# Install DEEPSOLVER 0.8 online preview

1. Download **DEEPSOLVER-Online-Setup-0.8.exe** from the release Assets and run it.
2. The installer downloads a checksum-verified portable Python runtime from the official astral-sh/python-build-standalone release, downloads the DEEPSOLVER compiled app payload from this release, and installs 57 pinned dependencies from public PyPI into its private runtime.
3. The installer creates a DEEPSOLVER desktop shortcut and opens the application. It does not modify your system Python or PATH. Installation needs internet and at least 1.1 GB of free disk space. Supported platform: Windows 10/11 x64 with .NET Framework and the standard Windows tar.exe utility.
4. In AI / ANSYS settings, configure your separate local Ollama model and appropriately licensed Ansys MAPDL executable.
5. In Trial / subscription, import your operator-issued signed activation file. Automatic public activation and Razorpay checkout are not live in this preview.
6. Create a DCB study or import APDL, review the model and inputs, then execute.

No ChatGPT subscription, OpenAI API key, Codex installation, Node.js or separately installed Python is required. After installation, inference uses your configured local model. Ansys and model licences are separate. No model weights are distributed.

The app is an unsigned engineering preview. General free-form Ansys/APDL generation is not implemented. The generated DCB template is 2D, fixed-crack and elastic; it does not establish ASTM compliance or determine GIc.

Settings, studies and activation: %LOCALAPPDATA%/DEEPSOLVER.
The small DEEPSOLVER-App-0.8.zip is the installer payload, not a complete portable application on its own.
The legacy offline parts and old archives are not needed for this online installer.

Validation: 12 product/licensing tests; private-runtime dependency installation; compiled-app self-test with plot and Excel export. No Ansys solver was rerun for this release; clean second-machine and broader Ansys-version testing remain pending.
