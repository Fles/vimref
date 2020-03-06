# useful commands

### Table of Contents
- **[Copy & Paste](#Copy-&-Paste)**<br>
- **[Copy & Paste with Registers](#with-Registers)**<br>
- **[Deleting](#Deleting)**<br>
- **[Indenting](#Indenting)**<br>
- **[Navigation](#Navigation)**<br>
- **[Insert Text](#Insert-Text)**<br>
- **[Search & Replace](#Search-&-Replace)**<br>
- **[Split Window Editing](#Split-Window-Editing)**<br>
- **[Undo](#Undo)**<br>
- **[View Directory & File Explorer](#View-Directory-&-File-Explorer)**<br>

---

## Copy & Paste

Press v. (To enter visual mode so you can highlight stuff)

Use the arrow keys (or h,j,k,l,w,b,$) to highlight

Press y to yank, p to paste. (shift-p to open up a line above and paste)

Copy a word                         yw
Copy a line                         yy
Copy from cursor to end of line     y$


### with Registers

Press v. (To enter visual mode so you can highlight stuff)

Use the arrow keys (or h,j,k,l,w,b,$) to highlight

Type "ay to yank into register a.
Type "ap to paste from register a.

---

## Deleting

Press v. (To enter visual mode so you can highlight stuff)

Use the arrow keys (or h,j,k,l,w,b,$) keys to higlight and press d

Delete character                x
Delete word                     dw
Delete word and insert text     cw
Delete line                     dd
Delete to end of line           d$

---

## Indenting

Press v and then arrow keys (or h,j,k,l,w,$) to highlight lines of text.

Type > or < to indent right or left.

(to indent more, type 2> or 3>)

(to change your indenting/tabbing to use spaces and not tabs, type :set et)
(to set auto-indenting, type :set ai)
(to set the tab-size, type :set ts=2 (or whatever number you want)
(also, for tabbing-size, set shiftwidth (>) by typing :set sw=2)

---

## Navigation

Go up                         k
Go down                       j
Go left                       h
Go right                      l
Go right a word               w
Go left a word                b
Go to beginning of file       gg
Go to end of file             G
Go 22 lines down              22j
Go to end of line             $
Go to beginning of 
non-whitespace part of line   ^

Go right 5 words              5w

---

## Insert Text

Insert at cursor                      i
Insert after cursor                   a     (useful when at the end of a line)
Open a line below cursor and insert   o
Open a line above cursor and insert   shift-o

---

## Search & Replace

Search  /  (after the slash put whatever you want to find 
            and press the enter key)

Find next       n
Find previous   N

Turn off highlighting (after a search)  :noh

Find next instance of a word that your
cursor is over    *

Search and replace from current 
line to end of file   :,$s/search/replace/gc (the gc means global and confirm)

---

## Split Window Editing

Type :sp followed by the filename.

Go to window above  ctrl-w-k
Go to window below  ctrl-w-j

Maximize window size  ctrl-w  _ 
(the underscore is NOT  pressed at the same time as the ctrl-w)

Make all windows equal size  ctrl-w =
(the equals sign is NOT pressed at the same time as the ctrl-w)

---

## Undo

Undo                              u
Redo an undo                      ctrl-r

---

## View Directory & File Explorer

Type :S  (the S is uppercase)

This will split the window and open up a file explorer.  
Use the <enter> key to select directories or to open files.