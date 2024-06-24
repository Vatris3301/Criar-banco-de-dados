# Criar-banco-de-dados
Banco de dados
```mermaid
graph TD;
    A[Código Python] --> B[connect_db()]
    B --> C[create_table()]
    A --> D[add_task('Estudar Python', '2024-07-01')]
    A --> E[add_task('Fazer compras', '2024-06-30')]
    A --> F[add_task('Preparar apresentação', '2024-07-05')]
    A --> G[get_all_tasks()]
    G --> H[SELECT * FROM tasks]
    A --> I[complete_task(1)]
    I --> J[UPDATE tasks SET status='Completed' WHERE id=1]
    A --> K[delete_task(2)]
    K --> L[DELETE FROM tasks WHERE id=2]

```
