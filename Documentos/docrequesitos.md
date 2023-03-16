<Project Name> Equipe: Carlos Roberto da Silva Júnior Projeto Integrador IV![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.001.png)![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.002.png)

**Documento de Requisitos do Sistema** 

**<*ProjectName*>**

**Versão 1.0**

**Histórico de Alterações![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.003.png)**

|**Data**|**Versão**|**Descrição**|**Autor**|
| - | - | - | - |
|17/01/2023|1\.0|xxxxxxxxxxx|xxxxxx|
|||||
|||||
**Conteúdo**

1. **INTRODUÇÃO 4**
1. VISÃO GERAL DO DOCUMENTO 4
1. CONVENÇÕES, TERMOS E ABREVIAÇÕES 4
1. *Identificação dos requisitos 4*
1. *Prioridades dos requisitos 4*
2. **DESCRIÇÃO GERAL DO SISTEMA 5**

2\.1 ABRANGÊNCIA E SISTEMAS RELACIONADOS 5

3. **REQUISITOS FUNCIONAIS (CASOS DE USO) 5**
1. CADASTRO 5

*[RF001] Criar componente 5 [RF002] Excluir componente 5 [RF003] Alterar componente 6*

2. INTERFACE 6

*[RF001] Visualizar Componente 6 [RF002] Copiar componente 6 [RF003] Colar componentes 7*

3. COMPILAÇÃO 7 *[RF001] Compilar componente 7*
3. IMPORTAÇÃO/EXPORTAÇÃO 7

*[RF001] Anexar documentos 7 [RF002] Exportar metodologia 8 [RF003] Importar metodologia 8 [RF004] Salvar metodologia 8 [RF005] Gerar site de metodologia 9*

4. **REQUISITOS NÃO-FUNCIONAIS 9**

*[NF001] Usabilidade 9 [NF002] Desempenho 9 [NF003] Hardware e Software 9*

5. **REFERÊNCIAS 10![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.003.png)**

**1. Introdução![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.004.png)**

Este documento especifica os requisitos do sistema *Fast System Support*, através de  casos  de  uso,  fornecendo  aos  desenvolvedores  e  cliente  as  informações 

necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

1. **Visão geral do documento**

Além  desta  seção  introdutória,  as  seções  seguintes  estão  organizadas  como descrito abaixo.

1. **Seção  2  –  Descrição  geral  do  sistema**:  apresenta  uma  visão  geral  do  sistema, caracterizando qual é o seu escopo e descrevendo seus usuários.
1. **Seção 3 – Requisitos funcionais (casos de uso)**: especifica todos os casos de uso do sistema, descrevendo os fluxos de eventos, prioridades, atores, entradas e saídas de cada caso de uso a ser implementado. 
1. **Seção 4 – Requisitos não-funcionais**: especifica todos os requisitos não funcionais do sistema,  divididos  em  requisitos  de  usabilidade,  confiabilidade,  desempenho,  segurança, distribuição, adequação a padrões e requisitos de hardware e software.
2. **Convenções, termos e abreviações**

A  correta  interpretação  deste  documento  exige  o  conhecimento  de  algumas convenções e termos específicos, que são descritos a seguir.

FSS - *Fast System Support*

Frame – É um elemento que permite exibir o conteúdo extra dentro de uma página.

1. **Identificação dos requisitos**

Por convenção, a referência a requisitos é feita através do nome da subseção onde eles  estão  descritos,  seguidos  do  identificador  do  requisito,  de  acordo  com  a especificação a seguir:

[*nome da subseção. identificador do requisito*]

Por  exemplo,  o  requisito  funcional  [Recuperação  de  dados.RF016]  deve  estar descrito  em  uma  subseção  chamada  “Recuperação  de  dados”,  em  um  bloco identificado  pelo  número  [RF016].  Já  o  requisito  não-funcional [Confiabilidade.NF008] deve estar descrito na seção de requisitos não-funcionais de Confiabilidade, em um bloco identificado por [NF008]. 

Os  requisitos  devem  ser  identificados  com  um  identificador  único.  A  numeração inicia com o identificador [RF001] ou [NF001] e prossegue sendo incrementada à medida que forem surgindo novos requisitos.

2. **Prioridades dos requisitos**

