# Especificações do Projeto

Os pontos mais relevantes a serem abordados na da busca de uma solução com este projeto foram consolidados a partir de uma ampla discussão pelos membros do grupo acerca das personas e histórias de usuários que aqui se apresentam.  As necessidades a qual o projeto possa sanar foram aqui elucidadas, bem como também os requisitos funcionais, não funcionais e as restrições do projeto.

## Personas

Desta forma, constatou-se que o presente projeto possui 2 principais personas:

•	Estudantes;
•	Profissionais de qualquer área.

A seguir, passamos à análise detalhada das personas e suas respectivas histórias de usuários.

| Milenne Ribeiro ![millene persona](https://user-images.githubusercontent.com/103156976/222037920-08e2ac04-280c-4c82-98e6-878589c33079.jpg)  | Sobre: Idade: 15 anos Ocupação: Estudante do Ensino Médio.   | História: Milenne sempre foi uma pessoa muito ativa e disposta. Ela ama sua rotina cheia, mas na maioria das vezes não consegue realizar todas as suas tarefas diárias devido à falta de organização, trazendo o sentimento de frustração. |
|------|-----------------------------------------|----|
| Motivações: Milenne estuda em período integral. Além disso, possuí outros compromissos, como curso de língua estrangeira. | Frustrações: Todas as suas atividades são essenciais, entretanto, há uma enorme dificuldade em conciliar tantas coisas, gerando acúmulos e atrasos. | Hobbies:  Além de estudar outros idiomas,  2x na semana participa de aulas de dança e natação. Aos fins de semana gosta de sair com as amigas. |


| José Ferreira ![jose ferreira persona](https://user-images.githubusercontent.com/103156976/222038650-1219eda3-0e31-4eea-96d7-2c584b2230da.jpg) | Sobre:  Idade: 32 anos  Ocupação: Personal trainer.   | História: José vive o sonho de trabalhar com o que ama. Após conhecer a musculação aos 19 anos, decidiu seguir carreira. Hoje possui muitos alunos, mas a grade mal organizada o impede de viver qualquer coisa além do trabalho.  |
|------|-----------------------------------------|----|
| Motivações: Com o intuito de ser um excelente profissional, pai, marido e amigo, José busca uma forma de atingir seus objetivos diários.| Frustrações: Muitas vezes José deixa faltar em alguma área. Seja nos estudos, em uma viagem de família que não conseguiu fazer, uma apresentação de seu filho na escola que não conseguiu participar ou um aniversário de uma velha amiga que não pode ir. Ele precisa de algo que o ajude a garantir uma qualidade de vida no cotidiano.  | Hobbies: Além da musculação, gosta de livros e filmes de ação, passear com sua família aos fins de semana e estudar sobre finanças. |


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Estudante  | Conseguir realizar os afazeres dentro do prazo determinado.          |Cumprir objetivos e obter qualidade de vida.              |
|Profissional     | Organizar a rotina.               | Conciliar as responsabilidades da vida pessoal e profissional. |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, foram consideradas como alta prioridade as necessidades reais das personas conforme suas histórias de usuário, determinando assim as funcionalidades que de fato tem maior impacto nestas necessidades; Já funcionalidades como as do escopo de personalização da aplicação foram classificadas com uma prioridade menor.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-01| A tela inicial deve exibir um botão para acessar o login.  | ALTA |
|RF-02| O software deve permitir cadastrar (criar) novos hábitos.    | ALTA |
|RF-03| O software deve mostrar de forma intuitiva a visão geral da semana do usuário.   | MÉDIA |
|RF-04|O software deve permitir ao usuário gerar um relatório sobre suas atividades ao fim de cada ciclo (mês)   | BAIXA |
|RF-05| O software deve permitir o compartilhamento de conclusão de uma atividade nas mídias sociais. s | BAIXA |
|RF-06| O software deve permitir ao usuário selecionar o modo (claro) ou (escuro)  | BAIXA |
|RF-07| Cadastro de tarefas/hábitos: o usuário poderá cadastrar uma lista de tarefas ou hábitos que deseja realizar diariamente.  | MÉDIA |
|RF-08| Marcar tarefas cumpridas ou não cumpridas: o usuário poderá marcar diariamente se realizou ou não cada uma das tarefas cadastradas.   | ALTA |
|RF-09| Notificações: o usuário poderá receber notificações diárias para lembrá-lo de realizar as tarefas cadastradas.  | MÉDIA |
|RF-10| Personalização: o usuário poderá personalizar o aplicativo, escolhendo cores e fontes de sua preferência.    | BAIXA |



### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-01| A aplicação deve ser publicada em repositório público acessível na internet. l | ALTA |
|RNF-02| Uso de design responsivo nas interfaces gráficas.  |  ALTA |
|RNF-03| O software deverá armazenar as informações descritas ou selecionadas pelo usuário. | MÉDIA |
|RNF-04| Os dados do usuário devem ser armazenados de forma segura e protegidos contra possíveis invasões ou vazamentos de informações. |  ALTA |
|RNF-05| O aplicativo deve funcionar em diferentes plataformas (iOS e Android) e em diferentes dispositivos, como tablets e smartphones.  | MÉDIA |



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01| O projeto necessita ser entregue até 23/06/2023, respeitando o prazo estipulado.  |
|RE-02| O projeto deve ser implementado com uso de tecnologias mobile, podendo fazer uso de bibliotecas que influenciem positivamente na qualidade do software.        |


## Diagrama de Casos de Uso

Na linguagem de modelagem unificada (UML), o objetivo do diagrama de caso de uso é demonstrar as diferentes maneiras que o usuário pode interagir com um sistema. O caso de uso abaixo apresenta as possibilidades de interação do usuário com o aplicativo Hábitos.

![DIAGRAMA CASO DE USO](https://user-images.githubusercontent.com/103156976/222037270-440659c7-ad70-47d3-8a57-a552f2b33ff1.jpg)

# Matriz de Rastreabilidade

Uma matriz de rastreabilidade de software é uma ferramenta usada no gerenciamento de projetos de software para rastrear e documentar as relações entre os requisitos do sistema, as funcionalidades do software e os testes realizados durante o processo de desenvolvimento. Essa matriz permite que os desenvolvedores e gerentes de projeto rastreiem a origem e o destino de cada requisito, bem como os testes e validações associados a cada um deles. Isso ajuda a garantir que todos os requisitos do sistema estejam implementados e testados corretamente, o que ajuda a garantir a qualidade e a efetividade do software.

![matriz de rastreabilidade](https://user-images.githubusercontent.com/103156976/222037537-8dd89880-c784-4446-b341-f27a4a0359b5.jpg)

# Gerenciamento de Projeto

Qualquer que seja o motivo que leve um projeto a ser realizado deve-se perguntar, bem no início do seu ciclo de vida: é viável realizá-lo? Que benefícios esse projeto trará, e a que custo? A partir destas respostas nasce a construção de um projeto e com ele surge a necessidade de se fazer gestão.

Como documento norteador levaremos em consideração O Guia de Conhecimento em Gerenciamento de Projetos (PMBoK) na sua versão 6. O PMBoK é um documento extenso que contempla conhecimentos e práticas validadas para à gestão de projeto, sua atualização é periódica a cada 4 anos contemplando assim a evolução dos conhecimentos e tecnologias da área.

Para o Guia PMBoK v6 gerenciamento de projeto é fazer a gestão integrada e multidisciplinar de 10 áreas pilares, sendo elas: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições e Partes Interessadas. 
Para que isto ocorra de forma plena sem gerar entraves no desenvolvimento do projeto, precisamos considerar que todos estes pilares são essenciais e estão diretamente relacionados.

Desta forma para realizar esta etapa, a equipe optou por utilizar o ProjectLibre, conforme sugerido nas aulas de Gerência de Projetos de TI pelo professor Pedro A. Oliveira no curso de Análise e Desenvolvimento de Sistemas da PUC Minas. 

Utilizando então a ferramenta ProjectLibre, registramos as etapas do projeto, elucidando as datas de entrega e requisitos, a ferramenta por sua vez apresenta uma visão hierárquica de todo o projeto, proporcionando assim melhor compreensão para gestão de tempo e/ou organização. 


## Gerenciamento de Tempo

A ferramenta gerou automaticamente o gráfico de Gantt e o diagrama de rede. O gráfico de Gantt, ou diagrama de Gantt, é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![PJ 01](https://user-images.githubusercontent.com/103156976/222039592-e39ff4e2-389b-43ee-a8d2-f96082324701.jpg)
![PJ 02](https://user-images.githubusercontent.com/103156976/222039605-2553c827-0c25-4ca9-95f5-3c2b7ffdd652.jpg)

O diagrama por sua vez mostra um planejamento geral das entregas com base nas etapas cadastradas inicialmente. Para realizar a gestão do tempo de forma eficaz a equipe optou por realizar a gestão de tempo e distribuição de tarefas (buckets) por meio do aplicativo Microsoft Planner  tal escolha também foi motivada pela disponibilidade do aplicativo, que se encontra na plataforma Microsoft 365 a qual temos acesso dentro do ambiente oferecido pela PUCMinas. Dentro do Microsoft Planner conseguimos trabalhar utilizando o método Kanban de uma forma que toda a equipe tenha acesso ao planejamento, possibilitando assim uma gestão de tempo eficaz. 


## Gerenciamento de Pessoal

A gestão de pessoas em projetos tem por objetivo fundamental tornar a relação entre o capital e o trabalho a mais produtiva e menos conflituosa possível. Nesta concepção as pessoas e seus conhecimentos, habilidades e competências passam a ser um dos pilares para um projeto bem sucedido.

Ter um controle adequado das tarefas e demandas de cada membro da equipe propicia uma visão mais ampla acerca do projeto, sendo também uma ferramenta útil de gestão, considerando que desta forma eventuais desvios do planejamento possam ser identificados pela equipe de forma mais rápida, alcançando assim uma solução imediata.

Este gerenciamento permite que o projeto alcance altos níveis de produtividade. 
Para facilitar este processo de gestão de tarefas e pessoas, a equipe conta também com recursos do Microsoft Planner , onde o aplicativo apresenta o detalhamento de cada sprint, bem como os responsáveis por determinada tarefa.

No Microsoft Planner, as tarefas podem também ser rastreadas por status, bucket, prioridade e responsável, bem como seu estado de execução conforme exposto na tela abaixo:

![PLANNER 01](https://user-images.githubusercontent.com/103156976/222039735-fbb40fab-a82b-4984-8000-a899f8f5f759.jpg)
![PLANNER 02](https://user-images.githubusercontent.com/103156976/222039740-7ab6bbb5-892f-447e-8a52-9f0802f68835.jpg)


## Gerenciamento financeiro

Ter uma visão clara dos dados financeiros do projeto ajudará a economizar tempo, reduzir erros e garantir maior qualidade na entrega de cada etapa.

|Gasto estimado | Valor                                       |
|-----------------|-------------------------------------------------------|
| Recursos Humanos | R$ 20.000,00 |
| Design (R$ 25,00/Hora)) | R$ 5.000,00 |
| Desenvolvedor (R$ 70,00/Hora) | R$ 140.000,00 |
| Administrador (R$ 25,00/Hora) | R$ 3.000,00 |
| Hardware | R$ 0.000,00 |
| 2 Iphones11| R$ 6.400,00 |
| 2 SamsungS22 | R$ 10.800,00 |
| 1 IPAD PRO | R$ 9.400,00 |
| 1 Samsung Galax TAB 8 | R$ 4.800,00 |
| 6 notebooks | R$ 36.000,00 |
| Especialização Profissional | R$ 1.400,00 |
| Cursos e treinamentos | R$ 100.000,00 |
| Licenças de Softwares | R$ 50.000,00 |
| TOTAL | R$ 386.800,00 |
