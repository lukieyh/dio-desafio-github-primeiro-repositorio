# **Introdução ao Git e ao GitHub**

1. Controle de Versão
2. Armazenamento em nuvem
3. Trabalho em equipe
4. Melhorar seu código
5. Reconhecimento

### Comandos

- cd
- dir
- mkdir
- del / rmdir

**UNIX**

- cd
- ls
- mkdir
- rm -rf
- cat
- pwd

**Como o Git funciona por baixo dos panos**

**Objetos Git**
Blobs
Trees
Commits

SHA1 As1s412…

`Blob
\0
Ola Mundo`

SHA1 hg1a8d…

`Tree
\0
blob sa4d8s texto.txt`

SHA1 487d4s…

`Commit
tree s4a5sq1
parente a98acq1
autor perkles
mensagem “inicia …”
timestamp`

O SHA1 desse commit é o hash de toda a essa informação

**Chaves SSH e Tokens**

Excutar no GIT BASH
ssh-keygen -t ed25519 -C email@gmail.com

eval $(ssh-agent -s)

ssh-add id_##### *(chave privada)*

 

Token de acesso pessoal

### Comandos com Git

- Iniciar o GIT
- Iniciar o versionamento
- Criar um commit

-git init
-git add // git add *
-git commit // git commit -m “Mensagem”

-git remote add origin *(Link)*
-git remote -v “Aponta de onde está vindo o repositorio”

-git push “Empurrar”
-git pull ~~*origin master~~  “Puxar”*

FLAGS
”ls -a” ← Visualiza arquivos ocultos 

Criando um repositório

MARKDOWN

### Commit incial

git add*

git commit - m “commit inicial” ← ***mensagem do commit***



**WORKING DIRECTORY
STAGING AREA
LOCAL REPOSITORY**