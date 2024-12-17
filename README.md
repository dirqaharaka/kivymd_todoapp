# kivymd_todoapp
To do and workout application created using kivymd and python

## Requirements
- Python==3.9.5
- Kivy==2.0.0
- kivy-deps.angle==0.3.0 #abaikan
- kivy-deps.glew==0.3.0 #abaikan
- kivy-deps.sdl2==0.3.1 #abaikan
- Kivy-examples==2.0.0 #abaikan
- Kivy-Garden==0.1.4
- kivymd==0.104.2
- olefile==0.47

#install pyenv
-  sudo apt install -y build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev xz-utils tk-dev libffi-dev liblzma-dev python3-openssl git
- curl https://pyenv.run | bash
- echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc
- echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc
- echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init --path)"\nfi' >> ~/.zshrc
- [ -z "$SHELL" ] && SHELL=/usr/bin/zsh
- exec $SHELL
- pyenv

install venv
- pyenv install 3.9.5
- pyenv local 3.9.5
- python -m venv .venv
- source .venv/bin/activate
- pip install -r requirements.txt

#if eror in linux 
- sudo apt update 
- sudo apt install xclip xsel

## What I learned
- Using kivymd widgets
- Kivy layouts for positioning widgets e.g floatlayout, boxlayout
- Handling different actions for the particular widgets
- Peforming CRUD operations using sqlite3

Reference : 
https://github.com/Ngonie-x/kivymd_todo_and_workout_app

