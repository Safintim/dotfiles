# Install Python dependencies

## Python build dependencies:
```bash
sudo apt-get update; sudo apt-get install make build-essential libssl-dev zlib1g-dev \
libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm \
libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev
```

## pip
```bash
sudo apt install python3-pip
```

## [poetry](https://python-poetry.org/)
```bash
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```

## user packages
```bash
pip install --user -r requirements.txt
```

## pyenv
 - [pyenv-installer](https://github.com/pyenv/pyenv-installer)

 - [pyenv-instruction](https://github.com/pyenv/pyenv#installation)

```bash
curl https://pyenv.run | bash
exec $SHELL
```
