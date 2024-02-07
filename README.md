# Desafio Cientista de Dados 

![Alt Text](https://github.com/LuceliaLima/LH_CD_LUCELIA/blob/main/img/Banner_NY.jpg?raw=true)

Você foi alocado(a) em um time da Indicium que está trabalhando atualmente junto a um cliente no processo de criação de uma plataforma de aluguéis temporários na cidade de Nova York.  Para o desenvolvimento de sua estratégia de precificação, pediu para que a Indicium fizesse uma **análise exploratória dos dados** de seu maior concorrente, assim como um **teste de validação de um modelo preditivo**.

## New York City

A cidade de Nova York é mais populosa do que qualquer cidade brasileira. Com uma população de mais de 8 milhões de habitantes, Nova York é uma das cidades mais densamente povoadas dos Estados Unidos e é um centro cultural, econômico e político importante não só para o país, mas também para o mundo. 

A cidade abrange cinco regiões chamadas **boroughs** são estes: Bronx, Brooklyn, Manhattan, Queens e Staten Island.



- **1 - Manhattan é o grande centro**, é o coração de Nova York, é conhecida por seus arranha-céus icônicos, como o Empire State Building e o One World Trade Center. É o centro financeiro, comercial e cultural da cidade, abrigando instituições como Wall Street, a Broadway e a Times Square. 
- **2 - Brookly** localizado ao sudoeste de Manhattan, é o **borough mais populoso de Nova York** e é conhecido por sua diversidade étnica e cultural e maiores instalações portuárias da cidade.
- **3 - Queens** é uma mistura de **áreas residenciais, comerciais e industriais bem deversificada**, com grandes aeroportos e estádios de tênis e baisebol. 
- **4 - Bronx** localizado ao norte de Manhattan, é o **local mais pobre e violento da cidade e do país.** 
- **5 - Staten Island** situado ao sul de Manhattan, é conhecido por seu **ambiente mais suburbano** em comparação com os outros boroughs. Possui grandes áreas verdes e praias. 

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/5_Boroughs_Labels_New_York_City_Map.svg/800px-5_Boroughs_Labels_New_York_City_Map.svg.png" width='65%'>
fonte: https://pt.wikipedia.org/wiki/Boroughs_de_Nova_Iorque


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

Os resultados do Projeto foi salvo no formato pkl (packle) ao executar no Jupy necessario instalar com comando pip install pickle e importar a blioteca  com import pickle.

- Execução:

No terminal ou prompt de comando, execute o seguinte comando para iniciar o servidor do Jupyter Notebook: jupyter notebook. Após iniciar o servidor do Jupyter Notebook, o navegador padrão será aberto automaticamente exibindo o painel do Jupyter Notebook. Navegue até o diretório onde o projeto está localizado e clique no arquivo do notebook (.ipynb) para abri-lo.

Para carregar o arquivo pickle use o seguinte comando: 

with open("result_models.pkl", "rb") as f:
    resultados = pickle.load(f)


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



