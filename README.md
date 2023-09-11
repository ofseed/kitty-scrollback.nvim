<img src="https://github.com/mikesmithgh/kitty-scrollback.nvim/assets/10135646/a7357844-e0e4-4053-8c77-6d129528504f" alt="kitty-scrollback" style="width: 20%" align="right" />

# 😽 kitty-scrollback.nvim
Open your Kitty scrollback buffer with Neovim. Ameowzing!

[![neovim: v0.10+](https://img.shields.io/static/v1?style=flat-square&label=neovim&message=v0.10%2b&logo=neovim&labelColor=282828&logoColor=8faa80&color=414b32)](https://neovim.io/)
[![kitty v0.29+](https://img.shields.io/badge/v0.29%2B-352217?style=flat-square&logo=data%3Aimage%2Fjpeg%3Bbase64%2C%2F9j%2F4AAQSkZJRgABAQAAAQABAAD%2F4gHYSUNDX1BST0ZJTEUAAQEAAAHIAAAAAAQwAABtbnRyUkdCIFhZWiAH4AABAAEAAAAAAABhY3NwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAA9tYAAQAAAADTLQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAlkZXNjAAAA8AAAACRyWFlaAAABFAAAABRnWFlaAAABKAAAABRiWFlaAAABPAAAABR3dHB0AAABUAAAABRyVFJDAAABZAAAAChnVFJDAAABZAAAAChiVFJDAAABZAAAAChjcHJ0AAABjAAAADxtbHVjAAAAAAAAAAEAAAAMZW5VUwAAAAgAAAAcAHMAUgBHAEJYWVogAAAAAAAAb6IAADj1AAADkFhZWiAAAAAAAABimQAAt4UAABjaWFlaIAAAAAAAACSgAAAPhAAAts9YWVogAAAAAAAA9tYAAQAAAADTLXBhcmEAAAAAAAQAAAACZmYAAPKnAAANWQAAE9AAAApbAAAAAAAAAABtbHVjAAAAAAAAAAEAAAAMZW5VUwAAACAAAAAcAEcAbwBvAGcAbABlACAASQBuAGMALgAgADIAMAAxADb%2F2wBDACodICUgGiolIiUvLSoyP2lEPzo6P4FcYUxpmYagnpaGk5GovfLNqLPltZGT0v%2FV5fr%2F%2F%2F%2F%2Fo8v%2F%2F%2F%2F%2F%2F%2FL%2F%2F%2F%2F%2F2wBDAS0vLz83P3xERHz%2FrpOu%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwAARCAEAAQADASIAAhEBAxEB%2F8QAGgABAAMBAQEAAAAAAAAAAAAAAAECAwQFBv%2FEAC8QAQACAQIEAgkFAQEAAAAAAAABAgMEERIhMVFBYQUTFCIyUnGRoUJTgZLB4SP%2FxAAXAQEBAQEAAAAAAAAAAAAAAAAAAQID%2F8QAGxEBAQEBAQEBAQAAAAAAAAAAAAERAhIhMUH%2F2gAMAwEAAhEDEQA%2FAPHAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAHXix1ikTtG8rzWs9ax9mfTXlwjrtgpPht9GVtPaPhnddieaxCYmJ2mNhUAiJmdojdpXBefCI%2BppjMbxpu9vwt7NXvKbF81zDp9mr3lWdN2t%2BDYeawGlsF48In6M5iYnnEwupgBETM7RG4A2rp7T8U7NK4KR4b%2FVNi%2Ba5R2xSsdKx9lcuOs0mdoiYhPS%2BXIA0yAAAAAAAAAA7MU746z5LsNNb3Zr2bud%2FXSfgAiotWLRtaN2UaesTvO8x2bC6YiIiI2iNkggAAAAImImNpjdIDGdPWZ3jeI7Na1isbVjZIumACAplnbHafJdhqbbVivdZ%2BpfxzgOjmAAAAAABtunhnsCBPDPZALY7cF4n7u1wOnT5N68M9Y6M9RrmtgGGwAATFLW%2BGsz9IJiYnaYmPqCAAAAAiJmdoiZnyWml6xvNbR9YBUAAABx5b8eSZ8PBvnvw02jrLlb5jHV%2FgCeGezTKBPDPZG2wAAAJisgg3nutwx3TwwmrisWlaJiUcMI4T4fUzWCsTF4267o3mq1bc%2FMHYKY78Uea7DoPQ02krWItkje3afBzaOkX1Fd%2Bkc3qNcxnqit6VvG16xMeaMlprtELVneIknUtxh5uq03qZ4q86T%2BHO9jNSMmK1Z8YeOlmOnN0b6XTzmtvblSOvmwevgpFMNKx25kmnVxalK442pWIjyWRadqzKuO02336r6kuObDU6St4m2ONrdo6S87o9t5mtpFNRO36o3Oo3zXOCmTJFeUdWWnNliZy23RFY8VrW57zzlTebNua0zEKzaThTwwfD6rvPcX4YRwx3NMVEzWUKgAALRXunesdk1cU3nunilbihpSsTG8gzj3vCUxXhtE7dJbgqs0%2FXjlpS3FXdTaazvX7d167Tzjlv1ZrUdWhtFdRG%2FjGz03iRMxMTHKYepp9RXNXaZ2v4wvNZ6i2X4o%2Bi%2BP4ILVi3VPKI7RDM5s6tZRktFMdrT4Ru8Z16zUxf8A86TvXxnu5F6rfMHsYrRfFW0eMPHdWj1MY%2FcvPuz0nsc06mu7J8CuLrLTlaO8SitYrHJLzb3Kws83X2i2o2j9MbOzUaiuGve3hDy7TNrTaZ3mectdVrmKZL8Fd%2FsypT9eWf4a2iN4tPPbpCm02ne327JGqyvXjvNoidlZ93wl0DWMuXilG89296REbwz4oEUF96yiax4GmKgKgAAtjpxz5Kt8HwT9QXisVjlCQRQAAAF6zunp0YZbzSu8TtLL12T5vwnlr09GuqzVjaMk%2FwA81b5smT47zMdnB67J834PXZPm%2FBlNjsb10ma0b8G31l5sZ8kTvFua%2Ftup%2Fev9zyXp3zpM0fo3%2BksJiYnaY2mHP7bqf3r%2FAHUnPlmZmbzMz4nlJ07qZsmP4LzEdl51Wa0bTkn%2BOTzfXZPm%2FB67J834Mq%2Bo7JmZneecomdnJ67J834a4rzeJ4p3lPJ6XmdwGkABBW1K26wsA5r0mk%2BSrfP8H8sFQAAAAXx34J59JUAdUTExyndLkImYneBddYyrm5e9H2JzRtyj7g0m0R1mIVnLWPHdzzMzO89QNTe03neUAIAAAAAAAAJpaazvCAHRXLWevJaLRPSYlykTMTvAuusZVzRt70fYtm5e7H3BqiZiOs7OWZmZ3nqBq%2BS%2FHPLpCgCAAAAAAAAAAAALY8d8s7Y6WtPlCLVtS01tExMdYl6vobJj4L4%2BUZN9%2FrDp12jrqqbxtGSOk%2F5IPAFslLY7zS8TFo6xKoAAAAAAAAAAAAAAAAAAAAAAAAAAAAJpa1LRaszFo6TD3dBra6mvDfaMsdY7vBTW1qWi1ZmLR0mAe9rtHXVU3jaMkdJ%2FyXhZKWx3ml4mLR1h7eg1tdTXhvtGWOsd1tdo66qm8bRkjpP%2BSDwBOSlsd5peJi0dYQAAAAAAAAAAAAAAAAAAAAAAAAAAAACa2tS0WrMxaOkw93QayNVThtyyVjn5%2BbxcGG%2BoyxTHG8z%2BHv6XTU02Phrzmetu4M9fo66jHNo5ZKxynv5PAex6S10Y4nDine88rT2eOAAAAAAAAAAAAAAAAAAAAAAAAAAA0wYb6jLFMcbzP4MGG%2BoyxTHG8z%2BHv6XTU02Lhpzmetu4Gl01NNj4a85nrbu5fSOv9VE4sM%2B%2F4z8v%2FT0jr%2FVb4sM%2B%2FwCNvl%2F68br1A6zzAAF64ct43pjvaO8VmU%2BzZ%2F2cn9ZBmNfZs%2F7OT%2Bsns2f9nJ%2FWQZDT2bP%2Bzk%2FrKLYctI3vjvWO81mAUAAAAAAAAAAAAAAAAAAAB6vobJirjvWZiMkzvz8YX9IekIxxOLBaJvPW0eDxwDr1AAI68%2BgA%2BmwXx2xVnFMTXblsu%2BWAfVIfLAPqVM18dMVpyzEV257vmQCevIAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAH%2F9k%3D&label=kitty&labelColor=282828)](https://sw.kovidgoyal.net/kitty/)

> [!WARNING]  
> This project is still a work in progress and not considered stable

https://github.com/mikesmithgh/kitty-scrollback.nvim/assets/10135646/5aba1ba2-1883-4ac0-bad3-7ecd12f46a7e

## ✨ Features
- 😻 Navigate Kitty's scrollback buffer with Neovim
- 🐱 Copy contents from Neovim to system clipboard
- 😺 Send contents from Neovim to Kitty shell
- 🙀 Execute shell command from Neovim to Kitty shell

## 🏃 Quickstart

To quickly test this plugin without changing your configuration run the command:
```sh
sh -c "$(curl -s https://raw.githubusercontent.com/mikesmithgh/kitty-scrollback.nvim/main/scripts/mini.sh)"
```
> [!NOTE]  
> It is good practice to first
> [read the script](https://github.com/mikesmithgh/kitty-scrollback.nvim/blob/main/scripts/mini.sh)
> before running `sh -c` directly from the web

## 📦 Installation

### Prerequisites
- Neovim [v0.10+](https://github.com/neovim/neovim/releases)
- Kitty [v0.29+](https://github.com/kovidgoyal/kitty/releases)

<details>

<summary>Using <a href="https://github.com/folke/lazy.nvim">lazy.nvim</a></summary>

```lua
  {
    'mikesmithgh/kitty-scrollback.nvim',
    enabled = true,
    lazy = true,
    cmd = { 'KittyScrollbackGenerateKittens', 'KittyScrollbackCheckHealth' },
    config = function()
      require('kitty-scrollback').setup()
    end,
  }
```

</details>
<details>

<summary>Using Neovim's built-in package support <a href="https://neovim.io/doc/user/usr_05.html#05.4">pack</a></summary>

```bash
mkdir -p "$HOME/.local/share/nvim/site/pack/mikesmithgh/start/"
cd $HOME/.local/share/nvim/site/pack/mikesmithgh/start
git clone git@github.com:mikesmithgh/kitty-scrollback.nvim.git
nvim -u NONE -c "helptags kitty-scrollback.nvim/doc" -c q
mkdir -p "$HOME/.config/nvim"
echo "require('kitty-scrollback').setup()" >> "$HOME/.config/nvim/init.lua"
```

</details>

## ✍️ Configuration

### Kitty 
The following steps outline how to properly configure [kitty.conf](https://sw.kovidgoyal.net/kitty/conf/)

<details>
<summary>Enable <a href="https://sw.kovidgoyal.net/kitty/conf/#opt-kitty.allow_remote_control">allow_remote_control</a></summary>

  - Valid values are `yes`, `socket`, `socket-only`
  - If `kitty-scrollback.nvim` is the only application controlling Kitty then `socket-only` is preferred to continue denying TTY requests.

</details>
<details>
<summary>Set <a href="https://sw.kovidgoyal.net/kitty/conf/#opt-kitty.listen_on">listen_on</a> to a unix socket</summary>

  - For example, `listen_on unix:/tmp/kitty`

</details>
<details>
<summary>Enable <a href="https://sw.kovidgoyal.net/kitty/conf/#opt-kitty.shell_integration">shell_integration</a></summary>

  - Set `shell_integration` to `enabled`
  - Do not add the option `no-prompt-mark`

</details>
<details>
<summary>Add <code>kitty-scrollback.nvim</code> mappings</summary>

  - Generate default Kitten mappings and add to `kitty.conf`
  ```sh
  nvim --headless +'KittyScrollbackGenerateKittens' +'set nonumber' +'set norelativenumber' +'%print' +'quit!' 2>&1
  ```

</details>

<details>
<summary>Completely close and reopen Kitty</summary>
</details>

</details>
<details>
<summary>Check the health of <code>kitty-scrollback.nvim</code></summary>

  ```sh
  nvim +'KittyScrollbackCheckHealth' +'quit!'
  ```
  - Follow the instructions of any `ERROR` or `WARNINGS` reported during the healthcheck

</details>
<details>
<summary>Test <code>kitty-scrollback.nvim</code> is working as expected by pressing <code>ctrl+shift+h</code> to open the scrollback buffer in Neovim</summary>
</details>

<details>
<summary>See example <code>kitty.conf</code> for reference</summary>

  ```sh
  allow_remote_control yes
  listen_on unix:/tmp/kitty
  shell_integration enabled
  
  # kitty-scrollback.nvim Kitten alias
  action_alias kitty_scrollback_nvim kitten /Users/mike/gitrepos/kitty-scrollback.nvim/python/kitty_scrollback_nvim.py --cwd /Users/mike/gitrepos/kitty-scrollback.nvim/lua/kitty-scrollback/configs
   
  # Browse scrollback buffer in nvim
  map ctrl+shift+h kitty_scrollback_nvim
  # Browse output of the last shell command in nvim
  map ctrl+shift+g kitty_scrollback_nvim --config-file get_text_last_cmd_output.lua
  # Show clicked command output in nvim
  mouse_map ctrl+shift+right press ungrabbed combine : mouse_select_command_output : kitty_scrollback_nvim --config-file get_text_last_visited_cmd_output.lua
  ```
  
</details>

### Kitten arguments

### Nerd Fonts 
By default, `kitty-scrollback.nvim` uses [Nerd Fonts](https://www.nerdfonts.com) in the status window. If you would like to 
use ASCII instead, set the option `status_window.style_simple` to `true`. 

<details>
  <summary>Status window with Nerd Fonts <code>opts.status_window.style_simple = false</code></summary>
  
  https://github.com/mikesmithgh/kitty-scrollback.nvim/assets/10135646/4cf5b303-5061-43da-a857-c99daea82332
  
</details>
<details>
  <summary>Status window with ASCII text <code>opts.status_window.style_simple = true</code></summary>
  
  https://github.com/mikesmithgh/kitty-scrollback.nvim/assets/10135646/a0e1b574-59ab-4abf-93a1-f314c7cd47b3
  
</details>


## 🫡 Commands and Lua API
The API is available via the `kitty-scrollback.api` module. e.g., `require('kitty-scrollback.api')`
| Command                              | API                              | Description                                                             |
| :----------------------------------- | :------------------------------- | :---------------------------------------------------------------------- |
| `:KittyScrollbackGenerateKittens[!]` | `generate_kittens(boolean\|nil)` | Generate Kitten commands used as reference for configuring `kitty.conf` |                 
| `:KittyScrollbackCheckHealth`        | `checkhealth()`                  | Run `:checkhealth kitty-scrollback` in the context of Kitty             |

## ⌨️ Keymaps and Lua API
The API is available via the `kitty-scrollback.api` module. e.g., `require('kitty-scrollback.api')`
| `<Plug>` Mapping            | Default Mapping | Mode  | API                   | Description                                                                             |
| --------------------------- | --------------- | ----- | --------------------- | --------------------------------------------------------------------------------------- |
| `<Plug>(KsbExecuteCmd)`     | `<C-CR>`        | n,i   | `execute_command()`   | Execute the contents of the paste window in Kitty                                       |
| `<Plug>(KsbPasteCmd)`       | `<S-CR>`        | n,i   | `paste_command()`     | Paste the contents of the paste window to Kitty without executing                       |
| `<Plug>(KsbToggleFooter)`   | `g?`            | n     | `toggle_footer()`     | Toggle the paste window footer that displays mappings                                   |
| `<Plug>(KsbCloseOrQuitAll)` | `<Esc>`         | n     | `close_or_quit_all()` | If the current buffer is the paste buffer, then close the window. Otherwise quit Neovim |
| `<Plug>(KsbQuitAll)`        | `<C-c>`         | n,i,t | `quit_all()`          | Quit Neovim                                                                             |
| `<Plug>(KsbVisualYankLine)` | `<Leader>Y`     | v     |                       | Maps to `"+Y`                                                                           |
| `<Plug>(KsbVisualYank)`     | `<Leader>y`     | v     |                       | Maps to `"+y`                                                                           |
| `<Plug>(KsbNormalYankEnd)`  | `<Leader>Y`     | n     |                       | Maps to `"+y$`                                                                          |
| `<Plug>(KsbNormalYank)`     | `<Leader>y`     | n     |                       | Maps to `"+y`                                                                           |
| `<Plug>(KsbNormalYankLine)` | `<Leader>yy`    | n     |                       | Maps to `"+yy`                                                                          |

## 🛣️ Roadmap
- [x] document setup with remote control and shell integration
- [x] add quick setup to allow user to test easily before installing
- [ ] add documentation and examples
- [ ] add details about relevant kitty config ( `scrollback_lines`, `scrollback_pager`, `scrollback_pager_history_size`, `scrollback_fill_enlarged_window`)
- [ ] release v1
- [ ] ci/cd
- [ ] add support for https://github.com/m00qek/baleia.nvim

## 👏 Recommendations
The following plugins are nice additions to your Neovim and Kitty setup.
- [vim-kitty](https://github.com/fladson/vim-kitty) - Syntax highlighting for Kitty terminal config files
- [smart-splits.nvim](https://github.com/mrjones2014/smart-splits.nvim) - Seamless navigation between Neovim and Kitty split panes 

## 🤝 Ackowledgements
- Kitty [custom kitten](https://sw.kovidgoyal.net/kitty/kittens/custom/) documentation
- [baleia.nvim](https://github.com/m00qek/baleia.nvim) - very nice plugin to colorize Neovim buffer containing ANSI escape sequences. I plan to add integration with this plugin 🤝
- [kovidgoyal/kitty#719 Feature Request: Ability to select text with the keyboard (vim-like)](https://github.com/kovidgoyal/kitty/issues/719) - ideas for passing the scrollback buffer to Neovim
- [kovidgoyal/kitty#2426 'Failed to open controlling terminal' error when trying to remote control from vim](https://github.com/kovidgoyal/kitty/issues/2426) - workaround for issuing kitty remote commands without a tty `listen_on unix:/tmp/mykitty`
- [kovidgoyal/kitty#6485 Vi mode for kitty](https://github.com/kovidgoyal/kitty/discussions/6485) - inspiration to leverage Neovim's terminal for the scrollback buffer
- [tokyonight.nvim](https://github.com/folke/tokyonight.nvim) - referenced for color darkening, thank you folke!
- [lazy.nvim](https://github.com/folke/lazy.nvim) - referenced for window sizing, thank you folke!
- [fzf-lua](https://github.com/ibhagwan/fzf-lua) - quickstart `mini.sh` and inspiration/reference for displaying keymapping footer
- [cellular-automaton.nvim](https://github.com/Eandrju/cellular-automaton.nvim) - included in a fun example config
- StackExchange [CamelCase2snake_case()](https://codegolf.stackexchange.com/a/177958/119424) - for converting Neovim highlight names to `SCREAMING_SNAKE_CASE`

- TODO doc up:
  - see :help clipboard
  - pbcopy and pbpaste on macos
  - xclip or wayland on linux
  - anything preceding `--nvim-args` will be passed to nvim, do no use --cmd or an error will occur
  - `--nvim-no-args` to disable default and pass no args
  - `--env` to set environment variables e.g., `--env NVIM_APPNAME=altnvim`
  - `--config-file` to set lua file with `config` function to set plugin options
