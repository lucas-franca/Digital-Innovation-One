# GIT e Github :octocat:

Inicia uma linha do tempo (novo projeto):

```powershell
git init
```

Prepara arquivo(s) para serem incluídos na linha do tempo: 

```powershell
git add NomeDoArquivo (ou . para tudo)
```

Incluí as alterações na linha do tempo:

```powershell
git commit -m "Mensagem do commit aqui"
```

Ver o estado das alterações (com e sem commits):

```powershell
git status
```

Mostrar alteração de um ou todos os commits:

```powershell
git show {hash} (use a hash caso queira filtrar)
```

Adicionar nova versão:

```powershell
git branch "nomeDaBranch"
```

Mudar entre as branchs:

```powershell
git checkout NomeDaBranch
```

Mostrar as alterações:

```powershell
git log
```

Aplicar alterações da branch na master:

```powershell
git merge NomeDaBranch
```

Deletar branch após aplicar na master (deve-se estar na branch):

```powershell
git branch -D
```

Adicionar repositório para envio:

```powershell
git remote add origin https://github.com/<usuario>/<repositorio>
```

Quando é o primeiro envio:

```powershell
git push -u origin master
```

Salvar User e Password:

```powershell
git config credential.helper store
```

Baixar atualizações do projeto:

```powershell
git pull
```