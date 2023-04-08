# Lista 01 - Exercicios teoricos. 


1 - Nas suas palavras o que é versionamento de código? Porque é necessário versionamento de código?

    - Versionamento de código é criar estados do código que está em desenvolvimento. O versionamento de codigo é necessario pois nos permitir ter um controle mais facil do codigo que está sendo desenvolvido, nos permitindo documentar, salvar e acessar todas as alteracoes feitas no codigo. 

2 - Fazendo parte de um time em que a todo momento novo código está sendo inserido, é possível que eu saiba quem foi a pessoa que escreveu uma determinada parte do código usando git? Se sim, descreva como.

    - Sim. É possivel é ver os autores de cada linha de codigo em um arquivo utilizando o comando 'git blame <file>'. Com o git blame é possivel selecionar intervalos de linhas utilizando opçao -L e passando o intervalo desejado para o resultado. Por padrao o git blame exibe o nome do autor, mas é possivel exibir o email do autor da linha passando a opcao -e. 

3 - Qual a diferença entre git e GitHub/GitLab/BitBucket etc?

    - Git é o sistema de controle de versão e fazemos o versionamento localmente. Já o GitHub/Gitlab/Bitbucket nos permite hospedar nosso codigo com todo os registros do versionamento feito pelo git localmente e gerenciar os repositorios de maneira geral.

4 - Qual a diferença de uma linguagem compilada e uma linguagem interpretada? O que é uma linguagem de alto nível?

    - Uma linguagem compilada tem seu codigo transformado em codigo binario antes de poder ser executada por um computador. Já uma linguagem interpretada, possui um interpretador que executa e transforma o codigo, linha por linha, em codigo binario. Esse processo acontece na hora em que executamos um arquivo contendo as instrucoes.

