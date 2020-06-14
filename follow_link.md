# Follow Link in vim is easy

open a new vim and paste the link in it:

https://raw.githubusercontent.com/ogaida/my-vim-howto/master/follow_link.md

than create a mapping for F3:

```
:map <F3> "zyiW:exe "r !curl -s '".@z."'"<CR>
```

go with the cursor on the link and press F3, look what you see...

## Conclusion

If the webservers would response in markdown format, it would be easy to read the content in vim.

[![asciicast](https://asciinema.org/a/qgMqBGkubugHd5L03UgXmjffa.svg)](https://asciinema.org/a/qgMqBGkubugHd5L03UgXmjffa)
