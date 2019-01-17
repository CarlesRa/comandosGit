# Comandos
## Inicialitzar i linkar repositori
```
git init
git add README.md
git commit -m "[missatge]" .
git remote add origin "[url del repositori]"
git push -u origin master

```
## Automatitzar clau
### Per a sempre
```
git config --global credential.helper store
```

### Per un temps determinat
```
git config --global credential.helper 'cache --timeout=3600'
```
## Important!
### Hay que crear un arxiu de excepcions ".gitignore"
#### Pàgina per autogenerar-lo
```
https://www.gitignore.io/
```
