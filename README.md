### Automação de Processo de Consulta Jurídica

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/gsoaresdz/automcacao-processo-consulta-juridica?color=56BEB8">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/gsoaresdz/automcacao-processo-consulta-juridica?color=56BEB8">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/gsoaresdz/automcacao-processo-consulta-juridica?color=56BEB8">
</p>
<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#sparkles-análises-realizadas">Funcionalidades</a> &#xa0; | &#xa0;
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-execução">Execução</a> &#xa0; | &#xa0;
  <a href="#memo-estrutura-dos-dados">Estrutura dos Dados</a> &#xa0; | &#xa0;
  <a href="#memo-licença">Licença</a> &#xa0; | &#xa0;
  <a href="https://github.com/gsoaresdz" target="_blank">Autor</a>
</p>
<br>

## **:dart: Sobre**

Este repositório contém um projeto de automação para processos de consulta jurídica, focado em consultas de saldo de pagamento total de pessoas jurídicas (PJ) com base em datas. Utiliza Python para a implementação dos serviços e consultas.

## **:sparkles: Funcionalidades**

:heavy_check_mark: **Funcionalidade 1**: Consulta de saldo de pagamento total de PJ com base em datas.

:heavy_check_mark: **Funcionalidade 2**: Mapeamento de DTOs para formatação de dados retornados.

:heavy_check_mark: **Funcionalidade 3**: Uso de Lombok para construção de DTOs com a anotação @Builder.

## **:rocket: Tecnologias**

As seguintes ferramentas foram usadas neste projeto:

- [Python](https://www.python.org/)
- Flask
- [Pandas](https://pandas.pydata.org/)
- [Jupyter Notebook](https://jupyter.org/)

## **:white_check_mark: Requerimentos**

Antes de iniciar :checkered_flag:, você precisa ter [Python 3](https://www.python.org/downloads/) e Jupyter Notebook instalados.

## **:checkered_flag: Execução**

### Clonando o Repositório

Primeiramente, clone o repositório do projeto para sua máquina local.

```bash
$ git clone https://github.com/gsoaresdz/automcacao-processo-consulta-juridica.git
```

### Configuração e Execução do Projeto

1. Navegue até o diretório do projeto:

```bash
$ cd automcacao-processo-consulta-juridica
```

1. Crie um ambiente virtual e ative-o:

```bash
$ python3 -m venv venv
$ source venv/bin/activate
```

1. Instale as dependências do projeto:

```bash
$ pip install -r requirements.txt
```

1. Execute o servidor Flask:

```bash
$ flask run
```

### Usando Jupyter Notebook

1. Instale as dependências necessárias para Jupyter Notebook:

```bash
$ pip install jupyter
```

1. Inicie o Jupyter Notebook:

```bash
$ jupyter notebook
```

1. Abra o arquivo **main.ipynb** e execute as células de código para visualizar as análises e gráficos.

## **:memo: Estrutura dos Dados**

Os dados estão estruturados nas seguintes colunas:

- id
- nome
- saldo
- dataConsulta

## **:memo: Licença**

Este projeto está sob licença do MIT. Para obter mais detalhes, consulte o arquivo [LICENSE](LICENSE).

Feito com :heart: by <a href="https://github.com/gsoaresdz" target="_blank">gsoaresdz</a>

&#xa0;

<a href="#top">De volta ao topo</a>
