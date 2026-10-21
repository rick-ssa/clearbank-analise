# Análise Financeira com Python - ClearBank

Projeto desenvolvido como desafio final do módulo de fundamentos práticos de Python aplicados à análise de dados. O objetivo é processar, validar, analisar e gerar relatórios financeiros a partir de um arquivo CSV de transações de clientes da fintech **ClearBank**.

## 🛠️ Tecnologias e Recursos Utilizados
- Python 3.10+
- Módulos nativos: `csv`, `json`, `datetime`
- Tratamento robusto de erros (`try/except`)
- Organização em funções com responsabilidades únicas

## 📁 Estrutura do Projeto
- `desafio-final.ipynb`: Notebook Jupyter contendo todo o código modularizado e as saídas executadas.
- `transacoes.csv`: Arquivo de entrada com dados de transações (incluindo registros válidos e inválidos para teste).
- `relatorio.json`: Arquivo de saída gerado automaticamente contendo o resumo mensal e as transações suspeitas.
- `README.md`: Documentação descritiva do projeto.

## 🚀 Como Executar
1. Certifique-se de que o arquivo `transacoes.csv` está na mesma pasta do projeto.
2. Abra o arquivo `desafio-final.ipynb` no Google Colab ou em um ambiente Jupyter Notebook local.
3. Execute todas as células em ordem sequencial (da leitura até a exportação e exibição).
4. O relatório será impresso no terminal e o arquivo `relatorio.json` será gerado automaticamente.
