---
id: introduction
title: Getting Started with Athanor
sidebar_position: 1
---

# Getting Started with Athanor

Welcome to the Athanor tutorial!

Athanor is a desktop application designed to help users and developers integrate AI assistants into their workflow. It streamlines creating AI prompts with relevant file context and applying the AI-generated changes back to your project or codebase.

<video
autoPlay
muted
playsInline
controls
className="tutorial-hero-video"
title="Athanor AI Workbench Demo"

>

  <source src="/video/athanor-demo-av1.mp4" type='video/mp4; codecs="av01.0.05M.08"' />
  <source src="/video/athanor-demo-x264.mp4" type="video/mp4" />
  Your browser does not support the video tag. Consider upgrading to a newer browser.
</video>

_Watch Athanor's workflow in action: Describe task → Select files → Generate prompts → Use any AI chat assistant → Review and apply changes_

## What You'll Learn

This tutorial will guide you through Athanor's main features:

- **Project Setup**: How to configure your project with Athanor
- **Interface Navigation**: Understanding the layout and panels
- **Prompt Creation**: Building effective AI prompts with context
- **Applying Changes**: Reviewing and implementing AI suggestions
- **Advanced Features**: Custom templates, preset tasks, and workflows

## Prerequisites

Before starting, ensure you have:

- **Node.js** (latest LTS version, v18.x+) installed
- A code project or folder you'd like to work with
- Access to an AI assistant like ChatGPT, Claude, or Gemini

## Installation

### Node.js

Follow these steps if **Node.js** is not installed in your system.

- **Windows**: Download and install from [nodejs.org](https://nodejs.org/)
- **macOS**:
  - Using Homebrew (recommended): `brew install node`
  - Download and install from [nodejs.org](https://nodejs.org/)
- **Linux**:
  - Ubuntu/Debian: `sudo apt update && sudo apt install nodejs npm`
  - Fedora: `sudo dnf install nodejs npm`
  - Or use [NVM](https://github.com/nvm-sh/nvm) (recommended): `nvm install --lts`

### Athanor

If you haven't installed Athanor yet, follow these steps.

The easiest way to install Athanor is with the command-line installer:

```bash
npx setup-athanor [athanor-installation-folder]
```

This command downloads the Athanor source code, installs all necessary dependencies, and compiles a ready-to-run desktop application. The `[athanor-installation-folder]` is optional and defaults to `athanor`.

### Running Athanor

After the setup script finishes, you can launch the compiled application.

1.  **Locate the application:** The Athanor executable is in the `out` subfolder of your installation directory.
    - **macOS**: `[athanor-installation-folder]/out/Athanor-darwin-*/Athanor.app`
    - **Windows**: `[athanor-installation-folder]\out\Athanor-win32-*\Athanor.exe`
    - **Linux**: `[athanor-installation-folder]/out/Athanor-linux-*/Athanor`
2.  **Launch Athanor:** Simply double-click the application to run it.

<details>
<summary>🛡️ <strong>Security Warning When Running the App for the First Time</strong></summary>

Because the application is compiled on your machine and not signed by a verified developer, your OS might show a security warning.

- **On macOS:** Gatekeeper may block the app.

  1.  Right-click the `Athanor.app` icon and select "Open".
  2.  A dialog will appear warning you that the developer is unidentified. Click the "Open" button to run the app.
      You only need to do this the first time you launch the application.

- **On Windows:** You may see a "Windows SmartScreen" popup. Click "More info" and then "Run anyway" to proceed.

</details>

<details>
<summary><strong>Manual Installation & Alternative Running Methods</strong></summary>

If the `npx` command fails, or if you prefer to set up the project manually, follow these steps.

**1. Clone the Repository:**

```bash
git clone [https://github.com/lacerbi/athanor.git](https://github.com/lacerbi/athanor.git)
```

Alternatively, you can [download the source code](https://github.com/lacerbi/athanor/archive/refs/heads/main.zip) as a ZIP file and extract it.

**2. Install Dependencies:**

```bash
cd athanor
npm ci
```

**3. Choose how to run the app:**

- **Option A: Compile the Application (Recommended)**
  Manually compile the application into a standalone executable.

  ```bash
  npm run package
  ```

  This creates the application in the `out` folder, which you can then run as described above.

- **Option B: Run in Development Mode**
  This method is useful for development but is slower and opens a console with the application.

  ```bash
  npm start
  ```

</details>

Once Athanor launches, you're ready to begin the tutorial!

## Open Source & Community Feedback

Athanor is an open-source project. You're welcome to explore the [codebase on GitHub](https://github.com/lacerbi/athanor).

:::warning 🚧 **ALPHA SOFTWARE**: 🚧

Please be aware that Athanor is currently in an **alpha stage**. This means the application is under active development. Features described here may evolve, and you might encounter some rough edges or bugs.

Your feedback is incredibly valuable as we refine both the application and this tutorial. Please report any issues or share your thoughts via [GitHub Issues](https://github.com/lacerbi/athanor/issues) and [GitHub Discussions](https://github.com/lacerbi/athanor/discussions).

Thank you for exploring Athanor!

:::
