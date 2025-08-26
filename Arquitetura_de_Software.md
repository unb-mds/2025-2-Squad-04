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