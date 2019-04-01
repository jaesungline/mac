# mac

## for coding, off caps lock, etc...

システム設定 > キーボード > キーボード > 修飾キー > Caps Lock - アクションなし

システム設定 > キーボード > ユーザ辞書 > 
英字入力中にスペルを自動変換をoff
文頭を自動的に大文字にするをoff
スペルチェック > KoreanとEnglishをoff

スマート引用符とスマートダッシュを使用をoff
https://torazuka.hatenablog.com/entry/20140724/smart

## off windows minimalize effect

defaults write com.apple.dock mineffect -string scale

killall Dock


# terminal application

using iTerm2 is recommended
https://www.iterm2.com/

customize
https://qiita.com/kinchiki/items/57e9391128d07819c321

change prompt name
```
$ export PS1="\w$ "
```
https://medium.com/@ajaykarwal/edit-the-terminal-prompt-name-on-macos-4d80163be6a1

# bash_profile

```
# alias
alias SB='source ~/.bash_profile'
alias VB='vi ~/.bash_profile'
alias f='open .'
alias hh='history'

# large history size 
HISTSIZE=50000

alias show='defaults write com.apple.finder AppleShowAllFiles TRUE && killall Finder'
alias hide='defaults write com.apple.finder AppleShowAllFiles FALSE && killall Finder'
alias KA='killall Finder'
```

# useful application
markdown editor
Typora
https://typora.io/

text editor
sublime text
https://www.sublimetext.com/

sourcetree
https://ja.atlassian.com/software/sourcetree
connecting with item2
環境設定 > ターミナルで使用するアプリケーション > iTerm2


