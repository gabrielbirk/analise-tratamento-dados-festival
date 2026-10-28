# Análise e Tratamento de Dados - Festival de Música

Este repositório contém um projeto prático de **ETL (Extração, Transformação e Carga)** e **Análise Exploratória de Dados (EDA)** desenvolvido em Python com a biblioteca Pandas. O objetivo principal foi receber um conjunto de dados (fictício) bruto e "sujo" de vendas de ingressos de um festival de música, tratar as inconsistências e gerar uma base limpa pronta para análises de negócio.

## 🛠️ Tecnologias Utilizadas

* **Python**
* **Pandas** (Manipulação, limpeza e transformação de dados)
* **NumPy** (Tratamento de valores numéricos, *outliers* e nulos)
* **Jupyter Notebook / VS Code**

## 📋 Etapas do Projeto

1. **Inspeção Inicial:** Leitura da base de dados bruta (`vendas_festival_bruto.csv`), verificação do número de linhas/colunas e tipos de dados através de `.info()` e `.head()`.
2. **Diagnóstico e Qualidade:** Checagem de registos duplicados e análise estatística inicial para detectar inconsistências.
3. **Limpeza e Tratamento:** 
   * Identificação e tratamento de *outliers* na idade dos clientes.
   * Preenchimento estratégico de valores nulos na coluna de idade utilizando a média, mantendo a tipagem numérica intacta para futuras operações matemáticas.
   * Tratamento de campos de gênero ausentes.
4. **Análise Exploratória de Dados (EDA):** Agrupamento por setor do festival para descobrir qual gerou mais vendas e calcular os valores médios pagos por categoria.
5. **Exportação:** Geração de um novo arquivo otimizado e estruturado (`vendas_festival.csv`).

## 📁 Estrutura de Arquivos

* `analise_festival.ipynb`: O notebook principal contendo todo o código documentado passo a passo.
* `vendas_festival_bruto.csv`: O dataset original contendo as inconsistências.
* `vendas_festival.csv`: O dataset final tratado e pronto para consumo.

## 🚀 Como Executar o Projeto

1. Certifica que possui o Python e o Jupyter instalados na máquina.
2. Instala as dependências necessárias (caso ainda não tenha).
3. Baixa ou clona este repositório para o computador.
4. Abre o ficheiro analise_festival.ipynb no VS Code ou ambiente Jupyter e executa as células.

Feito por Gabriel Birk.
