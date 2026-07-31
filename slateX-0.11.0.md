# slateX 0.11.0

## Your Zotero library, live

Connect once and `library.bib` keeps itself current. slateX asks Zotero
directly — through Better BibTeX's local endpoint — so adding a paper in
Zotero makes it citable here within two minutes, with no export step and
nothing to remember.

**Connect Library** now asks which manager you use rather than handing you
a file picker. Zotero connects for real; Mendeley and the Zotero web API
say so honestly and point at the exported-`.bib` route that works today,
which slateX watches for re-exports.

Entries carry their origin as a comment — `% from Zotero`,
`% added by DOI import`, `% added by hand` — so a `.bib` you send a
co-author explains itself. Anything you typed yourself is kept below a
divider instead of being flattened by the next sync.

## Two projects, two windows

Every window now owns its own project. **⇧⌘O** opens a folder in a new
window, and the menu bar, ⌘K, Version History and the Library panel all
follow whichever window is in front. Quitting saves every open window's
work, not just the one you were looking at.

## The Quick Hub

The start window is the Quick Hub now, and a first launch actually lands
on it — it used to open *behind* an empty editor, so slateX greeted a new
user with a dark, empty three-pane window. Reach it from ⌘K, the File
menu, or by clicking the slateX mark at the top of the sidebar.

## Typing got cheaper

Every keystroke used to copy the whole document across the SwiftUI
boundary. It doesn't any more, which is most noticeable in a long chapter.

Very large files now say what they're switching off — whole-document
highlighting, snapshots, live maths — rather than quietly becoming slow.
The threshold is yours to set in Settings ▸ Editor.

## Fixes

- **Deleting an included chapter no longer breaks the document.** Its
  `\input` line went with it — and deleting a folder takes every chapter
  under it. Left behind, that line was a hard LaTeX error in a file you
  had never opened. A crash on the same path is gone too.
- **A hand-written entry in `library.bib` no longer vanishes** on the next
  sync.
- The Library panel was showing raw LaTeX where it meant to show text.

## Smaller things

- **Help ▸ Report a Problem** — a real log file, with copy-everything and
  reveal-in-Finder.
- Optional interface text size, under Settings ▸ Appearance. The editor
  keeps its own.
- Settings lost the paragraphs that explained why a setting exists rather
  than what it does.
