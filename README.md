<p align="center">
  <img src="docs/icon-128.png" width="96" height="96" alt="Folder Stickers icon">
</p>

<h1 align="center">Folder Stickers</h1>

<p align="center">
  <b>Sticky notes that live inside your folders.</b><br>
  Free for Mac and Windows.
</p>

<p align="center">
  <a href="https://github.com/Himanshudaga13/folder-stickers/releases/latest"><b>⬇ Download the latest version</b></a>
</p>

<p align="center">
  <img src="docs/screenshot-mac.png" alt="Folder Stickers notes inside a Finder folder" width="820">
</p>

## What it does

Open any folder, add a sticker, and write on it. Drag it anywhere in the window.
Close the folder and the sticker goes with it. Open the folder again and the sticker is back,
**in the same spot, with the same text**.

Use it to leave yourself reminders exactly where you need them: which file is the final one,
what is still pending, who sent what.

## Features

- **Notes that stay with the folder.** Each note remembers its folder and its position.
- **Notes on files.** Attach a note to one file. It shows whenever that file is selected.
- **Reminders.** Set a date and time on any note. You get a notification even if the folder is closed,
  and clicking it opens the folder. Reminders can repeat every day, weekday, week, month or year.
- **Search all notes.** Find any note in any folder by typing a word, then jump straight to it.
- **Desktop notes.** Notes that sit on your screen, outside any folder, like paper notes on a monitor.
- **Bin.** Deleted notes stay in the bin for 30 days. Undo a delete with one click.
- **Templates.** Ready-made starting points such as a checklist or client follow-up. Make your own.
- **Export.** Save any note as a text file or a PDF.
- **Backup.** Save all notes to one file, and restore them on a new computer.
- **Text size and dark notes.** Larger text, and darker colours that follow your computer's dark mode.
- **Formatting:** bold, italic, underline, strikethrough and tick-box checklists.
- **Links and pictures.** Web addresses become links (Ctrl+click or Cmd+click to open).
  Paste a screenshot straight into a note.
- **Colours with meaning.** Seven colours, each with a label you choose, for example red = Urgent,
  green = Done.
- **Collapse to a tab.** Shrink a note to a slim bar so it doesn't cover your files.
- **Follows the window.** Move or resize the folder window and the notes move with it.
- **Your shortcuts, your way.** Change every keyboard shortcut and the right-click menu text.
- **Updates itself** on Windows. On a Mac you're told when a new version is out.
- **Private.** Notes are saved on your own computer, inside the folder. Nothing is uploaded.

## Download and install

