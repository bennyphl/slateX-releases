<div align="center">

# slateX

**A native LaTeX editor for macOS.**

Write in LaTeX without living in it — your document rendered as you type,
your Zotero library kept in step, and every successful compile saved.

[![Download slateX 0.11.0](https://img.shields.io/badge/Download-slateX%200.11.0-1f6feb?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/bennyphl/slateX-releases/raw/main/slateX-0.11.0.dmg)

macOS 13 or later · Apple silicon and Intel · requires a TeX distribution

</div>

---

## What it does

**Visual mode** hides the markup and styles the content in place — `\section{}`
becomes a heading, `\alpha` becomes α — while the source stays the only source
of truth, one keystroke away.

**Your Zotero library, live.** Connect once and `library.bib` keeps itself
current. Add a paper in Zotero and it's citable here within two minutes.

**The PDF and the source, in step.** Click a paragraph in the PDF to land on
the line that made it, and jump the other way from the editor.

**Every compile is a save point.** Version history that travels with the
project folder — no setup, nothing to remember.

Plus maths rendered as you type, a table editor that's an actual grid, an
arXiv-ready export, style warnings from `chktex`, project-wide search, an
outline that spans files, and fifteen themes.

## Installing

1. Download the DMG above.
2. Open it and drag **slateX** to Applications.
3. First launch: right-click the app and choose **Open**.

That last step is needed because slateX isn't notarized yet — the signing
account is a personal team, and Apple won't notarize a development-signed app.
It's on the list.

**You also need a TeX distribution.** slateX drives the `latexmk` on your Mac
rather than shipping its own, so the PDF you get is the one your publisher
gets. [MacTeX](https://tug.org/mactex/) is the usual choice. slateX tells you
if it can't find one.

## Updating

slateX updates itself — **slateX ▸ Check for Updates…**, or automatically once
a day. Settings ▸ General ▸ Updates has the switches.

## About this repo

This is the download and update feed only. `appcast.xml` is what the app
checks; the source lives elsewhere.

Found a bug? **Help ▸ Report a Problem** in the app collects the log for you.
