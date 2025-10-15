# ETL SuperStore

Este projeto realiza o processamento e análise de dados da SuperStore, implementando um pipeline ETL (Extract, Transform, Load) completo e preparando os dados para análise no BigQuery.

## 📂 Estrutura do Projeto

```
ETL-SuperStore/
├── data/
│   ├── raw/           # Dados brutos originais
│   └── processed/     # Dados após processamento
├── notebooks/         # Jupyter notebooks para análise
│   └── etl_superstore.ipynb
├── src/              # Códigos fonte do projeto
│   └── load_data.py  # Script para carregamento de dados
└── requirements.txt   # Dependências do projeto
```

## 🚀 Configuração do Ambiente

1. Clone o repositório:
```bash
git clone https://github.com/iannacastro/ETL-SuperStore.git
cd ETL-SuperStore
```

2. Crie e ative um ambiente virtual (opcional, mas recomendado):
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
.\venv\Scripts\activate   # Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

## 📊 Dataset

O dataset contém informações sobre vendas da SuperStore, incluindo:
- Categorias de produtos
- Informações de vendas e lucros
- Dados geográficos
- Informações de clientes
- Detalhes de envio

### Estrutura dos Dados:
- Total de registros: 51,290
- Total de colunas: 27
- Principais features incluem:
  - Categoria de produto
  - Cidade/País/Região
  - ID e nome do cliente
  - Dados de pedidos e vendas
  - Informações de envio
  - Datas e períodos

## 💻 Como Usar

1. Para carregar e visualizar os dados:
```bash
python src/load_data.py
```

2. Para análises interativas, abra o notebook Jupyter:
```bash
jupyter notebook notebooks/etl_superstore.ipynb
```

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Pandas para manipulação de dados
- Google BigQuery para armazenamento
- Jupyter Notebooks para análise interativa
- Bibliotecas auxiliares (requirements.txt)

## 📦 Dependências Principais

- pandas
- numpy
- python-dotenv
- google-cloud-bigquery
- pandas-gbq
- jupyter
- beautifulsoup4

## 👥 Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/NovaFeature`)
3. Commit suas mudanças (`git commit -m 'Adicionando nova feature'`)
4. Push para a branch (`git push origin feature/NovaFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
Desenvolvido por [iannacastro](https://github.com/iannacastro)