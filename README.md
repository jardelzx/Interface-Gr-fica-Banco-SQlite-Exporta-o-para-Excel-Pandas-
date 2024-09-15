# Ferramenta de Cadastro de Clientes

Este projeto é uma ferramenta de cadastro de clientes desenvolvida em Python, utilizando as bibliotecas **Tkinter**, **SQLite** e **Pandas**. A interface gráfica permite o cadastro de clientes e a exportação da base de dados para um arquivo Excel.

## Funcionalidades

- Cadastro de clientes com nome, sobrenome, e-mail e telefone.
- Exportação da base de clientes para um arquivo Excel.
  
## Requisitos

Certifique-se de ter instalado o Python e as bibliotecas necessárias para rodar este projeto.

### Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/jardelzx/Interface-Grafica-Banco-SQlite-Exportacao-para-Excel-Pandas.git
    ```
2. Instale as dependências:
    ```bash
    pip install pandas tk sqlite3 openpyxl
    ```

### Como Usar

1. Rode o arquivo Python:
    ```bash
    python nome_do_arquivo.py
    ```
2. Preencha os campos para cadastrar um cliente.
3. Utilize o botão **Exportar Base de Clientes** para gerar um arquivo Excel com todos os clientes cadastrados.

### Estrutura do Banco de Dados

O banco de dados `bancos_clientes.db` é criado automaticamente na pasta do projeto. Ele possui uma tabela chamada `clientes` com as seguintes colunas:

- `nome` - Nome do cliente
- `sobrenome` - Sobrenome do cliente
- `email` - Endereço de e-mail
- `telefone` - Telefone de contato
