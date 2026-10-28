# Phosphene

The Mac app for making logo films: the brand's mark at the same place and size in every shot, a different material or scene each time.

This repository holds only the app's releases (the download and its automatic updates), never its code.

## Install

1. Download `Phosphene_…_aarch64.dmg` from the latest [release](../../releases/latest) (a Mac with Apple silicon, M1 or newer).
2. Open it and drag Phosphene to Applications.
3. Open it. The first time, macOS says it cannot verify the developer (the app is not notarized by Apple yet): click **Done**,
   then open System Settings › **Privacy & Security**, scroll to "Phosphene was blocked…", click **Open Anyway** and enter your
   password. Only once: after that it opens normally, and it updates itself (when a new version is out it says so, and
   **Restart to update** installs it).

Have 0.1.0 and it says "damaged"? Take the latest version above instead (or, in Terminal:
`xattr -dr com.apple.quarantine /Applications/Phosphene.app`).

Your projects live in **Documents › Phosphene**. To start, open a project file you were sent (double-click it), or make a new one
from the project menu.
