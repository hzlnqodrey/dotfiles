# If you come from bash you might have to change your $PATH.
# export PATH=$HOME/bin:/usr/local/bin:$PATH

# Path to your oh-my-zsh installation.
export ZSH="$HOME/.oh-my-zsh"

# Set name of the theme to load --- if set to "random", it will
# load a random theme each time oh-my-zsh is loaded, in which case,
# to know which specific one was loaded, run: echo $RANDOM_THEME
# See https://github.com/ohmyzsh/ohmyzsh/wiki/Themes
ZSH_THEME="gnzh"

# Set list of themes to pick from when loading at random
# Setting this variable when ZSH_THEME=random will cause zsh to load
# a theme from this variable instead of looking in $ZSH/themes/
# If set to an empty array, this variable will have no effect.
# ZSH_THEME_RANDOM_CANDIDATES=( "robbyrussell" "agnoster" )

# Uncomment the following line to use case-sensitive completion.
# CASE_SENSITIVE="true"

# Uncomment the following line to use hyphen-insensitive completion.
# Case-sensitive completion must be off. _ and - will be interchangeable.
# HYPHEN_INSENSITIVE="true"

# Uncomment one of the following lines to change the auto-update behavior
# zstyle ':omz:update' mode disabled  # disable automatic updates
# zstyle ':omz:update' mode auto      # update automatically without asking
# zstyle ':omz:update' mode reminder  # just remind me to update when it's time

# Uncomment the following line to change how often to auto-update (in days).
# zstyle ':omz:update' frequency 13

# Uncomment the following line if pasting URLs and other text is messed up.
# DISABLE_MAGIC_FUNCTIONS="true"

# Uncomment the following line to disable colors in ls.
# DISABLE_LS_COLORS="true"

# Uncomment the following line to disable auto-setting terminal title.
# DISABLE_AUTO_TITLE="true"

# Uncomment the following line to enable command auto-correction.
# ENABLE_CORRECTION="true"

# Uncomment the following line to display red dots whilst waiting for completion.
# You can also set it to another string to have that shown instead of the default red dots.
# e.g. COMPLETION_WAITING_DOTS="%F{yellow}waiting...%f"
# Caution: this setting can cause issues with multiline prompts in zsh < 5.7.1 (see #5765)
# COMPLETION_WAITING_DOTS="true"

# Uncomment the following line if you want to disable marking untracked files
# under VCS as dirty. This makes repository status check for large repositories
# much, much faster.
# DISABLE_UNTRACKED_FILES_DIRTY="true"

# Uncomment the following line if you want to change the command execution time
# stamp shown in the history command output.
# You can set one of the optional three formats:
# "mm/dd/yyyy"|"dd.mm.yyyy"|"yyyy-mm-dd"
# or set a custom format using the strftime function format specifications,
# see 'man strftime' for details.
# HIST_STAMPS="mm/dd/yyyy"

# Would you like to use another custom folder than $ZSH/custom?
# ZSH_CUSTOM=/path/to/new-custom-folder

# Which plugins would you like to load?
# Standard plugins can be found in $ZSH/plugins/
# Custom plugins may be added to $ZSH_CUSTOM/plugins/
# Example format: plugins=(rails git textmate ruby lighthouse)
# Add wisely, as too many plugins slow down shell startup.
plugins=(
	git
	antigen
	1password
)

source $ZSH/oh-my-zsh.sh

# User configuration

# export MANPATH="/usr/local/man:$MANPATH"

# You may need to manually set your language environment
# export LANG=en_US.UTF-8

# Preferred editor for local and remote sessions
# if [[ -n $SSH_CONNECTION ]]; then
#   export EDITOR='vim'
# else
#   export EDITOR='mvim'
# fi

# Compilation flags
# export ARCHFLAGS="-arch x86_64"

# Set personal aliases, overriding those provided by oh-my-zsh libs,
# plugins, and themes. Aliases can be placed here, though oh-my-zsh
# users are encouraged to define aliases within the ZSH_CUSTOM folder.
# For a full list of active aliases, run `alias`.
#
# Example aliases
# alias zshconfig="mate ~/.zshrc"
# alias ohmyzsh="mate ~/.oh-my-zsh"

# Antigen Package
source /opt/homebrew/share/antigen/antigen.zsh

# ALIAS K8s
alias k=kubectl
alias kd='kubectl describe'
alias kgp='kubectl get pod'
alias kgd='kubectl get deploy'
alias kgs='kubectl get svc'
alias kgcm='kubectl get configmap'
alias kgi='kubectl get ingress'
alias kgnd='kubectl get nodes'
alias wkgp='watch kubectl get pod'
alias wkgn='watch kubectl get nodes'
alias ktpd='kubectl top pod'
alias ktpn='kubectl top nodes'

