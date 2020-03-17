# jj as Esc


## Vim

```shell
# vimrc
inoremap jj <esc>
# Quit insert mode
# inoremap jj <Esc>
# inoremap jk <Esc>
# inoremap kk <Esc>
```


## VSCode

```json
// settings.json
{
  "vim.insertModeKeyBindings": [
    {
      "before": ["j", "j"],
      "after": ["<Esc>"]
    }
  ]
}
```

## PyCharm-IdeaVim

```shell
# inoremap jj <esc>
# Quit insert modve
inoremap jj <Esc>
inoremap jk <Esc>
inoremap kk <Esc>
```


## SurfingKeys-浏览器插件

