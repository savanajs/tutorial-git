

# Configuração global

$ git config --global user.name "Username"

$ git config --global user.email "email@hotmail.com"

# Configuração local

git config user.name "Username"

git config user.email "email@gmail.com"


# Ver as infos do repositorio

```
git status
```

# Associa o repositorio remoto ao repositorio local

```
git remote (git remote add origin https://github...)
```

# Baixa os arquivos do repositorio remoto

```
git pull (git pull origin master)
```

# Adicionar arquivos na fila do git

```
git add nomedoarquivo.js
git add .
git add --all
```

# Adicionar o codigo previamente adicionado para o repositorio local

```
git commit -m "initial"
```

# Desfazer o commit local
```
git reset --soft HEAD~1
```

# Verificar a revisão criada para o commit

```
git log
```
