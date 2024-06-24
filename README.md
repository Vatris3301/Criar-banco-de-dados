# Criar-banco-de-dados
Banco de dados
```mermaid
graph TD;
    A[Código Python] --> B[Conectar ao Banco de Dados]
    B --> C[Criar Tabela]
    A --> D[Adicionar Tarefa ('Estudar Python', '2024-07-01')]
    A --> E[Adicionar Tarefa ('Fazer compras', '2024-06-30')]
    A --> F[Adicionar Tarefa ('Preparar apresentação', '2024-07-05')]
    A --> G[Obter Todas as Tarefas]
    G --> H[SELECT * FROM tasks]
    A --> I[Completar Tarefa (1)]
    I --> J[Marcar Tarefa 1 como 'Concluída']
    A --> K[Deletar Tarefa (2)]
    K --> L[Deletar Tarefa com ID 2]
]

```
