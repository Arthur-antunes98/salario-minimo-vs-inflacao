# Análise do Poder de Compra: Salário Mínimo vs. Inflação (2016-2026)

Projeto desenvolvido para o portfólio de Dados, explorando a evolução histórica do salário mínimo no Brasil e o seu poder de compra real após o desconto da inflação ao longo de uma década.

## Sobre o Projeto
O objetivo principal é responder a uma pergunta de negócio crucial: **O salário mínimo brasileiro realmente aumentou o poder de compra do trabalhador nos últimos 10 anos, ou a inflação corroeu esses ganhos?**

## Metodologia e Tecnologias
- **Linguagem:** Python 
- **Biblioteca de Análise:** Pandas (tratamento, limpeza e união de bases de dados heterogêneas).
- **Visualização de Dados:** Matplotlib (gráfico comparativo de séries temporais).
- **Fontes de Dados oficiais:**
  - **Banco Central do Brasil (SGS):** Série histórica do Salário Mínimo Nominal (código 1619).
  - **IBGE (SIDRA - Tabela 1737):** IPCA (Índice Nacional de Preços ao Consumidor Amplo) para o cálculo da inflação acumulada.

## Principais Descobertas
- O gráfico gerado demonstra a divergência entre a curva nominal (que aparenta um crescimento contínuo) e a curva real (deflacionada pelo IPCA), evidenciando os períodos de ganho e perda de poder aquisitivo da população.

## Como Executar o Código
1. Clone este repositório.
2. Certifique-se de ter as bibliotecas instaladas (`pip install pandas matplotlib`).
3. Execute o script no Jupyter Notebook ou Google Colab utilizando os arquivos de dados fornecidos na pasta.

![Gráfico Evolução Salário Mínimo](evolucao_salario_minimo_real%20(1).png)

