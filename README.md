# vim Configuration

## Setup and Installation:
### 1. Keyboard Hack(for Linux):
1. Swap CapsLock and Esc


```
sudo apt-get install dconf-tools
dconf-editor
```


2. Navigate to org >> gnome >> desktop >> input-sources


3. Make xkb-options ['caps:swapescape']


### 2. Guake
```
# Install a Cool Terminal
sudo apt-get install guake

# Guake Error Fix
gconftool-2 --install-schema-file=/usr/share/gconf/schemas/guake.schemas
```

### 3. vim IDE:


https://github.com/ets-labs/python-vimrc

:colo ^d       # To get the available color schemes (so that we can save the setting in .vimrc)


## Commands:
```
Note: It is like Verb + Noun

+----------------------------------------------------------------------------+
| Commands |                          Description                            |
+----------+-----------------------------------------------------------------+
|    dw    | Delete Word                                                     |
+----------+-----------------------------------------------------------------+
|    .     | Execute last command                                            |
+----------+-----------------------------------------------------------------+
|    u     | Undo                                                            |
+----------+-----------------------------------------------------------------+
|    cw    | Change Word (Delete the word and takes me into the insert mode) |
+----------+-----------------------------------------------------------------+
|    v     | Visually Select                                                 |
+----------+-----------------------------------------------------------------+
| shift+v+d| Visually Select one line and cut it for pasting                 |
+----------+-----------------------------------------------------------------+
|    y     | Yank(Copy)                                                      |
+----------+-----------------------------------------------------------------+
|    p     | Paste                                                           |
+----------+-----------------------------------------------------------------+
|    o     | append (open) a new line below the current line.                |
+----------+-----------------------------------------------------------------+
|    O     | append (open) a new line above the current line.                |
+----------+-----------------------------------------------------------------+
|    gg    | Move the cursor to the first line                               |
+----------+-----------------------------------------------------------------+
|    dG    | Delete all when cursor is on first line                         |
+----------+-----------------------------------------------------------------+
|    2j    | Cursor Down 2 lines                                             |  
+----------+-----------------------------------------------------------------+
|    2k    | Cursor Up 2 lines                                               |
+----------+-----------------------------------------------------------------+
|    w     | Forward by a word                                               |
+----------+-----------------------------------------------------------------+
|    b     | Back by a word                                                  |
+----------+-----------------------------------------------------------------+
|    di"   | Delete Inside the quotes (from any place on the line)           |
+----------+-----------------------------------------------------------------+
|    di(   | Delete Inside the Brackets                                      |
+----------+-----------------------------------------------------------------+
|    dip   | Delete paragraph (para contains blank lines around)             |
+----------+-----------------------------------------------------------------+
|    yip   | Copy the whole paragraph from any place inside the paragraph    |
+----------+-----------------------------------------------------------------+
|    cip   | Change inside paragraph (Delete para and go into insert mode)   |
+----------+-----------------------------------------------------------------+
|    viw   | Visualize (Hight-light) the current word                        |
+----------+-----------------------------------------------------------------+
|    cs("  | Change Surrounding ( to "                                       |
+----------+-----------------------------------------------------------------+
|   ysiw"  | Add Surrouding to inner word "                                  |
+----------+-----------------------------------------------------------------+

```

