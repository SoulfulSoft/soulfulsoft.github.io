---
title: Hikidashi Instruction
topa: "../index.en.html"
---

🌐 Language : 🇯🇵 [日本語](instructions.md) / 🇺🇸 English

{% capture my_content %}{% include link_icon.md %}{% endcapture %}{{ my_content | markdownify }}

<br />

# How to Use Hikidashi

Target Version: 1.0.0 / Last Updated: November XX, 2026

Hikidashi is an app designed to help you organize your scattered links into folders.
No account registration is required. All saved links are stored locally on your device.

Features marked as **[Premium]** are available via a one-time paid purchase. All other features are free to use. For more details, please see "[Premium Features and Support](#premium)."

## Table of Contents

1. [Getting Started in 3 Steps](#quickstart)
2. [Understanding the Interface](#screen)
3. [Saving Links](#save)
4. [Organizing with Folders](#organize)
5. [Sorting via Swipe](#swipe)
6. [Flags, Unread Items, and Duplicates](#flags)
7. [Searching and Filtering](#search)
8. [Opening Links](#open)
9. [Checking for Broken Links](#linkcheck)
10. [Trash](#trash)
11. [Importing and Exporting](#importexport)
12. [Sharing Links with Family](#family)
13. [Appearance Settings](#theme)
14. [Premium Features and Support](#premium)
15. [FAQ and Troubleshooting](#faq)
16. [Data and Privacy](#privacy)
17. [Contact Us](#contact)

---

<a id="quickstart"></a>

## 1. Getting Started in 3 Steps

### ① Create a Folder

Tap the **+** icon in the bottom-right corner and select "**Create Folder**." Enter a name and tap "Create" to add a new folder (🗄️) to the top level. <!-- Screenshot: 01-create-folder.png -->

### ② Saving Links

Open the page you wish to save in your browser (or another app), tap "**Share**," and select "**Hikidashi**" from the list. Choose a destination folder and tap "**Add here**" to save it.
The title and thumbnail image will be retrieved automatically.

<!-- Screenshot: 02-share-add.png -->

### ③ Organizing

You can **swipe** saved items left or right to flag them, mark them as read, or move them to the trash. For more details, see "[Sorting with Swipes](#swipe)."

---

<a id="screen"></a>

## 2. Understanding the Interface

### Home Screen and Folders

- The top level displays folders (indicated by the 🗄️ icon by default). You can place subfolders (indicated by the 📁 icon by default) or links inside these folders.
- Links (items) can only be placed **inside folders**. Only folders can be placed at the top level.
- The top bar contains the following buttons:

| Button | Function |
|---|---|
| ← | Go up one level (when inside a folder) |
| 🔍 | Search |
| Filter | Filter items |
| ↕ | Sort |
| ☰ | Menu |

- Use the **＋** button in the bottom-right corner to "Create folder" or "Add URL" (the "Add URL" option is only available when inside a folder).

<!-- Screenshot: 03-home.png -->

### Understanding Items (Links)

Each item is always displayed across three lines. 1. **Name** (a small red dot appears to the left for unread items)
2. **URL**
3. **Indicators**: Duplicates (🔁), flag icons, and link status (e.g., ⚠ for broken links)

A thumbnail image is displayed on the left. If an image cannot be retrieved, a 🔗 icon is shown instead.

<!-- Screenshot: 04-item-row.png -->

### Legend at the Bottom of the Screen

A legend explaining the flags is displayed at the bottom of the screen. The first row covers **Locked, Duplicate, and Pending Deletion** items, while the subsequent rows contain customizable flags.
If you find it distracting, you can toggle its visibility via the "Show Legend" option in the ☰ menu.

---

<a id="save"></a>

## 3. Saving Links

### Saving via the Share Menu (Recommended)

1. Tap "Share" in your browser, social media app, or other applications.
2. Select "**Hikidashi**" from the list (if you don't see it, tap "More" or "Show More").
3. Enter a title (optional) and select a destination folder.
4. Tap "**Add Here**."

- The destination folder defaults to the one you used last. If you are saving multiple items to the same folder, simply open that folder and tap "Add Here."
- In the folder selection screen, you can navigate to a higher level by tapping "↑ Go to parent folder," or create a new folder on the spot by tapping "+ New folder here."
- If the URL is already registered, the app will notify you (e.g., "This URL is already registered in [Folder Name]"), though you can still proceed to save it.

### Saving by Entering a URL

Within a folder, tap **+** and select "**Add URL**." Enter the URL (you can omit the `https://` prefix). You may leave the title field blank if you wish. ### Saving Multiple Links at Once

When you share text containing two or more links, an "**Import Links**" screen will appear. Specify a folder name and a destination, then tap "Import."

- If the first line of the text follows a format like `[Travel Options]`, that text will be suggested as the folder name.
- By checking "Do not import if the URL already exists," you can ensure that only new, unique links are added.

### About Titles and Thumbnails

After saving, the app will retrieve the page title and a thumbnail image in the background.

- Some sites may not allow this (e.g., pages requiring a login, certain social media platforms, etc.).
- If you wish to re-fetch this information, tap the "⋮" icon next to an item and select "**Refresh Info**."
- Any custom name you have assigned to an item will **not** be overwritten by the retrieved title.

---

<a id="organize"></a>

## 4. Organizing with Folders

You can perform the following actions by tapping the "⋮" icon next to a folder or item:

| Action | Description |
|---|---|
| Rename | Change the name of a folder or item. If you leave the item name blank, it will revert to displaying the site's domain name. |
| Change Icon (Folders) | Choose from 40 different emoji icons for each folder. Selecting "Reset to Default" will restore the original icon (🗄️ for the top-level directory, and 📁 for subfolders). |
| Move | Move an item or folder to a different location. In the selection screen, you can use options like "↑ Go up a level" or "+ New folder here." |
| Copy | Copy an item or folder to another location. A default name (e.g., "Copy of [Name]") will be suggested, which you can then edit. When copying a folder, all its contents are copied as well. |
| Move to Trash | Moves the item or folder to the Trash (see "[Trash](#trash)"). |

### Sorting

You can choose how items are sorted by using the ↕ button at the top. This applies to both folders and items.

- By date added (newest first) / By date added (oldest first)
- By name (ascending) / By name (descending) (alphabetical order)
- **Custom** (reorder using ▲▼)

Your chosen sort order will be saved.

### Custom (Manual Sorting)

When "Custom" is selected, small **▲ ▼** icons appear to the right of each row. Tap them to move an item up or down one position at a time. You can also use the "Move to top" / "Move to bottom" options found under the "⋮" menu to move items instantly.

- You can mix folders and items together in any order.
- The custom sort order is saved **per folder (page)**. Switching to a different sort method will not erase your custom arrangement.
- Newly added items (via saving, creating a folder, copying, moving, or importing) will appear at the **very top** of the page.
- The ▲▼ icons will not appear while filtering or searching.

---

<a id="swipe"></a>

## 5. Organizing via Swipe

You can quickly organize items by **swiping** them left or right.

### Basic Usage

1. Drag an item to the left or right.
2. Action **panels** will appear in sequence in the background.
3. Release your finger when the desired action panel is highlighted; the action will then be executed.
4. A message with an "Undo" option will appear at the bottom of the screen.

If you release your finger before reaching an action, or if you don't drag the item far enough, nothing will happen.

<!-- Screenshot: 05-swipe-stages.png -->

### Actions Change Based on Drag Distance

You can assign up to **three different actions** for both the left and right swipe directions. The action performed changes based on how far you swipe: a short swipe triggers the first action, while a longer swipe triggers the second.

The default settings are as follows:

- Swipe right: 🚩 Mark for deletion
- Swipe left: First action is 📖 Read later; second action is ✓ Read/Unread

### Accessing the Panel (All Flags)

If you swipe even further—beyond the threshold for the second action—an option labeled "**⋯ All**" will appear. Releasing your finger here transforms the row into a panel that remains in place.

- The panel displays **all available flags**, as well as options for "✓ Read/Unread" and "🗑 Trash" (you can scroll horizontally to view them).
- Tapping an option toggles that flag on or off. Enabled (on) options will be highlighted with color.
- **The panel stays open**, allowing you to apply multiple flags in succession.
- To close the panel, tap "**✕ Close**" or use your device’s "back" gesture/button.

<!-- Screenshot: 06-swipe-panel.png -->

### Customizing Swipe Settings

Go to the ☰ Menu and select "**Swipe Settings**." For both right and left swipes, you can assign specific actions to the first, second, and third swipe levels from the following options:

- Toggle individual flags on/off
- Toggle Read/Unread status
- Move to Trash (does not apply to locked items)
- None

---

<a id="flags"></a>

## 6. Flags, Unread Status, and Duplicates

### Flags

Flags are **markers** that can be applied to items. You can attach as many flags as you like to a single item. | Flag | Description |
|---|---|
| 🔒 Lock | **Prevents the item from being moved to the Trash** (a safeguard against accidental deletion) |
| 🚩 Pending Deletion | A marker for items to be reviewed later to decide whether they should be deleted |
| ⭐ Important | A flexible flag for your own use |
| 📖 Read Later | A flexible flag for your own use |
| 🔖 Of Interest | A flexible flag for your own use |
| 💡 🎯 📌 💬 🔍 | [Premium] Add 5 additional flags |

- For **locked items**, the "Move to Trash" option in the "⋮" menu becomes disabled, and the "Move to Trash" swipe action will not work. Folders containing locked items also cannot be moved to the Trash.
- Applied flags appear as icons on the third line of each item.

### Changing Flag Names and Icons

Open the ☰ menu and select "**Flag Settings**."

- You can change the **name and icon** for any flag. Note that for the "Lock" and "Pending Deletion" flags, changing the name or icon **does not alter their underlying function**.
- Names can be...
