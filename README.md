<p align="center">
  <img src="assets/icon.png" alt="MthwShell" width="144" height="144">
</p>

<h1 align="center">MthwShell</h1>

<p align="center">A portable Windows terminal with tabs, split panes, customizable themes, and desktop alerts.</p>

<p align="center">
  <a href="https://github.com/mthwSec/mthwshell/releases/latest">Download for Windows</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/mthwSec/mthwshell/issues/new/choose">Report an issue</a>
</p>

## Download and start

1. Open [the latest release](https://github.com/mthwSec/mthwshell/releases/latest).
2. Download **MthwShell-0.1.0-windows-x64.zip** from **Assets**.
3. Extract the ZIP into a folder on your PC or USB drive.
4. Run **mthwshell.exe**. No installer, Node.js or Rust is needed.

Choose the **MthwShell** ZIP from Assets. GitHub's automatic **Source code**
downloads contain this download page and documentation, not the application.

The package includes a short guide, checksums and third-party license notices.

## Features

- **Tabs:** keep terminals for several folders running at once.
- **Split panes:** work with terminals side by side or stacked vertically.
- **Your preferred shell:** Git Bash, PowerShell and Command Prompt, plus profiles for supported command-line tools.
- **Appearance:** eight themes, bundled fonts, cursor controls, spacing, opacity and window effects.
- **Desktop alerts:** attention indicators and notifications for supported profiles.
- **Portable preferences:** carry your appearance settings with the app.
- **Fresh start:** each launch opens one Home tab in the current Windows user's folder.

## Requirements

- Windows 10 or Windows 11, **64-bit x64**.
- [Microsoft Edge WebView2 Runtime](https://developer.microsoft.com/microsoft-edge/webview2/). If it is missing, the app displays installation instructions.
- Optional: [Git for Windows](https://gitforwindows.org/) for Git Bash. Home uses PowerShell when Git Bash is unavailable.
- Other command-line programs must be installed separately to use their profiles.

The executable is currently unsigned, so Windows may display a publisher warning.

## Preferences and USB use

MthwShell saves appearance and alert preferences in **mthwshell.config.json** beside
the executable. Keep that file when updating or moving the app to another PC.

Tabs, folder paths, selected shells and split layouts last for the current session.
They are not restored on the next PC. Each launch opens a fresh Home tab for that
PC's current user.

If the application folder is read-only, preferences are saved under
`%APPDATA%\MthwShell` instead, and the app shows the location. WebView2 and the
bundled console host also keep local files under `%LOCALAPPDATA%`. Shell history
and command-line account sign-ins are managed by the programs you run.

To update, close MthwShell and replace the application files with the new package.
Keep your existing preferences file.

## Keyboard shortcuts

| Action | Shortcut |
| --- | --- |
| New tab | Ctrl+Shift+N |
| Next / previous tab | Ctrl+Tab / Ctrl+Shift+Tab |
| Switch to tab 1–9 | Ctrl+Alt+1 through Ctrl+Alt+9 |
| Split right / down | Alt+Shift+= / Alt+Shift+- |
| Move between panes | Alt+Arrow |
| Close pane | Ctrl+Shift+W |
| Font bigger / smaller / reset | Ctrl+= / Ctrl+- / Ctrl+0 |
| Copy / paste | Ctrl+Shift+C / Ctrl+Shift+V |

The palette menu opens themes and appearance controls. **More settings** includes
the full keyboard guide.

## Feedback

Use [Issues](https://github.com/mthwSec/mthwshell/issues) for bug reports and feature
requests. Include your Windows version, MthwShell version and steps to reproduce.
Remove account details, private paths and sensitive terminal output before posting.

## License

MthwShell is **freeware**: free to use for personal and commercial purposes under
the [MthwShell Freeware License](LICENSE.txt). Its application source code is not
distributed. This repository contains download information and public documentation.

Third-party components retain their own licenses. Their notices and source
availability information are included with every release.

Maintained by [mthwSec](https://github.com/mthwSec).
