## Mac Setup
I'm planning on getting a new mac soon cause my current one is practecly dead. So I decided to make a repo with some of my settings and also things I'd need to install.

- Brew | https://brew.sh/
- NVM | https://github.com/nvm-sh/nvm
- Figma | https://formulae.brew.sh/cask/figma
- Chrome | https://formulae.brew.sh/cask/google-chrome#default
- MySql | https://dev.mysql.com/downloads/mysql/
- MongoDB | https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/
- Insomnia | https://formulae.brew.sh/cask/insomnia#default
- Discord | https://formulae.brew.sh/cask/discord#default
- VsCode | https://formulae.brew.sh/cask/visual-studio-code#default
- Alfred | https://formulae.brew.sh/cask/
- Rectangle | https://formulae.brew.sh/cask/rectangle#default
- AltTab | https://formulae.brew.sh/cask/alt-tab#default
- Iterm | https://formulae.brew.sh/cask/iterm2#default
- Xcode | /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
- Notion | https://formulae.brew.sh/cask/notion#default

* [ ] Install Brew
* [ ] Install Xcode
* [ ] Install iterm
  * [ ] Edit Iterm prefrences
* [ ] Install VS.Code
  * [ ] Edit VS.Code Settings
* [ ] Update .zshrc file
* [ ] Install Alfred
* [ ] Install Rectangle
* [ ] Install AltTab
* [ ] Install Insomnia
* [ ] Install NVM
* [ ] Update Python
* [ ] Install mySql
* [ ] Install MongoDb
* [ ] Install Discord
* [ ] Install Notion


## Vscode Settings
- Theme: poimandres
- Font Size: 14px
- Tabsize: 2
- Extentions: 
  - Cloak
  - DotEnv
  - React
  - Typescript
  - Eslint
  - Markdown
  - Material Icon
  - Prettier ESLint
  - VSCode icon


## .zshrc File
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
