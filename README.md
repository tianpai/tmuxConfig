# Tmux Configuration

A simple tmux configuration file for beginners.

## Installation Steps

1.  Install Tmux

    `brew install tmux`

2.  Clone this repo

    ```bash
    git clone https.//github.com/tianpai/tmuxConfig.git
    ```

3.  Soft link or cp .tmux.conf to home directory

    Change directory to tmuxConfig folder

         `cd path/to/tmuxConfig/`

    Options:

    1. Soft link .tmux.conf to home directory

       `ln -s tmuxConfig/.tmux.conf ~/.tmux.conf`

    2. Cpoy .tmux.conf to home directory

       `cp tmuxConfig/.tmux.conf ~/.tmux.conf`

4.  Source `.tmux.conf`

        tmux source-file ~/.tmux.conf

5.  Install TPM (Tmux Plugin Manager) and source .tmux.conf

    ```bash
    git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
    ```

6.  Open tmux and install plugins

    Open terminal and type:

    ```bash
    tmux
    ```

    Press prefix + I (capital i, as in Install) to fetch the plugin.

## USAGE

**Most of the key bindings are the same as default**

1. IMPORTANT: (same as default)

```bash
preifx + I Install plugins
prefix + U Update plugins
prefix + r Reload config file
```

2. CUSTOM KEY BINDINGS: (different from default)

```bash
prefix + - Split window vertically
prefix + | Split window horizontally
prefix + up Go to the pane above
prefix + down Go to the pane below
prefix + left Go to the pane on the left
prefix + right Go to the pane on the right
```
