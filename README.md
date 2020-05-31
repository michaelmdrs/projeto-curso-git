# projeto-curso-git
## Principais comandos utilizados no git bash. (terminal)
---
* __cd /diretório/ :__ Navega pelos diretórios.
* __cd .. :__ Volta para o diretório anterior.
* __mkdir nomeDoDiretório:__ Cria o diretório no local escolhido.
* __git init:__ Inicia o git dentro do diretório criado.
* __git clone:__ Clona o repositório do Git.
* __git add <<nome_do_arquivo>>:__ Adiciona um arquivo para ser commitado.
* __git commit -m 'nome_do_arquivo:__ Faz o commit do arquivo, importante sempre informar a descrição objetivo e curta. 
* __git push:__ Envia as modificações feitas e commitadas para o repositório remoto.
* __git pull:__ Atualiza o repositório local com as mesmas informações do repositório remoto.
* __git merge:__ Utilizada para juntar branchs a branch master de um projeto.
* __git status:__ Retorna informações atual do projeto.
* __git log:__ Retorna as informações das alterações feitas no projeto *(usuario, data, arquivo etc)*.
* __git branch <<nome_do_arquivo>>:__ Cria um *novo* ramo em paralelo ao branch principal. Essa criação é importante quando vamos fazer uma implementação na versão que está em produção e para não parar ou quebrar a versão podemos criar uma nova branch e implementar nosso código e testar. Caso funcione juntamos a alteração no branch master. 