Para  estabelecer  a  prioridade  dos  requisitos,  na  seção  4,  foram  adotadas  as denominações “essencial”, “importante” e “desejável”. 

4. **Essencial** é o requisito sem o qual o sistema não entra em funcionamento. Requisitos essenciais são requisitos imprescindíveis, que têm que ser implementados impreterivelmente.![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.003.png)
5. **Importante** é o requisito sem o qual o sistema entra em funcionamento, mas de forma não  satisfatória.  Requisitos  importantes  devem  ser  implementados,  mas,  se  não  forem,  o sistema poderá ser implantado e usado mesmo assim.
5. **Desejável** é o requisito que não compromete as funcionalidades básicas do sistema, isto é, o sistema pode funcionar de forma satisfatória sem ele. Requisitos desejáveis podem ser deixados para versões posteriores do sistema, caso não haja tempo hábil para implementá- los na versão que está sendo especificada.
2. **Descrição geral do sistema![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.005.png)**

**2.1 Abrangência e sistemas relacionados**

A competitividade e a velocidade da evolução do mercado cada vez mais demandam novas estratégias de negocio que visam aproximar cliente e empresa. A velocidade de reposta é uma técnica fundamental para satisfação do cliente e de forma  geral  um  fator  de  competitividade  que  pode  ser  alcançado  com  a informatização do atendimento ao cliente.

O FSS é uma ferramenta que intermédia a relação cliente/empresa com o intuito  não  somente  de  solucionar  problemas,  mas  como  solucioná-los  de  forma rápida garantindo a satisfação do cliente. 

Com uma intuitiva, eficiente e de fácil acesso interface WEB, o usuário pode sanar suas dúvidas, resolver problemas e levantar críticas ou sugestões.

A ferramenta também disponibiliza a funcionalidade de consulta de histórico de atendimento, permitindo ao usuário o cumprimento da obrigação levantada pelo atendente.

3. **Requisitos funcionais (casos de uso)![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.006.png)**
1. **Cadastro**

<INSERIR AQUI DIAGRAMAS DE CASO DE USO DE CADASTRO>

` `**[RF001] Selecionar Perfil ![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.007.png)**

**Descrição do caso de uso:** Este caso de uso permite ao sistema disponibilizar atendentes aos futuros usuários do sistema.

Ator: Atendente

**Prioridade**: ■ Essencial Importante Desejável

**Entradas e pré-condições**: Atendente estar cadastrado no sistema.![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.003.png)

**Saídas e pós-condição**: Está disponível para atendimento aos usuários.

` `**[RF002] Preencher Nome e E-mail![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.008.png)**

**Descrição do caso de uso:** Este caso de uso permite aos usuários informar os dados solicitados pelo sistema para realizar o atendimento. 

Ator: Cliente

**Prioridade**: ■ Essencial Importante Desejável

**Entradas e pré-condições**: Usuário acessar o sistema.

**Saídas e pós-condição**: O usuário é direcionado para a tela de seleção de atendentes disponíveis.

**[RF003] Escolher Atendente Disponível ![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.009.png)**

**Descrição do caso de uso:** Este caso de uso permite que o usuário escolha um atendente disponível para realizar o atedimento.

Ator: Cliente

**Prioridade**: ■ Essencial Importante Desejável

**Entradas e pré-condições**: RF[002]

**Saídas e pós-condição**: Tela de espera.

**[RF004] Aceitar ou Recusar Atendimento ![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.010.png)**

**escrição do caso de uso:** Este caso de uso permite que o atendente aceite ou recuse a solicitação de atendimento do usuário.

Ator: Atendente

**Prioridade**: ■ Essencial Importante Desejável

**Entradas e pré-condições**: RF[003]

**Saídas e pós-condição**: Caso aceite será direcionado para uma tela de atendimento ao cliente, caso contrario o atendente permanece na tela atual.

**[RF005] Realizar Atendimento ![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.011.png)**

**Descrição do caso de uso:** Este caso de uso permite a interação entre atendente e usuário.![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.003.png)

Documento de Requisitos Página 6 de 
Ator: Atendente

**Prioridade**: ■ Essencial Importante Desejável

**Entradas e pré-condições**: RF[004\*]

**Saídas e pós-condição**: Realizar o atendimento.

**[RF006] Consultar Histórico de Atendimento ![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.012.png)**

