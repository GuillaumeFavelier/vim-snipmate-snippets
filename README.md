# Snipmate-snippets

This plugins is inspired by [vim-snippets](https://github.com/honza/vim-snippets.git).
It is a repository for the [snipmate](https://github.com/garbas/vim-snipmate.git) plugins, but differ
from the previous one by adding substitution in snippets.

# Usage

You need to have this line on your _.vimrc_ file :

```vim
let g:snipMate.snippet_version=1
```

# Note

At the time this readme is written, the garbas snipmate plugins have a bug when using substitution.
You can use [this fork](https://github.com/CharlesGueunet/vim-snipmate.git) to avoid it.
