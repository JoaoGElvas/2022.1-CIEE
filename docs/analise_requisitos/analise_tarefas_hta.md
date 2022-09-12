# Análise de Tarefas

## Introdução

&emsp;&emsp;A analise de tarefas em IHC é utilizada principalmente para buscar um maior entendimento sobre o trabalho dos usuários, como eles o realizam e o porquê. O trabalho então é organizado em objetivos que os usuários necessitam ou querem atingir, com o resultado do trabalho se busca definir um “desempenho satisfatório” para o sistema e seus componentes. Esta analise pode ocorrer em diferentes etapas do desenvolvimento do sistema, seja para uma analise de situação atual, um (re)design de um sistema ou para uma avaliação que inclua uma introdução de um novo sistema.

## HTA – Análise Hierárquica de tarefas

&emsp;&emsp;Desenvolvida na década de 1960, esta analise busca entender as competências e habilidades apresentadas em tarefas bem definidas e não repetitiva, busca também auxiliar na identificação de problemas de desempenho, já que o caminho das tarefas proposto deve ser um caminho ideal. É uma técnica que se baseia na psicológica funcional, buscando entender e relacionar o que as pessoas fazem, por que o fazem e quais as consequências caso não façam corretamente as tarefas.

&emsp;&emsp;A HTA começa pela definindo um objetivo principal a ser atingido, sendo este um estado final ou especifico de passos, pode ser definido por um ou mais eventos ou por valores fisicamente observáveis de uma ou mais variáveis que atuam como critério para alcance desse objetivo.

&emsp;&emsp;Após a definição do objetivo de alto nível a HTA o decompõe em subobjetivos, que vão auxiliar a identificar quais os pontos de maior dificuldade e que limitam o alcance ao objetivo maior, com os subobjetivos e as relações entre eles definidas, temos a criação de um plano. No plano podemos ter diferentes tipos de relação entre subobjetivos, que são: sequencial, seleção ou paralela, para cada subobjetivo ser alcançado, deve-se definir uma operação, que é a unidade fundamental do HTA. A figura a seguir apresenta os elementos de um diagrama HTA:

| ![elementosHTA](https://user-images.githubusercontent.com/79341819/180094488-b25dff3f-844d-40c3-9245-1d049b642ab8.png) |
|:--:|
| *(Figura 1) Elementos de um diagrama HTA - Retirado de: BARBOSA, Simone. SILVA Bruno. "Interação Humano-Computador". Capítulo 6, página 193.* |

## Diagramas e tabelas

### Diagrama do objetivo preencher perfil:
| ![preencherperfil](https://user-images.githubusercontent.com/79341819/180103773-0c28f696-1a99-4b4c-abfe-f574da2edcb0.png) |
|:--:|
|*(Figura 2) Diagrama do "objetivo preencher perfil"*|

### Representação em Tabela do objetivo preencher perfil

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|---------------------------|
| 0. Preencher Perfil |  |
| 1. Fazer Login | **Plano**: entrar com um perfil no site <br> **Feedback:** usuário logado no sistema. |
| 1.1. Inserir Usuário| **Input**: campo de usuario <br> **Ação**: digitar cpf ou um codigo do usuário |
| 1.2. Inserir Senha | **Input**: campo de senha <br> **Ação:** digitar senha do usuário|
| 2. Inserir Dados |  |
| 2.2 Inserir Dados Pessoais| **Plano:** cadastrar dados pessoais do usuário <br> **Feedback:** dados pessoais cadastrados no sistema |
| 2.2.1 Inserir Dados de Conta Bancária | **Input:** campos relacionados a conta bancaria |
| 2.2.2 Inserir Contatos| **Input:** campos de telefones e emails |
| 2.2.3 Inserir Dependentes| **Ação:** adicionar filhos/conjuge casso possua  |
| 2.2.4 Inserir Endereços | **Input:** campos relacionados ao endereço |
| 2.2.5 Inserir Informações Pessoais | **Input:** campos de gênero, estado civil, carteira de trabalho, nacionalidade, etc |
| 2.2.6 Inserir Informações Sociais |  **Ação:** preencher questionário socioeconômico e ações voluntárias |
| 2.2.7 Inserir Deficiência| **Ação:** informar deficiência caso possua |
| 2.2 Preencher Currículo|  |
| 2.2.1 Realizar Análise Comportamental | **Feedback:** resultado da análise com um perfil do usuário |
| 2.2.2 Inserir Escolaridade| **Input:** campos de nota do enem e dados escolares primário e secundário |
| 2.2.3 Inserir Idiomas| **Input:** campos de idioma e nivel |
| 2.2.4 Inserir Conhecimentos | **Ação:** adicionar conhecimentos e/ou treinamento adicionais |
| 2.2.5 Inserir Experiência Profissional | **Input:** botão de adicionar experiência <br> **Ação:** preencher informações de empresa e cargo |
| 2.2.6 Realizar Redação | **Ação:** escolher tema e escrever redação |

### Diagrama do objetivo candidatar a vaga:
| ![candidatarVagas](https://user-images.githubusercontent.com/79341819/180103620-c3ea1e28-4d3b-4a69-a033-0dd28dd4ce2e.png) |
|:--:|
|*(Figura 3) Diagrama do "objetivo candidatar vagas"*|

### Representação em Tabela do objetivo candidatar vaga

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|---------------------------|
| 0. Candidatar Vaga |  |
| 1. Fazer Login | **Plano**: entrar com um perfil no site <br> **Feedback**: usuário logado no sistema. |
| 1.1. Inserir Usuário | **Input**: campo de usuario <br> **Ação**: digitar cpf ou um codigo do usuário |
| 1.2. Inserir Senha | **Input**: campo de senha <br> **Ação**: digitar senha do usuário|
| 2. Acessar Pagina de vagas | |
| 2.1. Consultar Vagas Abertas| **Plano**: consultar as vagas disponiveis <br> **Feedback:**: lista das vagas disponiveis  |
| 2.1.1 Aplicar Filtros | **Input**: campo de filtragem de vagas <br> **Ação**: filtrar as vagas <br> **Feedback**: lista de vagas filtradas |
| 2.2. Consultar Informações da Vaga | **Feedback**: lista de informações sobre a vaga |
| 2.3. Aceitar Vaga| **Input**: botão de aceitar vaga <br> **Feedback**: usuario concorrendo a vaga |

## Referências Bibliográficas
BARBOSA, Simone. SILVA Bruno. "Interação Humano-Computador"

## Versionamento
|Versão	| Data	| Descrição |	Autor(s)	| Revisor(s)|
|--------|----|-----------|-------|---------|
| 1.0 |	20/07/2022	| Criação do artefato de análise de tarefas| Davi Lima e Karla Chaiane | Guilherme Nishimura |