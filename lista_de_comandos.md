# Lista de comandos:

## Como inicializar um repositorio git
git init

## Como verificar e modificar as configurações do git
git config --global --list
git config --global user.name (meu nome ou nome de usuário do github)
git config --global user.email (meu email cadastrado no github)

## Rotina básica do git
git add nomedoarquivo.md ou .txt ou .py ou .pdf, etc (vc pode adicionar vários arquivos de uma unica vez em lista)
git commit -m "mensagem relevante"

## Rotina não tão basica do git com github

1. situação 01: atualizei meus arquivos no repositório local e fiz o backup no github
   salvei
   git add arquivo.md
   git commit -m "linda mensagem"
   git push

2. situação 02:
   a)atualizei meus arquivos no github e quero sincronizar com o repositorio local no meu computador
   b)meu colaborador atualizou o arquivo e eu quero sincronizar no repositoria local no meu computador

3. situação: O mundo indeal
   git pull
   editar os arquivos
   git status
   git add arquivo.md
   git commit -m "linda mensagem"
   git push
5. 

## Pergunta pro git o status de cada um dos arquivos da pasta (se os arquivos estão atualizados e com comentários)
git status

# o comando para ver o histórico das versões 
git log
no final aperta a letra Q de quit para voltar para a linha de comando

git log -n <colocaonumero> vc só vê as "n" ultimas atualizações
git --help
git --abbrev-commit


