# Tutorial sobre o uso do git e github 
 
## Início rápido (Criando uma pasta no seu PC e enviando para o github)

1. Criamos um novo repositório no github.
2. Fazemos um clone do repositório para nosso ambiente local
`git clone https://github.com/alvarojh123/Tutorial_git.git`
3. Criamos um arquivo dentro da pasta anteriormente criada
* `touch nome_do_archivo`
4. Editamos o conteudo do `nome_do-archivo`
5. Mudar branch
`git branch -M "main"`
6. Mandar arquivos para stage
`git add nome_do_archivo`
7. Checar os status
`git status`
8. Fazer o commit
`git commit -m "nome_do_archivo"`
9. Publicar no github
`git push -u origin main`

Após isso o git vai solicitar colocar login e senha. Dependendo a senha não vai ser a mesma do github, senão vai ser um token que deve ser criado no Github.

Para modificações posteriores ao repośitório usar repetimos os passos 6 ao 9.




