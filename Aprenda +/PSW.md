# Introdução
Este curso tem por objetivo proporcionar conhecimentos sobre a construção de projetos de sistemas Web. 

Você irá **aprender** sobre a utilização e **importâncias dos padrões de projetos** (_design patterns_) e sobre as **principais metodologias** de utilizadas para produção de projetos observando o futuro desenvolvimento de softwares, como utilizá-las buscando produzir da melhor forma o projeto de sistemas. Também irá conhecer e/ou aprimorar seus conhecimentos acerca da **linguagem de modelagem unificada (UML)** e  conceitos e processos da **modelagem de sistemas.**

**O curso está organizado em 5 módulos, totalizando 30 horas. Ao final de cada módulo é disponibilizado um questionário avaliativo.**

|Data de início|Data de término|Tempo máximo para terminar (certificado)|
| --- | ---| ---|
|05/12/2023|indefinido|31/01/2024|

# Módulo 1 - Projeto de Sistemas Web
## 1.1 Introdução

Construção do projeto de sistemas Web deve atender as necessidades do **sistema em questão.**
==Particularmente os aspectos da arquitetura e da usabilidade do projeto para sistema Web que envolve múltiplas especificidades e particularidades da plataforma.==

***A Web revolucionou o meio pelo qual as pessoas se comunicam, com isso, há vagas promissoras no mercado, que atendam as necessidades cabíveis.***

>É **fundamental** entender que desenvolver projetos de sistemas para Web  é uma **prática complexa** quando se leva em consideração a **plataforma** em que se trabalha, por ser formada por **componentes inter-relacionados**. Além disso, é importante que você reconheça a necessidade de utilização de métodos, técnicas e ferramentas, observando prazos, orçamentos e clientes.

**PSWs** devem ser desenvolvidos baseados em **princípios de engenharia** (Técnicas e ferramentas, modelos e princípios, planejamento e gerenciamento, qualidade do produto e do processo de desenvolvimento) , pois trata-se de um produto complexo.

***DADOS***: **Base** para todos os demais elementos do projeto. Após estabelecida a base, a arquitetura tem de ser extraída. **Só então deve realizar outras tarefas de projeto.**

## 1.2 Conceitos sobre o projeto de sistemas Web

O **PSW** deve ser observado a partir de **princípios** da **engenharia de softwares.**
	Atividade complexa e formada por componentes inter-relacionados, pensados e desenvolvidos por quem sabe.

### Características da construção dos sistemas
- Funcionalidade
- Eficiência
- Robustez
- Confiabilidade
- Portabilidade
- Facilidade para a utilização

Empregar essas características no projeto levam ao desenvolvimento por completo e de qualidade do produto. Os princípios do projeto estabelecem **um norte a ser seguido.**

O projeto de software trata-se de um processo de repetição, constante aprimoramento. Se traduz para uma _planta_ os requisitos, afim de construir o software. **A planta, inicialmente, representa uma visão global do software.** Um nível de abstração que se conduz pelo o que for requisitado **do projeto em específico**, sejam eles de dados, funcionalidade e comportamento.
## 1.3 Importância do projeto de sistemas Web

Sistemas e aplicações baseados na Web (WebApps) são complexos, por causa das sua funcionalidades para ampla população de usuários, por isso, para criar WebApps de qualidade, se usa o processo da engenharia da Web (WebE).
==WebE =! engenharia de software==

>Para Pressman (2006), o objetivo da atividade de projetar é **gerar um modelo ou representação** que apresente **solidez**, **comodidade** e **deleite**. Para tanto, temos de praticar a diversificação e, depois, a convergência.

==Visualizar amplamente o sistema, entender suas necessidades mais básicas as mais complexas, estratégias de negócios e peculiaridades.==

==Por mais que haja uma constante evolução nas metodologias, é fato que há certos passos que sempre devem ser seguidos para a conclusão do projeto em questão.==

>Pode-se dizer que a **importância** de se **construir um sistema** está relacionada a um sistema que atenderá às **expectativas do cliente.** Deve ser projetado para ser um sistema **confiável**, **usual**, **adaptável**, apresentando essas e outras características no sistema finalizado. É no **projeto de sistema** que os profissionais envolvidos, bem como o cliente podem **perceber necessidades não contempladas durante a extração de requisito** com o profissional responsável, podendo essas serem implantadas em tempo hábil, com menor desgaste dos profissionais e menor custo.





## 1.4 Princípios Gerais
Hooker (1996, apud PRESSMAN, 2006) enumera sete princípios gerais da engenharia de software:

