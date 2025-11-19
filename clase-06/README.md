# Clase 06 - Git Desarrollo Colaborativo

## Git alias
Comandos que me permiten usar de ágil y rápida comandos mas largos de git

## Crear un alias en git

```sh
git config --global alias.l "log --oneline"
git config --global alias.ll "log --oneline --decorate --all --graph"
git config --global alias.c "commit -m" #git c "mensaje"
git config --global alias.s "status --short" # git s | git status --short 
```

## Editar el archivo de configuración de git

```sh
git config -e --global -e
```
## Eliminar un alias

```sh
git config --global --unset alias.<nombre del alias>
git config --global --unset alias.s
```

## Ver toda la configuración global de nuestro git

```sh
git config --global --list
```

## Ver especificamente los alias que tengo

```sh
git config --global --get-regexp alias
```

