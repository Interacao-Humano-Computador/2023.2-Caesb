# Análise de Tarefas

## Introdução

<p align="justify">&emsp;&emsp;A análise de tarefas é utilizada para entender como é o trabalho dos usuários em um sistema descrevendo e detalhando as atividades realizadas para atingir determinados objetivos. Neste projeto, será utilizado a Análise Hierárquica de Tarefas - HTA, como método de análise das funcionalidades do sistema avaliado. </p>

## Análise Hierárquica de Tarefas

<p align="justify">&emsp;&emsp;A análise hierárquica de tarefas - HTA, tem o intuito de analisar e avaliar tarefas complexas por meio da decomposição em objetivos, subobjetivos e operações, seguindo um desdobramento hierárquico. Essa abordagem, pode ser representada por meio de tabelas ou diagramas e proporciona uma visão mais clara e organizada das atividades realizadas por um usuário sendo possível identificar pontos problemáticos e de aprimoramento.  Utilizando este método, foi selecionado as tarefas que serão analisadas, são elas: consultar contas pagas e consultar serviços relacionados a água e saneamento.</p>


## Consultar Contas Pagas

## Consultar falta de água

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
</br>
## Referências 
> <p id="1"> 1. BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2010.</p>

> <p id="3">3. Bilheteria Digital. Disnível em> <a href="https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/analise-de-tarefas/hta/">https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/analise-de-tarefas/hta/</a>. Acesso em 14 de outubro de 2023.</p>


## Histórico de versão
<center>

| Versão |    Data    |      Descrição       |  Autor(es) | Revisor(es) |
| :----: | :--------: | :------------------: | :-----: | :-----: |
|  1.0   | 14/10/2023 | Adicionando Análise de Tarefas | Jefferson | Tiago |
|  1.1   | 15/10/2023 | Adicionando Análise de Tarefas | Tiago | Jefferson |
</center>
