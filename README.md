# `zsh-copybuffer` plugin

This plugin binds the ctrl-o keyboard shortcut to a command that copies the text
that is currently typed in the command line ($BUFFER) to the system clipboard.

This is useful if you type a command - and before you hit enter to execute it - want
to copy it maybe so you can paste it into a script, gist or whatnot.

Extended from oh-my-zsh's copybuffer plugin.

## Usage

### Using zsh frameworks

#### [antigen](https://github.com/zsh-users/antigen)

Add `antigen bundle guillaumeboehm/zsh-copybuffer` to your `~/.zshrc`.

#### [zplug](https://github.com/zplug/zplug)

Add `zplug "guillaumeboehm/zsh-copybuffer"` to your `~/.zshrc`.

#### [oh-my-zsh](http://github.com/robbyrussell/oh-my-zsh)

* Clone the repository inside your oh-my-zsh repo:

        git clone https://github.com/guillaumeboehm/zsh-copybuffer ${ZSH_CUSTOM:=~/.oh-my-zsh/custom}/plugins/zsh-copybuffer

* Enable it in your `.zshrc` by adding it to your plugin list and reloading the completion:

        plugins=(… zsh-completions)
        autoload -U compinit && compinit

### Manual installation

* Clone the repository:

        git clone git://github.com/guillaumeboehm/zsh-copybuffer.git

* Source the plugin in your `~/.zshrc`

        `source /path/to/zsh-copybuffer`
