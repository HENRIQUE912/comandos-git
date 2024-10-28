Meu Projeto Git
Bem-vindo ao meu repositório! Aqui estão os passos para configurar o Git e enviar seus arquivos para o GitHub. Siga as instruções cuidadosamente.

Configurações Iniciais

Antes de começar, você precisa configurar seu nome de usuário e e-mail. Execute os seguintes comandos apenas uma vez:
$ git config user.email "seuemail@example.com"
$ git config user.name "usuariodogit"

Iniciar o Processo
 Agora, vamos iniciar o repositório e adicionar seus arquivos.

1.Iniciar o repositório:
$ git init

2.Verificar o status dos arquivos:
Mostra os arquivos que ainda não estão no repositório.
$ git status

3.Adicionar arquivos ao repositório:
Adiciona todos os arquivos para serem rastreados.
$ git add .

4.Criar a branch principal:
Nomeia essa branch como "main".
$ git branch -M main

5.Fazer o primeiro commit:
Envie os dados com uma mensagem descritiva.
$ git commit -m "Exemplo – exercícios sobre operadores aritméticos"

Conectar ao Repositório Remoto
Agora, vamos conectar seu repositório local ao repositório remoto no GitHub.

1. Adicionar o repositório remoto:
Copie o link do seu repositório do GitHub e execute:
$ git remote add origin https://github.com/seunome/nomerepositorio.git

2. Enviar os arquivos:
Agora, envie os dados para o repositório remoto.
$ git push origin main

Observação: Na primeira vez, ele irá pedir seu usuário e senha do GitHub.


Resolvendo Erros

Se ocorrer algum erro ao enviar os arquivos, você pode tentar o seguinte comando:
$ git pull origin main --allow-unrelated-histories

Após isso, tente enviar novamente:
$ git push origin main


