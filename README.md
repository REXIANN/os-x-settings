# os-x-settings

## Terminal 세팅

```bash
# 제일 먼저 기본 bash shell을 켜자
# Commnad Linte Tools Installation
$ xcode-select --install

# install brew
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
$ brew update
$ brew cask install iterm2
# bash를 종료하고 iterm2를 실행

# install zsh
$ brew install zsh
$ echo $SHELL 
$ which zsh
# echo의 경로와 which의 경로가 다른 것을 볼 수 있다. 쉘을 참조하는 위치는 echo이고 우리는 echo를 which로 바꿔야함.
$ chsh -s /usr/local/bin/zsh
# 만일 chsh가 안된다면 /etc/shells에 which의 경로를 맨 위에 추가해줄 것
$ vi /etc/shells
# /usr/local/bin/zsh 을 추가 후 esc -> :wq -> enter키 

# install oh-my-zsh
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# install for Fun!
$ brew install fortune
$ brew install cowsay
$ vi ~/.zshrc
fortune | cowsay -f tux
# 이제 터미널을 켤 때마다 턱스가 명언을 해준다!

# install git, vcprompt 
$ brew install git
$ brew install vcprompt

# install firefox, spectacle
$ brew cask install firefox google-chrome 
$ brew cask install spectacle

# install other programs
# brew search 프로그램이름 명령어로 해당 프로그램이 brew cask로 설치가능한지 먼저 알아볼 것!
$ brew cask install webex-meetings # 이거는 암호 입력이 한번 필요함
# 이후 다른 프로그램들은 편하게 설치 가능
$ brew cask install typora postman mattermost dropbox slack pdf-expert docker 

# 도커 로그인이 안될 때- 리눅스 기준
$ sudo apt install gnupg2 pass

```

## MacOS 설정 변경
* 키보드 - 한/영 전환키 설정, 보조키 변경, 데스크톱 단축키 활성화
* 핫코너 - 기역 자 모양으로 Mission Control, Launch Pad, Desktop
* Dock - 자동숨김 활성, 확대 활성
* 트랙패드와 마우스 - 둘다 제이 빠르게 설정


## 2022.09 현재 사용하는 프로그램들
Using Brew: cowsay, fnm, fortune, go-task, python@3.9, teraform, tmux, 
(Cask)logi-options-plus, firefox, google-chrome, macs-fan-control, spectacle, visual-studio-code

Using Dmg: MS Office, Slack, GitKraken, Microsoft Edge, Caffeine, iTerm2, intelliJ, Amphetamine

## intelliJ 플러그인 사용하는 것들
.env files supprot, .ignore, Atom Material Icons, AceJump, GitToolBox, Go, Import Cost, Key Promoter X,
Lines Sorter, Next.js, One Dark theme, Prettier, Prisma Support, Python, Rainbow Brackets, requirements, 
SmartSort, SonarLint, Styled Components & Styled JSX, Taskfile, Terraform and HCL

