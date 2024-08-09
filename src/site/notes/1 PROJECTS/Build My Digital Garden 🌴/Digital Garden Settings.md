---
{"dg-publish":true,"permalink":"/1-projects/build-my-digital-garden/digital-garden-settings/","dgHomeLink":"false","dgShowLocalGraph":"false"}
---

Pour mettre en ligne une image, add proprieties:

```
dg-publish: checkbox
```

https://dg-docs.ole.dev/getting-started/03-note-settings/
mais pas en check box en text

```
dg-publish: checkbox
dg-file-tree:
dg-show-local-graph:
dg-home-link:
dg-show-local-graph: true
dg-enable-search: false
```

## 03 Note Settings

### Show **home link**
### Show **local graph** for notes 

When turned on a local graph, like the one in Obsidian, will be shown to the right. It will show both outgoing and incoming links to the current note.

---

### Show a **table of content** for notes

Off by default. When turned on, a list of all headers in your note will be shown to the right.

---

### Show **backlinks** for notes

Off by default. When turned on, your published **notes will display a list of notes linking back to it**. It will only show notes that have been published.  
On desktop and bigger screens it will be placed on the right. On mobile and smaller screens it is put on the bottom of the page.

---

### Show **inline title**

When turned on, the **filename will be shown on the top of the page**. Similar to the "Show inline title" setting introduced in Obsidian v1.0.

---

### Show **filetree sidebar - folder**

a sidebar will be shown to the right, with all your published notes displayed in the folder hierarchy they are placed in in Obsidian. On smaller screens it will disappear, but can be viewed by clicking the "hamburger" menu in the top left corner.

---

### Link preview

---

### Enable search

Off by default. When enabled, users have the option to easily search through all your published notes. The searchbox can be viewed by clicking the search box that appears in the upper right corner, or on the top of the filetree sidebar if this is enabled. It can also be triggerd by pressing CTRL+K on Windows/Linux or CMD+K on MacOS.  
A dialog will pop up. The results can be navigated by using your keyboard using the up and down arrow keys. Pressing enter will take you to the note. Pressing ESC will close the search box.

When search is enabled, you can also construct URLs that shows a search and the result. This is done by specifying a "q" query parameter in the URL.  
E.g. for this site: [https://dg-docs.ole.dev/?q=Commands](https://dg-docs.ole.dev/?q=Commands)

---

### Show Tags

Off by default. When turned on, any tags in your note's frontmatter will show at the top of the page, just under the note title.  
If search is enabled, clicking on a tag will bring up the search box and show all notes with that tag.