- Um sistema de software existe para **fornecer valor** aos clientes e usuários.

- **Todas as decisões**, inclusive as de projeto, devem ser tomadas tendo **isso em mente.**

- Todo projeto de software deve ser tão simples quanto possível sem, no entanto, descartar características de qualidade importantes em nome da simplicidade.

- O **comprometimento com a visão arquitetural** do sistema é essencial para o sucesso do projeto de software.

- **Os modelos** elaborados na **fase de projeto** serão usados **posteriormente** por **desenvolvedores** responsáveis pela **implementação**, **testes** e **manutenção do sistema**. Assim, esses modelos **devem ser claros**, não ambíguos e **fáceis de entender.**

- Um sistema com um **longo tempo** de vida tem **mais valor.** Contudo, para ter vida longa, um sistema deve **ser projetado** para estar pronto para **acomodar mudanças.**

- A reutilização pode ajudar a poupar tempo e esforço, bem como aumentar a qualidade do sistema em desenvolvimento. Para conseguir um bom nível de reutilização, é necessário planejar o reuso com antecedência. Na fase de projeto, padrões arquitetônicos e padrões de projeto detalhado (design patterns) são bastante maduros e documentados.


## 1.5 Projeto de sistemas Web
==A fase de projeto buscar definir e especificar soluções visualizadas pelos profissionais envolvidos a partir do momento em que esses conhecem os requisitos necessários para a produção do projeto. Nessa fase, por haver muitas formas para solucionar certo problema, **inicia-se uma fase na qual os envolvidos deverão tomar decisões.**==

O projeto é uma fase de refinação do produto, cada parte do projeto devera ser tratada detalhadamente.

Independentemente do paradigma adotado, o processo de projeto envolve as seguintes atividades (PRESSMAN, 2006):

- **Projeto da arquitetura do software** - Visa definir os elementos estruturais do software e seus relacionamentos.

- **Projeto dos elementos da arquitetura** - Visa projetar em um maior nível de detalhes cada um dos elementos estruturais definidos na arquitetura, o que envolve a decomposição de módulos em outros módulos menores.

- **Projeto detalhado** - Tem por objetivo refinar e detalhar os elementos mais básicos da arquitetura do software: as interfaces, os procedimentos e as estruturas de dados. Deve-se descrever como se dará a comunicação entre os elementos da arquitetura (interfaces internas), a comunicação do sistema em desenvolvimento com outros sistemas (interfaces externas) e com as pessoas que vão utilizá-lo (interface com o usuário), bem como se devem projetar detalhes de algoritmos e estruturas de dados.


## 1.6 Qualidade de projeto de sistemas Web
A ISO/IEC (2001) utiliza como referência para a avaliação de produtos de software seis características de qualidade:

- **Funcionalidade** - Refere-se à existência de um conjunto de funções que satisfazem às necessidades explícitas e implícitas e suas propriedades específicas. Tem como subcaracterísticas: adequação, acurácia, interoperabilidade, segurança de acesso e conformidade.

- **Confiabilidade** - Diz respeito à capacidade do software de manter seu nível de desempenho, sob condições estabelecidas, por um período de tempo. Tem como subcaracterísticas: maturidade, tolerância a falhas, recuperabilidade e conformidade.

- **Usabilidade** - Refere-se ao esforço necessário para se utilizar um produto de software, bem como o julgamento individual de tal uso por um conjunto de usuários. Tem como subcaracterísticas: inteligibilidade, apreensibilidade, operacionalidade, atratividade e conformidade.

- **Eficiência** - Diz respeito ao relacionamento entre o nível de desempenho do software e a quantidade de recursos utilizados sob condições estabelecidas. Tem como subcaracterísticas: comportamento em relação ao tempo, comportamento em relação aos recursos e conformidade.

- **Manutenibilidade** - Concerne ao esforço necessário para se fazer modificações no software. Tem como subcaracterísticas: analisabilidade, modificabilidade, estabilidade, testabilidade e conformidade.

- **Portabilidade** - Refere-se à capacidade do software de ser transferido de um ambiente para outro. Tem como subcaracterísticas: adaptabilidade, capacidade para ser instalado, coexistência, capacidade para substituir e conformidade.

Pressman (2006) relaciona diferentes diretrizes de qualidade, afirmando que, para avaliar a qualidade da representação de um projeto, você e os outros membros da equipe de software devem estabelecer critérios técnicos para um bom projeto, considerando as seguintes _diretrizes_:

