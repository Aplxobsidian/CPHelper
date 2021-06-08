# Code Completion Helper

# Introduction

An effective code completion helper using N-gram language model to dynamically learn directoriers. Can assist to complete code lines and edit code blocks. With settings to customize working projects directory and preset directories.

# Usage Main Flow

The main window consist of clear code line box, suggestion list box and code editing box.

Side buttons correspond to these boxes.

### In completion line box:

1. Type in the pre-completion code 
2. Press Keys to call out functions
    - F1 - Search for help (Internet)
    - F2 - Search for token completion
    - ALT - Search for completion suggestion
3. After code completed, press ENTER to add to the code editing box.
4. Side buttons:
    - Add - Add current code line to edit box
    - Clear - Clear current code line (Key Ctrl-A Delete is faster)

### In suggestion dropdown box:

- ARROW KEYS - to cycle selection of completion
- ENTER - to confirm completion, add to code line box

### In code editing box:

- Normal editing is allowed.
- Use side buttons to configure code box.
    - Open - Open java code document to code box.
    - Save - Save current code box content to new file.
    - Copy - Copy code box content to system clipboard.
    - Delete - Clear code box content, making room for new edit.

# Settings

Settings page can be accessed by the side button "Settings" (Gear).

In settings page, there are preset directories and main custom editable directories list.

- Presets offered useful java code fragments, select the desired preset directory, and click "Add" to add them to the custom list.
- In the custom list, "Add dir" will let you choose your own project/working directory. Select a path and click "Delete" will remove that path.
- Finally click "Set" to inform the tool of the new learning path!

The final combined selection is the custom directories list.