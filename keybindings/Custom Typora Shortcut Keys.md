## Configure

1. Open `Menu`  →  `Preference` in Typora, then click "Open Advanced Settings".

2. Open and edit `conf.user.json` 
3. Set or add JSON object which represents a key binding.

4. Restart Typora, and the new key binding will be applied.

```
"keyBinding": {
    "Code": "Ctrl+K",
    "Task List": "Ctrl+T",
    "Insert Table": "Ctrl+Shift+T",
    "Reopen Closed File": "",
    "HyperLink": "Ctrl+L",
    "Select Line/Sentence": "",
    "Quote": "Ctrl+Q",
    "Ordered List": "Ctrl+[",
    "Indent": "",
    "Unordered List": "Ctrl+]",
    "Outdent": "",
    "Toggle Sidebar": "Ctrl+Shift+;",
    "Open Folder...": "Ctrl+Shift+O",
    "Preference": "Ctrl+P",
    "Open Quickly...": "",
    "Source Code Mode": "Ctrl+Shift+'",
    "Strike": "Ctrl+E"
  }
```

## Custom Shortcut Keys

### 1.File

```
Ctrl+N -> New file
Ctrl+Shift+N -> New Window

Ctrl+O -> Open...
Ctrl+Shift+O -> Open Folder...

Ctrl+S -> Save
Ctrl+P -> Preference
```

### 2.Edit

```
Ctrl+Z -> Undo
Ctrl+C/V/X -> Copy/Paste/Cut
Ctrl+Shift+C -> Copy as Markdown

Ctrl+A -> Select All
Ctrl+D -> Select Word

Ctrl+F -> Find
Ctrl+H -> Replace

Ctrl+\ -> Clear Format
```

### 3.Paragraph

```
Ctrl+1/2/3/4/5/6 -> Heading1/2/3/4/5/6 [#/##/###/####/#####/######]
Ctrl+0 -> Paragraph

Ctrl+K -> Code                [` `]
Ctrl+Shift+K -> Code Fences	  [```]

Ctrl+Q -> Quote           [>     ]
Ctrl+[ -> Ordered List    [1.    ]			（Use Tab/Shift+Tab to Control Indent/Outdent）
Ctrl+] -> Unordered List  [-     ]
Ctrl+T -> Task List       [- [ ] ]

Ctrl+Shift+T -> Insert Table    [ |---|---| ]
Ctrl+Shift+I -> Insert Image    [  ![image-name](image-link)  ]
```

### 4.Fromat

```
Ctrl+B -> Strong (Blod)              [    **content**   ]
Ctrl+I -> Emphasis (Italic)          [     *content*    ]
Ctrl+U -> Underline (Underline)      [  <u>content</u>  ]
Ctrl+L -> Hyperlink (Link)           [   [title](link)  ]
Ctrl+E -> Strike (Strike)            [    ~~content~~   ]
```

### 5.View

```
Ctrl+Shift+; -> Toggle Siderbar
Ctrl+Shift+' -> Source Code Mode
```