**Descrição do caso de uso:** Este caso de uso permite a consulta do atendimento realizado ao cliente mediante a apresentação da chave correspondente ao mesmo.

Ator: Cliente

**Prioridade**: Essencial ■ Importante Desejável

**Entradas e pré-condições**: Chave única do atendimento.

**Saídas e pós-condição**: A tela com o histórico de atendimento.

**[RF007] Histórico Resumido de Atendimentos ![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.010.png)**

**Descrição do caso de uso:** Este caso de uso permite que seja exibido na tela inicial do atendente o histórico resumido dos atendimentos realizados.

Ator: Atendente

**Prioridade**: Essencial ■ Importante Desejável

**Entradas e pré-condições**: O atendente deve estar conectado no seu perfil. **Saídas e pós-condição**: Resumo com o nome e-mail e data do atendimento.

**[RF008] Detalhes de Atendimento ![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.013.png)**

**Descrição do caso de uso:** Este caso de uso permite que seja visualizado os detalhes como nome, e-mail, data/hora do inicio e termino do atendimento e dialogo entre atendente e cliente.![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.003.png)

**Prioridade**: Essencial ■ Importante Desejável

**Entradas e pré-condições**: Selecionar o atendimento que deseja visualizar. **Saídas e pós-condição**: Tela com os detalhes de atendimento.

2. **Interface**

<INSERIR AQUI DIAGRAMAS DE CASO DE USO DE INTERFACE>

` `**[RF001] Visualizar Componente![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.008.png)**

**Descrição do caso de uso:** Este caso de uso permite que o usuário visualize os dados de um determinado componente (todos os seus atributos, exceto aqueles que são considerados suas propriedades). 

**Prioridade**: Essencial ■ Importante Desejável

**Entradas e pré-condições**: deve receber como entrada o componente que se deseja visualizar.

**Saídas e pós-condição**: o usuário visualiza o componente desejado

**[RF002] Copiar componente![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.009.png)**

**Descrição do caso de uso:** Este caso de uso permite que o usuário copie um componente do cadastro de componentes do sistema. Ou seja, copia o componente de onde ele estava e manda a cópia para a área de transferência.

**Prioridade**: ■ Essencial Importante Desejável

**Entradas  e  pré-condições**:  recebe  como  entrada  o  componente  que  se  deseja 

copiar.

**Saídas e pós-condição**: o usuário consegue copiar o componente que deseja

**[RF003] Colar componentes![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.014.png)**

**Descrição  do  caso  de  uso:**  Este  caso  de  uso  permite  que  o  usuário  cole  o componente armazenado na área de transferência do sistema no local indicado. O conteúdo da área de transferência continua inalterado. Aqui, local refere-se a uma pasta que contém componentes.

**Prioridade**: ■ Essencial Importante Desejável

**Entradas  e  pré-condições**:  recebe  como  entrada  o  componente  que  se  deseja colar e tem como pré-condição a necessidade de existência de alguma informação na área de transferência do sistema.![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.003.png)

Documento de Requisitos Página 8 de 

**Saídas e pós-condição**: o usuário consegue colar o componente no local desejado.

3. **Compilação**

<INSERIR AQUI DIAGRAMAS DE CASO DE USO>

` `**[RF001] Compilar componente![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.015.png)**

**Descrição  do  caso  de  uso:**  Este  caso  de  uso  permite  que  o  usuário  compile metodologias. Essa compilação permite que as metodologias sejam analisadas e comparadas entre si.

**Prioridade**: Essencial ■ Importante Desejável

**Entradas e pré-condições**: deve receber como entrada as metodologias a serem compiladas.

**Saídas  e  pós-condição**:  os  componentes  das  metodlogias  são  compilados  no sistema.

4. **Importação/Exportação**

**[RF001] Anexar documentos![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.016.png)**

**Descrição do caso de uso:** Este caso de uso permite que anexar documentos gerais a componentes. Por exemplo, anexar o *template* do *Documento de Requisitos* ao fluxo de requisitos.

**Prioridade**: Essencial ■ Importante Desejável

**Entradas e pré-condições**: deve receber como entrada o caminho absoluto para um arquivo no sistema de arquivos.

**Saídas e pós-condição**: O documento é anexado ao componente.

