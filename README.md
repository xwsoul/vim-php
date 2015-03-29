# phplint
a vim plugin auto check php errors when saving.

### Setup

#### Using Vundle
```vim
Plugin 'xwsoul/phplint'
```

### Options

1. command setting
```vim
let g:phplint_command = '/pathto/php' "default php
```

2. highlight error setting
```vim
let g:phplint_highlight_color = 'Any you want' "default DarkMagenta
```

###PHP Settings for phplint

1. no starting errors
2. display\_error = On
3. error\_reporting = E\_ALL (or other you like)

### Snapshots

![Snapshot for phplint][phplint]



[phplint]: http://farm7.static.flickr.com/6008/5979704329_a1899d79e1.jpg "PHPLint Snapshot"
