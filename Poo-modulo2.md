## Os Pilares da Programação Orientada a Objetos
# Abstração
Na POO, damos o nome de abstração para o processo de aproximar o mundo real do mundo da programação, sendo o seu objetivo, simplificar um problema difícil. Para isso, a abstração leva em conta os aspectos importantes de um determinado ponto de vista e desconsidera os aspectos restantes.

Assim como representado na imagem, a abstração é a criação de uma classe abstrata, que é uma classe incompleta, como se fosse um quebra-cabeça. Assim, esta classe não permite a criação de instâncias e obriga a implementação de todos os métodos da classe assinados como ‘abstract’

Resumindo, a abstração se concentra apenas nas informações que são importantes para o seu propósito. Dessa forma, ela mantém suas classes o mais simples possível, concentrando-se apenas no que é importante para uma determinada finalidade.

A abstração nada mais é do que você abstrair coisas, ou seja, quando você tem algo muito grande, mas não há necessidade de cadastrar todas as informações.

Vamos supor que você está desenvolvendo um código com a classe “ser humano”. Essa classe é composta por inúmeras variantes (atributos), como por exemplo: altura, peso, cor da pele, cor do olho, CPF, nome, endereço etc.

O objetivo do seu código é tratar o "ser humano" como cliente. Para cada cliente é preciso obter as informações de CPF, Nome e Endereço. As outras informações que pode obter na classe "ser humano", como cor da pele, cor do olho, altura, peso etc. não são importantes para esta situação.

Portanto, podemos abstrair estas informações e considerar somente o que importa.

# Encapsulamento
Agora que já entendemos o que é abstração, vamos aprender sobre o encapsulamento. Ao encapsular algo, você está colocando um objeto dentro de um recipiente, igual a um remédio de cápsula.

O encapsulamento é uma das principais técnicas da programação orientada a objetos. Quando você encapsula um objeto, você está criando uma proteção e um padrão. Com isso, o propósito é de proteger o desenvolvedor do código e o código do desenvolvedor.

Assim, quando você encapsula um objeto na POO, você está criando moldes padrão que fazem com que o conteúdo do objeto não importe. Você está determinando que o resultado será sempre o mesmo.

*Conceito de encapsulamento:* 
É a ação de ocultar partes independentes da implementação, permitindo construir partes invisíveis ao mundo exterior.

Ok, mas se no fim eu estou ocultando detalhes do código, como que ele vai funcionar? A POO permite que você converse com esta cápsula, trocando informações entre o mundo externo e o objeto por meio de mensagens. Portanto, ao enviar mensagens para essa cápsula, você vai obter uma resposta, sem precisar entrar nela.

Mas não podemos esquecer de um importante detalhe! Para que haja esta troca de mensagens, precisamos desenvolver uma interface. É a interface que permite esta comunicação com o mundo externo.

*Conceito de interface:*
É uma lista de serviços fornecidos por um componente. É o contato com o mundo exterior, que define o que pode ser feito com um objeto de determinada classe. Ou seja, a interface é uma classe composta apenas por métodos (não possui atributos).

Encapsular não é obrigatório na POO, mas é uma ótima prática para produzir classes mais eficientes.
No encapsulamento esse conceito é muito importante, já que os métodos da classe encapsulada serão abstratos, ou seja, os métodos abstratos são previstos ali, mas não são implementados na interface.

# Herança
Outro pilar da POO é a herança. Assim como no mundo real, a herança na POO também diz respeito à ação de herdar. Ela nada mais é do que um objeto poder ser criado em uma outra classe, levando consigo todos os atributos já existentes em sua classe de origem.

A herança é uma maneira de reutilizar o código já existente em uma nova classe. Desta forma, o código é aprimorado com novas e melhores capacidades. Ao utilizar este pilar, os programadores economizam tempo de desenvolvimento de um programa, já que eles reutilizam códigos já testados e aprovados.

No organograma abaixo, mostra um exemplo de herança. Ao analisá-la, percebe-se que as classes herbívoro, carnívoro e onívoro podem herdar quaisquer atributos necessários da classe animal: tamanho, raça, cor etc. Da mesma forma, as classes leão, hiena, homem e coelho podem herdar atributos das classes herbívoro, carnívoro ou onívoro.

conferir imagem "Herança"

# Polimorfismo
O polimorfismo é um pilar da POO que é utilizado para que duas classes façam uso do mesmo método, implementando-o de formas diferentes. Ele permite que o programador desenvolva o código de forma ampla ao invés de perder muito tempo no desenvolvimento de códigos específicos. Ou seja, o polimorfismo permite que sistemas sejam escritos de forma a processar objetos que compartilham a mesma superclasse (classe já existente), como se eles fossem parte direta dela.

Se pensarmos na superclasse Animal, estabelecemos o método “emitir o som do objeto animal”, ou seja, os objetos pato, cachorro e gato, por exemplo, devem emitir um som ao comando do método, mas cada um fará isso de um jeito diferente.

Agora observe no fluxo apresentado, mais um exemplo de que o polimorfismo foi este processo de implementar métodos (mover).

conferir imagem "Polimorfismo"