# alias gcp
alias gcvp='gcloud config get-value project'
alias gcsp='gcloud config set project'

# ALIAS GIT
alias gad='git add'
alias gcm='git commit -m'

# open aliases
alias

# asdf Config
export PATH="${ASDF_DATA_DIR:-$HOME/.asdf}/shims:$PATH"

# contextualize search cli
# > atuin
OME/.atuin/bin/env"

# Django VirtualEnvWrapper
export WORKON_HOME=$HOME/.virtualenvs
export VIRTUALENVWRAPPER_PYTHON=/Users/user_1/.pyenv/versions/3.10.4/bin/python3
export PROJECT_HOME=$HOME/Devel
source /Users/user_1/.pyenv/versions/3.10.4/bin/virtualenvwrapper.sh

# The following lines have been added by Docker Desktop to enable Docker CLI completions.
fpath=(/Users/user_1/.docker/completions $fpath)
autoload -Uz compinit
compinit
# End of Docker CLI completions


# ALIAS K8s
alias k=kubectl
alias kd='kubectl describe'
alias kgp='kubectl get pod'
alias kgd='kubectl get deploy'
alias kgs='kubectl get svc'
alias kgcm='kubectl get configmap'
alias kgi='kubectl get ingress'
alias kgnd='kubectl get nodes'
alias wkgp='watch kubectl get pod'
alias wkgn='watch kubectl get nodes'
alias ktpd='kubectl top pod'
alias ktpn='kubectl top nodes'

# ALIAS GIT
alias gad='git add'
alias gcm='git commit -m'
alias stat="git status"
alias gdiff="git diff HEAD"
alias vdiff="git difftool HEAD"
alias log="git log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
alias cfg="git --git-dir=$HOME/dotfiles/ --work-tree=$HOME"
alias push="git push"
alias g="lazygit"

# alias gcp
alias gcvp='gcloud config get-value project'
alias gcsp='gcloud config set project'

# alias docker
alias dockerkillall='[ -n "$(docker ps -q)" ] && docker rm -f $(docker ps -q) || echo "No running containers."'

# alias AI Model
alias zai="npx @z_ai/coding-helper"

# [OPEN ALIASES] keep this command on so I can see which alias default already on this device
#alias


# asdf Config
export PATH="${ASDF_DATA_DIR:-$HOME/.asdf}/shims:$PATH"

# contextualize search cli
# > atuin
. "$HOME/.atuin/bin/env"

eval "$(atuin init zsh)"
export GPG_TTY=$(tty)

# run neofetch
# neofetch

# golang 1.23
export PATH="/opt/homebrew/opt/go@1.23/bin:$PATH"
export PATH="$HOME/.local/bin:$PATH"

# SET KITTY_MOD KEYBIND
# run this in cli:
# set kitty_mod ctrl+shift

# opencode
export PATH=/Users/user_1/.opencode/bin:$PATH

# Added by Antigravity
export PATH="/Users/user_1/.antigravity/antigravity/bin:$PATH"

# Install plugin
# "opencode-antigravity-auth@latest"
# 1. go to ~/.opencode/config.json
# 2. edit plugin
#Run opencode auth login to authenticate with Google OAuth (if needed)
#The plugin will be installed automatically when you next run OpenCode

### OPEN CODE Guide
## installation
# curl -fsSL https://opencode.ai/install | bash
## configs
# cat ~/.opencode/oh-my-opencode.json
# cat ~/.opencode/config.json
## MCP
# Where I Put the .mcp.json Files
# ~/.claude/plugins/marketplaces/claude-plugins-official/external_plugins/memory/.mcp.json
# ~/.claude/plugins/marketplaces/claude-plugins-official/external_plugins/openspec/.mcp.json
# Context7
# filesystem
# grep_app
# sequential-thinking
# memory
# tavily-remote-mcp
# openspec
# websearch
## Provider
# GLM Z.AI Coding Plan
# Google Antigravity
## Plugins (they named it Ecosystem)
# https://opencode.ai/docs/ecosystem/
# opencode-antigravity-auth

## OpenSpec
# npm install -g @fission-ai/openspec@latest
# openspec init

# AI PROMPT Tutorial                      
# create comprehensive langraph for me, decide how many components for my learning journey. Each topic must be served as a one main file. 
# The main file format prefix should be 01_<topic>.py.
# each topic also have explanation in md file with format 01_<topic>.md
# each md must include
# 1. What to learn
# 2. Flow
# 3. Input
# 4. Output
# 5. Try Yourself
 
## Vi
# auto line number
# vi --version
# touch ~/.vimrc
# vi ~/.vimrc
#" explicit, no surprises
#set number
#set relativenumber