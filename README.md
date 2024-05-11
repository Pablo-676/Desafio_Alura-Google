# Desafio_Alura-Google : Gerador de Dashboards Automático


# Descrição:

- Este script Python utiliza a API Gemini para automatizar a criação de dashboards informativos a partir de um dataframe. O script segue um fluxo passo-a-passo, desde a análise do dataframe e sugestões de gráficos até a geração dos dashboards com descrições detalhadas.

# Funcionalidades:

- Análise de Dataframe: O script extrai informações relevantes das colunas do dataframe e as utiliza para sugerir gráficos adequados.
- Sugestões de Gráficos: O script sugere diferentes tipos de gráficos (linha, barra, scatter, histograma, etc.) e as colunas a serem utilizadas em cada um deles.
- Geração de Dashboards: O script gera automaticamente os dashboards utilizando a biblioteca Plotly Express, com base nas sugestões do Gemini.
- Descrições dos Gráficos: O script fornece descrições detalhadas para cada dashboard, explicando o que cada gráfico representa e quais insights podem ser obtidos.

# Pré-requisitos:
- Python 3.x
- Bibliotecas: pandas, google.generativeai, plotly-express
- Chave da API do Google Generative AI

# Como Usar:
- Clone este repositório.
- Instale as bibliotecas necessárias: pip install pandas google-generativeai plotly-express
- Substitua a chave da API do Google Generative AI no código (configuração da API Gemini).
- Carregue o seu dataframe no script (df = pd.read_csv('seu_dataframe.csv')).
OBS: Nesse repostorio existem dois arquivos csv, você pode testar com qualquer um deles, ou importar outro arquivo.
- Execute o script: python gerador_dashboards.py.
- O script irá gerar os dashboards e as descrições correspondentes.

#Observações:
- O script é um exemplo de como automatizar a criação de dashboards com a API Gemini. Você pode adaptá-lo às suas necessidades específicas.
- Certifique-se de ter acesso à chave da API do Google Generative AI para utilizar o script.
- O script pode ser expandido para incluir outras funcionalidades, como a geração de relatórios em PDF ou a integração com ferramentas de BI.
