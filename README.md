# Projeto de Engenharia de Dados | Epidemia Mundial
> A fim de diversificar os conhecimentos com diferentes ferramentas para Engenharia de Dados, neste projeto reescrevo seu propósito, criando uma operação para trabalhar em bacth integrada ao novo Data Warehouse dedicado.

Inicio as operações ingerindo dados CSV utilizando a ferramenta open-source "Airbyte", persisto os dados no Data Warehouse "Snowflake", em seguida, formalizo a modelagem que será aplicada utilizando a ferramenta open-source "DBT" e integro a mesma na operação com o Airbyte. Ao concluir este ciclo, será criado uma nova Table e utilizada com a ferramenta open-source "Metabase". Após o sucesso da operação, insiro a ferramenta open-source"Airflow" afim de orquestrar este ciclo diariamente.

Por fim, incluo um operador shell visando facilitar a inicialização por novos/leigos usuários.


### Arquitetura

<img src="arquitetura-epidemia-19.png">