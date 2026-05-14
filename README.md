# Projeto Sprint 5 - Web App de Análise de Veículos

https://project-sprint-5-5j6o.onrender.com

Este projeto consiste no desenvolvimento de uma aplicação web interativa para a análise exploratória de dados de anúncios de veículos, utilizando Python, Streamlit e Plotly Express.

## Funcionalidades
- Visualização de um subconjunto dos dados estruturados (`vehicles.csv`).
- Geração automática de um histograma interativo da quilometragem (`odometer`) através de um botão dedicado.
- Geração automática de um gráfico de dispersão (Preço vs Quilometragem) através de um botão dedicado.
- Opção de filtros alternativos utilizando caixas de seleção (`st.checkbox`).

## Tecnologias Utilizadas
- Python
- Streamlit
- Pandas
- Plotly Express

## Como executar localmente
1. Clonar o repositório.
2. Criar e ativar o ambiente virtual: `python -m venv vehicles_env` e `source vehicles_env/Scripts/activate`.
3. Instalar dependências: `pip install -r requirements.txt`.
4. Executar a app: `streamlit run app.py`.
