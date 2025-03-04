### Material de consulta 

## Comandos comuns usados em situações diversas:

### Iniciar a area de trabalho
| *Comando* | *Descrição* |
|-----------|-------------|
| `clone` | Clona um repositório em um novo diretório. |
| `init` | Cria um repositório Git vazio ou reinicia um ja existente. |

### Trabalhando com alterações atuais
| *Comando* | *Descrição* |
|-----------|-------------|
| `add` | Adiciona o conteúdo do arquivo ao incice.|
| `mv`| Move ou renomeia um arquivo, diretório ou symlink. |
| `restore` | Restaura arquivos da arvore de arquivos. |
| `rm` | Remove arquivos da arvore de trabalho e do indice. |

### Examina o historico e o estado
| *Comando* | *Descrição* |
|-----------|-------------|
| `bisect` | Utiliza busca binaria para localizar o commit que introduziu o bug. |
| `diff` | Apresenta alterações entre os commits, commit e arvore de trabalho, etc. |
| `grep` | Imprime linhas que corresponder a um padrão. |
| `log` | Apresenta os logs dos commit. |
| `show` | Apresenta varios tipos de objetos. |
| `status` | Apresenta o estado da arvore de trabalho. |

### Crescer, marcar e ajustar seu histórico comum
| *Comando* | *Descrição* |
|-----------|-------------|
| `branch` | Lista, cria ou deleta branches. |
| `commit` | Grava alterações no repositório. |
| `merge` | Agrupa duas ou mais historicos de desenvolvimento. |
| `rebase` | Reaplicar commits em cima de outra dica base. |
| `reset` | Redefine o HEAD atual a um estado especifico. |
| `switch` | Muda de branch. |
| `tag` | Cria, lista, deleta ou verifica a tag de um objeto assinado com GPG. |

### Colaboração
| *Comando* | *Descrição* |
|-----------|-------------|
| `fetch` | Baixa objetos e referencias de outro repositório. |
| `pull` | Busca e integra com outro repositório ou branch local. |
| `push` | Atualiza referencias remotas junto com objetos associados. |


### Comandos uteis ja utilizados (Reload no cerebro)

`git config --list`
>

`cat ~/.gitconfig`
>

`git init`
>

`git status`
>

`git add ARQUIVO`
>

`git commit`
>

`git commit -m "TEXTO"`
>

`git log`
>

`git log -p ARQUIVO`
>

`git commit -a -m "TEXTO"`
>

`git checkout COMMIT_ID`
>

`git checkout main`
>

`git reset --soft HEAD~1`
>

`git reset --hard`
>

`git checkout HEAD`
>

`vim .gitignore` - https://drive.google.com/file/d/1I0uTKeMAEOX2FA8OgUDx5gMJZrbaa4FB/view
>

`git reset --hard COMMIT_ID`
>

`git reset`
>

`git branch BRANCH_NAME`
>

`git branch`
>

`git checkout BRANCH_NAME`
>

`git branch -d BRANCH_NAME`
>

`git branch -D BRANCH_NAME`
>

`git checkout -b BRANCH_NAME`
>

`git merge BRANCH_NAME`
>

`git rebase BRANCH_NAME`
>

`git cherry-pick COMMIT_ID`
>

`git tag`
>

`git tag -a TAG -m "MENSAGEM"`
>

`git tag -d TAG`
>

`git remote add REMOTE_REPO CAMINHO_REPO`
>

`git branch -M BRANCH_NAME`
>

`git push -u REMOTE_REPO BRANCH_NAME`
>