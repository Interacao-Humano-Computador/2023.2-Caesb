# Análise de Tarefas

## Introdução

<p align="justify">&emsp;&emsp;A análise de tarefas é utilizada para entender como é o trabalho dos usuários em um sistema descrevendo e detalhando as atividades realizadas para atingir determinados objetivos. Neste projeto, será utilizado a Análise Hierárquica de Tarefas - HTA, como método de análise das funcionalidades do sistema avaliados. </p>

## Análise Hierárquica de Tarefas

<p align="justify">&emsp;&emsp;A análise hierárquica de tarefas - HTA, tem o intuito de analisar e avaliar tarefas complexas por meio da decomposição em objetivos, subobjetivos e operações, seguindo um desdobramento hierárquico. Essa abordagem, pode ser representada por meio de tabelas ou diagramas, como apresentado na figura 1, e proporciona uma visão mais clara e organizada das atividades realizadas por um usuário sendo possível identificar pontos problemáticos e de aprimoramento. </p>

<figure markdown>
<font size="3"><b>Figura 1</b> - Notação dos elementos de um diagrama HTA.</font>

![Notação diagrama HTA](../../assets/analise_de_tarefas/HTAlight_elementos.png#only-light){width: 500}
![Notação diagrama HTA](../../assets/analise_de_tarefas/HTAdark_elementos.png#only-dark){width: 500}

<font size="3"><p style="text-align: center"> Fonte: BARBOSA e SILVA, 2010.</p></font>

</figure>

## Consultar Contas Pagas

<p align="justify">&emsp;&emsp;Nessa tarefa, o usuário precisa acessar a página de consultar contas pagas, realizar login e acessar informações a respeito das faturas pagas listadas com base no mês. A figura 2 e a tabela 1 apresentam, respectivamente, o diagrama e a tabela HTA da tarefa.</p>

<figure markdown>
<font size="3"><b>Figura 2</b> - Diagrama HTA de consulta a Contas Pagas.</font>

![Notação diagrama HTA](../../assets/analise_de_tarefas/HTAlight_fatura_paga.png#only-light){width=500px}
![Notação diagrama HTA](../../assets/analise_de_tarefas/HTAdark_fatura_paga.png#only-dark){width=500px}

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/JeffersonSenaa" target="_blank">Jefferson Sena</a></p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - HTA de consulta a contas pagas.</p></font>


|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                                                               |
| :--------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  0. consultar contas pagas   |                                                                                                                                                                                                         |
|      1.   Acessar a aba Portal de Serviços |**feedback**: usuário é redirecionado para a página Portal de Serviços.<br> **plano**: clicar na imagem portal de serviços - autoatendimento. |
|     2.  Selecionar Contas Pagas | **feedback**: usuário é redirecionado para a página de login.  <br> **plano**: clicar no botão Contas Pagas. |
|       3. Fazer Login  | **input**: Dados de login.<br>  **feedback**: usuário é redirecionado para a página de  inscrições. <br>**plano**: Acessar área de inscrições. <br>|
| 3.1 Pesquisar com minha inscrição   | **feedback**: O usuário é redirecionado para uma página com uma lista de faturas pagas de acordo com o mês.<br>    **plano**: Clicar no botão pesquisar.|
| 3.2 Pesquisar com outra inscrição  | **input**: Inserir o número da inscrição que deseja ter acesso as contas.<br>   **feedback**: O usuário é redirecionado para uma página com uma lista de faturas pagas de acordo com o mês.  <br>    **plano**: Clicar na aba "Pesquisar outra inscrição".|

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/JeffersonSenaa" target="_blank">Jefferson Sena</a></p></font>

</br>

## Consultar Falta de Água

<p align="justify">&emsp;&emsp;Nessa tarefa, o usuário precisa acessar a página de consulta a falta de água e acessar informações a respeito da falta de água em um área de uma região administrativa do DF. A figura 3 e a tabela 2 apresentam, respectivamente, o diagrama HTA da tarefa e o HTA em tabela</p>

<figure markdown>
<font size="3"><b>Figura 3</b> - Diagrama HTA de consulta a falta d'água.</font>

![Notação diagrama HTA](../../assets/analise_de_tarefas/HTAlight.png#only-light){width=500px}
![Notação diagrama HTA](../../assets/analise_de_tarefas/HTAdark.png#only-dark){width=500px}

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/Tiago1604" target="_blank">Tiago Albuquerque</a></p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - HTA de consulta a falta d'água.</p></font>

|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                                                               |
| :--------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  0. consultar falta de água   |                                                                                                                                                                                                         |
|      1. Acessar página de consulta a partir da tela inicial|**feedback**: usuário é redirecionado para a página de consulta.<br> **plano**: clicar no botão do menu da tela incial. |
|     1.1 Selecionar o botão no menu inicial | **input**: No botão "água" do menu, escolher a opção "Consultar Falta de água."<br>**feedback**: página de consultas a falta de água é carregada.|
|       2. Consultar falta de água em uma área da região| **feedback**: a página de consultas a falta de água é carregada.<br>**plano**: inserir a informações de consulta. <br>|
| 2.1 Selecionar a região na barra de pesquisa  | **input**: inserir a região a ser consultada barra de pesquisa "RA".<br>**feedback**: A região é mostrada se houver falta de água.<br>|
| 2.2 Selecionar a área na barra de pesquisa  | **input**: inserir a área a ser consultada barra de pesquisa "Área Afetada".<br>**feedback**: A área da região escolhida é mostrada se houver falta de água<br>|

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/Tiago1604" target="_blank">Tiago Albuquerque</a></p></font>
</br>

## Emitir segunda via da conta

<p align="justify">&emsp;&emsp;Nessa tarefa, o usuário precisa acessar a página de segunda via da conta, realizar login e acessar as informações a respeito da conta. A figura 4 e a tabela 3 apresentam, respectivamente, o diagrama e a tabela HTA da tarefa.</p>

<figure markdown>
<font size="3"><b>Figura 4</b> - Diagrama HTA de emissão de segunda via.</font>

<center>

![Notação diagrama HTA](../../assets/analise_de_tarefas/HTAlight_segunda.png#only-light){width=500px}
![Notação diagrama HTA](../../assets/analise_de_tarefas/HTAdark_segunda.png#only-dark){width=500px}

</center>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/leomitx10" target="_blank">Leandro de Almeida</a></p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - HTA de emitir segunda via da conta.</p></font>


|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                                                               |
| :--------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  0. Acessar o site da Caesb   |                                                                                                                                                                                                         |
| 1. Clique no botão segunda via da conta |**feedback**: usuário é redirecionado para a página de autenticação.<br>|
| 2. Faça login | **input**: Dados de login.<br>**feedback**: o usuário é redirecionada para a página de segunda via.|
| 3. Clique em pesquisar | **feedback**: o usuário será redirecionado para uma página com todas as suas contas.<br>|
| 4. Localize a conta  | **plano**: o usuário deve achar a conta desejada.<br>|
| 4.1 Clique em código de barras  | **feedback**: o download de um PDF contendo um código de barras irá começar.<br>|
| 4.2 Clique em download  | **feedback**: o download da segunda via em formato de PDF irá começar. <br>|

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/leomitx10" target="_blank">Leandro de Almeida</a></p></font>

</center>


## Informar vazamento na rua

<p align="justify">&emsp;&emsp;Para essa tarefa o objetivo do usuário seria informar à CAESB um vazamento de água ou esgoto no endereço em questão. A figura 5 e a tabela 4 abaixo apresenta o diagrama e a tabela HTA dessa tarefa.</p>


<center>
  
<font size="3"><b>Figura 5</b> - Diagrama HTA para informar vazamento na rua.</font>


![Notação diagrama HTA](../../assets/analise_de_tarefas/../../assets/analise_de_tarefas/HTAlight_Vazamento.png#only-light){width=500px}
![Notação diagrama HTA](../../assets/analise_de_tarefas/diagrama hta darkP.png#only-dark){width=500px}


</center>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/Muniz2811" target="_blank">Pedro Henrique</a></p></font>

<font size="3"><p style="text-align: center"><b>Tabela 4</b> - HTA para informar vazamento na rua.</p></font>

|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                                                               |
| :--------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|0.Informar vazamento na rua.| | 
|1.Acessar o portal de serviços.| **input** : Selecionar na tela inicial a opção de portal de serviços.<br> **feedback**:  Redirecionado para a tela de portal de serviços.<br> **Plano** : Acessar o portal de serviços para informar o vazamento na rua.|
|1.1. Realizar login.| **Input**: Dados para login.<br>**Feedback**:Redirecionado para o portal de serviços.<br>**Plano**: Realizar o login e prosseguir para a área de portal de serviços.|
|2. Selecionar a opção de informar vazamento.| **Input**: Apertar o botão “Informar vazamento na rua”.<br> **Feedback**: Redirecionamento para o formulário para informar vazamento.<br> **Plano**: Obter um formulário para preencher o endereço do vazamento.|
|3. Preencher formulário com endereço do vazamento. | **Input**: Dados do endereço com vazamento e dados da pessoa que está reportando o problema.<br> **Plano** : Fornecer o endereço do vazamento e confirmar o envio para a CAESB.|
|4. Enviar o formulário.| **Input**: Selecionar o botão informar vazamento na rua.<br> **Feedback**: Confirmação do envio ou indicação de algum dado obrigatório que falta no formulário.|

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/Muniz2811" target="_blank">Pedro Henrique</a></p></font>


## Revisão de Conta 
<p align="justify">&emsp;&emsp; Nessa tarefa, o usuario ira fazer a revisão das suas contas, onde ele precisa acessar o site da caesb, acessar a pagina revisão de conta, fazer o login, selecionar a residência onde queira fazer a revisão, selecionar a conta a ser revisada e por fim clicar no botão "Selecionar revisão".</p>

<figure markdown>
<font size="3"><b>Figura 6</b> - Diagrama HTA da Revisão de contas.</font>

![Notação diagrama HTA](../../assets/analise_de_tarefas/HTAlight_Revisão.png#only-light){width=500px}
![Notação diagrama HTA](../../assets/analise_de_tarefas/HTAdark_Revisão.png#only-dark){width=500px}

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/rodfon3301" target="_blank">Rodrigo Fonseca</a></p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 5</b> - HTA da Revisão de Conta.</p></font>

|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                                                               |
| :--------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  1. Acessar o site da Caesb   |                                                                                                                                                                                                         |
| 1.1 Acessar pagina de Revisão de Conta |*feedback*: usuário é redirecionado para a página de Revisão de conta.<br>|
| 1.2 Faça login | *input: Dados de login.<br>feedback*: o usuário é redirecionada para a página de selecionar a residencia a ser revisada via.|
| 2. Selecionar a residência desejada | *feedback*: o usuário escolhe a residência a ser revisada.<br>|
| 2.1 Selecionar a conta a ser revisada  | *plano*: o usuário escolhe qual conta que ele quer revisar.<br>|
| 2.2 Clique no botão Solicitar Revisão  | *feedback*: o usuário solicita a revisão, onde ela vai ser revisada pela caesb onde alvaliará se é procedente a sua ação.<br>|

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/rodfon3301" target="_blank">Rodrigo Fonseca</a></p></font>


## Consultar Qualidade da Água  

<p align="justify">&emsp;&emsp; Nessa tarefa, o usuario ira consultar a qualidade da água em sua região administrativa. No qual ele precisa acessar o site da caesb, acessar o menu "Água", acessar o submenu "Controle de Qualidade", selecionar "Análises e Resultados", por fim clicar em  "Resultados na Rede de Distribuição - Síntese por Sistemas de Abastecimento" ou  "Qualidade da Água Distribuída" ou "Relatório Anual da Qualidade da Água". Caso selecionado "Relatório Anual da Qualidade da Água", clicar no ano desejado. </p>

<figure markdown>
<font size="3"><b>Figura 7</b> - Diagrama HTA Qualidade.</font>

![Notação diagrama HTA](../../assets/analise_de_tarefas/HTAlight_qualidade.png#only-light){width=500px}
![Notação diagrama HTA](../../assets/analise_de_tarefas/HTAdark_qualidade.png#only-dark){width=500px}

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/mateus9levy" target="_blank">Mateus Levy</a></p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 6</b> - HTA da Qualidade da Água.</p></font>

|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                                                               |
| :--------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  0. Consultar qualidade da água  |                                                                                                                                                                                                         |
| 1. Acessar a aba Água |*plano*: usuário é deve acessar o submenu Controle de Qualidade.<br>|
| 2. Selecionar submenu Controle de Qualidade | *feedback*: Abrirá um submenu chamando "Analises e Resultados" |
| 3. Selecionar Análise e Resultados | *feedback*: o usuário será redirecionado para a página de Analises e Resultados.<br>|
| 3.1 Resultados na Rede de Distribuição - Síntese por Sistemas de Abastecimento  | *feedback*: o usuário será redirecionado para um pdf contendo uma análise mensal detalhada por sistema de abastecimento.<br>|
| 3.2 Qualidade da Água Distribuída  | *feedback*: o usuário será redirecionado para um pdf contendo uma análise mensal detalhada por sistema de abastecimento. <br>|
| 3.3 Relatório Anual da Qualidade da Água | *feedback*: o usuário será redirecionado para uma página contendo os relatórios anuis <br>|
| 3.3.1 Selecionar o ano desejado| *plano*: o usuário deverá escolher  relatório do ano que deseja <br>|

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/mateus9levy" target="_blank">Mateus Levy</a></p></font>


## Situação de débitos

<p align="justify">&emsp;&emsp;Nessa tarefa o usuário precisa acessar a área de autoatendimento, clicar em situação de débito, efetuar o login e  verificar a situação de suas respectivas contas. A figura 5 e a tabela 4 apresentam, respectivamente, o diagrama e a tabela HTA da tarefa.</p>

<center>

<font size="3"><b>Figura 8</b> - Diagrama HTA de Situação de débitos.</font>



![Notação diagrama HTA](../../assets/analise_de_tarefas/Blankdiagram .png#only-light){width=500px}

![Notação diagrama HTA](../../assets/analise_de_tarefas/Blank diagram(black).png#only-dark){width=500px}

</center>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/OscarDeBrito" target="_blank">Oscar de Brito</a></p></font>

<font size="3"><p style="text-align: center"><b>Tabela 7</b> - HTA de situação de débito.</p></font>


|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                                                               |
| :--------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  0. Acessar o site da Caesb   |                                                                                                                                                                                                         |
| 1. Clique em portal de serviço de atendimento |**feedback**: usuário é redirecionado para a página de atendimentos.<br>|
| 2. Clique no botão situação de débitos | **feedback** : usuário e redirecionado para a paǵina de efetuar login|
| 3. Faça login |**input**: Dados de login.<br>**feedback**: o usuário é redirecionada para a página de situações de débitos.|
| 3. Clique em pesquisar | **feedback**: o usuário será redirecionado para uma página com todos os débitos.<br>|
| 4. O download do arquivo com os débitos será executado automatimente  | **feedback**: o download dos débitos em PDF irá começar e o usuário será redirecionado para a página de download de débitos.<br>|
| 4.1. O download do arquivo com débito não será executado automaticamente  | **feedback**: O usuário será redirecionado para a página de download de débitos <br>|
| 5. Clique no botão de download  | **feedback**: o download dos débitos em PDF irá começar. <br>|


<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/OscarDeBrito" target="_blank">Oscar de Brito</a></p></font>


## Referências 

> <p id="1" align="justify"> 1. BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2010.</p>


## Bibliografia

> <p id="4" align="justify">1. Bilheteria Digital. Análise Hierárquica de Tarefas. Repositório do Grupo Bilheteria Digital da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/analise-de-tarefas/hta/. Acesso em: 16 de out. 2023.</p>

## Histórico de versão


| Versão |    Data    |      Descrição       |  Autor(es) | Revisor(es) |
| :----: | :--------: | :------------------: | :-----: | :-----: |
|  1.0   | 14/10/2023 | Adicionando Análise de Tarefas | Jefferson | Tiago |
|  1.1   | 15/10/2023 | Adicionando Análise de Tarefas | Tiago | Jefferson |
|  1.2   | 15/10/2023 | Adicionando Análise da consulta a contas pagas | Jefferson | Tiago |
|  1.3   | 15/10/2023 | Adicionando emição da segunda via | Leandro | Oscar |
|  1.4   | 16/10/2023 | Adicionando Revisão de contas | Rodrigo | Leandro |
|  1.5   | 16/10/2023 | Adicionando Qualidade da Água | Mateus | Leandro |
|  1.6   | 16/10/2023 | Adicionando Situação de débito | Oscar | Leandro |
|  1.7   | 17/10/2023 | Correção da Análise de Tarefas | Jefferson e Tiago | Rodrigo e Mateus |
