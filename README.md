* **Acadêmica:** Francine Estefanela Moura
* **Disciplina:** Técnicas de Machine Learning
* **Dataset:** NBA Players Stats (nba_stats.csv)

### **Objetivo**
Este projeto usa técnicas de machine learning para prever o "Win Share" de jogadores da NBA, que indica quanto cada jogador ajuda nas vitórias do time. Os dados vão de 1950 a 2017 e trazem informações sobre o desempenho dos jogadores, como pontos e eficiência. Aplicamos os métodos aprendidos em aula, focando em identificar os atributos mais importantes para tornar o modelo mais preciso.

### **Etapas do Projeto**

* **1. Importação de Bibliotecas:**
  
Utilizei bibliotecas como `pandas`, `numpy`, `matplotlib`, `seaborn` e `sklearn` para manipular dados, visualização e modelagem.

* **2. Carregamento do Dataset:**
  
O arquivo `nba_stats.csv` contém as estastísticas dos jogadores que foram carregadas e preparadas para análise.

* **3. Preparação de dados:**
  
A preparação do dataset inclui análise das variáveis, tratamento de outliers e normalização para melhorar a precisão do modelo.

* **4. Análises realizadas:**

  Analisei a correlação entre variáveis como arremessos e pontos, tratei outliers usando Z-score e intervalo interquartil e criei gráficos de dispersão, boxplots e histogramas para entender melhor os dados e suas relações.

* **5. Modelo de Machine Learning:**
 
Aplicação do modelo de Random Forest Regressor para prever o Win Share, com avaliação utilizando métricas como o erro quadrático médio (MSE) e o R².

### **Principais variáveis do dataset**
* **TrueShootingPercentage (TS%):** Eficiência nos arremessos, considerando pontos de dois e três pontos e lances livres.
* **OffensiveWinShares:** Contribuição do jogador para as vitórias de sua equipe com base no desempenho ofensivo.
* **DefensiveWinShares:** Contribuição do jogador para as vitórias de sua equipe com base no desempenho defensivo.
* **WinShares:** Total de vitórias que o jogador ajudou a conquistar.

### **Resultados Esperados**
Previsões de Win Share para os jogadores com base em suas estatísticas, gerando insights sobre o impacto das variáveis no desempenho e aprimorando a capacidade de análise e decisão de treinadores e equipes da NBA.
