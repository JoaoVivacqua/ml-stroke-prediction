# Predição de AVC (Stroke): Projeto de Machine Learning

**Integrantes:** Murilo Godoy e João Pedro Pessoa

Projeto da disciplina de Machine Learning (Insper, 2026.2), usando o
[Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).

| Etapa | Página | Notebook |
|---|---|---|
| APS1: Análise Exploratória (EDA) | [aps1.html](https://colab.research.google.com/drive/1f0UktZYCRpEYeQXjdzjJjA6Oid_2PENd#scrollTo=8ec71d92) | `APS1_EDA_Stroke_MuriloGodoy_JoaoPedroPessoa.ipynb` |
| APS2: Classificação | [index.html](https://colab.research.google.com/drive/1PJ_bsHuSy-bVrRC9PJfBD8SeiC35bXNv#scrollTo=95c83a78) | `APS2_Classificacao_Stroke_MuriloGodoy_JoaoPedroPessoa.ipynb` |

## Resumo da APS2

- Modelos: Dummy, regressão logística regularizada e Random Forest, comparados por PR-AUC com validação cruzada estratificada repetida (5 folds × 3).
- Melhor modelo: regressão logística (Elastic Net) com indicador de IMC ausente adicionado ao pipeline da APS1.
- Teste: ROC-AUC 0,840 e PR-AUC 0,241 (prevalência 0,049).
- Interpretação com coeficientes, importância de features e SHAP.

## Como reproduzir

Abra o notebook no Google Colab e execute todas as células (cerca de 5 minutos). O dataset é baixado automaticamente.

Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn e shap.
