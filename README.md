🏟️ FIFA Players Dashboard with Streamlit
📋 Project Overview
This project focuses on creating an interactive dashboard using Streamlit to explore FIFA players' data. The dashboard allows users to filter, visualize, and analyze player attributes, providing valuable insights into player performance and trends.

Key features include:

Filter players by overall rating, position, and nationality.
Dynamic visualizations of players' attributes.
Comparison of players across various metrics.
An intuitive and responsive user interface powered by Streamlit.
📊 Dataset
Source: The dataset used in this project contains player information from FIFA. It includes various attributes such as player names, ratings, positions, nationalities, and more.
Size: ~18,000 players.
Columns: Examples include Name, Age, Nationality, Overall, Potential, Value, and Position.
🛠️ Tools and Technologies
Python: Main programming language.
Streamlit: Framework for building interactive dashboards.
Pandas: For data manipulation and preprocessing.
Matplotlib & Seaborn: For generating static and interactive visualizations.
🚀 How to Run the Project
Clone the Repository

bash

git clone https://github.com/rodrigohigashi/FIFA-Dashboard.git
cd FIFA-Dashboard
Install the Dependencies
Make sure you have Python installed. Then, install the required libraries:

bash

pip install -r requirements.txt
Run the Streamlit App
Start the Streamlit dashboard by running:

bash

streamlit run app.py
Access the Dashboard
Open your browser and navigate to http://localhost:8501.

📈 Dashboard Features
Filters and Explorations:
Filter players by attributes such as:
Overall rating (e.g., 80+).
Age range.
Nationality (e.g., Brazil, Germany).
Position (e.g., Forward, Goalkeeper).
Visualizations:
Player Distribution: Visualize players' ratings, ages, and nationalities.
Top Players: Identify players with the highest overall ratings.
Comparisons: Compare players across multiple attributes (e.g., overall, potential, and value).
🎯 Insights and Observations
Age Distribution: The majority of players are in their mid-20s, peaking around 24–27 years.
Top Nations: Countries such as Brazil, Argentina, and Germany consistently produce high-rated players.
Position Trends: Forwards tend to have higher market values compared to defenders.
📂 Project Structure
bash

### Estrutura do Projeto

```plaintext
FIFA-Dashboard/
├── data/                         # Pasta com os dados
│   └── fifa_players.csv          # Arquivo com o dataset
├── app.py                        # Aplicação Streamlit
├── requirements.txt              # Dependências do projeto
├── README.md                     # Documentação do projeto
└── assets/                       # Arquivos visuais para o dashboard
```

## 🧠 Lições Aprendidas

- **Streamlit** é uma excelente ferramenta para criar dashboards amigáveis de forma rápida.
- O **pré-processamento de grandes conjuntos de dados** é essencial para garantir um bom desempenho em aplicativos interativos.
- **Visualizações eficazes** ajudam a descobrir padrões e tendências nos dados.

## 🌟 Melhorias Futuras

- Adicionar uma **função de comparação de jogadores** para selecionar e comparar jogadores lado a lado.
- Incluir uma **visualização no mapa** para destacar as nacionalidades dos jogadores.
- Melhorar o **desempenho** otimizando o carregamento de dados e utilizando cache.

