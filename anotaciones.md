
# Alias

```sh
git config --global alias.l "log --oneline"
git config --global alias.ll "log --oneline --decorate --all --graph"
git config --global alias.s "status --short"
git config --global alias.c "commit -m"
```

## GIT SHOW

```sh
git show <HASH>
git show 13145e2 # Ejemplo
```

## Creando el archivo de configuración (Para solucioanr problema que no toma los estilos)

<https://vitejs.dev/config/>

# Git Reset

## 3 tipos de resets

Las fotos (commit) que le diga, las borrar y los archivos los mueve a el staging area

### GIT RESET SOFT
```sh
git reset --soft <hash>
```
### GIT RESET MIXED

Las fotos (commit) que le diga, la va a borrar y los archivos los mueve a el working directy

```sh
git reset --mixed <hash>
```

### GIT RESET HARD

Las fotos (commit) que le diga, la va a borrar y los archivos o los cambios los pierdo.

```sh
git reset --hard <hash>
```