1. Um projeto deve exibir uma arquitetura que foi criada usando estilos ou padrões arquiteturais reconhecíveis, seja composta por componentes que apresentem boas características do projeto ou que possa ser implementada de forma evolucionária facilitando, portanto, a implementação e os testes.

2. Um projeto deve ser modular e o software deve ser logicamente dividido em elementos ou subsistemas, de modo que seja facilmente testado e mantido.

3. Um projeto deve conter representações distintas de: dados, arquitetura, interfaces e componentes.

4. Um projeto deve levar as estruturas de dados adequadas às classes a serem implementadas e baseadas em padrões de dados reconhecíveis.

5. Um projeto deve levar a componentes que representem características funcionais independentes (baixo acoplamento).

6. Um projeto deve levar a uma interface que reduza a complexidade das conexões entre os componentes e o ambiente externo (encapsulamento).

7. Um projeto deve ser obtido usando-se um método repetível, isto é, dirigido por informações obtidas durante a análise de requisitos de software.

8. Um projeto deve ser representado usando-se uma notação que efetivamente comunique seu significado.

O PMBOK (2004) descreve que o projeto é um empreendimento temporário, de elaboração progressiva e com o objetivo de criar um produto ou serviço único, apresentando as seguintes fases:

- **Temporário** - O projeto possui início e fim bem definidos e pode ser de curta ou longa duração. O projeto chega ao fim quando os seus objetivos são atingidos.

- **Elaboração progressiva** - O desenvolvimento ocorre em etapas e continua por incrementos.

- **Produto ou serviço único** - Cada projeto é exclusivo.

## 1.7 Projeto de sistemas e padrões de projeto (design patterns)
==patterns = padrões.==

Patterns podem ser usadas para reutilizar parte do projeto, para não precisar começar do zero, reutilização que é um aspecto fundamental para o desenvolvimento de software.

==Patterns são soluções já existentes, testadas e aprovadas.==

>Foi o arquiteto austríaco Christopher Alexander (1936-) que introduziu a ideia de _patterns_, em 1970, para construir um vocabulário comum para discussões sobre design.

>Para Pressman (2006), cada _Pattern_ descreve um problema que ocorre várias vezes ao nosso redor e, com isso, descrevem a solução para o problema de uma maneira que você pode usar essa solução diversas vezes sem ter que fazer a mesma coisa duas ou mais vezes.

==O objetivo de um padrão de projeto é registrar uma experiência no projeto de software, que possa ser efetivamente utilizada por projetistas.==

Observando os estudos de Buschmann et al. (1996), um padrão tem os seguintes elementos:

- **Nome**: identificação de uma ou duas palavras, utilizadas para nomear o padrão.
- **Contexto**: uma situação que dá origem a um problema.
- **Problema**: explica o problema que surge repetidamente no dado contexto.
- **Solução**: descreve uma solução comprovada para o problema, incluindo os elementos que compõem o projeto, seus relacionamentos, responsabilidades e colaborações.
- **Consequências**: são os resultados e os comprometimentos feitos ao se aplicar o padrão. ==Atentar-se as consequências, ser criterioso.==



## 1.8 Documentação do projeto
O projeto de um sistema é de suma importância por se tratar do início técnico do processo de desenvolvimento, o que garante um bom projeto. Por isso a necessidade da **documentação do projeto**, pois uma equipe pode variar de integrantes ou ser completamente mudada, diferentes profissionais envolvidos no projeto podem querer determinada informação, **a documentação de projeto é primordial para a comunicação entre esses profissionais.**

Para Bass; Clements; Kazman (2003), a documentação do projeto de sistemas deve conter:

- **informações gerenciais,** tais como versão, responsáveis, histórico de alterações;
- uma **descrição geral do sistema**;
- uma **lista das visões consideradas e informações** acerca do mapeamento entre elas.

***Lembre-se de que as visões podem ser apresentadas por meio de representação gráfica, tabular ou textual. Elas são essenciais e a documentação deve abranger visões consideradas relevantes e abrangentes do sistema.***

## 1.9 Resumo
>Projeto de sistemas Web é uma fase muito importante para o desenvolvimento de software, pois os profissionais e as demais pessoas que utilizarão ou manipularão o sistema para qualquer finalidade necessitarão do projeto de sistema.
>
>A dinamicidade que nos propõe a Web se reflete na mutação rápida das necessidades atuais e, por isso, a projeção do projeto de sistema dará suporte e respaldo aos profissionais envolvidos no desenvolvimento, teste e manutenção do sistema.
>
>Sem dúvida, conhecer e entender as características, importância e peculiaridades acerca do projeto do sistema permitirá que você domine esse processo dinâmico que reflete as necessidades atuais dos usuários e clientes, vez que podemos contar com diversas tecnologias para buscar de maneira mais rápida e eficiente tal elaboração e construção.


