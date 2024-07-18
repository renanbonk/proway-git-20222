GIT

Markdown - é uma forma de documentar texto

# titulo

## subtítulo

`git init` : Criar um repositório local

`git status` : Verificar o estado dos arquivos do repositorio

`git add <nome-arquivo.extensao>` : Adicionar arquivo para ser colocado incluído quando fechar o pacote

`git config user.name "Seu nome completo"`: Definir quem está fazendo o commit

`git config user.email "Seu email completo"` : Definir o e-mail de quem está fazendo o commit

`git commit --message "Mensagem descrevendo o que foi feito"` Definir o e-mail de quem está fazendo o commit

`git remote add origin <link-do-github>` : Configura para este repositório enviar os commits para o destino(github)

`git push origin master` : Enviar o commit da máquina para o destino (github)

echo "# proway-git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/renanbonk/proway-git.git
git push -u origin main

git remote add origin https://github.com/renanbonk/proway-git.git
git branch -M main
git push -u origin main