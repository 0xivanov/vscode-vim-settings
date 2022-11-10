# vscode-vim-settings
```json
"vim.normalModeKeyBindingsNonRecursive": [
  "vim.useSystemClipboard": true,
    {
      "before": ["i"],
      "after": ["k"]
    },
    {
      "before": ["k"],
      "after": ["j"]
    },
    {
      "before": ["j"],
      "after": ["h"]
    }
  ],
  "vim.visualModeKeyBindingsNonRecursive": [
    {
      "before": ["i"],
      "after": ["k"]
    },
    {
      "before": ["k"],
      "after": ["j"]
    },
    {
      "before": ["j"],
      "after": ["h"]
    }
  ],
  "vim.handleKeys": {
    "<C-w>": false
  },
  "vim.insertModeKeyBindings": [
    {
      "before": ["j", "j"],
      "after": ["<Esc>"]
    }
  ],
