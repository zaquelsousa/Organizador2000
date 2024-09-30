# Especificações do Projeto

Nesta etapa seria onde deveria ser feito uma idealização da solução partindo da pespectiva do usuario, onde as necessidades do usuario seriam identificadas atravezes da criaçao de personas e historias de usuarios, para isso é importante conhecer o publico alvo do problema que se busca solucionar, porem como este projeto é algo pessoal eu optei por não fazer uma pesquisa sobre o publico algo, desta forma nao ha como identificar corretamente as personas e suas dores, optei entao por nao fazer, pois como falei isso é o um projeto pessoal, assim eu pulei direto para o levantamento de requisitos. 

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-01| O sistema deve permtir que o usuario crie tarefas principais | ALTA | 
|RF-02| o sistema deve permitir que o usuario crie subtarefas para uma tarefa princial ou subtarefa| ALTA | 
|RF-03| O sistema deve permitir que o usuario associe uma tarefa princiapl a um dia e horario da semana | ALTA | 
|RF-04| O sistema deve permitir que o usuario cria textos formatados dentro de suas tarefas e sub-tarefas | MEDIA | 
|RF-05| O sistema deve permitir que o usuario crie listas TODO acossiadas a tarefa princiapal | BAIXA | 
|RF-06| o sistema deve conter fleshCards associadas a uma tarefa princiapal | BAIXA | 
|RF-07| o sistema deve mostrar o status de uma tarefa princiapal | MEDIA | 
|RF-08| o sistema deve permitir que o usuario envie convite para outros usuario participarem de uma tarefa princial | BAIXA | 
|RF-09| o sistema deve permitir que os usuario de uma tarefa marquem reunioes | BAIXA | 
|RF-10| o sistema deve permitir que o usuario edite o horario, dia e a duraçao das sessoes | MEDIA | 
|RF-11| o sistema deve permitir que o usuario vizualize as tarefas a serem realizadas na semana sem formado de grade, bem como vizualizar somente as que vao ser realizadas no dia em que esta acessando o sistema| MEDIA | 
|RF-12| o sistema deve permitir que o usuario realize login| MEDIA | 
|RF-11| o sitema deve permitir que o usuario realize auto registro e gerenciamento de suas credenciais de acesso | MEDIA | 


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-01| A criação de tarefas o usuario deve adcionar um titulo, descrição, representante, dia da semana, horario, tempo da sessao | MÉDIA | 
|RNF-02| o sistema deve estar disponeivel 99% do tempo durante todos os dias da semana | MÉDIA | 
|RNF-03| o sistema deve funcionar em diverentes plataformas | MÉDIA | 
|RNF-04| as listas TODO nao devem afetar o progresso da tarefa princiapal que esta associada | MÉDIA | 
|RNF-05| as tarefas princiapis devem sempre mostrar o valor atual de seu progresso, bem como quantas subtarefas estao peendentes | MÉDIA | 
|RNF-06| para seja agenda uma reunião todos os membros de uma tarefa devem aceitar o convite, o convite pode ser criado por qualquer membro | MÉDIA | 
|RNF-07| o progresso de tarefas e subtarefas devem sempre estarem atualizados, sendo que a ultima subtarefa que sera possivel de se marcar como concluida e apatir dela o progresso sera calculado | MÉDIA | 
|RNF-08| o tempo de carregamento da interfaçce deve ser no maximo 3 segundos | MÉDIA | 
|RNF-09| o sistema deve garantir que todas as edições sejam refletidas imediatamente na interfaces | MÉDIA | 


## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

![diagrama de caso de uso](./imgs/Diagrama%20caso%20de%20uso.png)