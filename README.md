# RETECH Manager — releases

Builds of **RETECH Manager**, the desktop app that runs RETECH Endoscope Repair. The source is
private; this repository only publishes the Windows executable, and it is where an installed
copy looks for its next update.

## Install

1. Open the latest release under **Releases** and download `RetechManager.exe`.
2. Run it. Windows SmartScreen may warn that the app is unrecognised (it is not code-signed
   yet): choose **More info → Run anyway**.
3. Choose **Install**. The app copies itself to `%LOCALAPPDATA%\RetechManager\app\` and adds a
   desktop shortcut.

## Updates

The installed app checks this feed when it starts. When a new version is out, a banner offers
**Download & install**; the app replaces itself and restarts. Your data stays in
`%LOCALAPPDATA%\RetechManager` and is backed up automatically before any database change.

## What a build contains

No credentials, no customer data and no prospect lists: those live only on the machine that
runs the app. Each release's notes are the app's own changelog entry for that version.
