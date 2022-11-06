# vim-ultisnippets

A Collection of custom snippets for ultisnips

**snippets list:**

- verilog.snippets
- systemverilog.snippets
- verilog_systemverilog.snippets

## Installation

Assume using `Vundle` to install,

1. add `Plugin 'qian-gu/vim-ultisnippets'` to .vimrc
2. run `vim +PluginInstall`

## Configuration
```
let g:UltiSnipsEnableSnipMate     = 0                             " disable snipmate snippets
let g:UltiSnipsSnippetDirectories = ["UltiSnips", "ultisnippets"] " add third party snippets
```
