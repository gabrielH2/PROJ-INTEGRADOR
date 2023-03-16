||
| :- |
||<p>**Diagrama de Casos de Uso**</p><p>**Prof:** **Léuson da Silva** </p><p>(leuson.silva@unicap.br)</p><p>NSIN-0027 - Projeto Integrador IV</p><p>Sistemas para Internet - Semestre 2023.1</p><p>UNICAP</p>|
|||
||||
||

**Casos de Uso![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

Especificação  mais  detalhada  do  que  a  especificação  de  requisitos, considerando diferentes fluxos de execução (normal e extensões)

Seu uso não é tão comum junto de metodologias ágeis.

3

**Exemplo de Caso de Uso![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.002.jpeg) 3


**Diagrama de Casos de Uso![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

Técnica usada para captar e entender: 

- as funcionalidades de um sistema;
- delimitar os atores envolvidos em cada funcionalidade;
- relacionamentos entre diferentes funcionalidades

Explorar o sistema sob a perspectiva dos usuários

**Diagrama de Casos de Uso na UML![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

Diagrama mais abstrato dentre os diagramas disponíveis pela UML

Sobre o sistema:

- **O que** o sistema faz?
  - Ao invés do **como…**
- **Por quem** uma funcionalidade é realizada?

**Componentes Principais - Atores![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

Atores:

- Papéis que desempenhados pelos diferentes usuários;
- Quem interage com o sistema usando suas funcionalidades;
- Um sistema pode ter vários atores (usuário, outros sistemas, dispositivos de hardware);
- Um ator não faz parte do sistema, apenas há uma interação.

**Diferentes sistemas, diferentes atores…![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

Quem seriam os atores, nos seguintes sistemas, que usamos todos os dias na Unicap:

- TOTVS
- Catraca

**Atores Primários e Secundários![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

Atores Primários:

- Interação direta com o sistema
- Em um caixa eletrônico, o usuário interage diretamente com o sistema

Atores Secundários:

- Interação com outros atores do sistema
- Em uma agência bancária, o usuário interage com o atendente do banco, que, interage diretamente com o sistema

**Componentes Principais - Casos de Uso![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

Casos de Uso

- As funcionalidades do sistema;
- Descrevem as interações entre usuários e o sistema
- Uma boa prática é usar verbos no infinitivo explorando a ideia de **ação;**

**Identificando Casos de Uso![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

A  partir  dos  requisitos  do  sistema,  busca-se  identificar situações  onde  é possível estabelecer uma interação entre um usuário e o sistema:

- Um requisito pode estar vinculado a diferentes casos de uso;
- Um caso de uso pode estar vinculado a diferentes requisitos.

**Quais Casos de Uso podemos listar a partir dos Requisitos?![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

- RQ1: Um professor pode atribuir trabalhos aos alunos cadastrados em uma disciplina.
- RQ2: Um professor pode avaliar os trabalhos avaliados pelos alunos em uma disciplina.
- RQ3:  Um  aluno  pode  enviar  trabalhos  cadastrados,  bem  como acompanhar a respectiva nota atribuída.
- RQ4: Todos os usuários do sistema devem realizar autenticação antes de usar o sistema.

**Diferentes sistemas, diferentes casos de uso…![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

Quem seriam os casos de uso, nos seguintes sistemas, que usamos todos os dias na Unicap:

- TOTVS
- Catraca

**Componentes Principais - Relacionamentos![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

Relacionamentos

- Como atores e casos de uso se relacionam;
- Um caso de um uso pode estar associado a diferentes atores, bem como um ator pode executar diferentes casos de uso.

` `![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.003.png)

**Inclusão![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

Ocorre quando um caso de uso tem um comportamento parcial, comum a vários outros casos de uso;

Desta forma, a inclusão nos permite:

- Reuso, pois se evita a repetição de relacionamentos
- A inclusão do caso de uso se torna obrigatória

**Inclusão - Diagramas de Casos de Uso![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

**Extensão![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

Um  caso  de  uso **B**  estende  outro  caso  de  uso **A**,  se **B**  acrescenta comportamento em relação a **A**

Desta forma, adotamos a extensão quando:

- Fluxo alternativo complexo e que merece um detalhamento maior;
- Mudança em um caso de uso, mas sem alterar sua base (comportamento padrão)
- A execução do novo caso de uso não é obrigatória.

19

**Extensão - Diagramas de Casos de Uso![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**

![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.004.png) 18


**Especialização/Generalização**

Ocorre quando um caso de uso **A** tem características semelhantes a um caso de uso ![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)**B**.

Desta forma, com a generalização temos:

- o reuso de comportamento;
- o destaque das especializações de **B** em relação à **A.**

![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.005.png)![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)

![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.006.png)![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.001.png)

24

**Bibliografia![](Aspose.Words.d1b5a418-f980-4061-af4d-abadc12082c6.007.png)**

- FOWLER, Martin; SCOTT, Kendall. Uml essencial: um breve guia para linguagem-padrão de modelagem de objetos. 2. ed. Porto Alegre: Bookman, 2000.
- Notas de Aula do Professore Eduardo Figueiredo
- Notas de Aula da Professora Elisa Yumi Nakagawa

**22**

||
| :- |
||<p>**Diagrama de Casos de Uso**</p><p>**Prof:** **Léuson da Silva** </p><p>(leuson.silva@unicap.br)</p><p>NSIN-0027 - Projeto Integrador IV</p><p>Sistemas para Internet - Semestre 2023.1</p>|
|||
||||
||


