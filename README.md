# Padrões de projetos

### - Adapter

Função de permitir que uma classe que tenha uma interface diferente possa ter a comunicação com outra classe "gerenciadora". Ao exemplo de um adaptador de tomada que permite que entradas diferentes encaixem em uma entrada específica. Uma classe unificadora de interfaces.

##### Objetivos e funcionalidades:

- Fazer com que classes antigas sejam traduzidas para novos componentes, que tenham comunicação com as novas
- Clientes chamam métodos de uma classe intermediadora que acessa os métodos da classe com interface diferente
- Promove uma abordagem traduzida a uma classe existente

### - Facade (fachada)

Define uma interface única de fachada de um nível mais alto para um subsistema, tornando estes mais fáceis de serem usados. Define uma interface unificada, que abrange todas. Uma integração a todos os subsistemas.

##### Analogia: 

Existe uma empresa com vários departamentos e que, um cliente deseja modificar um pedido feito anteriormente. Ficaria muito mais fácil se o mesmo comunicar-se com uma recepcionista, que o direcionaria para o departamento correto para que a comunicação fosse feita.

Outro exemplo seria o serviço de emergência 911 dos EUA, em que você fala com uma "interface" de um nível mais alto e que direciona-o para o serviço correto, sem que seja necessário memorizar vários números diferentes.

##### Objetivos e funcionalidades:

 - Reduzir a dependência de subsistemas
 - Reduzir a complexidade
 - Interface única para todos os recursos e funcionalidades dos sub-sistemas
 - Possibilitar fácil especialização do sistema todo para cada cliente

##### Representação:

![Facade (Java Design Pattern) - explanation and example](https://www.learn-it-with-examples.com/development/java/java-design-patterns/pictures/9-java-facade-design-pattern/1-facade-java-design-pattern-uml-diagram.png)

### - Composite

Compor objetos em estrutura de árvore para representar hierarquias do todo. Permite que objetos simples e composições sejam tratados uniformemente pelo cliente.

##### Analogia:

Uma receita, pode ter ingredientes simples (componente direto) como alguns dos ingredientes pode ser outras receitas. Então para fazer esta receita, é preciso um componente que seria outra receita (componente composto). 

##### Representação:

![Composite scheme](https://sourcemaking.com/files/v2/content/patterns/Composite.png)



### - Bridge

Separar a interface de um objeto de sua implementação.

