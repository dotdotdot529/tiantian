Setup
-----

## Find your terminal
A place to interact with your computer

![where is your terminal](../imgs/where_is_terminal.png)

![welcom_page_terminal](../imgs/welcome_page_terminal.png)

- 它能干啥：你可以在这里指挥你的电脑做各种各样的事情，远远比你单纯使用各种带图形化的软件可以做的事情多得多
- 如果你想让你的terminal变的更漂亮&&更productive，go to [zsh](zsh/README.md)
- What is `zsh`：A shell with a lot of features that makes you HIGHLY PRODUCTIVE

## Install homebrew
Package manager for macOS
> you may also want to access https://brew.sh/
```bash
# Install by entering the following command into your terminal
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- 为啥要安装homebrew：这是macOS下的包管理工具，我们可以用homebrew来安装各种东东

## Install Python3
```bash
# install python3 via homebrew 
# 打开你的terminal输入以下指令
brew install python3

# enter the following command to verify the installation
python --version
```
- 这时候就可以通过homebrew轻松的安装好python了

## Install IDE
> go to https://code.visualstudio.com/
- 你未来将用这个工具来写代码
- 为什么用这个，而不是用`Text Editor`
  - 它提供了很多Feature，举例
    - Syntax-Highlight：帮助你
    - Auto-Completion：自动补全你的代码
    - Format：将你的代码自动格式化，变的整齐
    - Static-Checking：自动检测你在代码编写中出现的错误