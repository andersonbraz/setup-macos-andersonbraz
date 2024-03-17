# Preparando o MacOS


## Instalar Homebrew

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Instalar OhMyZsh

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Renomear hostname do macbook

```shell
sudo scutil --set HostName machine.com
```

## Instalar pyenv

```shell
git clone https://github.com/pyenv/pyenv.git ~/.pyenv
```

## Criar variável de ambiente e habilitar o pyenv

```shell
export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

## Baixar o plugin zsh-autosuggestions

```shell
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

## Baixar o plugin zsh-syntax-highlighting

```shell
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

## Habilitar os plugins instalados

```shell
plugins=(
    git
    docker
    zsh-syntax-highlighting
    zsh-autosuggestions
)
```

## 

```shell
```

## 

```shell
```

## 

```shell
```

## 

```shell
```

## 

```shell
```