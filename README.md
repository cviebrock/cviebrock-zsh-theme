# cviebrock oh-my-zsh theme

![sample of cviebrock.theme for oh-my-zsh](https://i.imgur.com/pRI8iHl.png)

## Installation

1. Install [oh my zsh](http://ohmyz.sh/) as per their instructions.

2. Clone this repo into your the directory where you install your custom themes
   (I recommend you create a `~/.oh-my-zsh-custom/themes` directory and install 
   it there):

    ```sh
    cd ~
    mkdir -p .oh-my-zsh-custom/themes
    cd .oh-my-zsh-custom/themes
    git clone https://github.com/cviebrock/cviebrock-zsh-theme.git cviebrock
    ```

3. Edit the following entries in your `~/.zshrc` file:

    ```
    ZSH_THEME="cviebrock/cviebrock"
    ZSH_CUSTOM=$HOME/.oh-my-zsh-custom
    ```

4. Log out and in again.

5. Enjoy!
