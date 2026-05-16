# KotlinSense Privacy Policy

**Effective Date:** May 17, 2026
_Last updated: May 17, 2026_
**Version:** 1.0.0

KotlinSense ("we," "our," or "us") is a Claude Code plugin for Kotlin and Android developers that connects Claude Code to `kotlin-language-server` running locally, then surfaces Kotlin diagnostics, missing imports, null-safety issues, and navigation context while you work. This Privacy Policy explains what information the plugin can access locally, how it is used, and the choices you have. By installing or using KotlinSense, you agree to the practices described below.

## Information We Collect

### Location Data
- **Not collected**: KotlinSense is a Claude Code plugin, not an Android app or mobile service. It does not request, collect, infer, store, or share device location data.
- **No background location**: The plugin does not run a mobile background location service and does not use GPS, Wi-Fi, Bluetooth, or cell-tower location signals.

### Account Information
- **No plugin account**: KotlinSense does not require a separate account, login, or hosted user profile.
- **Local developer settings**: The plugin may use developer details you enter in Claude Code settings or local project configuration, if relevant to the command you run.
- **GitHub identity**: If a workflow references GitHub repositories, it uses the repository URLs or usernames you provide locally. KotlinSense does not operate a separate identity service.

### Device Information
- **Local project files**: Kotlin source files and Gradle/Kotlin project files opened in the local Claude Code workspace.
- Diagnostics produced locally by `kotlin-language-server`, including file paths, line numbers, unresolved references, type errors, missing imports, and related code-intelligence metadata.
- **Environment information**: The plugin may inspect local tool availability, such as Git, Java, Gradle, shell commands, or Claude Code plugin settings, only to perform requested local workflows.
- **No telemetry**: KotlinSense does not collect analytics, device identifiers, advertising IDs, crash reports, or usage telemetry.

## How We Use Your Information

### Location Sharing
- **Not applicable**: KotlinSense does not provide location sharing and does not share your location with anyone.
- Any location-related Android permissions in projects you inspect are treated only as local project text if they appear in files you ask Claude Code to analyze.

### Account Management
- There is no hosted KotlinSense account to create, manage, or delete.
- Local developer settings are used only to avoid repeated prompts and to generate project-specific output when you run commands.

### Service Improvement
- KotlinSense does not send usage data, diagnostics, or generated output to a SudarshanTechLabs server.
- Improvements happen through local plugin updates, source-code changes, documentation updates, and issue reports you choose to file manually.
- We do not run ads and do not sell, rent, or monetize your data to third parties.

## Storage and Retention

### Data Storage
- KotlinSense may install or reference a local `kotlin-language-server` binary and may use local LSP configuration files. It does not create a remote account or remote diagnostic store.
- All plugin-accessed content remains in your local Claude Code session, local filesystem, or the project repository you are working in.
- No plugin data is stored on a SudarshanTechLabs backend server.

### Data Retention
- Local settings remain until you delete them, reset Claude Code plugin settings, remove the project config, or uninstall the plugin.
- Generated files remain in your local project until you delete or commit them.
- Claude Code itself may retain conversation or workspace context according to Anthropic/Claude Code settings and policies; KotlinSense does not control that retention.

### Data Security
- KotlinSense is designed for local-first use inside Claude Code.
- Sensitive generated content, such as signing snippets, local config, or project metadata, should be reviewed before committing to git.
- The plugin does not intentionally transmit plugin-accessed data to external servers.

## Data Sharing

### Family Groups
- **Not applicable**: KotlinSense does not include family groups, groups, teams, social sharing, or location-sharing communities.
- Data is not shared with family members or other users by the plugin.

