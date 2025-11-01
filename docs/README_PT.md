🏟️ Dashboard de Jogadores FIFA com Streamlit
📋 Visão Geral do Projeto

Este projeto cria um dashboard interativo usando Streamlit para explorar dados de jogadores de FIFA. O dashboard permite filtrar, visualizar e analisar atributos dos jogadores, oferecendo insights valiosos sobre desempenho e tendências.

🚀 Link do Dashboard

Acesse a versão em português do dashboard: FIFA Dashboard PT

⚠️ Observação: O conteúdo do dashboard é idêntico à versão em inglês, apenas a interface é levemente diferente em tamanho/visualização.

📊 Conjunto de Dados

Fonte: O dataset contém informações sobre jogadores de FIFA, incluindo atributos como nome, idade, nacionalidade, classificação geral, potencial, valor de mercado e posição.

Tamanho: ~18.000 jogadores

Colunas: Exemplos incluem Nome, Idade, Nacionalidade, Overall, Potential, Value, Posição.

🛠️ Ferramentas e Tecnologias

Python — Linguagem principal

Streamlit — Framework para dashboards interativos

Pandas — Manipulação e pré-processamento de dados

Matplotlib & Seaborn — Visualizações estáticas e interativas

🚀 Como Executar o Projeto

1️⃣ Clone o repositório

git clone https://github.com/rodrigohigashi/FIFA-Dashboard.git
cd FIFA-Dashboard


2️⃣ Instale as dependências

pip install -r requirements.txt


3️⃣ Execute o dashboard Streamlit

streamlit run app.py


4️⃣ Acesse o dashboard
Abra seu navegador em: http://localhost:8501

📈 Funcionalidades do Dashboard

Filtros e Exploração:

Classificação geral (e.g., 80+)

Faixa etária

Nacionalidade (e.g., Brasil, Alemanha)

Posição (e.g., Atacante, Goleiro)

Visualizações:

Distribuição de jogadores: Ratings, idades e nacionalidades

Top Players: Identificação dos jogadores com maiores ratings

Comparações: Comparação de jogadores em múltiplos atributos (Overall, Potential, Value)

🎯 Insights e Observações

Distribuição de Idade: A maioria dos jogadores está entre 24–27 anos

Principais Nações: Brasil, Argentina e Alemanha produzem jogadores de alto rating

Tendências por Posição: Atacantes tendem a ter maior valor de mercado do que defensores

📂 Estrutura do Projeto
FIFA-Dashboard/
├── data/                         # Pasta com os dados
│   └── fifa_players.csv          # Dataset
├── app.py                        # Aplicação Streamlit
├── requirements.txt              # Dependências
├── README_PT.md                  # Documentação em português
└── assets/                       # Arquivos visuais para o dashboard

🧠 Aprendizados

Streamlit é excelente para criar dashboards rapidamente e de forma amigável

Pré-processamento de grandes datasets é essencial para performance

Visualizações eficientes ajudam a identificar padrões e tendências

🌟 Melhorias Futuras

Adicionar comparação lado a lado de jogadores selecionados

Incluir mapa para destacar nacionalidades

Melhorar performance via otimização de carregamento e cache de dados

App criado no Streamlit Cloud: (https://appfifadash.streamlit.app/)

Nota: O conteúdo da versão PT é o mesmo que o da versão EN. A única diferença está na interface de visualização no Streamlit, onde o tamanho dos letreiros varia um pouco.