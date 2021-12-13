Comandos utilizados
git init <- iniciar o repositório local;
touch (file_name) <- criar os arquivos "versoes.txt", "READ.md", ".gitignore" e "arquivo-nao-publicado";
git remote add origin (https://github.com/viniciuscarton/Senai_Atividade-UC7.git) <- informar o repositório remoto;
git remote -v <- verificar o repositório remoto;
git status <- conferir os arquivos;
git add (file_name) <- adicionar os arquivos do repositório local na staging;
git commit -m <- registrar as alterações do repositório local com uma mensagem;
git push -u origin master <- publicar os arquivos no repositório remoto;
git tag -a v1.0 -m "versão 1.0" <- criar a tag v1.0;
git push origin --tags <- publicar a tag no repositório remoto;
git checkout -b programador_1 <- criar a branch "programador_1";

** Comandos utilizados na branch
git status <- conferir a alteração do arquivo README.md;
git add (file_name) <- adicionar os arquivos do repositório local na staging;
git commit -m <- registrar as alterações no repositório local com uma mensagem;
git push -u origin programador_1 <- publicar os arquivos no repositório remoto;
