# Classificação de Espécies de Crocodilos 🐊


## 📊 Dataset
O dataset utilizado contém informações sobre crocodilos, incluindo:
- Nome comum (espécie)  
- Comprimento e peso observados  
- Faixa etária, sexo e habitat  
- Status de conservação  
- Região de ocorrência  

A variável alvo (**y**) escolhida foi o **Common Name** (espécie do crocodilo).


## ⚙️ Etapas
1. **Exploração dos Dados** → análise inicial e distribuição das espécies.  
2. **Pré-processamento** → remoção de colunas irrelevantes e transformação de variáveis categóricas.  
3. **Divisão em Treino/Teste** → 70% treino / 30% teste.  
4. **Modelagem** → treinamento de três algoritmos:
   - Decision Tree Classifier
   - KNeighbors Classifier (k=5)
   - Logistic Regression
5. **Avaliação** → métricas de acurácia, matriz de confusão, precisão, recall e F1-score.  
6. **Comparação Final** → gráfico comparando os três modelos.

## 🏆 Resultados
Acurácias finais obtidas:

- **Decision Tree**: 0.93  
- **KNN (k=5)**: 0.37  
- **Logistic Regression**: 0.98  

O modelo que apresentou **melhor desempenho** foi a **Logistic Regression**, atingindo quase 98% de acurácia.

## 🚀 Melhorias Futuras
- Aplicar normalização para melhorar o desempenho do KNN.  
- Realizar tuning de hiperparâmetros.  
- Testar modelos adicionais como Random Forest e SVM.  

## 📂 Estrutura do Repositório

├── crocodile_dataset.csv
├── Atividade-Crocodilo.ipynb 
└── README.md
