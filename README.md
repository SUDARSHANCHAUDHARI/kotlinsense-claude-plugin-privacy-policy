# KotlinSense — Privacy Policy

This repository hosts the official privacy policy for the **KotlinSense** Claude Code plugin.

**Live privacy policy:** https://sudarshanchaudhari.github.io/kotlinsense-claude-plugin-privacy-policy/

---

## About KotlinSense

**KotlinSense** is a Claude Code plugin for Kotlin and Android developers. It connects Claude Code to `kotlin-language-server` running locally on your machine, providing automatic type-error diagnostics, missing import detection, null safety checks, and code navigation — injected directly into Claude's context after every `.kt` file edit.

### What It Does

1. Connects Claude Code to `kotlin-language-server` via the Language Server Protocol (LSP)
2. After every `.kt` / `.kts` file edit, diagnostics are injected into Claude's context automatically
3. Claude sees errors like `"Unresolved reference 'foo' at MainActivity.kt:42"` and fixes them in the same turn — no manual compile step needed

### Commands

| Command | Description |
|---|---|
| `/kotlinsense:install` | Download and install `kotlin-language-server` |
| `/kotlinsense:status` | Check binary, Java, and LSP activation status |
| `/kotlinsense:navigate` | Go-to-definition, find references, type inspection |

---

## Install

```bash
/plugin install kotlinsense@SUDARSHANCHAUDHARI-KotlinSense
/kotlinsense:install
```

Requires Java 17+. No project-specific config needed — install the binary and go.

---

## Plugin Repository

Full source code, documentation, and issue tracker:
**https://github.com/SUDARSHANCHAUDHARI/KotlinSense**

---

## Privacy Policy for This Plugin

KotlinSense does **not** collect, transmit, or store any user data. All code analysis happens locally via `kotlin-language-server` on your machine. No source code or diagnostics are sent to any external server.

The full privacy policy for this plugin is available at:
**https://sudarshanchaudhari.github.io/kotlinsense-claude-plugin-privacy-policy/**

---

## Author

**SUDARSHANCHAUDHARI** — [github.com/SUDARSHANCHAUDHARI](https://github.com/SUDARSHANCHAUDHARI)
SudarshanTechLabs | sudarshantechlabs@gmail.com

## License

MIT
