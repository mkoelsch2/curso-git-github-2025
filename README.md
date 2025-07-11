# Curso TMW Git & Github 2025

Um curso para iniciantes aprenderem a trabalhar com versionamente de codigo e repositorios remotos com GitHub.

Alem disso, vamos trabalhar com GitFlow ao final do curso e Visual Studio Code.

Confira tudo o que temos no nosso YouTube. E gratis! Segue o link:

[Curso Git 2025](https://youtube.com/@teomewhy)

## Fluxo de trabalho Git local

1. git checkout -b "nova branch"
2. cria ou atualiza arquivos
3. git status
4. git add .
5. git status
6. git commit -m "minha mensagem"
7. git checkout main
8. git merge nova_branch

## Fluxo de trabalho Github <-> Local (projeto proprio ou da sua empresa)

1. git clone -endereco do projeto-
2. git checkout -b "nova branch"
3. alteracoes de arquivos
4. git status
5. git add "arquivos"
6. git status
7. git commit -m "nova mensagem"
8. git push origin -nova_branch-
9. abrir pull request no github para main
10. excluir -nova_branch- origin
11. git checkout main
12. git branch -d -nova_branch-

## Fluxo de trabalho Github <> Local (projetos open-source)

1. git clone -endereco do projeto-
2. git checkout -b -nova branch-
3. alteracoes de arquivos
4. git status
5. git add "arquivos"
6. git status
7. git commit -m "nova mensagem"
8. git push origin main -nova_branch-
9. abrir pull request no github da branch fork para main do projeto original
10. excluir -nova_branch- origin
11. git checkout main
12. git branch -d -nova_branch-

Pessoas participantes:

- Marcelo Koelsch

- Teo Calvo