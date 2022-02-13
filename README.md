# Git e Github

Guia prático para iniciantes.

### Download / Instalação

https://git-scm.com/download

# Etapas

- [x] Você deseja criar pontos na história da produção do seu projeto
	- git init
	- git status
	- git add nome-do-arquivo ou git add . para adicionar todos os arquivos da pasta atual
	- git commit -m

- [x] Você deseja verificar mudanças feitas no seu projeto
	- git log
	- git show id-do-log ou git show para mostrar o log mais recente

- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.
	- git branch nome-da-branch para criar uma nova branch
	- git branch para listar as branchs existentes no projeto
	- git checkout nome-da-branch

- [x] Você adiciona as novas funcionalidades no seu projeto em produção
	- git merge nome-da-branch

- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.
	- git branch -D nome-da-branch

- [x] Você quer colocar o seu projeto na nuvem
	- git remote add origin link-do-repositório
	- git remote -v para verificar os repositórios (local e remoto)
	- git push -u origin master para criar a branch main master no repositório remoto por ser o primeiro acesso
	- git push para inserir os arquivos no repositório remoto

- [x] Você vai pegar um projeto já iniciado, para trabalhar com o time
- [] Você precisa resolver um conflito

## Comandos aprendidos até aqui

- `git init` // inicia a linha do tempo
- `git add` // adiciona ou atualiza mudanças para irem para a linha do tempo
- `git commit` // adiciona um ponto na linha do tempo
- `git log` // visualiza os pontos na linha do tempo / commit
- `git status` // informa o estado das alterações do nosso projeto
- `git show` // apresenta determinado ponto na história
- `git branch` // gerenciar novas linhas do tempo
- `git checkout` // manipula as linha do tempo
- `git merge` // unir linhas do tempo
- `git push` // enviar alterações locais para o repositório remoto


## Atalho

- `git checkout -b nome-da-branch` para criar uma branch nova e começar a usar instataneamente
- `git commit -am 'mensagem do commit'` para adicionar arquivos novos/alterados e realizar o commit na sequência