<<<<<<< HEAD
# Fundamentos

Repo de fundamentos das aulas dos stags 2022 - Atualizado Jade / Luiz Paulo

# O QUE SIGNIFICA .gitignore? Vamos explicar!

.gitignore informa ao git quais arquivos (ou padrões) deve ignorar. Usado para evitar a confirmação de arquivos transitórios do diretório de trabalho que não são úteis para outros colaboradores, como produtos de compilação, arquivos temporários criados por IDEs e por aí vai... Outros detalhes nesse link: https://www.atlassian.com/br/git/tutorials/saving-changes/gitignore

# CURIOSIDADES:

1. Você tem acesso a todos os arquivos em seu repositório local, quer esteja trabalhando em um ou vários arquivos.
2. Você pode visualizar repositórios públicos sem uma conta do Bitbucket (http://www.luizguarino.com.br/site/bitbucket/BitBucket%20-%2001%20Cadastro.pdf#:~:text=Acesse%20o%20site%20https%3A%2F%2Fbitbucket.org%2Faccount%2Fsignup%2F%20e%20crie%20uma%20conta.,de%20usu%C3%A1rio%20para%20a%20sua%20conta%20do%20BitBucket.) se tiver a URL desse repositório.
3. Cada repositório pertence a uma conta de usuário ou a uma equipe. No caso de uma conta de usuário, esse usuário é o responsável pelo repositório. + No caso de uma equipe, essa equipe é responsável por ele.
4. O responsável pelo repositório é a única pessoa que pode excluir o repositório. Se o repositório pertencer a uma equipe, um administrador pode excluir o repositório.
5. Um projeto de código pode consistir em vários repositórios em várias contas, mas também pode ser um repositório único de uma conta única.
6. Cada repositório tem um limite de espaço de 2 GB, mas recomendamos manter seu repositório com no máximo 1 GB.
7. Só pra lembrar de estudar mais...
=======
# Recapitulando

**ssh-keygen** - Cria uma chave publica de ssh, no linux ele cria a chave publica na pasta .ssh na home. A chave e criada como id_rsa.pub e é importada nas configurações da pagina do github.

**git clone** - Pega os arquivos que estao no repo e "baixa" para o diretorio local.  
**git remote -v** - Mostra o endereço do nosso repo.  
**git pull** - Pega as atualizações do repo remoto.  
**git add** - Add um arquivo para a fila de modificações.  
**git commit -m**- Cria um pacote com as modificações alteradas e atribui a esse pacote um nome e um identificador chamado hash.  
**git push origin (nome da branch onde vc se encontra)**- Pega todas as alterações que foram devidamente commitadas e envia para o nosso repo.  
**git status** - Mostra se há alguma modificação local e em qual branch estamos.  
**git log** - Mostra o historico dos ultimos commits realizados no repo, mostra o nome, autor e hash do commit.
>>>>>>> 6d599fa76a7e8079c9e2b7cd20fca64027a343b5
