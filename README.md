- General
  - brew cask
    - google-chrome
    - firefox
    - slack
    - spectacle
    - spotify
    - dockutil
      - used if you want to modify mac Dock from CLI. common command on new Mac's is to remove all items from dock
    - mas
      - https://github.com/mas-cli/mas
      - a cli tool for install mac app store applications
    - bitwarden
      - better password manager then lastpass
      - has dark theme
      - is open-source
      - ability to run server yourself in docker container
  - Add CMD+L as lockscreen shortcut
    - setup hotcorner screensaver + lockscreen?
  - Preferances
    - dont rearrance spaces based on most recent use
    - Allow running apps from internet
    - disable sound effects on boot
    - Password after sleep or screensaver
    - screenshots directory & auto save screenshots there
    - perform search in current directory first by default
    - disable warning when changing file extension
    - avoid creating .DS_Store files on volumes or USB drives
    - Apps
      - Apple Mail
        - Copy email address as foo@example.com instead of foo bar \<foo@example.com\>
      - iterm2
        - set status bar up
        - change background
        - change theme to minimal
        - don't display prompt when quitting
      - Activity Monitor
        - Visualize CPU usage on dock icon
    - Toolbar Menu
      - Show battery percentage
      - show volume bar
      -


- Theme
  - Dark mode
  - Background?


- AppStore
  - the unarchiver
  - xCode
  - slack
  - WhatsApp Desktop
  - Microsoft Remote Desktop 10
  - Telegram

- Local Sys Admin
  - Etcher
    - for burning ISOs to USB drives

- Terminal
  - .oh-my-zsh
  - homebrew
    - git
    - vim
      - https://github.com/amix/vimrc.git
    - ack
    - nmap
    - tmux
    - htop
    - wget
    - jq
      - xpath for JSON
    - geoip
      - used to get geographical location of an IP address
      - good for security engineer
  - brew cask
    - iterm2
    - gpg-suite
      - generate GPG keys & upload to Github
  - SSH Keys
  -


- General Coding
  - brew cask
    - sublime-text
    - visual-studio-code
    - atom
    - sourcetree
      - git gui
    - postman

- Kubernetes
  - docker for mac
  - brew
    - docker for mac
    - oh-my-zsh plugins
      - kubectl
    - kubectx
    - octant (local Web GUI for remote and local kubernetes clusters)
    

- AWS
  - awscli
  - https://github.com/awslabs/git-secrets
  - Terraform


- Java
  - brew
    - jenv (for managing jdk versions)
    - sdkman
      - for installing and managing jdk's, jvm's, java based sdks (kotlin, grails, gradle, etc...)
    - jabba
      - same as jenv. Lets you install multiple jdk versions through it instead of brew
      - See: https://stackoverflow.com/questions/52524112/how-do-i-install-java-on-mac-osx-allowing-version-switching for comparision of jenv, sdkman, homebrew, brew cask, jabba
    - maven
  - brew cask
    - oracle-jdk
    - adoptopenjdk8


References
- http://sourabhbajaj.com/mac-setup/



Support installation of drivers
- https://github.com/Homebrew/homebrew-cask-drivers
