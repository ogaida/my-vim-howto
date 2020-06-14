# Follow Link

open a new vim and paste the link in it:

https://raw.githubusercontent.com/ogaida/my-vim-howto/master/follow_link.md

than create a mapping for F3:

```
:map <F3> "zyiW:exe "r !curl -s '".@z."'"<CR>
```

go with the cursor on the link and press F3


