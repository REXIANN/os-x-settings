# os-x-settings

## Terminal 세팅
### install brew
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
$ brew update
$ brew cask install iterm2
# bash를 종료하고 iterm2를 실행

### iterm2 setting
theme = lovelace or argonaut 설정
Preferences > Appearance > General > Theme: Minimal 
Preferences > Apperarance > Tabs > XXOOOOXOOX
Preferences > Profiles > General > Working Directory: Reuse previous session's directory
Preferences > Window > Transparency: 20~30 

### install oh-my-zsh and powerlevel10k
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
$ git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
.zshrc 파일의 테마를 ZSH_THEME="powerlevel10k/powerlevel10k" 로 변경
이후 터미널을 재실행하여 마저 진행하며 됨

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

