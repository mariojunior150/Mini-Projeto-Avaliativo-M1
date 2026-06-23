# Mini Projeto Avaliativo - Módulo 1 - IA Preditiva - T2
# DataView

## Sobre o projeto

O DataView.ipynb é um projeto de análise exploratória de dados (EDA) de vendas,
desenvolvido em Python. O notebook lê, limpa, transforma,
analisa e visualiza um dataset de vendas, gerando métricas e insights.

## O que o projeto analisa

Como as vendas se comportam ao longo do tempo;  
Quais produtos e categorias geram mais receita;  
Quais regiões têm melhor desempenho;  
Quais clientes são mais valiosos;  


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

Conforme solicitado no RF12 e executado no item 5 do dataview.ipynb foi selecionado o df_v2 (outliers removidos) como base da análise final.

## Observações

Temos como respostas após a análise:  
As maiores receitas estão concentradas nos meses de janeiro e novembro  
Os produtos smartphone e notebook e as respectivas categorias celulares e computadores são as que geram mais receita  
A região que apresenta melhor desempenho pela receita total é a região norte  
Dos 30 clientes 25 estão na maior categoria (Ouro)

## Bibliotecas e suas versões

Pandas: 3.0.3  
NumPy: 2.4.6  
Matplotlib: 3.11.0  
Seaborn: 0.13.2  

## Vídeo de demonstração

https://drive.google.com/file/d/10l0c2zMgYusQAiJ5Lx1ZhKaUqke_pnBz/view?usp=sharing