# spade.nvim

## Install

Install the plugin with your preferred package manager.
Here's how it would look like if you're using [lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
{
    "ethanuppal/spade.nvim",
    dependencies = {
        "nvim-treesitter/nvim-treesitter"
    },
    config = function()
        require("spade").setup()
    end
}
```

Then, run `:TSInstall spade` once.
