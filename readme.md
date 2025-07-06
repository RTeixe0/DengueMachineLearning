# 🧠 Previsão de Casos de Dengue no Brasil com Aprendizado de Máquina

Este projeto foi desenvolvido como parte da **Atividade Prática 2** da disciplina de **Aprendizado de Máquina** (FATEC, 2025-1). O objetivo foi aplicar algoritmos de regressão para prever o número de casos de dengue com base em variáveis climáticas, populacionais e geográficas.

## 👨‍💻 Integrantes do grupo

- Renan Teixeira  
- Rodrigo Rodrigues

## 📊 Objetivo

Aplicar um pipeline completo de aprendizado de máquina para prever a variável `Cases` (número de casos de dengue), utilizando dados reais do Brasil entre 2012 e 2021.

## 📁 Etapas do projeto

1. **Importação e análise do dataset**
2. **Análise Exploratória de Dados (EDA)**
3. **Limpeza e preparação dos dados**
4. **Treinamento com 3 algoritmos:**
   - Regressão Linear
   - Ridge Regression
   - Random Forest
5. **Validação cruzada com GridSearchCV**
6. **Avaliação com métricas de regressão (R², RMSE, MAE)**
7. **Teste alternativo com transformação logarítmica**

## 🧪 Dataset

Utilizamos o dataset público:  
📎 [Dengue in Brazil (Kaggle)](https://www.kaggle.com/datasets/jimmyyyyyyy/dengue-in-brazil-2012-2021)

## 📈 Resultados

Após testes e tuning, a melhor performance foi obtida com Random Forest após aplicar **log-transform** na variável alvo:

- **R²:** 0.11
- **RMSE:** ~61.700
- **MAE:** ~29.850

## 💡 Conclusões

Apesar dos desafios com outliers e variabilidade nos dados, o projeto mostrou como aplicar um pipeline completo de aprendizado de máquina, além de demonstrar senso crítico com testes alternativos e sugestões de melhoria.

---

