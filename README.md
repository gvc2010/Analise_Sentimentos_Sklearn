# Análise de Sentimentos com Redução de Granularidade

Este projeto realiza uma análise de sentimentos em um corpus de textos, utilizando técnicas de processamento de linguagem natural (NLP) e algoritmos de aprendizado de máquina. O objetivo principal é reduzir a granularidade dos sentimentos de sete emoções para três classes clássicas (positivo, neutro, negativo) e comparar o desempenho de diferentes classificadores.

## Redução da Granularidade dos Sentimentos

A granularidade dos sentimentos foi reduzida da seguinte forma:
- **Positivo**: Inclui as instâncias originalmente rotuladas como "alegria".
- **Negativo**: Inclui as instâncias originalmente rotuladas como "raiva", "medo", "desgosto" e "tristeza".
- **Neutro**: Inclui as instâncias originalmente rotuladas como "neutro".
- **Surpresa**: Instâncias rotuladas como "surpresa" não são utilizadas.

## Tecnologias Utilizadas

- **Python**
- **Pandas**
- **NumPy**
- **NLTK**
- **Scikit-learn**

## Estrutura do Projeto

- `analise-sentimentos-2000-noticias.txt`: Arquivo de texto contendo o corpus de análises de sentimentos.
- `README.md`: Descrição do projeto.
- `main.py`: Script principal que realiza o processamento dos dados e a análise de sentimentos.

## Passos para Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu_usuario/analise-sentimentos.git
   cd analise-sentimentos
