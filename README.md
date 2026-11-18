# CoDev

A Mac terminal for running several [Claude Code](https://claude.com/claude-code) sessions side by
side: a status dot per session (blue working, orange needs you, green done), tabs for the files
Claude touches, and a code panel that lights up what it just changed.

Universal (Apple silicon + Intel), macOS 14 Sonoma or newer. Built from a private repo; this one
only holds the releases.

## Install — ask Claude

Paste this to Claude Code:

> Please install the CoDev app for me. Download
> https://github.com/kenjichristopherv-del/codev-releases/releases/latest/download/CoDev.zip
> with curl into a new temporary folder, unzip it there with `ditto -x -k`, and replace
> /Applications/CoDev.app with the CoDev.app from it. Don't quit CoDev if it's running; I'll
> reopen it myself. Then open it.

The same request installs updates.

## Install — by hand

Download [CoDev.zip](https://github.com/kenjichristopherv-del/codev-releases/releases/latest/download/CoDev.zip),
unzip it, drag CoDev into Applications and open it. The first time, macOS will say it can't check
CoDev for malware: click **Done**, then System Settings › Privacy & Security › **Open Anyway**.
