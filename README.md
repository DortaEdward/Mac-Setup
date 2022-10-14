## Mac Setup
I'm planning on getting a new mac soon cause my current one is practecly dead. So I decided to make a repo with some of my settings and also things I'd need to install.

* Brew
* NVM
* Figma
* Chrome
* MySql
* MongoDB
* Insomnia
* Discord
* VsCode
* Alfred
* Spectacle
* Rectangle
* AltTab
* Iterm
* Xcode
* Notion

* [ ] Install Brew
* [ ] Install Xcode
* [ ] Install iterm
  * [ ] Edit Iterm prefrences
* [ ] Install VS.Code
  * [ ] Edit VS.Code Settings
* [ ] Update .zshrc file
* [ ] Install Alfred
* [ ] Install Spectacle
* [ ] Install Rectangle
* [ ] Install AltTab
* [ ] Install Insomnia
* [ ] Install NVM
* [ ] Update Python
* [ ] Install mySql
* [ ] Install MongoDb
* [ ] Install Discord
* [ ] Install Notion


```
export ZSH="$HOME/.oh-my-zsh"
  
ZSH_THEME="robbyrussell"

source ~/.nvm/nvm.sh
nvm use stable 

plugins=(git)

source $ZSH/oh-my-zsh.sh

# General Aliases
alias edit='code ~/.zshrc'
alias c="code ."

# Python Aliases
alias py='python3'

# NPM Aliases
alias ns='npm start'
alias start='npm start'
alias nr='npm run'
alias run='npm run'

# Github Aliases
alias gs="git status"
alias ga="git add ."
alias gc='git commit'
alias gcm='git commit -m'
alias gd='git diff'
alias gi='git init'
alias gl='git log'
alias gp='git pull'
alias gpsh='git push'
alias gss='git status -s'

# Dev Aliases
alias d2='git clone https://github.com/DortaEdward/ts-express-starter.git server && npm create vite@latest client -- --template reacte-ts'

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion

```
