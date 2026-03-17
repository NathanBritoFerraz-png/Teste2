Caso o git (git bash) não funcione siga o passo a passo:

1- Faça o Login do git com este comando: git config --global credential.helper manager (Caso seja a primeira instalação do git)

2- Caso o login já esteja efetuado, na pasta selecionada faça: 

git init (para iniciar o git)

git status (apenas para verificar os arquivos da pasta)

git add . (para salvar os arquivos da pasta)

git commit -m "NOME_DO_COMMIT" (faça o commit e escolha o nome dele)

git remote add origin https://github.com/NathanBritoFerraz-png/Teste2.git (A url é o HTTPS do seu repositório)

git branch -M main (para mudar o nome de master para main do git)

git pull origin main --rebase (Caso tenha feito modificações no repositório em outra maquina (secundária) é necessário fazer este comando
para atualizar o estado da máquina (principal)

git push -u origin main (para fazer o upload de seus arquivos no seu repositório do Git Hub)

FIM
