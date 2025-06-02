# Curso de Git e GitHub TeoMeWhy 2025

Um curso para iniciantes aprenderem a trabalhar com versionamento de códigos e repositórios remotos com GitHub.

Além disso, trabalha-se com GitFlow ao final do curso, bem como Visual Studio Code.

O curso no YouTube é maravilhoso. Confira!

#Fluxo de trabalho (local).

1. git checkout -b	-> cria ou atualiza arquivos
2. git status		-> mostra se algum arquivo foi alterado ou não
3. git add		-> <arquivos; ou . (pasta inteira)>
4. git status
5. git commit -m "minha mensagem"
6. git checkout <branch>
7. git merge nova_branch

# Fluxo de trabalho Local <> Github (projeto próprio ou da empresa)
1. git remote -v (saber se está conectado no github)
2. cria repositório no github
3. git remote add origin <link do repositório github>
4. git push origin main (envia o que está no repositório logal para o github)

pula para 6. ou;

5. git clone <link do repositório?>
6. git checkout -b <nova_branch>
7. alterações de arquivos
8. git status
9. git add arquivos
10. git status
11. git commit -m "nova mensagem"
12. git push origin <nova_branch>
13. abrir Pull request no GitHub para main
14. excluir <nova_branch> origin
15. git checkout main
16. git branch -D <nova_branch>

# Fluxo de trabalho GitHub <> Local (projetos open-source)
1. Fork do projeto para seu próprio github
2. git clone
3. git checkout -b <nova_branch>
4. alterações de arquivos
5. git status
6. git add arquivos
7. git status
8. git commit -m "nova mensagem"
9. git push origin <nova_branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>
