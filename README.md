# Análise de Dados: Otimização de Portfólio de Lojas - Alura Store BR

[![Python](https://img.shields.io/badge/Python-3.12.3-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.1.4-green.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8.2-orange.svg)](https://matplotlib.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow.svg)](https://jupyter.org/)

## 📖 Descrição

Este projeto realiza uma análise exploratória de dados (EDA) sobre o desempenho de quatro lojas de uma rede varejista brasileira (Alura Store BR). Utilizando dados de vendas, faturamento, avaliações de clientes, custos de frete e categorias de produtos, o notebook identifica padrões, compara o desempenho entre as lojas e fornece uma **recomendação estratégica final**: qual loja vender para otimizar o portfólio da empresa.

Os dados incluem informações como:
- Preço e frete de produtos
- Datas de compra e localizações
- Avaliações e métodos de pagamento
- Coordenadas geográficas (lat/lon)

O foco é em métricas chave como faturamento total, vendas por categoria, avaliação média e custos operacionais, culminando em um score de desempenho para auxiliar decisões de negócio.

## 🎯 Objetivos

- **Analisar o faturamento**: Comparar receitas entre lojas e calcular percentuais relativos.
- **Explorar vendas por categoria**: Identificar as categorias mais rentáveis por loja.
- **Avaliar satisfação do cliente**: Calcular médias de avaliações e frete.
- **Recomendação estratégica**: Usar um score ponderado (faturamento 50%, avaliação 30%, frete 20%) para sugerir a venda da loja com pior desempenho.
- **Gerar insights acionáveis**: Relatório executivo com projeções pós-venda e próximos passos.

## 🛠️ Tecnologias Utilizadas

- **Python 3.12.3**: Linguagem principal.
- **Pandas**: Manipulação e análise de dados.
- **Matplotlib**: Visualizações (gráficos de barras e comparativos).
- **Jupyter Notebook**: Ambiente interativo para análise e relatórios.
- **Dados**: CSV de quatro lojas (loja_1.csv a loja_4.csv), carregados via URLs do GitHub.

## 🚀 Como Executar

1. **Clonar o Repositório**:
   ```
   git clone https://github.com/seu-usuario/alura-store-analysis.git
   cd alura-store-analysis
   ```

2. **Instalar Dependências** (recomendado com ambiente virtual):
   ```
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   pip install pandas matplotlib jupyter
   ```

3. **Executar o Notebook**:
   ```
   jupyter notebook Data_science_Alura_Store_BR.ipynb
   ```
   - Abra o arquivo no navegador e execute as células sequencialmente.

4. **Requisitos Mínimos**:
   - Python 3.10+
   - Bibliotecas listadas acima.

**Nota**: Os dados são baixados automaticamente do GitHub durante a execução da célula de importação.

## 📊 Resultados Principais

- **Faturamento Total**: R$ 5.871.490,79
- **Loja Líder**: Loja 1 (R$ 1.534.509,12 - 26,1% do total)
- **Melhor Avaliação**: Loja 3 (4,05/5 estrelas)
- **Recomendação**: **Vender a Loja 1** (score de desempenho: 0,761 - pior performance relativa).
  - Justificativa: Baixo faturamento relativo, avaliação mediana e frete acima da média.
- **Vendas por Categoria**: Eletrônicos e Móveis lideram (maior rentabilidade geral).

### Exemplo de Output (Recomendação Final)
```
🚨 RECOMENDAÇÃO: VENDER A LOJA 1 🚨

📊 JUSTIFICATIVA:
1. FATURAMENTO: R$ 1.534.509,12 (26,1% do total)
2. AVALIAÇÃO: 3,98/5
3. FRETE MÉDIO: R$ 34,69

RANKING (da melhor para pior):
1ª - Loja 4: 0.691 ✅ MANTER
2ª - Loja 3: 0.725 ✅ MANTER
3ª - Loja 2: 0.736 ✅ MANTER
4ª - Loja 1: 0.761 🚨 RECOMENDADA PARA VENDA
```

Para mais detalhes, execute o notebook e visualize os gráficos e tabelas gerados.

## 📁 Estrutura do Repositório

```
alura-store-analysis/
├── Data_science_Alura_Store_BR.ipynb  # Notebook principal de análise
├── README.md                          # Este arquivo
└── requirements.txt                   # Dependências (opcional)
```

## 📈 Insights e Recomendações Estratégicas

- **Benefícios da Venda**: Libera R$ 1,5M em capital, reduz custos e foca em lojas de alto potencial.
- **Oportunidades**: Reinvestir em expansão da Loja 1 (líder em faturamento) e marketing nas demais.
- **Projeção Pós-Venda**: Faturamento concentrado em 3 lojas, com expectativa de crescimento de 10-15% em eficiência operacional.

Este projeto demonstra como a análise de dados pode impulsionar decisões de negócio, como otimização de portfólio.

## 📝 Autor

- **Nome**: Adilson 
- **GitHub**: (https://github.com/adnds)
- **LinkedIn**: 
- **Email**: 

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

