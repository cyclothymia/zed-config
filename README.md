# Zed Editor Configuration

This repository contains my custom configuration for the [Zed Editor](https://zed.dev), designed to enhance productivity and streamline the development process. Below is a detailed overview of the configuration settings:

## General Settings
- **Default Open AI Model:** gpt-4o
- **Base Keymap:** VSCode
- **Nightly Channel:** Enabled (stable)

## Telemetry
- **Diagnostics:** Disabled
- **Metrics:** Disabled

## UI & Font
- **Theme:** XY-Zed (suitable for both day and night use)
- **UI Font Size:** 18 (alternates between 15 and 18)
- **Buffer Font Size:** 18 (alternates between 15 and 18)
- **Buffer Font Family:** AnonymicePro Nerd Font Mono
- **UI Font Family:** AnonymicePro Nerd Font Mono
- **Buffer Line Height:** Comfortable

## Editor Settings
- **Tab Size:** 4
- **Cursor Blink:** Enabled
- **Preferred Line Length:** 80
- **Formatter:** Prettier
- **Autosave:** On focus change with 200ms delay
- **Autosave on Build:** Enabled with 300ms delay for build, run, and debug events
- **Vim Mode:** Disabled
- **Confirm Quit:** Disabled
- **Hover Popover:** Enabled
- **Copilot Suggestions:** Enabled
- **Inlay Hints:** Enabled (type hints, parameter hints, chaining hints)

## Terminal Settings
- **Alternate Scroll:** Off
- **Blinking:** Terminal controlled
- **Copy on Select:** Disabled
- **Font Family:** AnonymicePro Nerd Font Mono
- **Font Size:** 18
- **Option as Meta:** Disabled
- **Working Directory:** Current project directory

## Git Integration
- **Enabled:** Yes
- **Auto Fetch:** Enabled with 300s interval and on focus/window change/build
- **Git Gutter:** Tracked files

## Prettier Configuration
- **Print Width:** 80
- **Tab Width:** 2
- **Use Tabs:** No
- **Semicolons:** Yes
- **Single Quotes:** Yes
- **Trailing Commas:** All
- **Bracket Spacing:** Yes
- **JSX Bracket Same Line:** No
- **Arrow Parentheses:** Avoid
- **Prose Wrap:** Preserve
- **End of Line:** LF

## Linter
- **Linter:** ESLint
- **Bracket Pairing:** Always
- **ESLint Auto Fix on Save:** Yes
- **ESLint Auto Fix on Format:** Yes with 1500ms delay

## Language Specific Settings
- **JavaScript:** Auto fix on format with ESLint
- **TypeScript:** Organize imports and auto fix with ESLint
- **TSX:** Organize imports and auto fix with ESLint

## Language Server Protocol (LSP)
- **TypeScript Language Server Initialization Options:**
  - **Inlay Parameter Name Hints:** All
  - **Inlay Function Parameter Type Hints:** Yes
  - **Inlay Variable Type Hints:** Yes (excluding when type matches name)
  - **Inlay Property Declaration Type Hints:** Yes
  - **Inlay Function-like Return Type Hints:** Yes
  - **Inlay Enum Member Value Hints:** Yes