### Third Parties
- KotlinSense does not send source code or diagnostics to Firebase, Google Cloud, analytics services, advertising networks, or data brokers.
- The initial language-server installer may download `kotlin-language-server` from its upstream distribution source when you explicitly run the install command.
- See [Anthropic's Privacy Policy](https://www.anthropic.com/privacy) for Claude/Claude Code data practices.
- See [GitHub's Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement) for GitHub-hosted repositories or GitHub Pages that you choose to use.

We do **not** share your data with:
- Advertising networks
- Data brokers
- Analytics services operated by this plugin
- A SudarshanTechLabs backend server

## Permissions Used

### Required Permissions

* **Local workspace file access**: Required so Claude Code and KotlinSense can read or update project files that you explicitly work on.
* **Claude Code plugin configuration access**: Required to read plugin settings or command configuration when a command needs it.
* **Command-specific local tool access**: Read access to Kotlin and Gradle files in the local project where Claude Code is running. Local process execution for `kotlin-language-server` and install/status scripts when you explicitly run those commands.

### Optional Permissions

* **Network access**: Not required for normal local policy behavior, except for command-specific tasks you explicitly request, such as downloading a local tool, viewing documentation, or publishing a GitHub Pages repository.
* **Git/GitHub access**: Optional and used only when you explicitly ask for repository or publishing workflows.
* **Shell command execution**: Optional and subject to Claude Code/macOS approval flows when commands need to run local tools.

## Your Rights and Controls

### Location Sharing Control
- KotlinSense does not collect or share location data.
- If you inspect an Android project with location permissions, you control that project and its privacy disclosures separately.

### Account Management
- There is no KotlinSense hosted account.
- You can remove local plugin settings, project config, generated files, and the plugin itself at any time.

### Data Access
- You can inspect all files generated by KotlinSense in your local project.
- You can inspect plugin settings in Claude Code settings where applicable.
- You can review source code and documentation in the plugin repository.

### GDPR Rights (EU Users)
If you are in the European Union, you may have additional rights regarding personal data:
- **Right to Access**: Request a copy of personal data we may hold
- **Right to Rectification**: Correct inaccurate data
- **Right to Erasure**: Request deletion of data
- **Right to Restrict Processing**: Limit how data is used
- **Right to Data Portability**: Receive data in a portable format
- **Right to Object**: Object to certain types of processing

Because KotlinSense does not operate a hosted backend or collect plugin telemetry, most plugin-related data is under your direct local control. For questions, contact us using the methods in the Contact Us section.

### Permissions
- You can disable or uninstall KotlinSense in Claude Code.
- You can delete generated files from your project.
- You can deny local command execution when Claude Code asks for approval.
- You can avoid GitHub publishing workflows unless you explicitly want to publish generated files.

## Children's Privacy

- KotlinSense is a developer tool and is **not intended for children under 13**.
- We do not knowingly collect data from children under 13 through this plugin.
- If you believe a child has provided personal information through plugin-related communication, contact us to request deletion.

## Security

- KotlinSense follows a local-first design and does not intentionally transmit plugin-accessed files to a SudarshanTechLabs server.
- Review generated output before committing, publishing, or sharing it.
- Do not commit secrets, private keys, keystores, tokens, local config, or signing material.
- Keep Claude Code, Git, Java, Gradle, and other local tools updated.
- Use git ignore rules for machine-specific and secret files.

## Changes to This Policy

We may update this Privacy Policy to reflect new plugin features, legal requirements, or changes in our practices. Significant changes will be:
- Noted in plugin release notes or changelog when applicable
- Updated in this repository
- Published with a new "Last updated" date

The "Last updated" date at the top of this policy indicates when revisions occurred. Continued use of the plugin after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions about this Privacy Policy, wish to request deletion of any information you sent us directly, or have privacy concerns:

* **GitHub Repository:** https://github.com/SUDARSHANCHAUDHARI/kotlinsense-claude-plugin-privacy-policy
* **Email:** sunny.sudarshan@gmail.com
* **Plugin Repository:** https://github.com/SUDARSHANCHAUDHARI/KotlinSense
* **Live Privacy Policy:** https://sudarshanchaudhari.github.io/kotlinsense-claude-plugin-privacy-policy/

We will respond as quickly as possible, typically within 48 hours.

## Data Deletion

### How to Delete Your Account:
There is no hosted KotlinSense account. You have multiple options to remove plugin-related local data:

#### Option 1: In-App Deletion
1. Open Claude Code
2. Disable or uninstall the KotlinSense plugin
3. Remove any KotlinSense plugin settings from Claude Code settings
4. Delete any generated files or local configuration from the project where you used the plugin

#### Option 2: Email Deletion Request
Send an email to: **sunny.sudarshan@gmail.com**
- Subject: "KotlinSense Privacy/Data Deletion Request"
- Include: What information you believe you sent to us directly
- We'll review and respond within 48 hours

#### Option 3: Web Deletion
KotlinSense does not provide a hosted web account deletion portal because it does not create hosted user accounts.

### What Gets Deleted:
- Local plugin settings you remove from Claude Code
- Local generated files you delete from your project
- Local project configuration files you delete
- Any direct support-request information you ask us to delete, where legally and technically possible

### Data Retention After Deletion:
- **Immediate:** Local files/settings are removed when you delete them from your machine
- **Support email:** Support messages may remain in email systems unless you request deletion and deletion is legally/technically possible
- **No hosted plugin backend:** There is no KotlinSense server database to delete from

1. Uninstall KotlinSense from Claude Code.
2. Remove the locally installed `kotlin-language-server` binary if it was installed by the plugin.
3. Remove any local LSP/config files you no longer want in the project.

## Firebase and Google Services

- KotlinSense does not use Firebase Authentication, Firebase Realtime Database, Firebase Analytics, Firebase Crashlytics, Google Maps, AdMob, or Google Location Services as part of the plugin privacy-policy workflow.
- If KotlinSense helps inspect or generate disclosures for an Android app that uses Firebase or Google services, that information is read from your local project files and belongs to that Android app's own privacy policy.
- See [Google's Privacy Policy](https://policies.google.com/privacy) for Google's data practices when you independently use Google services.

## About KotlinSense

KotlinSense is a Claude Code plugin for Kotlin and Android developers that connects Claude Code to `kotlin-language-server` running locally, then surfaces Kotlin diagnostics, missing imports, null-safety issues, and navigation context while you work.

Main commands include: `/kotlinsense:install`, `/kotlinsense:status`, `/kotlinsense:navigate`.

The plugin is intended to run inside Claude Code and operate on local project files under your control.

## Recent Updates (Version 1.0.0 - May 17, 2026)

- Initial plugin privacy policy aligned with the shared SudarshanTechLabs privacy policy structure.
- Clarifies local-only Kotlin diagnostics and language-server behavior.
