# Projeto Automação Web com Selenium

Este repositório contém projetos de automação web utilizando Selenium.

## Projetos

1. Site: https://www.saucedemo.com/ \
   Simulação de compra em site.

   O site permite utilizar 4 usuários e uma única senha. Desses 4 usernames possíveis, apenas 1 não apresenta problemas ao logar e possibilita a compra de forma fluida. 
   O código foi criado de forma que o username fosse escolhido aleatoriamente, da seguinte forma:
   - Se o usuário for o "problem_user" ou o "performance_glitch_user", o programa faz o login mas logo em seguida realiza o logout pela barra lateral esquerda, escolhendo novamente outro username a ser testado;
   - Se o usuário for o "locked_out_user", o programa tenta fazer o login mas é impossibilitado e a página é recarregada para remover os valores dos campos, escolhendo novamente outro username a ser testado;
   - Se o usuário for o "standard_user", o programa realiza a compra normalmente.
   
   Ou seja, o programa só finaliza quando consegue utilizar o username "standard_user" e finalizar a compra. A quantidade de itens a serem adicionados no carrinho é escolhida de forma aleatória, e os itens a serem escolhidos também.

2. Site: https://demoqa.com/ \
   Testes de diferentes elementos.