App Preço de Ações
Este projeto consiste em uma aplicação web que permite analisar a performance histórica de ações de empresas listadas na B3 (Bolsa de Valores Brasileira) de forma interativa e visual. A aplicação utiliza dados financeiros extraídos da Yahoo Finance API e fornece uma interface intuitiva para seleção e visualização de ativos, com indicadores de performance e filtros de data.

Objetivo
A aplicação foi desenvolvida para facilitar o acompanhamento e análise da variação de preços de ações ao longo dos anos, proporcionando a investidores e interessados uma visão simplificada e dinâmica da performance de diferentes ativos. Através da aplicação, é possível observar a evolução de preços, calcular a performance de uma carteira selecionada e exibir os resultados de forma visual e descritiva.

Funcionalidades
Seleção de Ações: Permite a escolha de múltiplas ações para análise, com dados do período de 2010 a 2024.
Filtros de Data: Controle de intervalo de datas para visualização personalizada dos gráficos.
Gráficos Interativos: Exibição de gráficos de linha que representam a variação dos preços das ações ao longo do tempo.
Cálculo de Performance: Cálculo da performance individual de cada ativo e da carteira total, com indicadores visuais que diferenciam ativos com performance positiva, negativa ou neutra.
Tecnologias Utilizadas
Linguagem: Python
Bibliotecas:
Streamlit: Para desenvolvimento da interface de usuário.
Pandas: Para manipulação e tratamento de dados.
Yahoo Finance API (yfinance): Para extração dos dados financeiros das ações.
Datetime: Para manipulação de datas nos filtros de data.
Pré-requisitos
Python 3.10 ou superior
Bibliotecas listadas no arquivo requirements.txt
Para instalar as bibliotecas, execute:

bash
Copy code
pip install -r requirements.txt
Como Executar
Clone este repositório e navegue até o diretório do projeto.
Certifique-se de que os pré-requisitos foram instalados.
No terminal, execute o comando:
bash
Copy code
python -m streamlit run nome_do_arquivo.py
Acesse a aplicação em http://localhost:8501 em seu navegador.
Estrutura do Código
carregar_dados(empresas): Função que utiliza a Yahoo Finance API para carregar o histórico de preços das ações selecionadas.
carregar_tickers_acoes(): Função que carrega a lista de tickers das ações da B3 a partir de um arquivo IBOV.csv.
Interface do Usuário: Implementada com Streamlit, permitindo a seleção de ativos, ajuste de datas e visualização dos resultados.
Cálculo de Performance: Realiza o cálculo de retorno para cada ativo e para a carteira total, com feedback visual (cores) para ganhos e perdas.
Melhorias Futuras
Expansão de Ativos: Adicionar suporte para outros tipos de ativos, como fundos imobiliários ou ETFs.
Indicadores Técnicos: Incluir indicadores de análise técnica para uma visão mais completa do histórico de preços.
Versão Mobile: Desenvolver uma versão otimizada para dispositivos móveis.
Licença
Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para sugerir melhorias ou corrigir problemas.
