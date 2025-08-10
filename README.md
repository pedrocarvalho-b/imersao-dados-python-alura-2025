# imersao-dados-python-alura-2025

📊 Dashboard de Salários na Área de Dados
Este projeto é um dashboard interativo desenvolvido com Streamlit para explorar dados salariais na área de dados.
O usuário pode aplicar filtros e visualizar métricas, gráficos e tabelas de forma dinâmica.

🚀 Funcionalidades
Filtros dinâmicos por:

Ano

Senioridade

Tipo de contrato

Tamanho da empresa

Métricas principais (KPIs):

Salário médio

Salário máximo

Total de registros

Cargo mais frequente

Visualizações interativas:

Top 10 cargos por salário médio

Distribuição de salários anuais

Proporção dos tipos de trabalho (remoto, presencial, híbrido)

Salário médio de Data Scientists por país

Tabela detalhada com todos os registros filtrados

🛠 Bibliotecas Utilizadas
O projeto utiliza as seguintes bibliotecas Python:

Biblioteca	Função no projeto
streamlit	Criar a interface web interativa
pandas	Manipulação e filtragem dos dados
plotly.express	Criação de gráficos interativos

📂 Estrutura do Código
Configuração da página
Define título, ícone e layout do dashboard.

Carregamento dos dados
Os dados são carregados diretamente de um CSV hospedado no GitHub.

Barra lateral (filtros)
Permite selecionar múltiplos valores para cada categoria de filtro.

Filtragem do DataFrame
Aplica as seleções feitas pelo usuário para atualizar métricas e gráficos.

Exibição de métricas (KPIs)
Calcula e exibe estatísticas relevantes.

Criação dos gráficos
Usa o Plotly para gerar visualizações interativas.

Tabela detalhada
Exibe os dados filtrados em uma tabela interativa no Streamlit.

▶️ Como Executar o Projeto
1. Clonar o repositório
bash
Copiar
Editar
git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
cd NOME_DO_REPOSITORIO
2. Criar e ativar ambiente virtual (opcional, mas recomendado)
bash
Copiar
Editar
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
3. Instalar dependências
bash
Copiar
Editar
pip install -r requirements.txt
4. Executar o dashboard
bash
Copiar
Editar
streamlit run app.py
📦 requirements.txt sugerido
txt
Copiar
Editar
streamlit
pandas
plotly
