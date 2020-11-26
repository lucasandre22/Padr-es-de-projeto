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

Compor objetos em estrutura de árvore para representar hierarquias do todo. Permite que objetos simples e composições sejam tratados uniformemente pelo cliente. É declarado um component, uma interface para os objetos na composição, que implementa comportamentos default ao longo das classes derivadas. Essas classes então são chamadas de folha e são acessadas pela interface.

##### Analogia:

Uma receita, pode ter ingredientes simples (componente direto) como alguns dos ingredientes pode ser outras receitas. Então para fazer esta receita, é preciso um componente que seria outra receita (componente composto).

##### Representação:

![Composite scheme](https://sourcemaking.com/files/v2/content/patterns/Composite.png)



### - Bridge

Separar a interface de um objeto de sua implementação. Os dois lados podem varias independentemente.

Mudanças na implementação de uma abstração não afetaria o cliente, pois a implementação está separada de sua interface.

##### Representação:

![Bridge pattern - Wikipedia](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Bridge_UML_class_diagram.svg/500px-Bridge_UML_class_diagram.svg.png)

### - Proxy

Definir um substituto para um objeto, um intermediário, que controla acesso a um outro objeto e permite que ações sejam executadas antes ou depois de um procedimento ser chamado. Criar um objeto sob demanda.

É implementado quando se quer uma referência mais sofisticada do que um simples ponteiro para um objeto.

##### Analogia:

Um cartão de crédito é um proxy de um banco, através dele, o cliente pode ter a mesma função do dinheiro sem ficar carregando muito por aí.

Um cliente deseja solicitar um serviço de um advogado, como o mesmo pode estar ocupado, é conveniente por parte do cliente avisar sua secretária que então passaria a requisição ao advogado.

Editor de texto não precisa carregar todas as imagens, podem ser carregadas de acordo com o avanço de páginas. Assim, o documento acessa as imagens de acordo com a iteração com um proxy de imagens, em tempo de execução.

##### Representação:

![A credit card is a proxy for a bundle of cash](https://refactoring.guru/images/patterns/diagrams/proxy/live-example.png)

































