# Acid for Neovim

Two flavours: **Acetic** (`#000000`), vibrant, and **Citric** (`#1c1b19`), muted.

Part of [Acid](https://github.com/acid-theme/acid), a very dark colourscheme in two
flavours. The main README lists the other ports.

## Preview

| Acetic | Citric |
| --- | --- |
| ![Acid Acetic](previews/acetic.png) | ![Acid Citric](previews/citric.png) |

## Install

With Neovim's built-in plugin manager:

```lua
vim.pack.add({ { src = "https://github.com/acid-theme/neovim" } })
vim.cmd.colorscheme("acid-acetic")
```

With lazy.nvim:

```lua
{ "acid-theme/neovim", name = "acid", lazy = false, priority = 1000 }
```

Or without a plugin manager, by dropping `colors/acid-acetic.lua` into
`~/.config/nvim/colors/`.

Covers the editor and chrome groups, legacy syntax, treesitter, markup,
diagnostics, LSP semantic tokens, diffs, spelling, `:terminal` and git signs.

## Files

- `colors/acid-acetic.lua`
- `colors/acid-citric.lua`

## Generated

Acid 0.1.0, rendered by acidify from
[`ports/neovim/acid.lua.tera`](https://github.com/acid-theme/acid/blob/main/ports/neovim/acid.lua.tera).
Edits to these files are overwritten on the next release. Report issues on
[acid-theme/acid](https://github.com/acid-theme/acid/issues).

## Licence

MIT.
