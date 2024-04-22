# REQUISITOS FUNCIONAIS

1. Agendamento de tarefas:
     * Cadastro de **listas**, onde as tarefas são *agrupadas* de acordo com um **objetivo** especificado pelo usuário.
     * Os usuários podem **atribuir, alterar ou excluir** tarefas em uma lista.
     * As tarefas possuem um **conteúdo e um prazo** determinado.
2. Lembretes e notificações:
     * O sistema **alerta** o usuário com **notificações** de acordo com o prazo de uma tarefa agendada.
     * Os usuários são capazes de **criar, alterar e excluir** lembretes.
     * Os lembretes *podem* independer das tarefas.
     * O **calendário** é um recurso que facilita a visualização das tarefas e lembretes existentes.

A tabela abaixo descreve os requisitos levantados acima, considerando a **prioridade** correspondente.
  
| ID      |                                 Requisito                                         | Prioridade | Requisitos Relacionados |
| :--:     | :-----------------------------------------------------------------------: | :------------: | :--------------------------------: |
| RF01 | O software deve permitir o usuário cadastrar e gerenciar **listas** de tarefas.                    |  Alta          |   -     |
| RF02 | O software deve permitir o usuário **criar, alterar e excluir** tarefas da lista     |  Alta           |  RF01   |
| RF03 | O software deve informar o usuário que este **precisa** atribuir um *conteúdo* e um *prazo* para a tarefa .   |  Alta  |      RF02      |
| RF04 | O software deve permitir o usuário poder **criar, alterar e excluir** lembretes.                 |  Média    |     RF03   |
| RF05 | O software deve permitir o usuário criar lembretes que não *pertencem* às tarefas.   |  Média   |  RF04           |
| RF06 | O software deve permitir o usuário poder **visualizar** as tarefas e lembretes existentes em um **calendário**.  |  Baixa   |  RF02, RF04  |


<div style="text-align: center">
<p>Tabela 1: Requisitos Funcionais</p>
</div>
