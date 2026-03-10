# Challenge Telecom X parte2

Challenge Alura-ONE Telecom X parte2

# ** Análise de Churn - Telecom X parte2 **

## Introdução

Esse projeto é a parte 2 do projeto Telecom X e tem como objetivo explorar modelos de Machine Learning e desenvolver modelos capazes de prever quais clientes têm maior chance de cancelar seus serviços na empresa Telecom X com os dados previamente tratados.

##  Tecnologias Utilizadas

- Python  
- Pandas 
- NumPy 
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Pipeline do Projeto

O projeto foi estruturado em etapas sequenciais, formando um fluxo de trabalho claro:
 
1. Preparação dos Dados:
    * Extração do Arquivo Tratado: Extrair o arquivo CSV previamente tratado
    * Remoção de Colunas Irrelevantes: Eliminar colunas que não trazem valor para a análise
    * Encoding: Transformar variáveis categóricas em numéricas para torná-las compatíveis com algoritmos de machine learning, com o método One-Hot Encoding.
    * Verificação da Proporção de Evasão: Calcular a proporção de clientes que evadiram em relação aos que permaneceram ativos
2. Correlação e Seleção de Variáveis:
    * Visualizar a matriz de correlação para identificar relações entre variáveis numéricas
    * Análises Direcionadas: Investigar como variáveis específicas se relacionam com a evasão, gerando gráficos como boxplot ou de dispersão (scatter plots)
3. Modelagem Preditiva:
    * Separação de Dados: Dividir dados em treino e teste para avaliar o desempenho do modelo
    * Criação de Modelos: Criar modelos diferentes para prever a evasão dos clientes
    * Avaliação dos Modelos: Avalie cada modelo utilizando métricas de acurácia precisão, recall, f1-score e matriz de confusão. Em seguida fazer uma análise crítica e comparar os modelos, verificar também modelos com Overfitting ou Underfitting
4. Análise de Importância das Variáveis:
    * Análise das variáveis mais relevantes para a previsão de evasão
    * Conclusão: Fazer relatório detalhado destacando os fatores que mais influenciam a evasão, com base nas variáveis selecionadas e no desempenho de cada modelo.

##  Estrutura do Projeto

```
 challengeTelecomXparte2/
│
├── notebook/
│   └── ChallengeTelecomXparte2.ipynb          
│
├── dados_tratados.csv
│
└── README.md
```

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https

2. Abra o arquivo 'TelecomXparte2.ipynb', pelo Google Collab ou como preferir
3. Altere o caminho do arquivo caso necessário 'dados = pd.read_csv('/CAMINHO/dados_tratados.csv')'
4. Execute todas as células
