# Desafio Cientista de Dados 

Você foi alocado(a) em um time da Indicium que está trabalhando atualmente junto a um cliente no processo de criação de uma plataforma de aluguéis temporários na cidade de Nova York.  Para o desenvolvimento de sua estratégia de precificação, pediu para que a Indicium fizesse uma **análise exploratória dos dados** de seu maior concorrente, assim como um **teste de validação de um modelo preditivo**.

### Objetivo:
- Desenvolver um modelo de previsão de **preços** a partir do dataset oferecido; 
- Avaliar tal modelo utilizando as **métricas de avaliação** que mais fazem sentido para o problema. 

### **Dicionário de variáveis:**

*   **id** - Atua como uma chave exclusiva para cada anúncio nos dados do aplicativo
*   **name** - O nome do anúncio (propriedade)
*   **host_id** - O id do usuário que hospedou o anúncio
*   **host_name** - Nome do usuário que hospedou o anúncio
*   **bairro_group** - Nome do bairro onde o anúncio está localizado
*   **bairro** - Nome da área onde o anúncio está localizado.
*   **latitude** - Latitude do local
*   **longitude** - Longitude do local
*   **room_type** - Tipo de espaço de cada anúncio (tipo de quarto)
*   **price** - Preço por noite em dólares listado pelo anfitrião
*   **minimo_noites** - Número mínimo de noites que o usuário deve reservar
*   **numero_de_reviews** - Número de comentários(avaliações) dados a cada listagem
*   **ultima_review** - Data da última revisão dada à listagem
*   **reviews_por_mes** - Número de avaliações fornecidas por mês
*   **calculado_host_listings_count** - Quantidade de imóveis por anfitrião.
*   **disponibilidade_365** - Número de dias em que o anúncio está disponível para reserva em 365 dias

a) Como instalar e executar o Projeto

- Instalação:

O projetom foi realizado no Jupyter notebook, caso não tem o Jupyter Notebook instalado, pode instalá-lo usando o pip (gerenciador de pacotes do Python) com o seguinte comando no terminal ou prompt de comando: pip install notebook. 

- Execução:

No terminal ou prompt de comando, execute o seguinte comando para iniciar o servidor do Jupyter Notebook: jupyter notebook. Após iniciar o servidor do Jupyter Notebook, o navegador padrão será aberto automaticamente exibindo o painel do Jupyter Notebook. Navegue até o diretório onde o projeto está localizado e clique no arquivo do notebook (.ipynb) para abri-lo.

b) Pacotes e Versões

Foi utilizado as seguintes bibliotecas para a análise:

* pandas - version: 2.2.0
* matplotlib - version: 3.7.2
* seaborn - version: 0.12.2
* scikit-learn - version: 1.3.0
* wordcloud - version: 1.9.3
* xgboost - version: 2.0.3
* lightgbm- version: 4.3.0
* catboost - version: 1.2.2
* Python - version: 3.11.5



