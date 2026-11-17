---
title: Hikidashi Instruction
topa: "../index.en.html"
---

🌐 Language : 🇯🇵 [日本語](instructions) / 🇺🇸 English

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

Flags are **markers** that can be applied to items. You can attach as many flags as you like to a single item.  
| Flag | Description |
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
- Names can be You can enter up to 12 characters. If you leave the field blank, only the icon will be displayed.
- You can revert to the default name and icon by selecting "Reset to default name/icon."

### Unread Red Dot

If a **red dot** appears to the left of an item's name, it means the item has not yet been marked as "read."

- To mark an item as read, you can use the "Read/Unread" swipe action or the "✓ Read" option in the panel.
- Go to the ☰ menu → "**Unread Mark Settings**" to adjust the following:
- "Show unread red mark" (Enabled by default; if disabled, the red dot will no longer appear).
- "Mark as read when opened" (Disabled by default; if enabled, items will be automatically marked as read when opened).

### Duplicates

If two or more items share the same URL, both will be marked with a "🔁 Duplicate" indicator.

- Differences such as `http` vs. `https`, the presence or absence of `www.`, a trailing `/`, content following a `#`, or tracking parameters (e.g., `utm_`) are ignored; these are treated as the same URL.
- If you delete one of the items (move it to the trash), the duplicate indicator will disappear from the remaining item.

---

<a id="search"></a>

## 7. Searching and Filtering

### Search

Tap the **🔍** icon at the top and enter a keyword. The search covers folder names, item names, and URLs within the **currently open folder and its subfolders** (or everything, if you are at the top-level directory).

- The search is case-insensitive and ignores differences between full-width and half-width characters, as well as between hiragana and katakana.
- You can use **spaces to separate keywords** to filter for items that contain all of the specified terms.
- Results are displayed in a list. Each entry shows its location (the folder it belongs to) in smaller text; tapping the folder name will take you to that folder. - To close, tap the ← icon in the top-left corner or use your device’s "back" action.

### Filtering

Tap "Filter" at the top to select your criteria. The filter applies to the **currently open folder and its subfolders**; the results are displayed as a flat list (folders are not shown).

| Criterion | Description |
|---|---|
| Flag | Items with the selected flag(s). You can toggle between "contains any" and "contains all." You can also select "no flag." |
| Read Status | All / Unread only / Read only |
| Duplicates | Only items that are duplicates |
| Link Status | Broken link / Cannot be verified / Temporary error |

- When multiple criteria (Flag, Read Status, Duplicates, Link Status) are selected, only items that meet **all** of them will be displayed.
- While a filter is active, a banner reading "Filtering: [number] items" appears above the list. You can "Change" or "Clear" the filter from here.
- You can still use swipe gestures and the "⋮" menu as usual while a filter is active.

---

<a id="open"></a>

## 8. Opening Links

### Opening Items

Tap an item to open it.

- For sites with dedicated official apps (such as X, Instagram, or YouTube), the link will open in the official app (if installed).
- If no specific browser has been assigned, the link will open in your device's default browser.

### Assigning a Specific Browser for Individual Items

Open the "⋮" menu for an item and look for "Specify" to the right of the "Open" option. Tapping this will display a list of browsers installed on your device. Once you select one, that specific item will always open in that browser.

- When a browser has been assigned, the word "Specify" will appear in bold and in color. - If the specified browser is no longer installed on your device, the link will open in your default browser.

### Long-press menu

**Long-press** an item to display the following menu:

- **Open with...**: Allows you to choose which app to use (e.g., for music, videos, or maps) via your device's standard app selection screen.
- **Share**: Sends the URL to another app.
- **Copy URL**: Copies the URL to your clipboard.

The "Share" option is also available in the "⋮" menu.

---

<a id="linkcheck"></a>

## 9. Checking for broken links

This feature verifies whether the saved link is still active. The result is displayed on the third line of the item.

| Display | Meaning |
|---|---|
| (Nothing displayed) | The link is valid. |
| ⚠ Broken link | The page cannot be found, or the site no longer exists. |
| Cannot verify (Access restricted) | The site has blocked verification attempts. It may still be accessible via a web browser. |
| Temporary error | Unable to connect, or the site is experiencing a temporary issue. Please try again later. |

### Checking individual items

Tap the "⋮" menu for an item and select "**Check link**."

### Automatic checks when opening a folder

When you open a folder, the app automatically checks the items located **directly within that folder**.

- Items checked within the last 24 hours are excluded.
- A maximum of 30 items are checked at a time.
- Results are automatically reflected in the list.

### Bulk check [Premium]

Go to the ☰ menu and select "**Check for broken links (Bulk)**."

- You can choose the scope: "All" or "Current folder and subfolders."
- Progress is displayed while the check is running. **Even if you close the app, the process will continue in the background.** You can also "cancel" the process.
- Once finished, a summary of the results will be displayed. Selecting "**Show broken links**" will provide a list containing only the broken links.

### Excluded from checks

**X, Instagram, Facebook, Threads, TikTok, and LinkedIn** are excluded from checks because they cannot be verified correctly due to login requirements or access restrictions.