Go to **[Releases](https://github.com/Himanshudaga13/folder-stickers/releases/latest)** and pick the file for your computer:

| Your computer | Download |
|---|---|
| Mac with Apple chip (M1 or later) | `Folder-Stickers-x.y.z-arm64.dmg` |
| Mac with Intel chip | `Folder-Stickers-x.y.z-x64.dmg` |
| Windows 10 or 11 | `Folder-Stickers-Setup-x.y.z.exe` |

Not sure which Mac you have? Click the Apple menu > **About This Mac**. "Chip: Apple M…" means Apple chip.

### Mac

1. Open the `.dmg` and drag **Folder Stickers** into **Applications**.
2. Open it from Applications. macOS will say it can't check the app, because it isn't from the App Store.
   Click **Done**, then go to **System Settings > Privacy & Security**, scroll down and click **Open Anyway**.
3. When asked, click **Allow** so Folder Stickers can **control Finder**. This is only used to see
   which folder each Finder window shows.

If macOS says the app "is damaged", open **Terminal** and run this once, then open the app again:

```bash
xattr -cr "/Applications/Folder Stickers.app"
```

### Windows

1. Run `Folder-Stickers-Setup-x.y.z.exe`.
2. If a blue "Windows protected your PC" box appears, click **More info** > **Run anyway**.
   (This shows for any new app that isn't from a big publisher.)
3. Accept the licence and finish the setup. Folder Stickers starts in the system tray.

## How to add a sticker

| | Mac (Finder) | Windows (File Explorer) |
|---|---|---|
| **Keyboard** | Press **⌘⇧S** in any Finder window | Press **Ctrl+Alt+N** in any Explorer window |
| **Mouse** | Click the **Add Sticker** button in the Finder toolbar | Right-click empty space > **Add sticker here** |
| **Menu** | Menu bar icon > Add sticker | Tray icon > Add sticker |

**Note on a file:** select the file, then press **⌃⌥N** (Mac) or **Ctrl+Alt+F** (Windows).
On Windows you can also right-click the file > **Add note to this file**.

**Add the Finder toolbar button (Mac, one time):** click the Folder Stickers icon in the menu bar >
**Show Finder toolbar button…**, then hold **⌘ Command** and drag **Add Sticker** onto the top bar
of any Finder window.

**Windows 11:** the right-click entry is under **Show more options** (or hold Shift while right-clicking).

## Using a sticker

- **Move:** drag the coloured top bar. **Resize:** drag an edge or corner.
- **Format:** use the buttons in the top bar (they appear when you point at the note), the shortcuts
  below, or right-click inside the note.
- **Checklist:** click ☑ in the top bar. Click a ☐ to tick it. Press Enter for the next item,
  Enter on an empty item to stop.
- **Reminder:** click the 🔔 bell. Pick *In 1 hour*, *Tomorrow 9 am*, *Monday 9 am* or any date and time.
  When it's due the note turns red. Click the bell > **Mark done**.
- **Collapse:** click ⌃ in the top bar, or double-click the bar. Click again to open it.
- **Links:** type or paste a web address. Hold **Ctrl** (Windows) or **Cmd** (Mac) and click to open it.
- **Pictures:** copy a screenshot and paste it into the note, or drag an image file onto it.
- **Colour and transparency:** click ◐ in the top bar.
- **Repeat a reminder:** in the reminder panel, pick *Every day*, *Every weekday*, *Every week*, *Every month* or *Every year*.
- **Delete:** click ✕. If the note has text, you're asked to confirm. Click the notification that follows
  to undo, or find the note later in the **Bin**.
- **Template:** right-click inside a note > **Insert template**.
- **Export:** right-click inside a note > **Export…**, then choose a text file or PDF.
- **All your reminders:** tray / menu bar icon > **Reminders**.

## Search, desktop notes and the bin

Click the Folder Stickers icon (menu bar on Mac, near the clock on Windows) > **Search all notes…**,
or press **⌃⌥F** (Mac) / **Ctrl+Alt+L** (Windows) while a folder is in front.

| Tab | What it shows |
|---|---|
| All notes | Every note, grouped by folder. Click one to open its folder with the note showing. |
| Reminders | Notes with a reminder, the soonest first. |
| Desktop | Your desktop notes. |
| Bin | Deleted notes from the last 30 days. Click **Restore** to put one back. |

**Desktop notes:** icon > **New note on the desktop** (or **⌃⌥D** / **Ctrl+Alt+D**). They stay on screen
whatever is open. Right-click one > **Keep on top of other windows** to float it above everything.

**Backup:** icon > **Shortcuts & settings…** > **Backup** > **Back up…** saves every note to one file.
On a new computer, install Folder Stickers and click **Restore…**. Notes go back into the same folders.
If a folder isn't on the new computer, its notes are put on the desktop with the folder name at the top.

## Keyboard shortcuts

| Action | Mac | Windows |
|---|---|---|
| Add a sticker to the current folder | ⌘⇧S | Ctrl+Alt+N |
| Add a note to the selected file | ⌃⌥N | Ctrl+Alt+F |
| Show / hide all stickers | ⌘⌥S | Ctrl+Alt+S |
| Search all notes | ⌃⌥F | Ctrl+Alt+L |
| New note on the desktop | ⌃⌥D | Ctrl+Alt+D |
| New sticker next to this one | ⌘N | Ctrl+N |
| Bold / Italic / Underline | ⌘B / ⌘I / ⌘U | Ctrl+B / Ctrl+I / Ctrl+U |
| Strikethrough | ⌘⇧X | Ctrl+Shift+X |
| Checklist item on / off | ⌘⇧C | Ctrl+Shift+C |
| Next colour | ⌘⇧K | Ctrl+Shift+K |
| Set a reminder | ⌘⇧R | Ctrl+Shift+R |
| Collapse / expand | ⌘⇧M | Ctrl+Shift+M |
| Delete this sticker | ⌘⇧⌫ | Ctrl+Shift+Backspace |

## Make your own shortcuts

Click the Folder Stickers icon in the menu bar / tray > **Shortcuts & settings…**
(or right-click inside any sticker).

<p align="center">
  <img src="docs/screenshot-settings.png" alt="Shortcuts and settings window" width="440">
</p>

- Click a shortcut and press the keys you want. It saves straight away.
- **↺** puts back the default. **✕** removes the shortcut.
- Turn the right-click entry on or off, and change what it says.
- Choose whether the add-sticker shortcuts work only in folder windows (default) or everywhere.
- Give each colour a meaning, and choose whether it shows on the notes.
- Pick the colour for new stickers, and whether the app starts when you log in.
- Choose the text size and dark notes, edit your templates, and back up or restore all notes.
- Check for updates.

## Where are my notes saved?

In a hidden file called `.stickers.json` inside each folder. So if you copy, zip, back up or sync the
folder (iCloud, OneDrive, Google Drive, Dropbox), the notes go with it. When you delete the last
sticker in a folder, the file is removed. For read-only folders, notes are kept in the app's own
data folder instead.

## Questions

**Does it slow my computer down?** No. It checks the folder windows a few times a second, which
uses very little power.

**Can I put stickers on the Desktop, Recents or This PC?** Not inside those windows, because they
aren't real folders. Use a **desktop note** instead. Stickers work in any normal folder, including
drives and synced folders.

**The "Add Sticker" item doesn't show in the Mac right-click menu.** Newer versions of macOS
hide it. Use the toolbar button or ⌘⇧S instead.

**How do I uninstall?**
- **Mac:** menu bar icon > Shortcuts & settings… > switch off the right-click entry and the
  toolbar button > Quit. Then drag the app from Applications to the Bin.
- **Windows:** Settings > Apps > Folder Stickers > Uninstall.

Your `.stickers.json` files stay in your folders until you delete them.

## Licence

Folder Stickers is **free to use**, at home and at work. It is **not open source**: copying,
modifying, redistributing, reverse engineering or selling it is not allowed.
See the full [Folder Stickers Freeware Licence](LICENSE.txt).

Copyright (c) 2026 Himanshu Daga. All rights reserved.
