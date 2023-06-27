# jornadadedados
Esse é um repositório de um projeto que eu desenvolvi em uma semana na Jornada de Dados da EBAC com a finalidade de aprender possibilidades de processos que vão do tratamento à visualização de dados no BI

**Descrição do Case**

**Contextualizando:**
A empresa “ConstruBem” extraiu dados brutos do seu sistema e precisa lapidar e tratar os dados por alguém que os interprete e auxilie na tomada de decisões para otimização das vendas e captação/fidelização de clientes.
É sabida a necessidade de aumentar as vendas dos produtos das categorias XT660, XTZ250 e CB750.

**Objetivo**
Entender e identificar a oportunidade de acelerar vendas e prospectar clientes, evitando perdas.
São duas bases de dados: potencial por cliente, e Vendas
Período: 2020 a 2022

**O que fazer:**
- Entender o nível de qualidade e consistência dos dados – campos missings, tipo de dados, etc.

- Criar ambiente no Databricks e carregar dados.

- Processar dados e fazer resumo de quantidades.

- Transferir estruturas finais para um banco SQL e iniciar análises utilizando T-SQL com saídas gráficas em Power Point.

- Trazer mais dinamismo para as análises criando um relatório no Power BI Desktop.

- Apresentar insights.

**Mapa de Dados**

Vendas em Potencial:

Client ID: ID único de cada cliente

Area: área construída por ano, em metro quadrado. 
Year: ano
BRL_Potencial: estimativa de potencial máximo de vendas por cliente.


Vendas:

Client ID: ID único de cada cliente
Categoria: categorias de produto. 
Subcategoria: indica as subcategorias de produto. São 10 ao todo. Cada subcategoria pertence a apenas uma categoria.
Produto: produto específico sendo vendido para o cliente na transação específica.
Year: ano
Month: mês
Cidade: cidade do cliente
Valor: valor de vendas realizadas. 
Volume: volume do produto vendido (pode ser kg ou litros)
