# Git e Github

## 01- O que é Git?

- Sistema de controle de versões
  - ajuda a manter um histórico de alterações
  - ajuda a ter controle sobre cada alteração no código
  - ajuda para que uma alteração de determinada pessoa não influencie na alteração realizada por outra
- `git init`: cria um repositório Git
- `git status`: mostra o estado do nosso repositório 


## 02- Iniciando os trabalhos

- `git config user.name "Nome"`
- `git config user.email "seu@email.com"`
- `git commit -m mensagem`: salva um estado ou versão do nosso código
- `git add arquivo`: adiciona o arquivo ao git
- `git log`: verificar o histórico de commits

```git
git log --oneline
git log -p
git log --pretty="parametros de formatação"
```

- **.gitignore**: para não monitorar arquivos
