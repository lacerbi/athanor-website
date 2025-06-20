---
id: project-setup
title: Project Setup
sidebar_position: 2
---

# 1. Project Setup

When you first launch Athanor, you'll be prompted to **select a project folder**. This is where Athanor will analyze your files and help you create AI prompts.

## Folder Selection

Choose any folder containing code, documentation, or files you want to work with. This could be:

- A software development project
- A documentation repository
- A research project with various file types
- Any folder structure you'd like AI assistance with

## Ignore File Configuration

Athanor filters files using both `.gitignore` and its own `.athignore` file. This keeps your workspace clean and ensures prompts contain only relevant content.

### How It Works

- **`.gitignore`**: By default, Athanor automatically respects the rules in your project's `.gitignore` file. You can disable this behavior in the **Settings** tab.
- **`.athignore`**: This file is used for Athanor-specific rules or to override `.gitignore`. For example, you can re-include a file ignored by `.gitignore` using an exception rule like `!path/to/file`.

### Initial Project Setup

When you first select a project folder, Athanor helps you configure your ignore settings:

- If a `.gitignore` file is present, its rules are applied automatically.
- If your project does not have an `.athignore` file, a dialog will appear offering to create a default one. This is recommended and includes common rules for files like `node_modules/`, `.git/`, and build artifacts.

:::info What is the `.athignore` file?
The `.athignore` file gives you fine-grained control over file visibility within Athanor without modifying your project's main `.gitignore`.

Key characteristics:

- **Role**: It works alongside `.gitignore` to filter the project. Use it for Athanor-specific rules or to override `.gitignore` rules.
- **Gitignore-like Syntax**: It uses the same pattern matching as `.gitignore` (e.g., `node_modules/`, `*.log`, `build/`) and supports advanced wildcards.
- **Purpose**: To hide irrelevant files, build artifacts, or sensitive directories, keeping your Athanor workspace focused.

**If a file or folder does not appear in Athanor's file explorer, it is likely due to a rule in either `.gitignore` or `.athignore`.** You can edit the appropriate file to adjust visibility.
:::

## Project Scanning

Once the folder is selected:

1. Athanor scans your project directory.
2. Files and folders matching rules in `.gitignore` (if enabled) and `.athignore` will **not** appear in the File Explorer.
3. The filtered file tree is displayed in the **File Explorer** on the left panel

## Supplementary Materials

Athanor automatically creates a hidden `.ath_materials` folder in your project to store:

- Documentation fragments
- Project-specific settings
- Custom prompt templates (if you create any)
- Other supplementary materials

This folder helps keep Athanor-specific files organized without cluttering your main project.

## Next Steps

With your project configured, you're ready to explore Athanor's interface and start creating your first AI prompts!