---

<a id="trash"></a>

## 10. Trash

Items moved to the "Trash" are not deleted immediately. You can access them by going to the ☰ menu → "**Trash**."

- Items remain in the Trash for **30 days**, after which they are automatically and permanently deleted (the cleanup process occurs when you open the app).
- You can return items to their original location by selecting "**Restore**."
- You can permanently delete an item immediately by selecting "⋮" → "**Delete permanently**." Once an item is permanently deleted, it cannot be recovered.
- You can permanently delete all items in the Trash at once by selecting "**Empty**" in the top-right corner of the screen.

### Moving folders to the Trash

- When a folder is moved to the Trash, the folder itself along with all its subfolders and items are moved **together**. In the Trash, the folder appears as a single entry.
- Restoring a folder also restores all its contents.
- If you restore an individual item while its original folder is still in the Trash, that folder will also be restored.
- Folders containing **locked items** cannot be moved to the Trash.

---

<a id="importexport"></a>

## 11. Import & Export

### Import

You can import bookmarks from web browsers such as Chrome.

1. On your computer's browser, **export your bookmarks as an HTML file** (in Chrome, for example, select "Export bookmarks" from the "⋮" menu in the Bookmark Manager). 
- Please note that the Android version of Chrome does not have an export feature. Export the data from your computer and transfer it to your smartphone.
2. In the Hikidashi ☰ menu, tap "**Import**" and select the file.

- Imported items will be placed in a folder named "**Import [Date]**," preserving their original folder structure.
- Items with URLs that already exist will also be imported (marked with a "🔁 Duplicate" label).
- Links using protocols other than `http` or `https` will not be imported.
- The maximum file size is 30 MB.
- Titles and thumbnails for imported items will be retrieved sequentially in the background.

### Exporting

Tap "**Export**" in the ☰ menu.

- You can choose the scope: "All," "Current folder and subfolders," or "Select folder." If you are currently filtering your items, you can also choose "Export filtered results only."
- The saved HTML file can be imported into other browsers.
- Files exported from Hikidashi include folder structure, titles, URLs, and dates, as well as **flags, read/unread status, and folder icons**. When you import this file back into Hikidashi, everything—including flags and other attributes—will be restored to its **original location (at the top-level hierarchy)**.
- Thumbnail images and various settings (such as custom flag names or swipe gestures) are not included.

### Switching Devices

- The most reliable method is to **export your data and then import it onto your new device**.
- If your device's backup feature (e.g., Google Backup) is enabled, your data may be restored automatically on the new device.

---

<a id="family"></a>

## 12. Sharing Links with Family

You can share the contents of a folder with family members via email, LINE, or other messaging apps. **"Sending" is a [Premium] feature, while "receiving" is free.** ### Sharing [Premium]

Tap the "⋮" icon for a folder, then select "**Share**."

| Sharing Method | Description |
|---|---|
| Share as text (List of URLs) | Sends a text list containing the [Folder Name] followed by the URLs (one per line). This can be used with any app that supports sending text, such as email, LINE, or SMS. Includes links from subfolders (folder hierarchy is not preserved). Limit: **up to 50 items**. |
| Share as a file (HTML) | Sends a file that preserves the folder hierarchy. Use this option if you have more than 50 items. |

- Only the content—such as the URLs—is shared. Flags, read/unread status, folder icons, and thumbnails are not included.
- If you enable the option "Ask to move this folder to the Trash after sharing," the app will prompt you with "Move to Trash?" once you return to Hikidashi after selecting your destination app. Since Hikidashi cannot verify whether the content was successfully sent, it will not move the folder to the Trash automatically.

### Receiving (Free)

The recipient can import the content using one of the following methods:

**A. Receiving via text**

1. Long-press the received message, select "**Share**," and then choose "**Hikidashi**."
2. On the "Import Links" screen, verify the folder name and destination, then tap "Import."

If "Hikidashi" does not appear in the share menu, copy the text, then go to the ☰ menu and select "**Import from Clipboard**."

**B. Receiving via file**

1. Tap the attached file to open it (or select "Hikidashi" via the "Share" option).
2. When prompted to choose an app, select "**Hikidashi**" (choosing "Just once" is recommended). 3. On the confirmation screen, verify the number of folders and bookmarks, as well as the destination, then click "Import."

- A confirmation screen will always appear; data will not be imported automatically just by opening the app.
- If you check the box for "Do not import if the same URL already exists," items that are already registered will be excluded from the import.
- Files created using the "Send" function will be imported under their original folder names. Files from other browsers will be grouped into a folder labeled "Import [Date]."
- Depending on the app In some cases, when you tap a file, a "Save" option may appear first. If this happens, please save the file, then select it via the "Import" option in the ☰ menu.

---

<a id="theme"></a>

## 13. Appearance Settings

Open the ☰ menu and select "**Background & Text Colors**."

### Free

- **Match OS Settings**: Adapts to your device's system settings (Light/Dark mode).
- **White**: White background, black text.
- **Black**: Black background, white text.

Changes take effect immediately upon selection.

### Custom Colors [Premium]

