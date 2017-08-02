# Teste para Gamedev Pleno.

Leia primeiro todas as instruções do projeto, faça uma estimativa de horas para o desenvolvimento e envie um email com o título "[Teste Gamedev Pleno] Estimativa de Horas" para contato@hermitcrabstudio.com.

Quando finalizar, publique o teste em sua conta BitBucket ou Github e envie um email com o título "[Teste Gamedev Pleno] Finalizado" para contato@hermitcrabstudio.com.

## Instruções

- Faça um fork desse projeto para a sua conta pessoal do BitBucket ou GitHub e use-o para subir o seu projeto.
- Siga as especificações abaixo para criar esse jogo.
- Crie um README com as instruções para compilar, testar e rodar o projeto.
- Quando finalizar, publique o teste em sua conta e envie um email com o título "[Teste Gamedev Pleno] Finalizado" para contato@hermitcrabstudio.com.

## Especificações

Para esse teste, pedimos que você desenvolva um prótótipo de jogo de embaixadas. A idéia principal é fazer uma bola pular em um primeiro toque e começar a cair com a gravidade. Ao chegar em uma determinada altura, caso o jogador clique a bola deve quicar novamente para o alto e o jogo deve contar a quantidade de bolas quicadas.

Exemplo da idéia: https://www.youtube.com/watch?v=yHlzje7TDlM

### Regras

- O jogo deve ser desenvolvido usando a Unity com a linguagem C# - pode-se criar arquivos de configurações externas se caso desejar;
- A bola deve subir e descer aleatoriamente para um dos dois lados: caso caia mais para o lado direito o jogador deve clicar em qualquer canto da tela na direita. Caso seja mais para a esquerda, o jogador deverá clicar em qualquer canto da tela mais para a esquerda;
- O jogo deverá ser feito em 3D - ou seja, não pode ser feito usando a engine 2D da Unity;
- Caso o jogador clique muito antes ou depois, ele "perde" o tempo da bola, ela deve cair no chão e depois disso aparece uma tela de Fim de Jogo, com duas opções: Reiniciar ou Voltar ao Menu;
- A altura em que a bola deve estar para o toque funcionar não deverá ser muito ampla;
- Será necessário fazer uma transição entre cenas. Então o jogo terá uma Tela de Iniciar Jogo com um tutorial de como jogar e a tela de jogo, com as condições para perder o jogo caso o jogador;
- Não é necessário ter uma animação gráfica do personagem quicando a bola;
- O jogador poderá, através de um menu de botões na tela inicial, mudar a cor/textura da bola. 2 bolas ou mais são suficientes;
- É importante que o projeto esteja configurado para funcionar em algum aparelho mobile (iOS ou Android);
- O jogo deverá ter um cuidado especial com as HUDs para funcionar em diferentes telas (16:9, 16:10 e 4:3). Ele também deverá estar configurado como Portrait.

## Considerações

Apesar de não haver um limite de tempo, recomendamos que você não gaste mais do que 8 horas nesse desafio. Para esse teste, pedimos que não utilizem nenhuma biblioteca ou asset para programação, mas você é livre para usar quaisquer tipos de assets para arte ou música. Gostaríamos de ver a sua lógica para solucionar o problema. Tente escrever o melhor código possível para que possamos avaliar o seu pull-request com mais facilidade. E lembre-se: Você vai ter que explicar pessoalmente para nós depois.

Se tiver qualquer dúvida sobre esse teste, por favor envie um email com o título "[Teste Gamedev Pleno] Dúvida" para contato@hermitcrabstudio.com.
