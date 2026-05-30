# Avaliação P2 - Linguagem de Programação - Prof. Bruno Zolotareff
Dupla: 
- Eliza Franchini Bassi Garcia
- Eloah Caroline Andrade Pereira

## Máquina de café com POO

 No sistema da máquina de café, a abstração está representada na classe Drink, que modela uma bebida de forma genérica, reunindo características comuns, como sabor e valor, sem se preocupar com os detalhes específicos de cada tipo de café. Dessa forma, a classe serve como uma base para a criação de outras bebidas no sistema.
  A herança foi utilizada na classe Cafe, que herda os atributos e métodos da classe Drink por meio da instrução extends Drink. Isso permite o reaproveitamento de código, evitando a duplicação de funcionalidades já definidas na classe pai e tornando o sistema mais organizado e fácil de manter.
  O encapsulamento é aplicado através dos métodos getValor() e setValor(), responsáveis por controlar o acesso e a modificação dos atributos do objeto. Essa prática garante maior segurança e integridade dos dados, impedindo alterações indevidas e permitindo que as informações sejam manipuladas de forma controlada.
  Em relação ao polimorfismo, esse conceito não foi implementado no código atual, pois existe apenas uma classe concreta, Cafe, derivada de Drink. Para que o polimorfismo fosse utilizado, seria necessário criar outras classes de bebidas, como Capuccino, CafeLatte ou CafeComChocolate, todas herdando de Drink. Assim, diferentes objetos poderiam ser tratados como uma bebida genérica (Drink), mas executariam comportamentos específicos de acordo com sua própria implementação. 
