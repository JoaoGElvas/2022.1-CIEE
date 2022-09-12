## Introdução

O modelo de árvores de tarefas concorrentes (ConcurTaskTrees - CTT) é utilizado para ajudar a avaliação e o design de IHC (Paterno, 1999, apud Barbosa, 2021). 

Esse modelo é composto por quatro tipos de tarefas, definidas como do usuário, do sistema, interativas e abstradas, como explicado a seguir:

- Tarefas do usuário: são realizadas fora do sistem;
- Tarefas do sistema: são realizadas pelo sistema em um processamento sem interagir com o usuário;
- Tarefas interativas: ocorrem os diálogos usuário-sistema;
- Tarefas abstratas: não são tarefas em si, mas sim uma representação de uma composição de tarefas que auxilie a decomposição.

As representações desses tipos é demonstrado a seguir na Figura 1:

<center>
![tiposctt](https://user-images.githubusercontent.com/78981063/189671459-8dd94b54-f034-476c-9e3e-995275318af6.png)

*Figura 1: Representação dos tipos de tarefas no CTT*  
<small>Fonte: Barbosa, 2021</small></center>

Além da hierarquia, o CTT também permite que as relações entre tarefas tenham diversas representações, que aumentam a expressividade da notação. Esses significados são:

- Ativação: T1 >> T2 significa que a segunda tarefa (T2) só pode iniciar após a primeira tarefa (T1)
terminar;
- Ativação com passagem de informação: T1 [] >> T2 especifica que, além de T2 só poder ser iniciada
após T1, a informação produzida por T1 é passada para T2;
- Escolha (tarefas alternativas): T1 [] T2 especifica duas tarefas que estejam habilitadas num momento,
mas que, uma vez que uma delas é iniciada, a outra é desabilitada;
- Tarefas concorrentes: T1 ||| T2 especifica que as tarefas podem ser realizadas em qualquer ordem ou
ao mesmo tempo;
- Tarefas concorrentes e comunicantes: T1 |[]| T2 especifica que, além de as tarefas poderem ser
realizadas em qualquer ordem ou ao mesmo tempo, elas podem trocar informações;
- Tarefas independentes: T1 | = | T2 especifica que as tarefas podem ser realizadas em qualquer ordem,
mas quando uma delas é iniciada, precisa terminar para que a outra possa ser iniciada;
- Desativação: T1 [> T2 especifica que T1 é completamente interrompida por T2;
- Suspensão/retomada: T1 | > T2 especifica que T1 pode ser interrompida por T2 e é retomada do
ponto em que parou assim que T2 terminar.

Essas relações são demonstradas na seguinte Figura 2:

<center>
![relaçõesctt](https://user-images.githubusercontent.com/78981063/189676006-60d4a039-e654-4b69-9fc7-d8de76267e76.png)

*Figura 2: Representação dos tipos de tarefas no CTT*  
<small>Fonte: Barbosa, 2021</small></center>

## Árvore Concorrente de Tarefas 

Aplicando os conceitos da CTT, foi gerado o seguinte diagrama da Figura 3, abordandos as principais tarefas do site, que são as de preencher perfil e cadidatar-se a vagas.

<center>
![ctt](https://user-images.githubusercontent.com/78981063/189704276-ddbdc3d3-a7b6-409d-a134-a0d55ce5be7f.png)

*Figura 3: Árvore de tarefas concorrentes de preencher perfil e candidatar a vaga*  
<small>Fonte: Autoria própria</small></center>

## Referências Bibliográficas
BARBOSA, Simone. Barbosa, Junqueira (et. al.). "Interação Humano-Computador e experiência do usuário". 2021.

## Versionamento
| Versão | Data       | Descrição                                     | Autor(s)      | Revisor(s) |
| ------ | ---------- | --------------------------------------------- | ------------- | ---------- |
| 1.0    | 12/09/2022 | Criação do documento e análise de tarefas CTT | Karla Chaiane | Davi Lima  |