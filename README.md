# Find Open Chrome Tab!!
For those of us with too many Chrome tabs open on macOS :flushed:...this is a simple applescript to search all tab titles and urls across all Chrome browser windows for a match string and if found it sets that as the active tab. :sunglasses:

## To Use:
1. Open in the macOS Script Editor
2. Edit the **match** variable at the top for your match string. For example, if I want to find a stackoverflow tab, I would enter **"stackoverflow"** as the match string.
3. Run and it will set the active browser tab to that tab (if the tab is found). If there are multiple tabs that it finds, it will quickly cylce through each and end with the last one it found open. If that happens, just make the match string more specific
