# Criar-banco-de-dados
Banco de dados
```mermaid
graph TD;
    A[Código Python] --> B[Conectar ao Banco de Dados]
    B --> C[Criar Tabela]
    A --> D[Adicionar Tarefa]
    D --> E['Estudar Python', '2024-07-01']
    A --> F[Adicionar Tarefa]
    F --> G['Fazer compras', '2024-06-30']
    A --> H[Adicionar Tarefa]
    H --> I['Preparar apresentação', '2024-07-05']
    A --> J[Obter Todas as Tarefas]
    J --> K[SELECT * FROM tasks]
    A --> L[Completar Tarefa]
    L --> M[1]
    M --> N[Marcar como 'Concluída']
    A --> O[Deletar Tarefa]
    O --> P[2]
    P --> Q[Deletar tarefa com ID 2]

```
