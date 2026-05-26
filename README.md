# Projeto de Mineração de Dados: Análise Demográfica e Ocupação Domiciliar em SP.

Este projeto tem como objetivo realizar a mineração de dados para identificar padrões de ocupação em domicílios no Estado de São Paulo, utilizando dados do Censo Demográfico do IBGE SIDRA.

# Objetivo da Análise
A análise foca em compreender a relação entre o perfil demográfico por gênero e a média de moradores por domicílio, investigando como diferentes grupos populacionais ocupam o espaço habitacional no estado de São Paulo comparados com os demais Estados do Brasil.

# Metodologia
- **Base de Dados**: Integração de dados da tabela 6678 do IBGE SIDRA: Domicílios, por número de moradores, comparativo anos 2022 e 2025.

- **Técnicas Aplicadas**:

  - **Pré-processamento**: Tratamento, normalização e discretização de variáveis demográficas.
  - **Agrupamento**: Algoritmo K-Means com definição do número de grupos via Método do Cotovelo.
  - **Associação**: Algoritmo Apriori para extração de regras de comportamento demográfico e padrões de ocupação.

# Resultados
O estudo identifica padrões consistentes de ocupação, revelando correlações significativas entre gênero e a densidade média de moradores por domicílio no estado, validando a eficácia das técnicas de mineração de dados na interpretação de estatísticas populacionais.


# Objetivo do Projeto

O objetivo deste projeto é analisar os padrões de domicílios por número de moradores no Brasil, comparando os anos de 2022 e 2025, com foco especial no estado de São Paulo.

Foram utilizadas técnicas de mineração de dados para identificar:

* padrões demográficos;
* agrupamentos semelhantes entre municípios;
* relações entre os perfis de moradores nos domicílios.

# Base de Dados

A base utilizada contém informações sobre:

* domicílios com 1 morador;
* 2 moradores;
* 3 moradores;
* 4 moradores;
* 5 moradores;
* 6 moradores ou mais.

Os dados referem-se aos anos:

* 2022
* 2025

Além disso, o projeto realiza comparações entre:

* Brasil
* Estado de São Paulo

# Tecnologias Utilizadas

* Python
* Jupyter Notebook
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* Mlxtend

# Técnicas de Mineração de Dados

## K-Means

O algoritmo K-Means foi utilizado para agrupar municípios com características semelhantes relacionadas ao número de moradores nos domicílios.

O modelo identificou:

* grupos de municípios com perfis parecidos;
* padrões demográficos semelhantes;
* diferenças entre municípios brasileiros.

Também foi utilizado:

* Método do Cotovelo;
* Silhouette Score.

## Apriori

O algoritmo Apriori foi utilizado para encontrar regras de associação entre os padrões de moradores nos domicílios.

Foram analisadas:

* relações entre os anos de 2022 e 2025;
* padrões frequentes;
* associações entre os tipos de domicílios.

As métricas utilizadas foram:

* Support (Suporte)
* Confidence (Confiança)
* Lift

# Resultados

Os resultados mostraram:

* crescimento de domicílios com poucos moradores;
* mudanças no perfil das famílias brasileiras;
* agrupamentos demográficos semelhantes entre os Estados;
* fortes associações entre os padrões de moradores ao longo dos anos.

O município de São Paulo foi analisado separadamente para comparação com os dados nacionais.

# Visualizações

O projeto contém:

* gráficos comparativos Brasil x São Paulo;
* gráfico do Método do Cotovelo;
* visualização dos clusters do K-Means;
* gráfico das regras de associação do Apriori.

# Estrutura do Projeto

```bash
📂 projeto_mineracao_dados
 ├── moradias.ipynb
 ├── domicilios num moradores brasil.xlsx
 ├── README.md
 ├── LICENSE

```

# Como Executar

## 1. Instalar bibliotecas

```python
pip install pandas matplotlib seaborn scikit-learn mlxtend openpyxl
```

## 2. Abrir o Jupyter Notebook

Executar o arquivo:

```python
moradias.ipynb

```
