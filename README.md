# pack
Gerenciamento dos packages do vim. [Créditos](https://shapeshed.com/vim-packages/).

## Download
Se estiver no linux clone o repositório em `~/.vim`
```sh
git -C ~/.vim clone https://github.com/nenitf/pack.git
cd ~/.vim/pack
git submodule update --init --recursive
```
Se estiver no Windows clone o repositório em `%userprofile%\vimfiles`
```sh
git -C %userprofile%\vimfiles https://github.com/nenitf/pack.git
cd %userprofile%\vimfiles\pack
git submodule update --init --recursive
```

## Manutenção dos módulos
### Adicionar
Submodulos devem ser adicionados dentro de `/*/start` ou `/*/opt`
```sh
git submodule add https://github.com/vim-airline/vim-airline.git vim/pack/shapeshed/start/vim-airline
```
