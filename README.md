# The Recursive Manifesto

## Quick Start (Fork + Stamp 105)

1. In the site, type your tenet in line 100 and click Fork this manifesto.
2. The app copies one line to your clipboard: 105 "your tenet".
3. Create your fork on GitHub.
4. In your new fork, set repository description to your tenet text (replace paste your tenet here).
5. Open Actions in your fork and run Stamp Tenet From Description.
6. The workflow writes line 105 into MANIFESTO.txt and README.md, commits, and creates the next minor tag.

Note: The workflow does not auto-run at fork creation. It runs when you trigger it in Actions (or on a later push).

- 000 Process cannot exist without goals.
- 010 Build only what’s unique, steal the rest.
- 020 There is no worthy form without restraint.
- 030 If it cannot be observed it cannot be controlled.
- 040 What cannot bend, breaks. What cannot hold, hollows the whole.
- 050 There are no observers, only participants.
- 060 There is no improvement without corruption.
-
- 080 Complacency causes casualty.
- 090 Nothing exists in isolation.
- 100 Complete works are dead works.
- 110 GOTO 000

## Fork Stamping Behavior

- Enter text on 100 and click Fork this manifesto.
- The app inserts line 105 only when you enter text on 100; with no input, 105 does not exist.
- Before opening GitHub fork, the app copies the single tenet line 105 "your tenet" to your clipboard.
- The fork link includes a preseeded description query value: paste your tenet here.
- After the repo exists, run the Stamp Tenet From Description action in Actions.
- The action reads repository description, inserts line 105 into MANIFESTO.txt and README.md, commits, and bumps a minor tag (for example v0.1.0 -> v0.2.0).
