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
- **macOS**: Using Homebrew: `brew install node`
- **Linux**:
  - Ubuntu/Debian: `sudo apt update && sudo apt install nodejs npm`
  - Fedora: `sudo dnf install nodejs npm`
  - Or use [NVM](https://github.com/nvm-sh/nvm) (recommended): `nvm install --lts`

### Athanor

If you haven't installed Athanor yet, follow these steps:

1. **Clone the repository**: `git clone https://github.com/lacerbi/athanor.git`
   - Or simply [**download it**](https://github.com/lacerbi/athanor/archive/refs/heads/llm-api-calls.zip)
2. **Navigate to the project directory**: `cd athanor`
3. **Install dependencies**: `npm install`
4. **Run the application**: `npm run dev`
   - You can also compile it into an executable with `npm run package`

Once Athanor launches, you're ready to begin the tutorial!

## Open Source & Community Feedback

Athanor is an open-source project. You're welcome to explore the [codebase on GitHub](https://github.com/lacerbi/athanor).

:::warning 🚧 **ALPHA SOFTWARE**: 🚧

Please be aware that Athanor is currently in an **alpha stage**. This means the application is under active development. Features described here may evolve, and you might encounter some rough edges or bugs.

Your feedback is incredibly valuable as we refine both the application and this tutorial. Please report any issues or share your thoughts via [GitHub Issues](https://github.com/lacerbi/athanor/issues) and [GitHub Discussions](https://github.com/lacerbi/athanor/discussions).

Thank you for exploring Athanor!

:::
