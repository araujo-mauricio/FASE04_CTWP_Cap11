# 🌾 Classificação de Grãos de Trigo com Machine Learning

> **Entrega Fase 04 / CTWP / Cap11 - FIAP**
>
> Salvador Dalí ficaria orgulhoso dessa obra de IA: surreal na precisão, bela na análise! 🎨🧙‍♂️

---

## 📌 Descrição do Projeto

Este projeto aplica algoritmos de aprendizado supervisionado para classificar variedades de sementes de trigo com base em características físicas, utilizando a biblioteca `Scikit-learn`. Toda a análise segue a metodologia CRISP-DM, contemplando desde a exploração dos dados até a otimização dos modelos.

---

## 📂 Estrutura de Arquivos

- `seeds_dataset.csv` → Conjunto de dados tratado (210 amostras, 8 atributos).
- `classificacao_graos_seeds_final.ipynb` → Notebook final com todas as etapas.
- `Relatorio_Classificacao_Graos_Entrega_Final.docx` → Relatório completo em Word.
- `Relatorio_Classificacao_Graos_Entrega_Final.pdf` → Relatório completo em PDF.
- `README.md` → Este arquivo com explicação geral.

---

## 📊 Técnicas Utilizadas

- Análise exploratória de dados (EDA)
- Estatísticas descritivas
- Gráficos: histogramas, boxplots, matriz de correlação e pairplot (gráfico de dispersão)
- Pré-processamento com `StandardScaler`
- Divisão de dados: 70% treino / 30% teste
- Treinamento com 3 algoritmos:
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Random Forest
- Otimização de hiperparâmetros com `GridSearchCV` para SVM
- Avaliação: acurácia, precisão, recall, F1-score, matriz de confusão

---

## 📈 Resultados Finais

| Modelo         | Acurácia | F1-Score (Macro) |
|----------------|----------|-------------------|
| KNN            | 90.48%   | 90.55%            |
| SVM (Padrão)   | 92.06%   | 92.09%            |
| Random Forest  | 88.89%   | 89.00%            |
| **SVM Otimizado** | **90.48%** | **90.48%**        |

---

## 🔎 Contextualização

Este estudo pode ser aplicado por cooperativas agrícolas e indústrias de alimentos para automatizar o processo de classificação de grãos, garantindo maior eficiência, rapidez e redução de erros manuais.

---

## 🚀 Como Executar

1. Abra o notebook `classificacao_graos_seeds_final.ipynb` em um ambiente Jupyter ou Google Colab.
2. Certifique-se de ter o arquivo `seeds_dataset.csv` na mesma pasta.
3. Execute célula a célula para reproduzir a análise completa.

---

## 🧮 Requisitos Técnicos

- Python >= 3.8
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Instalação rápida (se necessário):

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

**Desenvolvido com zelo, café e pitadas de IA. ☕🤖**

