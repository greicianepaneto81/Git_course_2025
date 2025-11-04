# Dicionário de conceitos

## O que é git?
**git** é um software de controle de versão, como uma linha do tempo, que gerencia alterações nos scripts/documentações.

## O que é github?
**github** é uma plataforma web que serve como um repositório remoto para projetos Git. É a rede social para programadores. Funciona como backup da linha do tempo.

## Áreas conceituais

- área de desenvolvimento: é o local do meu computado que consta a pasta que foi criadas para o git, onde vc edita os arquivos no seu computador. (é um arquivo colocado na pasta)
- area_de_staging_:  area e preparo para triagem do que será enviado para o git. (é o arquivo que vc colocou na pasta e foi previamente visto pelo programa git)
- repositório local: é o local onde vao os comites, as versões dos meus arquivos e projetos existem. este é encontrado como forma de arquivo na pasta .git que deve ser protegida com a minha própria vida, perdeu este arquivo, perdeu tudo se nao estiver salvo no github (é o arquivo visto pelo git e atualizado que aparece na linha do tempo)

# Rotina básica do git
save
git status (conferir em qual área conceitual meu arquivo está)
git add nomedoarquivo
git commit -m "mensagem relevante"
git push (somente quando vc quer mandar os arquivos para o github pra salvar e aparecer lá)

## Quando usar git status e como entender os resultados
Usar o comando git status para saber o status dos arquivos e ver as versões que eles estão (se estão atualizados)

uncommited = não foi atualizada a versão e não está com comentários - o arquivo encontra-se na area staging, o que significa que eu já fiz "git add" 
unstaged = arquivo com mudanças que não foram enviadas para a área staging, o que significa que eu preciso dar git add e git commit -m
untraked = existe um arquivo novo sem nenhuma versão salva


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
git push é o comando que manda os arquivos para o github e salva lá

# no github
logar e ir no profile ... repositório ...novo repositório
preencher somente o nome do repositorio que vai aparecer e se vai ser publico ou privado, nao clicar em mais nada e criar
vai ser criado um comando que será a ponte da pasta no seu computador com o github
por ex. git remote add origin https://github.com/greicianepaneto81/Git_course_2025.git
este comando vc copia e roda no terminal do vscode dentro da pasta do seu projeto
depois vc pede o git do computador para mandar pro github com o comando "git push"
as vezes dá uns bugs que precisam ser resolvidos
isso irá gravar uma copia no github - se vc atualizar algo via github vc precisa mandar pro seu computador via "git pull"

# git push e git pull
só servem para vc enviar e trazer arquivos que vc já tem no seu computador

# git clone
vc usa quando quer baixar os arquivos de um projeto de outra pessoa que está no github para fazer colaboração. mas antes vc tem que pedir a colaboração em settings, collaborators e achar ele e enviar o pedido. o pedido vai por email e ele precisa aceitar

# git tag 
vc adiciona um tag (uma observação, como versao 01, 02) para um commit especifico ou o ultimo

#
git log mostra todas as modificações que foram feitas

# comandos
pwd monstra onde está
cd entra na pasta que vc escreve depois
cd .. é sair

# arquivo readme.md (abre como arquivo de texto mas salva com extensão md)
arquivo que explica o que é o projeto, o que faz, como usa e como instala
é um sumário
pode ser para um programa, um curso, etc

# arquivo .gitignore
é um arquivo sem extensão (vc abre como arquivo texto mas nao coloca extensão)
neste arquivo vc coloca o nome dos arquivos que vc quer que ele ignore, tipo arquivos de sequenciamentos, backup, etc, lembrando de colocar a extensão
se colocar asterisco =  *.csv vai ignorar todos os arquivos csv , !dataset.csv ignora todos com exceção deste, # faz um comentário
nao precisa fazer o commit pq vc quer que estes arquivos sejam ignorados

# Obs.

arquivo .md é um arquivo mark down usado no git

$ git init - quando rodado dentro de uma pasta, transforma esta pasta no repositorio do git

no terminal precisa estar usando wsl no windows, se for linus zbash ou wsl

