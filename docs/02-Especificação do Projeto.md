# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação dos usuários em um trabalho de imersão feita pelos membros da equipe a partir da observação dos usuários em seu local natural e por meio de entrevistas. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.


## Personas

Amanda Alves tem 41 anos, é recepcionista e recém-formada em gestão de recursos humanos. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteira e sempre quis fazer um intercâmbio. Está buscando se profissionalizar cada vez mais e aplicar tecnologias novas em suas funções.

Carlos Gomes tem 51 anos, é médico com especialização em pneumologia. Motivado a salvar vidas e dar o melhor de si mesmo todos os dias, se sente profissionalmente realizado e com um núcleo familiar estável. Gostaria de desburocratizar e a agilizar seus processos de trabalhos na medicina.

Thiago Mitef tem 27 anos, é administrador de empresas e técnico de laboratório, ama estudar e perseguir seus sonhos. Atualmente é dono e proprietário de uma clínica médica que emprega um grande quadro de funcionários e atende centenas de pacientes. Gostaria de aplicar soluções tecnológicas para facilitar a sua vida e a de seus colaboradores.



## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Amanda Alves
* Eu como recepcionista cadastrar pacientes de forma rápida e eficiente para economizar tempo.
* Ter controle das informações primordiais de cada paciente em um lugar só para melhor organizar e deixar tudo dentro dos conformes.
* manter um registro de forma visual de todos os pacientes, com a possibilidade de alterar na hora as informações para ter na ponta dos dedos de forma rápida cada paciente registrado.

Carlos Gomes
* Eu como médico quero ter um cadastro completo de todos os meu pacientes para o meu controle pessoal e melhor atendimento.
* Uma agilidade maior no processo de receituário para meus pacientes economizar meu tempo.

Thiago Mitef
* Eu como administrador da empresa quero Unificar todas as fontes de informação em um único lugar que todos possam utilizar para superar a dificuldade de comunicação e transparência entre setores diferentes.
* Imprimir um receituário de forma prática para uma qualidade de vida melhor no ambiente de trabalho.

## Requisitos

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.


### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve apresentar uma tela de login para cada tipo de usuário (Administrador, Recepcionista e Médico) | ALTA | 
|RF-002| O sistema deve ter uma interface gráfica de fácil interpretação   | MÉDIA |
|RF-003| O sistema deve encerrar ao clicar no X.   | MÉDIA |
|RF-004| O sistema deve permitir a navegação entre as diversas páginas.   | MÉDIA |
|RF-005| O sistema deve ter a funcionalidade de cadastro de todos os tipos de funcionários e pacientes, armazenados no banco de dados interno.   | ALTA |
|RF-006| O sistema deve permitir visualizar as informações dos cadastros no banco.   | MÉDIA |
|RF-007| O sistema deve alertar logins incorretos ou não cadastrados.   | BAIXA |
|RF-008| O sistema deve permitir alterar informações no DGV.   | BAIXA |
|RF-009| O sistema deve permitir a impressão do receituário.   | ALTA |
|RF-010| O sistema deve gerar o receituário automaticamente.   | MÉDIA |
|RF-011| O sistema deve permitir o cadastro de médicos, recepcionistas e pacientes, também como o de testes laboratoriais, salvar cada um no banco, permitir edição em tempo real e que seja de fácil visualização.   | ALTA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser publicado em um ambiente acessível publicamente na Internet (Github). | ALTA | 
|RNF-002| O sistema deverá ser compilado sem erros e em formato de executável. |  ALTA | 
|RNF-003| O sistema deve ter bom nível de contraste entre os elementos da tela em conformidade. |  MÉDIA |
|RNF-004| O sistema deve ser compatível com Windows. |  ALTA |

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 15/12/2021. |
|02| O aplicativo deve se restringir às tecnologias básicas dos sistemas feitos em .NET.        |
|03| A equipe não pode subcontratar o desenvolvimento do trabalho.       |
