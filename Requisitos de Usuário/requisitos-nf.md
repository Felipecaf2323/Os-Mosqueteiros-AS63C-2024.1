# REQUISITOS NÃO FUNCIONAIS

1. Requisitos para o **front end**:
  * A interface deve ser implementada em *Java Script* utilizando o framework **React**.
  * Os **formulários** possibilitarão a **criação, alteração** e **remoção** de **listas** de tarefas, **tarefas** e **lembretes**.
  * O arranjo dos **componentes** e o *design* geral favorecerá a experiência do usuário.
  * A ***interface*** precisa garantir que o usuário **NÃO** deixará nenhuma tarefa sem conteúdo ou prazo.

2. Requisitos para o **back end**:
  * O banco de dados deve ser implementado em **MySQL** e a configuração do servidor com o framework **Node**. 
  * O servidor deve permanecer **estável** em sua carga, lidando com as rotas e solicitações HTTP previstas.
   * O sistema deve **validar** (e filtrar) as entradas, garantindo que o **cadastro** e as **notificações** são gerenciadas corretamente.
  * A **regra de negócios** para a criação do banco deve facilitar a *manutenção* e, consequentemente, garantir a **segurança** dos dados.

A tabela abaixo descreve os requisitos citados acima de acordo com a categoria e prioridade.

| ID   |                                 Requisito NF                              | Categoria/Tipo | Prioridade | Requisitos Relacionados |
| :--: | :-----------------------------------------------------------------------: |:-------------: | :--------: | :-----------------: |
| RNF01 |  Interface deve ser implementada em **JavaScript** usando **React**. | Organizacional/Implementação               |Alta       |    -             |
| RNF02 |  Uso de **formulários** para **criação, alteração** e **remoção** de **listas** de tarefas, **tarefas** e **lembretes**.     |  Organizacional/Implementação     |Alta        |    RNF01          |
| RNF03 |  O design precisa favorecer a **experiência de usuário**.              |  Produto/Usabilidade      | Alta       |     RNF01, RNF02              |
| RNF04 |  A interface **não** deve permitir tarefas sem conteúdo.              |  Produto/Consistência       | Alta       |     RNF02               |
| RNF05 |  Implementação do banco de dados deve ser em **MySQL** e o servidor configurado com o **Node**.              |  Organizacional/Implementação      | Alta       |     -               |
| RNF06 |  Servidor deve permanecer **estável** em sua *carga*.       | Produto/Segurança       |     Alta              | RNF05
| RNF07 |   O sistema deve **validar** (e *filtrar*) as entradas.       | Organizacional/Implementação       |    Média              | RNF05, RNF06
| RNF08 |   A **regra de negócios** para a criação do banco deve facilitar a manutenção.       | Organizacional/Implementação       |    Média              | RNF06

<div style="text-align: center">
<p>Tabela 2: Requisitos Não Funcionais</p>
</div> 