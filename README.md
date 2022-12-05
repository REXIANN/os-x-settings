# os-x-settings
## MacOS setting
```
$ xcode-select --install
$ /usr/sbin/softwareupdate --install-rosetta --agree-to-license
```
* 키보드 - 한/영 전환키 설정, 보조키 변경, 데스크톱 단축키(Ctrl + number) 활성화
* 핫코너 - 기역 자 모양으로 Mission Control, Launch Pad, Desktop
* Dock - 자동숨김 활성, 확대 활성
* 트랙패드와 마우스 - 둘다 제일 빠르게 설정

## Terminal
### install brew
```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
$ brew update
$ brew cask install iterm2
```
bash를 종료하고 iterm2를 실행

### iterm2 setting
theme = lovelace or argonaut 설정
* Preferences > Appearance > General > Theme: Minimal 
* Preferences > Apperarance > Tabs > XXOOOOXOOX
* Preferences > Profiles > General > Working Directory: Reuse previous session's directory
* Preferences > Profiles > Session > Miscellaneous: Status bar enabled > Configure Status Bar
* Preferences > Window > Transparency: 20~30 

### install oh-my-zsh and powerlevel10k
```
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
$ git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
.zshrc 파일의 테마를 ZSH_THEME="powerlevel10k/powerlevel10k" 로 변경
이후 터미널을 재실행하여 마저 진행

### install for Fun!
```
$ brew install fortune
$ brew install cowsay
$ vi ~/.zshrc
fortune | cowsay -f tux
```

## install applications
필수 설치: 크롬, 슬랙, spectacle, 깃크라켄, 인텔리제이, 도커(cask), kensingtonworks
```
$ brew install --cask google-chrome slack spectacle git-kraken intellij docker kensingtonworks gitkraken docker macs-fan-control
```

## 기타
### 2022.09 현재 사용하는 프로그램들
Using Brew: cowsay, fnm, fortune, go-task, python@3.9, teraform, tmux, 
(Cask)logi-options-plus, firefox, google-chrome, macs-fan-control, spectacle, visual-studio-code

Using Dmg: MS Office, Slack, GitKraken, Microsoft Edge, Caffeine, iTerm2, intelliJ, Amphetamine

### intelliJ 플러그인 사용하는 것들
.env files supprot, .ignore, Atom Material Icons, AceJump, GitToolBox, Go, Import Cost, Key Promoter X,
Lines Sorter, Next.js, One Dark theme, Prettier, Prisma Support, Python, Rainbow Brackets, requirements, 
SmartSort, SonarLint, Styled Components & Styled JSX, Taskfile, Terraform and HCL

