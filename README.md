# tips útils a github

## Problemes a l'hora de fer un ```git push``` amb tema de permisos a Windows

![credential_manager.png](/images/credential_manager.png)


## Renombrar una carpeta

Si volem renombrar la carpeta **Presentacions** a **presentacions**:
```bash
$ git ls-files
$ git mv Presentacions presentacions_temp
$ git add .
$ git commit -am "canvi a presentacions_temp"
$ git push origin master
$ git mv presentacions_temp presentacions
$ git add .
$ git commit -am "canvi a presentacions"
$ git push origin master
```
