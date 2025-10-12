# 📊 Classificação com Random Forest no Dataset Madelon

## 🎯 Objetivo
Este projeto tem como objetivo aplicar o algoritmo **Random Forest** e técnicas de **Ensemble** para classificar dados do dataset **Madelon**. O foco é avaliar o impacto de diferentes sistemáticas de predição (modelo individual vs. comitê de modelos) na acurácia da classificação.

O trabalho foi desenvolvido como parte de uma atividade prática na disciplina de **Tópicos Especiais**, explorando desafios de classificação em datasets de alta dimensionalidade e com variáveis irrelevantes.

## 📚 Dataset
O dataset utilizado é o **Madelon**, desenvolvido para o **NIPS 2003 Feature Selection Challenge**. Ele é conhecido por ser um problema de classificação binária artificialmente construído para testar a capacidade de algoritmos em selecionar características relevantes.

- **Características**: 500 atributos contínuos.
- **Amostras**: 2000 no conjunto de treino.
- **Desafio**: Apenas 20 dos 500 atributos são informativos, o restante é ruído.

O dataset original pode ser encontrado em repositórios de aprendizado de máquina, como o da UCI.

## 📝 Estrutura do repositório
```
.
Madelon-RandomForest-Classification/
│
├─ dataset/            # Arquivos do dataset Madelon (após descompactar)
├─ madelon.zip         # Arquivo zip original do dataset
├─ main.ipynb          # Notebook com todo o código, análises e visualizações
├─ *.png               # Gráficos gerados pela análise
└─ README.md           # Este arquivo
```

## ⚙️ Pré-requisitos
Para executar o projeto, é necessário ter instalado:

- Python >= 3.8
- Bibliotecas Python:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

Instalação via `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## 🖥️ Como executar
Clone o repositório: 
```
git clone [https://github.com/EmillySatiro/Madelon-RandomForest-Classification.git](https://github.com/EmillySatiro/Madelon-RandomForest-Classification.git)
cd Madelon-RandomForest-Classification
```
Abra o notebook main.ipynb no Jupyter:

```
jupyter notebook main.ipynb
```
Execute célula por célula seguindo a ordem do notebook.

## 📝 Referências
- **UCI Machine Learning Repository: Madelon Data Set**
  - [Link do dataset](https://archive.ics.uci.edu/dataset/178/madelon)

- **Documentação Scikit-learn:**
  - [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
  - [VotingClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.VotingClassifier.html)
