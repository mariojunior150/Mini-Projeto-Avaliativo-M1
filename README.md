# Mini Projeto Avaliativo - Módulo 1 - IA Preditiva - T2
# DataView

## Sobre o projeto

O DataView.ipynb é um projeto de análise exploratória de dados (EDA) de vendas,
desenvolvido em Python. O notebook lê, limpa, transforma,
analisa e visualiza um dataset de vendas, gerando métricas e insights.

## O que o projeto analisa

Como as vendas se comportam ao longo do tempo (por mês, por trimestre);
Quais produtos e categorias geram mais receita;
Quais regiões têm melhor desempenho;
Quais clientes são mais valiosos (segmentação simples);


## Estrutura do projeto

projeto/  
├── data/  
│ ├── raw/                      # dados brutos, originais   
│ ├── processed/   
│ │ ├── v1_com_outliers/        # dados com limpeza geral, mas com os outliers mantidos  
│ │ └── v2_outliers_tratado/    # dados com limpeza geral v1 + tratamento de outliers  
│ └── final/                    # Dados que serão usados futuramente em um treinamento de modelo de IA  
│  
├── notebooks/                  # Notebook para análise exploratória  
├── outputs/                    # resultados finais, relatórios, e visualizações  
│ ├── metricas_por_mes.csv      # métricas mensais extraído dos dados  
│ ├── segmentacao_clientes.csv  # segmentação de clientes  
│ ├── estatisticas_gerais.json  # estatísticas do dataframe  
│ ├── graficos/                 # visualizações para análise  
├── README.md                   # documentação do projeto, estrutura de pastas e justificativas de decisão  

## Decisão de versão

Qual das versões v1 ou v2 foi escolhida para salvar dentro da pasta \data\final

## Observações

## Bibliotecas e suas versões

Pandas: 3.0.3
NumPy: 2.4.6
Matplotlib: 3.11.0
Seaborn: 0.13.2

## Vídeo de demonstração