**[RF002] Exportar metodologia![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.017.png)**

**Descrição do caso de uso:** Este caso de uso permite ao usuário a possibilidade de exportar uma metodologia num determinado formato, como XML, por exemplo. O usuário  também  tem  a  opção  de  escolher  se  o  componente  deve  ou  não  ser exportado juntamente com seus anexos.![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.003.png)

Documento de Requisitos Página 9 de 

**Prioridade**: ■ Essencial Importante Desejável

**Entradas e pré-condições**: A entrada é uma metodologia a ser exportado e seus sub-componentes,  ou  seja,  todos  os  componentes  que  um  determinada metodologia.

**Saídas e pós-condição**: Os componentes são exportados para um arquivo em um determinado formato (como XML).

**[RF003] Importar metodologia![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.018.png)**

**Descrição do caso de uso:** Este caso de uso permite que componentes de uma metodologia exportada sejam importados do sistema de arquivos e apresentados no *Methodology Explorer*. Os componentes, para serem importados precisam estar no mesmo formato utilizado no caso de uso [Importação/Exportação.RF002]. Importar um componente apenas permite manipular o componente dentro do Methodology Explorer.  Para  inseri-lo  de  fato,  é  preciso  realizar  o  caso  de  uso [Importação/Exportação.RF004]

**Prioridade**: ■ Essencial Importante Desejável

**Entradas e pré-condições**: A entrada é o caminho absoluto para um arquivo no sistema de arquivos.

**Saídas e pós-condição**: O componente importado será inserido na(s) árvore(s) de componentes adequada.

**[RF004] Salvar metodologia![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.019.png)**

**Descrição  do  caso  de  uso:**  Este  caso  de  uso  permite  salvar  as  alterações realizadas nos componentes de uma metodologia. 

**Prioridade**: Essencial ■ Importante Desejável

**Entradas e pré-condições**: A entrada é uma metodologia.

**Saídas e pós-condição**: um componente é persistido no *Methodology Explorer*.

**[RF005] Gerar site de metodologia![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.016.png)**

**Descrição do caso de uso**: Este caso de uso permite que um *site* seja gerado** para uma metodologia já compilada. O site deve conter também os possíveis artefatos que foram anexados.

**Prioridade**: Essencial ■ Importante Desejável![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.003.png) **Entradas e pré-condições**: Um componente metodologia é a entrada para o caso de uso que tem, como pré-condição, que a toda a metodologia já esteja salva.

**Saídas  e  pós-condição**:  um  site  completo  é  gerado  no  sistema  de  arquivos contendo os arquivos HTML e os artefatos anexados à metodologia.

4. **Requisitos não-funcionais![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.020.png)**

Usabilidade

Portabilidade

Desempenho

Não Roda no Internet Explorer

**[NF001] Usabilidade![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.021.png)**

A interface com o usuário é de vital importância para o sucesso do sistema. Principalmente por ser um sistema que não será utilizado diariamente, o usuário não possui tempo disponível para aprender como utilizar o sistema.

O  sistema  terá  uma  interface  amigável  ao  usuário  primário  sem  se  tornar  cansativa  aos usuários mais experientes. Em especial, o módulo de publicação HTML possuirá um wizard para ajudar o usuário.

**Prioridade**: ■ Essencial Importante Desejável

**[NF002] Desempenho![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.022.png)**

Embora  não  seja  um  requisito  essencial  ao  sistema,  deve  ser  considerada  por corresponder a um fator de qualidade de software. 

**Prioridade**: Essencial ■ Importante Desejável

` `**[NF003] Hardware e Software![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.023.png)**

Visando criar um produto com maior extensibilidade, reusabilidade e flexibilidade, deve ser adotar como linguagem principal de desenvolvimento Java seguindo cuidadosamente as técnicas de orientação a objetos. Entretanto, outras linguagens também poderão ser usadas quando indicações técnicas recomendem. 

O uso da linguagem Java permite não especificar qual será o sistema operacional e a máquina em que o programa irá executar. No entanto, essa máquina deverá se comunicar com um sistema de banco de dados.

**Prioridade**: Essencial ■ Importante Desejável![](Aspose.Words.06c16675-061a-4342-a8f7-59730fdfd965.003.png)
Documento de Requisitos Página 11 de 
