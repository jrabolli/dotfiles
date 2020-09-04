# dotfiles
new Mac setup

# Tools we use
- Slack
- TablePlus
- VS Code
- Dash
- Homebrew
- Heroku Toolbelt
- oh-my-zsh (https://ohmyz.sh)
- Postgresql mac app (https://postgresapp.com)
- GIT

# Homebrew installs
- heroku
- rbenv
- ruby-build
- zsh-history-substring-search
- zsh-syntax-highlighting
- zsh-autosuggestions

# setup order
- install xcode tools
- install homebrew
- oh-my-zsh
- postgresql app
- brew install (all)

# clone projects
(in code directory)
- git clone git@github.com:jrabolli/####.git
- check ruby version from project ruby-version file
- rbenv install (version)
- check gemfile for bundler version
- gem install bundler:[version]
- bundle install
- rails db:setup
