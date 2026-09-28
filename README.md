## Estrutura do Repositório

```text
imdb-data-engineering-mvp/
│
├── README.pdf
│
└── notebooks/
    ├── 00_bronze_coleta.py
    ├── 01_silver_limpeza.py
    ├── 02_gold_modelagem.py
    ├── 03_qualidade_dados.py
    └── 04_analise.py

Descrição

- README.pdf: Documento principal do projeto contendo o contexto de negócio, arquitetura adotada, etapas do pipeline, modelagem, qualidade dos dados, análises realizadas e instruções para reprodução.

Pasta notebooks/

- 00_bronze_coleta.py: Responsável pela ingestão dos arquivos do IMDb armazenados no Databricks e pela criação das tabelas da camada Bronze.

- 01_silver_limpeza.py: Executa o processo de limpeza, tipagem, deduplicação, padronização e transformação dos dados para a camada Silver.

- 02_gold_modelagem.py: Implementa o modelo dimensional utilizando esquema estrela e cria as dimensões, tabelas ponte, tabela fato e view analítica da camada Gold.

- 03_qualidade_dados.py: Realiza verificações de completude, unicidade, consistência, validade e análise de possíveis outliers presentes nos dados.

- 04_analise.py: Executa as consultas analíticas e responde às perguntas de negócio definidas para o projeto.
