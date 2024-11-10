# Especificações do Projeto

### Requisitos Funcionais

| ID      | Descrição do Requisito                                                                                 | Prioridade |
|---------|--------------------------------------------------------------------------------------------------------|------------|
| RF-01   | O sistema deve permitir que o usuário crie tarefas principais.                                         | ALTA       |
| RF-02   | O sistema deve permitir que o usuário crie subtarefas para uma tarefa principal ou subtarefa.          | ALTA       |
| RF-03   | O sistema deve permitir que o usuário associe uma tarefa principal a um dia e horário da semana.       | ALTA       |
| RF-04   | O sistema deve permitir que o usuário crie textos formatados dentro de suas tarefas e subtarefas.      | MÉDIA      |
| RF-05   | O sistema deve permitir que o usuário crie uma ZettelKasten                  | BAIXA      |
| RF-06   | O sistema deve permitir que o usuário visualize suas ZettelKasten                  | BAIXA      |
| RF-07   | O sistema deve permitir a criação de flashcards associados a uma tarefa principal.                                    | BAIXA      |
| RF-08   | O sistema deve apresentar os flahscards em formato de quiz                                    | BAIXA      |
| RF-09   | O sistema deve mostrar o status de uma tarefa principal.                                               | MÉDIA      |
| RF-10   | O sistema deve permitir que o usuário envie convite para outros usuários participarem de uma tarefa principal. | BAIXA      |
| RF-11   | O sistema deve permitir que os usuários de uma tarefa marquem reuniões.                                | BAIXA      |
| RF-12   | O sistema deve permitir que o usuário edite o horário, dia e a duração das sessões.                    | MÉDIA      |
| RF-13   | O sistema deve permitir que o usuário visualize as tarefas a serem realizadas na semana, bem como visualizar somente as que serão realizadas no dia em que está acessando o sistema. | MÉDIA      |
| RF-14   | O sistema deve permitir que o usuário realize login.                                                   | MÉDIA      |
| RF-15   | O sistema deve permitir que o usuário realize auto-registro e gerenciamento de suas credenciais de acesso. | MÉDIA      |
| RF-16   | O sistema deve permitir que o usuário inicie uma sessão de uma tarefa principal, no dia e horario marcado e pelo tempo registrado. | MÉDIA      |
| RF-17   | O sistema deve permitir que o usuário visualize as tarefas princiais e subtarefas. | MÉDIA      |
| RF-17   | O sistema deve conter "caderno" para o usuario fazer anotaçoes, simulando a liberdade do papel e caneta | MÉDIA      |


### Requisitos não Funcionais

| ID      | Descrição do Requisito                                                                               | Prioridade |
|---------|------------------------------------------------------------------------------------------------------|------------|
| RNF-01  | Na criação de tarefas, o usuário deve adicionar um título, descrição, representante, dia da semana, horário e tempo da sessão. | MÉDIA      |
| RNF-02  | O sistema deve estar disponível 99% do tempo durante todos os dias da semana.                        | MÉDIA      |
| RNF-03  | O sistema deve funcionar em diferentes plataformas.                                                  | MÉDIA      |
| RNF-04  | As listas TODO não devem afetar o progresso da tarefa principal a que estão associadas.              | MÉDIA      |
| RNF-05  | As tarefas principais devem sempre mostrar o valor atual de seu progresso, bem como quantas subtarefas estão pendentes. | MÉDIA      |
| RNF-06  | Para que uma reunião seja agendada, todos os membros de uma tarefa devem aceitar o convite, que pode ser criado por qualquer membro. | MÉDIA      |
| RNF-07  | O progresso de tarefas e subtarefas deve estar sempre atualizado, sendo que a última subtarefa marcada como concluída calcula o progresso. | MÉDIA      |
| RNF-08  | O tempo de carregamento da interface deve ser no máximo 3 segundos.                                  | MÉDIA      |
| RNF-09  | O sistema deve garantir que todas as edições sejam refletidas imediatamente na interface.            | MÉDIA      |



## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

![diagrama de caso de uso](./imgs/Diagrama%20caso%20de%20uso.png)

