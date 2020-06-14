# Follow Link

open a new vim and paste the link in it:

https://raw.githubusercontent.com/ogaida/my-vim-howto/master/follow_link.md

than create a mapping for F3:

```
:map <F3> "zyiW:exe "r !curl -s '".@z."'"<CR>
```

go with the cursor on the link and press F3

If the webservers would response in markdown format, it would be easy to read the content in vim.

https://asciinema.org/a/qgMqBGkubugHd5L03UgXmjffa

<script id="asciicast-qgMqBGkubugHd5L03UgXmjffa" src="https://asciinema.org/a/qgMqBGkubugHd5L03UgXmjffa.js" async></script>
