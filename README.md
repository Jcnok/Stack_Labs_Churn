## 🚀 Prevendo o Churn: Retenção de Clientes com Machine Learning 🧪

[![Status do Projeto](https://img.shields.io/badge/Status-Concluído-brightgreen.svg)](https://github.com/Jcnok/Stack_Labs_Churn)
[![Linguagem](https://img.shields.io/badge/Linguagem-Python-blue.svg)](https://www.python.org/)
[![Bibliotecas](https://img.shields.io/badge/Bibliotecas-Pandas,%20Scikit--learn,%20Streamlit-orange.svg)](https://github.com/Jcnok/Stack_Labs_Churn)

### 📖 O Desafio do Churn nas Empresas

O churn, a taxa de cancelamento de clientes, é um desafio crucial para empresas de todos os setores. Esse vazamento silencioso pode comprometer seriamente o crescimento e a sustentabilidade do negócio. O grande desafio é antecipar quais clientes estão prestes a cancelar, permitindo que a empresa atue de forma proativa e personalizadas para reter esses clientes.

### 🎯 Construindo um Modelo Preditivo de Churn

Neste projeto, desenvolvi um modelo de Machine Learning capaz de prever o churn com uma boa precisão. Utilizando dados, Python e bibliotecas poderosas como Pandas, Scikit-learn e PowerBI, transformei informações brutas em insights valiosos, capacitando a equipe de Customer Success a agir de forma preventiva e estratégica.

### 🗺️ Da Análise Exploratória ao Deploy

1. **Análise Exploratória de Dados (EDA):** Realizei uma análise profunda dos dados, identificando padrões, *outliers* e pistas valiosas sobre os fatores que levam os clientes a cancelar.
   - 🔗 **[Notebook de EDA no GitHub](https://github.com/Jcnok/Stack_Labs_Churn/blob/main/Analise_churn.ipynb)**

2. **Modelagem (Machine Learning):** Testei diversos algoritmos, comparando suas performances para encontrar o modelo mais preciso na identificação de clientes em risco.
   - 🔗 **[Notebook de Machine Learning no GitHub](https://github.com/Jcnok/Stack_Labs_Churn/blob/main/Models/DataScience.ipynb)**

### ✨ Resultados e Impacto

- **O modelo desenvolvido alcançou uma acurácia de 84%, com um F1-score de 0,76, um recall de 0,66 e uma precisão de 0,60. Esses resultados demonstram a capacidade do modelo em identificar com precisão os clientes com maior risco de churn.**

- Insights Acionáveis: 
**A análise revelou que os principais fatores que influenciam o churn estão relacionados à duração do contrato, tipo de serviço contratado e satisfação do cliente. Esses insights permitirão que a equipe de Customer Success crie estratégias de retenção personalizadas e eficazes.**

- Impacto Financeiro Significativo: 
**De acordo com os cálculos, o modelo é capaz de prever 66% do total de churn, o que representa uma perda de reserva de 122.943.097,71 euros. Mesmo considerando uma taxa de retenção de apenas 5% desses clientes, isso representaria uma economia de 6.031.348,85 euros para o banco.**

- **Além disso, reter clientes existentes é significativamente mais barato do que adquirir novos. Estima-se que um cliente retido representa uma economia de até 7 vezes o custo de aquisição de um novo cliente.**


### 📁 Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
Stack_Labs_Churn/
├── Data/
│   └── ... (arquivos de dados)
├── Models/
│   ├── DataScience.ipynb (Notebook de Machine Learning)
│   └── ... (modelos salvos)
├── html/
│   ├── Analise_churn.html (versão HTML do notebook de EDA)
│   └── DataScience.html (Versão HTML do notebook de ML)
├── Analise_churn.ipynb(Notebook de EDA)
├── Analise_Churn.pbix(Dashboard em PowerBI)
└── README.md (este arquivo)
```

### 💡 Próximos Passos e Evolução

Este projeto foi uma jornada de aprendizado e descobertas! Algumas ideias para o futuro:

- **Aprimorar o Modelo:** Explorar algoritmos mais avançados (Redes Neurais, XGBoost) e otimizar hiperparâmetros.
- **Enriquecer os Dados:** Incorporar dados de outras fontes (interações com suporte, uso do produto) para refinar as previsões.
- **Automatizar Alertas:** Integrar o modelo a ferramentas de CRM para notificar automaticamente a equipe de Customer Success.
- **Análise de Custo-Benefício:** Avaliar o impacto financeiro das ações de retenção baseadas no modelo.

### 🤝 Vamos nos Conectar!

Adoraria trocar ideias, receber feedback e colaborar em projetos futuros! Se você se interessa por ciência de dados, machine learning e resolução de problemas do mundo real, vamos conversar! 😊
