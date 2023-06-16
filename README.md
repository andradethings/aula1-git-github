# aula1-git-github
Este repositório é para fins de estudo do módulo git e github.


- Para criar pasta: 
mkdir nome-da-pasta

- Encontrar pasta:

cd nome-do-pasta

- Criar iniciar repositório:

git init

- Voltar a pasta anterior:

cd ..

- Criar arquivo dentro da pasta:

echo "# NOME-DA-PASTA" >> NOME-DO-ARQUIVO.EXTENSÃO (.MD, .JS, .TXT)

OU

touch NOME-DO-ARQUIVO.EXTENSÃO

- Listar arquivos e pastas:

ls

- Adicionar conteúdo (Arquivos ou pasta):

git add NOME-DO-ARQUIVO-PASTA

- para adicionar todos os arquivos/pastas:

git add .

- Para desfazer um add específico:

git reset nome-do-arquivo

- Para desfazer um add geral:

git reset

- adicionar rótulo:

git commit -m "Adicionamos pasta aula e arquivo README"




- Retornar ao arquivo para a staged area:

git reset [arquivo]



- Retorna ao último commit, mantendo as alterações feitas nos arquivos:

git reset --soft HEAD~1


- Retona ao último commit, removendo as alterações feitas nos arquivos:

git reset --hard HEAD~1


- Retorna ao commit do ID especificado, mantendo as alterações (soft) ou removendo as alterações (hard):

git reset --soft [id do commit] / git reset --hard [id do commit]



