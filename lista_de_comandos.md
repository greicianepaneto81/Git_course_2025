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

## Pergunta pro git o status de cada um dos arquivos da pasta (se os arquivos estão atualizados e com comentários)
git status

# o comando para ver o histórico das versões 
git log
no final aperta a letra Q de quit para voltar para a linha de comando

git log -n <colocaonumero> vc só vê as "n" ultimas atualizações
git --help
git --abbrev-commit

