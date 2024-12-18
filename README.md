# Human-Resource-Management
Este projeto consiste em uma série de queries SQL utilizadas para criação, inserção e análise de dados em um banco de dados fictício de gerenciamento de recursos humanos (HR Management).

Objetivo
Fornecer um conjunto de scripts SQL organizados que:

  - Criam tabelas necessárias para um sistema de gestão de RH.
  - Inserem dados de exemplo.
  - Realizam consultas para obter insights e análises sobre os funcionários, salários e desempenho.

#Estrutura do Projeto
A estrutura de arquivos está organizada da seguinte forma:

```plaintext
hr-management-db/
│
├── table_creations.sqlx         # Criação das tabelas necessárias
├── data_insertion.sqlx          # Inserção de dados fictícios
│
├── definitions/queries/
│   ├── employees/               # Consultas relacionadas aos funcionários
│   │   ├── employees_before_2000.sqlx      # Funcionários nascidos antes de 2000
│   │   ├── employees_by_age_range.sqlx     # Funcionários por faixa etária e Número de Funcionários por Faixa Etária
│   │   ├── employees_by_department.sqlx    # Quantidade de Funcionários por Departamento
│   │   └── employees_by_gender.sqlx        # Quantidade de funcionários por gênero
│   │
│   ├── performance/             # Consultas relacionadas à performance
│   │   ├── current_year_reviews.sqlx       # Funcionários que Receberam Avaliações no Ano Atual
│   │   ├── performance_by_category.sqlx    # Pontuação de Funcionários por Categoria
│   │   ├── performance_ranking.sqlx        # Ranking de Funcionários por Avaliação
│   │   └── top_performers.sqlx             # Funcionários que receberam Pontuação maior ou igual a 90
│   │
│   ├── salaries/                # Consultas relacionadas aos salários
│   │   ├── above_market_salaries.sqlx      # Funcionários com Salários Acima da Média do Mercado
│   │   ├── average_salary_by_gender.sqlx   # Média de Salários por Gênero
│   │   ├── employee_salaries.sqlx          # Salários de cada funcionário com Departamento, Cargo e Datas do Salário
│   │   └── salary_statistics.sqlx          # Salário Médio dos Funcionários, Soma dos Salários e Salários Mínimos e Máximos
│
├── .gitignore                   # Arquivos que devem ser ignorados pelo Git
├── README.md                    # Documentação do projeto
└── workflow_settings.yaml       # Configurações do Workflow
```
#Exemplo de Query
![Query_Example](https://github.com/user-attachments/assets/1ec37ac6-c87c-4853-9851-69a2f9aac50a)
##Output
![Output](https://github.com/user-attachments/assets/da56cd52-e086-4f7b-a13c-7ae54107c405)
