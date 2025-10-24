# Clase 02 - Git Desarrollo Colaborativo

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

# Agregar la url del remoto al local

```sh
git remote add <alias> <url-al-remoto>
git remote add origin https://github.com/Damiansilvano2025/80746-git-desarrollo-colaborativo.git
```

## Controlar que se haya colocado la url en el local

```sh
git remote
git remote -v # más detalle
```


## Para subir al repositorio remoto

```sh
git push -u <remoto> <rama>
git push -u origin main # Relacionar la rama local con la remota
git push " Una vez asociadas (relacionadas) no necesito volver a indicarle el remoto y la rama 
```