# Módulo 2 - Levantamento, especificação e análise de requisitos
## 2.1 Introdução
Nesse módulo você compreenderá a atividade de **levantamento de requisitos**; aprenderá sobre os requisitos necessários para o projeto de sistemas Web e também terá **noções gerais** sobre a **especificação** e **análise de requisitos** do projeto de sistemas Web.

Você começa a estudar os requisitos para  o projeto de sistemas, ou seja, nesse momento passará a **compreender** a **necessidade existente no mundo real** para que seja **projetada** no **mundo computacional.**
## 2.2 Levantamento de requisitos para projeto de sistemas Web
==Levantamento de requisitos é a pratica de identificar as necessidades que o cliente tem e buscar soluções com a criação de determinado sistema.==

==Entender a real necessidade do cliente para poder projetar e passar a desenvolver o sistema.==

==Para ser capaz de levantar requisitos é necessário ter o domínio do negócio, conhecer bem o problema.==

**Domínio do negócio** é conquistado a partir do conhecimento que o profissional tem sobre o problema no **mundo real**, o que reflete **diretamente** no **desenvolvimento do software.**

==Domínio do negócio == Domínio da aplicação == Domínio do problema==

==O documento criado contendo o levantamento de requisitos é conhecido como documento de requisitos.==

As **principais seções** de um **documento de requisitos** são os **requisitos funcionais** e os **requisitos não funcionais**, conforme quadro abaixo:

|Requisitos Funcionais|Requisitos não funcionais|
|---|---|
|São os requisitos que definem as funcionalidades do sistema.|São os requisitos que declaram as características  <br>de qualidade que o sistema deve possuir e que estão relacionadas às suas funcionalidades.|
|**Exemplos**|**Exemplos**|
|O sistema deve permitir que cada professor realize o lançamento de notas das turmas nas quais lecionou.|Confiabilidade: corresponde a medidas quantitativas da confiabilidade do sistema, tais como tempo médio entre falhas, recuperação de falhas ou quantidade de erros por milhares de linha de código-fonte,|
|O sistema deve permitir que um aluno realize a sua matrícula nas disciplinas oferecidas em um semestre.|Desempenho: requisitos que definem tempos de resposta esperados para as funcionalidades do sistema.|
|Os coordenadores de escola devem poder obter o número de aprovações, reprovações e trancamentos em todas as turmas em um determinado período.|Portabilidade: restrições sobre as plataformas de hardware e de software nas quais o sistema será implantado e sobre o grau de facilidade para transportar o sistema para outras plataformas.|

## 2.3 Importância dos requisitos para o projeto de sistemas Web
==Engenharia de requisitos leva ao entendimento dos requisitos.==

Na perspectiva do processo de software, a engenharia de requisitos é uma ação de engenharia de software importante que se inicia durante a atividade de comunicação e continua na modelagem.

A formulação de sistemas e aplicações baseados na Web representa uma sequência de ações de engenharia da Web que: 

- começa com a identificação das necessidades do negócio;
- avança para uma descrição dos objetivos da WebApp; 
- define as principais características e funções;
- realiza a coleta de requisitos que levam ao desenvolvimento de um modelo de análise.

==Nesse sentido, você deve, ao iniciar um projeto de sistema Web, refletir sobre qual a necessidade para o seu desenvolvimento.==

==Deve-se pensar como o usuário do sistema.==

***Se imediatismo e evolução contínua são atributos principais de uma WebApp, uma equipe de engenharia da Web pode escolher um modelo de processo ágil que produz versões WebApp em uma sequência rápida. Por outro lado, se uma WebApp precisar ser desenvolvida durante um período de tempo maior (por exemplo, uma grande aplicação de e-commerce), um modelo de processo incremental pode ser escolhido.***
# Perguntas a serem respondidas no final do módulo
### Mas, o que é projeto de sistemas Web? 
==RESPOSTA==
### Quais são as características e peculiaridades na construção de projeto Web? 
==RESPOSTA==
### Como ocorreu a evolução do desenvolvimento de sistemas Web?
==RESPOSTA==
### Como são os processos de desenvolvimento de sistemas Web?
==RESPOSTA==