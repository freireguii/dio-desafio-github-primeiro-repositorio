
# Repositório do desafio proposto pela DIO, sobre Git/GitHub.

Esse é um desafio de projeto proposto pela Dio sobre Git/GitHub, o primeiro de muitos.

## I)

### Comandos úteis no GIT:

-git config --global user.email "EMAIL A SER USADO" (se for a primeira vez utilizando o GIT)

-git config --global user.name "NOME A SER USADO" (se for a primeira vez utilizando o GIT)

-git remote add origin "link do repositório criado no GitHub)"

-git remote -v (lista os repositórios remotos)

-git add* (usado para adicionar tudo o que foi modificado ao staged)

-git commit -m "mensagem do commit"

-git push origin master (se houver algum problema no push, será necessário dar pull e arrumar o merge)


### CHAVES SSH E TOKENS:

A chave SSH é uma forma de estabelecer uma conexão segura e encriptada entre duas máquinas (existe sempre a chave pública e a privada).

->Processo para gerar uma chave SSH: 

i) ssh-keygen 

ii) irá pedira para colocar uma senha

iii) navegar até a pasta usando o comando cd/_________

iv) depois de estar na pasta é necessário listar os arquivos com o comando ls

v) logo após, utilizando a chave pública (.pub), usar o comando cat____nome da chave pública

vi) pegar essa chave e colocar no GITHUB

vii) após pegar a chave e colocar no GITHUB é necessário ativar o agente que irá gerir as chaves; eval $ (ssh-agent -s)

viii) após ser gerado esse agente é necessário passar o a chave para ele, através do caminho onde está a chave privada; ssh-add______caminho da chave privada

## II)

### Links Úteis:

[Sintaxe Básica MarkDown](https://markdown.net.br/sintaxe-basica/)

