# **Projeto de Consulta Jurídica**

## **Sobre o Projeto**

O projeto de Consulta Jurídica é um script em Python que automatiza a pesquisa de processos jurídicos em um site fictício utilizando Selenium. Ele lê os dados dos processos de um arquivo Excel e preenche um formulário no site para buscar informações sobre cada processo.

## **Requisitos**

- Python 3.x
- Selenium
- Pandas
- Google Chrome

## **Instalação**

1. Instale o Python 3.x em seu sistema operacional (caso não esteja instalado): **[https://www.python.org/downloads/](https://www.python.org/downloads/)**
2. Instale o pacote Selenium:

```python
pip install selenium
```

1. Instale o pacote Pandas:

```python
pip install pandas
```

1. Baixe o ChromeDriver compatível com a versão do seu navegador Google Chrome: **[https://sites.google.com/a/chromium.org/chromedriver/downloads](https://sites.google.com/a/chromium.org/chromedriver/downloads)** e extraia o arquivo em uma pasta acessível.

## **Como Usar**

1. Atualize a variável **`webdriver.Chrome()`** no código com o caminho para o ChromeDriver baixado. Por exemplo:

```
navegador = webdriver.Chrome(executable_path='caminho/para/o/chromedriver')
```

1. Prepare um arquivo Excel chamado **`Processos.xlsx`** com as informações dos processos a serem pesquisados. O arquivo deve ter as colunas "Cidade", "Nome", "Advogado" e "Processo". Salve o arquivo no mesmo diretório do script.
2. Execute o script:

```python
python consulta_juridica.py
```

1. Após a execução do script, um novo arquivo Excel chamado **`Processo Atualizado.xlsx`** será gerado no mesmo diretório, contendo os resultados das pesquisas.

## **Funcionamento**

O script realiza as seguintes ações:

1. Abre o navegador Google Chrome.
2. Carrega o arquivo Excel **`Processos.xlsx`** e exibe seu conteúdo.
3. Para cada linha da tabela de processos:
    - Abre a página inicial do site de busca jurídica.
    - Seleciona a cidade do processo.
    - Preenche o formulário com os dados do processo (Nome, Advogado e Número).
    - Clica em "Pesquisar".
    - Confirma a pesquisa no alerta.
    - Aguarda o resultado da pesquisa e atualiza o status do processo na tabela (Encontrado ou Não encontrado).
4. Fecha o navegador.
5. Exibe a tabela atualizada com os resultados das pesquisas.
6. Salva a tabela atualizada em um novo arquivo Excel chamado **`Processo Atualizado.xlsx`**.
