# One place to start from, and sharing that explains itself

The Quick Hub stops being a window and becomes a panel over your work — and
eleven other windows go with it. Sharing a project has been rebuilt around what
actually goes wrong with it, and there is a guide for the one thing slateX
cannot do for you: getting LaTeX onto the Mac in the first place.

## The Quick Hub

- ⌘H opens it over your project; Escape, ⌘H again, or a click outside puts it away. As a window it opened behind things, could be resized into shapes the layout never expected, and had no Escape
- Eleven windows became panels with it — Guides, Help, Get in Touch, What's New, Import, Licence, Report a Problem, Shortcuts, Version History, Add To-Do and pandoc. The popped-out library stays a window, because keeping it open beside your work is the whole point of one
- Every door out of the hub comes back to it when you close what it opened. The two that do not are the two where you have arrived rather than passed through: opening a project, and starting a guide
- Every project card says what is true about it — when you last wrote in it, how many to-dos are open, whether the PDF is behind the source, and how many commits a co-author cannot see yet
- Send a project's PDF, or zip the whole thing, without opening it first
- The header stays put as you scroll, and Settings opens from the hub at all — it used to do nothing

## Sharing

- Every git command now runs off the main thread. A push over a slow connection no longer freezes the window
- A password pasted into the repository URL is moved into the keychain rather than being written into the project in plain text and shown on screen
- An SSH key the server turned down is told apart from a missing password — one of those a password box can fix and the other it cannot
- A missing name and email, a rejected key and a dropped connection each get a sentence instead of git's own wording
- Half a resolved conflict counts as a conflict: deleting the closing marker and stopping used to read as finished, and committed the markers
- Clone a repository returns you to the hub like everything else, and Disconnect asks first and says what it does not delete

## Finding your way

- A course on getting LaTeX onto a Mac that has never had it — what latexmk is, MacTeX against BasicTeX, why you have to restart slateX afterwards, and the three places it looks
- Guides says so at the top whenever this Mac cannot typeset yet
- What's New is this page, in the app, read from the same feed the updater checks — so it cannot be a version behind
- The Extras list is things you can act on: pandoc copies its install command, chktex points at MacTeX
- ⌘K closes the command palette as well as opening it

## Writing

- Type \todo or \comment and it becomes a % TODO: or % COMMENT: as you finish the word, coloured in the editor and collected in the task board
- Zotero and Mendeley say "Coming soon" instead of being disabled and silent about it

## Fixed since 0.13

- Sparkle's helper executables were signed by nobody, so no automatic update had ever installed — it downloaded, quit the app, and left the old version in place. A copy older than 0.13.1 cannot update itself to this fix, so it needs installing by hand once (0.13.1)
- With no project open the window stopped half-way down and left the rest bare. The page fills it now, the same way three open panes do (0.13.2)
