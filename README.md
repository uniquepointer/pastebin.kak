# Pastebin.kak
Paste to some pastebins through YOUR TEXT EDITOR

Install and setup 8D
``` plug 'uniquepointer/pastebin.kak' %{
    map global normal <a-y> ': enter-pastebin-mode<ret>' -docstring 'pastebin'
}
```

## Supported sites
* ix.io
* paste.rs
* dpaste.org
* paste.mozilla.org
