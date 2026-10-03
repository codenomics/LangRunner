# LangRunner

> This application is built by AI. I made this for myself and I'm uploading it to GitHub for backup and to share in case anyone can get any use out of it. It's pretty specific to my setup and my needs, but if you can get any use out of it, then enjoy.
>
> Use at your own risk. I offer no warranty or guarantees for this software.

## Download

**Latest version: v1.4** (Oct 3, 2026)

- [LangRunner_v1.4_no-install.zip](https://github.com/codenomics/LangRunner/releases/download/v1.4/LangRunner_v1.4_no-install.zip) - 429 KB
- [LangRunner_v1.4_Setup.exe](https://github.com/codenomics/LangRunner/releases/download/v1.4/LangRunner_v1.4_Setup.exe) - 507 KB

What's new in v1.4:

- The Guide's closing button now says Close instead of Got it

Older versions are on the [Releases page](https://github.com/codenomics/LangRunner/releases).

## Getting started

### Installer (recommended)

1. Download the file ending in `_Setup.exe` above.
2. Double-click it and click Install. It installs just for you - no admin password needed - and adds Start menu and Desktop shortcuts.
3. To remove it later: Windows Settings > Apps, find LangRunner and click Uninstall.

### No install (portable zip)

1. Download the file ending in `_no-install.zip` above.
2. Right-click it > Extract All, and pick a folder. Don't run it from inside the zip.
3. Open the folder and double-click the app's .exe. Nothing is installed; delete the folder to remove it.

Windows says "Windows protected your PC"? Click More info > Run anyway. It shows that for apps without a paid signing certificate.

## More details

```
LANGRUNNER
==========

Edits Star Citizen's language file (global.ini) and keeps your edits, so
you can put them back on every new version of a language pack in a few
clicks. Saves the result straight into the game, with backups.

LangRunner is a fan-made tool. It is not made by or affiliated with Cloud
Imperium Games. Star Citizen is a trademark of Cloud Imperium.


GETTING STARTED
---------------
Pick one. Both give you the same app.

OPTION 1 - INSTALLER (recommended)
  Download the file ending in _Setup.exe, double-click it and click Install.
  It installs just for you (no admin password) and adds Start menu and
  Desktop shortcuts. Needs Windows 10 or 11 (64-bit).
  To remove it later: Windows Settings > Apps > LangRunner > Uninstall.

OPTION 2 - NO INSTALL (zip)
  1. Download the file ending in _no-install.zip. Right-click it -> Extract
  All... and put the LangRunner folder somewhere it can stay (for example
  Documents). Don't run it from inside the zip.
  2. Double-click LangRunner.exe. Nothing is installed; to remove it, delete
  the folder.

EITHER WAY
  Optional: pin it to Start (right-click it in the Start menu or on the
  desktop -> Pin to Start).

"Windows protected your PC"? Click "More info" -> "Run anyway".
Windows shows that for apps downloaded from the internet that aren't
signed with a paid certificate.


USING IT
--------
Home page
- Get newest <pack>  = downloads the latest version of a language pack from
  GitHub and opens it. The text beside it says how recent that version is
  and whether you already have it. StarStrings (by MrKraken) is in the list
  to start; Manage packs... adds other creators' GitHub pages.
- Choose language file... / Open game file / Reopen last file = open a
  global.ini you already have (or drag one onto the window).

Editing
- Search by key or text, click an entry, edit "Current value".
  Edited entries get a pink dot. Enter adds a line break (\n).

Buttons at the top
- Save my changes     = saves a small file with only your edits into
                        Documents\LangRunner, named with the date and time.
- Load my changes...  = your saved changes files: Load one onto the open
                        file, Delete one, Purge old ones, or Browse.
- Save to game        = writes the file into the game's language folder
                        (...\StarCitizen\LIVE\data\Localization\english) and
                        backs up the file that was there first.
- Backups...          = the game-file backups: Restore or Purge them.
- Guide (F1)          = help and keyboard shortcuts, the version number, and
                        Check now to look for a newer LangRunner.

When a new version of your pack comes out:
  Get newest  ->  Load my changes...  ->  Save to game


GOOD TO KNOW
------------
- For the game to use the file, user.cfg in the LIVE folder needs the line
  g_language = english. Save to game offers to add it (your other settings
  in user.cfg are kept), and to create the language folder if it's missing.
- If the game folder is protected by Windows, you'll see a Windows prompt
  asking to allow changes - click Yes.
- LangRunner keeps the 10 newest backups plus the oldest one (the game's file
  from before your first save).
- Settings are kept in %APPDATA%\LangRunner\settings.txt.
  Downloaded packs go to Documents\LangRunner\Packs.
- Updates: when LangRunner starts it checks GitHub for a newer version (it only
  reads the public release page; nothing is sent). If you used the installer,
  Update now downloads and runs the new installer for you. If you use the
  no-install zip, it opens the download page instead. To turn the startup
  check off, open the Guide (F1) and untick "Check for updates at startup".
- If something goes wrong, LangRunner-log.txt next to LangRunner.exe says what.
- To remove LangRunner: delete its folder, plus %APPDATA%\LangRunner and
  Documents\LangRunner if you don't want your settings and saved changes.
```

