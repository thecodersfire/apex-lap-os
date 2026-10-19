# Built-in features for apex-lap-os

Purpose: racing simulation

1. **prepare racing and game notes** — run apex-lap-os-workspace. It creates ~/Documents/apex-lap-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run apex-lap-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/apex-lap-os-session-plans/.
3. **check game and controller readiness** — run apex-lap-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/apex-lap-os-workspace features/apex-lap-os-plan features/apex-lap-os-check "$HOME/.local/bin/"
