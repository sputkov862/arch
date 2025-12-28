## 🚀 Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/sputkov862/arch
    cd arch
    ```
2.  Run the installation script:
    ```bash
    ./install.sh
    ```

    > **Note:** You must install the Tmux Plugin Manager manually:
    > ```bash
    > mkdir -p ~/.config/tmux/plugins && git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm
    > ```

The script will back up your existing configuration files to `~/.config/filename.bak` and `~/.zshrc.bak` before copying the new files.
