# Dicionário de conceitos

## O que é git?
**git** é um software de controle de versão, como uma linha do tempo, que gerencia alterações nos scripts/documentações.

## O que é github?
**github** é uma plataforma web que serve como um repositório remoto para projetos Git. É a rede social para programadores. Funciona como backup da linha do tempo.

## Áreas conceituais

- área de desenvolvimento: é o local do meu computado que consta a pasta que foi criadas para o git, onde vc edita os arquivos no seu computador.
- area_de_staging_:  area e preparo para triagem do que será enviado para o git.
- repositório local: é o local onde vao os comites, as versões dos meus arquivos e projetos existem. este é encontrado como forma de arquivo na pasta .git que deve ser protegida com a minha própria vida, perdeu este arquivo, perdeu tudo se nao estiver salvo no github

# PASSO A PASSO DO CURSO
Criar uma pasta no desktop que será usada pelo git
Abrir o vscode, entrar na pasta que vc criou dentro do vscode para ele reconhecer a pasta (file, open folder e abrir a pasta que vc criou). Abrir um terminal executando o wsl dentro do vscode
abrir um arquivo novo -  new file - e gravar com ".md" dentro da pasta. Este arquivo tem os scripts que vc quer salva. salvar sempre o seu arquivo - control S.
Entrar na pasta que vc criou pelo terminal do vscode na linha de comando
usar o comando "git init" para iniciar o git dentro da sua pasta na linha de comando
para salvar um ponto (versao) na linha do tempo - git add nomedoarquivo.md - isso vc faz a cada versao do seu arquivo, pois ele cria um backup do arquivo modificado na sua linha do tempo
para informar a mudança que houve no arquivo usar o comando git commit -m "definicao de conceitos de git e github" - indica o nome da versao que será salva na linha do tempo - colocar a informação do que foi modificado pra vc lembrar depois - pq, como , efeitos e limitações - mensagem mais completa possível entre aspas
pode ser que ele te peça para colocar seu nome e email, ele indicará qual comando usar
a cada vez que for adicinada uma versao na linha do tempo precisa do comando "git add" e depois o "git commit -m"




# comandos
pwd monstra onde está
cd entra na pasta que vc escreve depois
cd .. é sair


# Obs.

arquivo .md é um arquivo mark down usado no git

$ git init - quando rodado dentro de uma pasta, transforma esta pasta no repositorio do git

no terminal precisa estar usando wsl no windows, se for linus zbash ou wsl

