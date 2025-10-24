# Clase 01 - Git Desarrollo Colaborativo

# Configuración inicial de GIT

```sh
git config --global user.name "Damian Silvano"
git config --global user.email "damian.silvano@gmail.com"
```

## Visualizar si la configuración impacto.

``sh
git config --global --list
```

## Editar la configuración 

``sh
git config --global -e
```

## Para ver el estado de los archivos y en que área de git estan

```sh
git status
```
## Para pasar los archivos del Working Directory al Staging Area (index área)

```sh
git add .
```
## Para pasar de SA a el LR

```sh
git commit # Editor de texto para colocar el mensaje
git commit -m "mensaje descriptivo"
```

## Diferencia entre el archivo/s que están Working Directory contra el Local Repo

```sh
git diff # compara el archivo que está en WD con el archivo que está en LR
```

## Ver el contenido del commit 

```sh
git show <hash>
git show 728f4c2
```

## Ver de manera corta el status de los archivos y en que área están"

```sh
git status --short
```

## Ver timeline de commits

```sh
git log --online #forma corta
git log # forma larga (detallada)
git log --online -<cantidad de commits> # ver una cantidad de commit especifica
```

## Subir el repo local al remoto

```sh
git push
```
