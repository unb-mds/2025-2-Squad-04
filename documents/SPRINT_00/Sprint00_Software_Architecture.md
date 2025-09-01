# Arquitetura de Software

## O que é arquitetura de software?

Após estudos sobre o tema, a arquitetura de software é a forma como se planeja lidar com as partes importantes do projeto, definidas pelos desenvolvedores.

Ela define o que é o sistema em termos de componentes computacionais e, os relacionamentos entre estes componentes, os padrões que guiam a sua composição e restrições.

A arquitetura é de suma importância para o software, pois sem ela você pode deixar o codigo desorganizado e sem saber o caminho para desenvolver seu software, fazendo com que atrase o fim do seu projeto.

[Link para o artigo](https://martinfowler.com/architecture)

[Link para o artigo](https://www.inf.ufpr.br/andrey/ci163/IntroduzArquiteturaAl.pdf)

## O processo de arquitetura de software

- Elaboração do modelo de negócio - envolve analisar custo, tempode desenvolvimento, restrições de mercado, interfaces com outros sistemas, etc.

- Entendimento dos requisitos: levantamneto de requisitos e modelo de dóminio.

- Criação ou selção de uma arquitetura: identificação dos componentes e sua interações, das dependências de construção e tecnologias que apoiam a implemntação.

- Representação de arquitetura e divulgação: para permitir aos desenvolvedores e testadores o entendimento da arquitetura.

- Implementação da arquitetura, seguindo seus protocolos e estruturas.

- Análise e avaliação: verificar a adequação da arquitetura, regustrando impactos, risco e dificuldades, o que servirá para evolução da arquitetura 

[Link para o artigo](https://www.inf.ufpr.br/andrey/ci163/IntroduzArquiteturaAl.pdf)

## Importância da Arquitetura 

- Ela atua como uma estrutura a fim de checar o atendimento aos requisitos do sistema

- Suporte no controle de gastos e gerência da complexidade do sistema

- Reduz o intervalo entre especificação e implementação 

- Reduz riscos associados à construção do software

- Serve como base para criar um entendimento mútuo entre os participantes 

- Guia para o projetp de sua implementação, teste e implatação do sistema 

## Definição da Arquitetura 

__Engenharia de requisitos como subsídio à arquitetura__

A fase da engenharia de requisitos fornece a base necessária para a definição da arquitetura do sistema. dessa etapa são obtidos:

- O processo do negócio modelado;

- O planejamento estratégico das versões;

- Os requisitos de cada versão;

Essas informações permintem ao arquiteto compreender o dominío da aplicação e alinha as decisões arquiteturais às necessidades do projeto.

__Importância da definição da arquitetura__

A definição da arquitetura deve atender a critéros que garantem a evolução e a longevidade do sistema, tais como:

- Facilitar o reúso em diferentes níveis;

- Permitir alterações localizadas, sem afetar outras partes do sistema;

- Viabilizar a adição de novas funcionalidades semimpacto nas funcionalidades já existentes;

- Apoiar a evolução contínua dp sistema, prolongando sua vida útil.

__Estratégia na definição da arquitetura__

A definição da arquitetura está baseada na seleção das alternativas mais adequadas ao domínio da aplicação. Para isso, é fundamental:

- Reutilizar soluções e estratégias previamente validadas;

- Adotar frameworks, estilos arquiteturais, padrões de projeto e linguagens de descrição de componentes;

- Basear-se em boas práticas consolidadas, garantindo consistência e qualidade no desenvolvimento.

[Link para o artigo](https://www.inf.ufpr.br/andrey/ci163/IntroduzArquiteturaAl.pdf)

__Conceito de padrão__

- Um teplate de solução para um problema recorrente que seja comprovadamente útil em um determindao contexto

- Um padrão de software é instanciado através da vinculação de valores e seus parâmetros.

- Os padrões podem existir em várias escalas níveis de abstração; por exemplo, como padrões de arquitetura, padrões de análise, padrões de projeto, padrões de teste e idiomas ou padrões de implementação.

__Definição__:“um padrão expressa uma solução reutilizável descrita através de três partes: um contexto, um problema e uma solução”. (GAMMA et al., 1995). 

- Contexto:  estende o problema a ser solucionado, apresentando situações de ocorrência desses problemas.

- Problema: determinado por um sistema de forças, onde estas forças estabelecem os aspectos do problema que devem ser considerados. 

- Solução: mostra como resolver o problema recorrente e como balancear as forças associadas a ele.

__Padrões em ES__

- Eles permitem que desenvolvedores possam recorrer a soluções já existentes, para solucionar problemas que normalmente ocorrem em desenvolvimento de software.

- __Padrões Arquiteturais__: expressam um esquema de organização estrutural fundamental para sistemas de software.(BUSCHMANN et al., 1996)

## Estilos de arquitetura 

- Uma arquitetura de software pode adotar um estilo de arquitetura, que estabelece um conjunto de padrões e restrições, reduzindo as opções de implementação e promovendo uniformidade na solução. Esse estilo é definido pela escolha de componentes e conectores que servirão como base estrutural do sistema. Em essência, os estilos de arquitetura representam esquemas de organização que determinam os principais componentes, suas responsabilidades e a forma de interação entre eles. Cada estilo atende a diferentes atributos de qualidade, e a escolha adequada depende da análise de quais atributos são mais relevantes para a solução desejada.

- A arquitetura de um sistema pode aderir a um ou mais estilos arquiteturais

- Um estilo define os tipos de elementos que podem aparecer em uma arquitetura e as regras que regem a interconexão entre estes elementos.

- Esses estilos podem simplificar o problema de definição de arquiteturas de sistema.

__Exemplo de estilos arquiteturais__

- Cliente servidor 

- Camadas 

- Filtros e dutos(pipes and filter)

- Repositório 

- Orientado a eventos (publisher/subscriber)

- Objetos distribuídos

## Definição dos estilos de arquiteturas

__Layers (camadas)__

- Na arquitetura Model-View-Controller (MVC), os sistemas são desenvolvidos nessas três camadas. O model estabelece regras de negócio e a interação entre o back-end e o banco de dados (recepção ou envio de dados). O view define e gerencia como os dados são apresentados ao usuário (parte ligada fortemente ao 
front-end). Por último, o controller é responsável por ser o nível intermediário entre o model e o view, ao receber dados do usuário, e os manipula e reage de acordo com a necessidade do programador.

__SOA (Orientada a serviço)__

- Na arquitetura orientada a serviço, divide-se o sistema em serviços independentes, e depois, criam-se interfaces para que os serviços interajam entre si.Em analogia, estamos preparando um prato de almoço. Onde os serviços são, por exemplo, a região da proteína, a região do carboidrato, e a fibrosa. A interface seria, portanto, a própria louça que abriga essas 3 regiões do seu prato de almoço. 

__Pipers  and  Filters (Filtos e dutos)__

- Nessa, o dado recebido pelo sistema e cada componente independente do sistema (chamado filtro), opera de forma específica dentro do filtro. Se pensar no caso de se passar um café, o dado é o pó de café, e o filtro, ele interage com o pó, de forma a transformar o pó em um café. Mas para que o pó seja transformado em café, é preciso que o nosso líquido seja conduzido por um duto. Podemos aplicá-lo, por exemplo, para criar um agente de IA que identifica e-mails que são SPAM, já que o agente recebe o email, o manipula até que o simplifiquemos a ponto criar parâmetros simples para identificar spam.

__Monolítica__

- Na arquitetura monolítica, criamos apenas um bloco onde os serviços são interdependentes, ou seja, sua manutenção é mais complexa. A interação entre serviços/métodos é feita de forma vertical. Pode haver modulação nesse tipo de sistema, para haver maior facilidade na manutenção do código. Exemplo famoso: 
Amazon Prime Video e Github.  

__Baseada em mircrosserviços__

-  Considerada uma variante da arquitetura orientada a serviços, a arquitetura baseada em microsserviços é um tipo muito útil para arquitetura em que se busca uma independência maior em termos de serviços, e mais descentralizada do que a arquitetura monolítica.

__Hexagol__

- A arquitetura hexagonal é uma arquitetura conhecida por seu desacoplamento e fácil manutenção, pois há grande descentralização dos serviços. Segundo Pessôa: “As portas são as interfaces que permitem que a lógica de de negócios se comunique com o mundo externo, e os adaptadores são responsáveis por implementar as portas.” Um ponto muito positivo dessa arquitetura é a 
possibilidade de se incrementar outras arquiteturas devido ao grande desacoplamento. No entanto, a escritora supracitada diz que é preciso que tenhamos um núcleo bem definido para que a implementação dessa estrutura seja eficaz. Camila Pessôa ainda acrescenta que: “Essa arquitetura traz uma perspectiva diferente sobre a ordem das camadas de uma aplicação, em que normalmente temos a primeira camada como a interface e a última como um banco de dados para armazenamento. A ideia é entender front-end e back-end como camadas 
externas ao seu domínio!”  

## Arquiteturas de referência 

- A arquitetura de referência consiste em componentes de software e seus relacionamentos, implementando funcionalidades definidas no modelo de referência. Cada parte do modelo pode ser mapeada para um ou mais componentes, de forma que nem sempre há correspondência um-para-um. Essas arquiteturas são específicas de um domínio, derivadas de estudos de aplicação ao invés de sistemas existentes, e podem servir como base para implementar sistemas ou comparar soluções diferentes, funcionando como padrões de avaliação. Exemplos clássicos incluem o modelo OSI para sistemas de comunicação e a organização tradicional de compiladores em vanguarda e retaguarda.

[Link para o artigo](https://www.inf.ufpr.br/andrey/ci163/IntroduzArquiteturaAl.pdf)