Tap "Change to custom colors..." to open a separate screen.

- You can set the **background color, text color, and accent color** (used for buttons and selection highlights) by choosing from the provided samples or by entering a **color code** (`#RRGGBB`).
- A **preview** is displayed at the top of the screen. Changes will not be applied to the app until you tap "Use this color scheme."
- If the contrast between the text and background colors is too low to be readable, the "Use this color scheme" button will be disabled.
- You can revert to the default settings by selecting "Reset to match OS settings."

---

<a id="premium"></a>

## 14. Premium Features and Support

Core organizational features are available for **free**. The following features are part of the **Premium** version (a one-time, lifetime purchase).  
| Feature | Free | Premium |
|---|---|---|
| Organize, search, filter, swipe, and trash folders/items | ✓ | ✓ |
| Save from share menu; receive links (via sharing, clipboard, or files) | ✓ | ✓ |
| Import and export | ✓ | ✓ |
| Check broken links individually; automatic checks when opening folders | ✓ | ✓ |
| Background color options: "Match OS," "Light," or "Dark" | ✓ | ✓ |
| Customizable flags | 3 | 8 (5 additional) |
| Set custom colors | – | ✓ |
| Bulk check for broken links (in the background) | – | ✓ |
| Feature to send/share folders | – | ✓ |

### How to Purchase

Open the menu (☰) → select "**Support Development**" → tap "**Treat me to a snack**." Once you complete the payment via the Google Play purchase screen, you can immediately begin using the Premium features.

### Restoring Purchases

If you switch devices or reinstall the app, it will automatically detect your purchase (provided you are using the same Google account) and enable the Premium features. If they do not become available, please tap "**Restore Purchase**" on the "Support Development" screen.

### In Case of a Refund

If a purchase is refunded, the Premium features will become unavailable the next time the app verifies your purchase status via Google Play.

- Items marked with additional flags (flags 4–8) will not have their tags deleted; they will simply be hidden. If you purchase the app again, these tags will reappear.
- "Custom colors" will revert to the "Match OS" setting, though your saved color configurations will be preserved.

### If Purchase Status Cannot Be Verified

If the app is unable to connect to Google Play for an extended period, it will continue to use the last verified status for up to 30 days. If verification cannot be completed during this period, premium features will become unavailable until it is successfully verified. Connecting to the internet and opening the app will trigger a re-verification process.

---

<a id="faq"></a>

## 15. Frequently Asked Questions & Troubleshooting

**Q. "Hikidashi" does not appear in the sharing menu.**
A. Try selecting "More" at the bottom of the list. If it still does not appear, try reinstalling the app or restarting your device.

**Q. Titles or thumbnails are not being retrieved.**
A. Information may not be retrievable from pages that require a login, or from certain social media platforms. Please ensure you are connected to the internet. You can retry the retrieval by selecting "⋮" on an item and choosing "Retrieve information again." You can also manually set a name by selecting "Rename."

**Q. I see an error message like "Cannot verify (access restricted)" or "Temporary error."**
A. This means the website has blocked the verification request, or there was a temporary connection issue. It does not necessarily mean the link is broken; please check if you can open the page in your browser.

**Q. I cannot select "Move to Trash."**
A. The item is locked. You must unlock it first (you can do this via a swipe gesture or by toggling the "🔒 Lock" option in the item panel). If it is a folder, please check to ensure there are no locked items inside.

**Q. Swiping does not seem to work.**
A. Make sure to drag the item row **horizontally**. If you are scrolling vertically, the app will not register it as a swipe. Drag the item far enough to reach the first action slot, and you will see the slot appear in the background.

**Q. I performed an action by mistake.**
A. Immediately after performing a swipe action or moving an item to the Trash, an "Undo" option will appear at the bottom of the screen. Items moved to the trash can be restored for up to 30 days.

**Q. What happens to my data if I delete the app?**
A. Data stored on your device will be deleted. If Google backup is enabled, your data may be restored when you reinstall the app using the same Google account. We recommend exporting your important data to a file.

**Q. I see a "Premium feature" message when I tap "Send."**
A. The "Send" function is a premium feature. You can purchase it via the "Support Development" section.

**Q. I made a purchase, but premium features are not working.**
A. Please ensure you are connected to the internet and try reopening the app. If it still does not work, tap "Restore Purchases" within the "Support Development" section. Also, please verify that the Google account used for the purchase matches the account currently logged into Google Play on your device.

---

<a id="privacy"></a>

## 16. Data and Privacy

- **Saved links are stored locally on your device.** They are not sent to the developer's servers. No account registration is required.
- The app connects to the internet only to **retrieve titles and thumbnails** or to **check for broken links**. All network communication occurs directly between your device and the destination website.
- The clipboard is accessed only when you select the "Import from clipboard" option.

For more details, please refer to our [Privacy Policy](privacy-policy).

---

<a id="contact"></a>

## 17. Contact Us

Please send any feedback, feature requests, or bug reports via the [official SoulfulSoft website](https://soulfulsoft.github.io/).
When contacting us, it would be very helpful if you could provide your device model, Android version, and a description of the issue you are experiencing.

