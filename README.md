# Previsão de Score de Crédito

Este projeto utiliza técnicas de Machine Learning para prever o score de crédito de clientes com base em características pessoais e comportamentais. O objetivo é identificar quais clientes possuem maior ou menor risco de crédito.

---

## Objetivo

- Prever a classificação do score de crédito (`boa`, `ok`, `ruim`) dos clientes.  
- Comparar diferentes modelos de Machine Learning e escolher o mais adequado.  
- Aplicar o modelo treinado em novos clientes para prever seu score de crédito.

---

## Base de Dados

O projeto utiliza duas bases:  

1. **clientes.csv** – dados históricos dos clientes com informações como:  
   - Profissão  
   - Mix de crédito  
   - Comportamento de pagamento  
   - Score de crédito (target)  
2. **novos_clientes.csv** – dados de clientes para os quais o score de crédito será previsto.  

> Todas as colunas categóricas foram codificadas usando `LabelEncoder` do `scikit-learn`.

---

## Etapas do Projeto

1. **Importação e exploração dos dados**  
2. **Pré-processamento**  
   - Tratamento de colunas categóricas  
   - Separação entre features (`X`) e target (`y`)  
3. **Divisão em treino e teste** (`train_test_split`)  
4. **Treinamento de modelos de Machine Learning**  
   - Random Forest (árvore de decisão)  
   - KNN (vizinhos próximos)  
5. **Avaliação de modelos**  
   - Comparação da acurácia nos dados de teste  
   - Escolha do melhor modelo (Random Forest)  
6. **Aplicação em novos clientes**  
   - Transformação dos dados categóricos  
   - Previsão do score de crédito

---

## Ferramentas Utilizadas

- **Python** – linguagem principal  
- **Pandas** – manipulação de dados  
- **scikit-learn** – Machine Learning (Random Forest, KNN, LabelEncoder, train_test_split)  
- **Jupyter Notebook** – desenvolvimento do projeto

---

## Como Rodar

1. Clone o repositório:  
   ```bash
   git clone https://github.com/seu-usuario/nome-do-projeto.git
Navegue até a pasta do projeto:

bash
Copiar código
cd nome-do-projeto
Instale as dependências:

bash
Copiar código
pip install pandas scikit-learn
Abra o notebook e execute as células:

bash
Copiar código
jupyter notebook
Estrutura do Repositório
kotlin
Copiar código
nome-do-projeto/
│
├── data/
│   ├── clientes.csv
│   └── novos_clientes.csv
├── notebooks/
│   └── previsao_score_credito.ipynb
├── README.md
Autor
Pedro H. Mendonça
https://www.linkedin.com/in/pedrohmmwing
