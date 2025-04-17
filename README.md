# install
1. hammerspoon 설치
> brew install hammerspoon --cask

2. WindowScreenLeftAndRight 설치
> curl -L -O https://github.com/Hammerspoon/Spoons/raw/master/Spoons/WindowScreenLeftAndRight.spoon.zip && mkdir -p ~/.hammerspoon/Spoons && unzip WindowScreenLeftAndRight.spoon.zip -d ~/.hammerspoon/Spoons && rm WindowScreenLeftAndRight.spoon.zip

3. init.lua 생성
> curl https://raw.githubusercontent.com/hohoonlee/backup/refs/heads/main/hammerspoon > ~/.hammerspoon/init.lua