# Aplicação de Análise de Dados em Python
Este projeto é uma aplicação desenvolvida em Python para análise de dados utilizando a biblioteca tkinter para a interface gráfica e matplotlib para a visualização de gráficos. A aplicação permite abrir arquivos Excel, visualizar e editar dados, e criar diversos tipos de gráficos para análise.

## Funcionalidades
- Abrir Arquivo: Permite ao usuário abrir arquivos Excel e carregar os dados para análise.
- Visualização de Dados: Mostra dados em uma Treeview que pode ser editada.
- Criação de Gráficos: Gera diferentes tipos de gráficos utilizando matplotlib:
  - Gráfico de Colunas
  - Gráfico de Pizza
  - Gráfico de Linhas
  - Gráfico de Área
  - Gráfico de Funil
- Edição de Dados: Oferece opções para editar os dados carregados, como:
  - Renomear Colunas
  - Remover Colunas
  - Remover Linhas em Branco
  -  Remover Linhas Alternadas
  - Remover Duplicados
## Estrutura do Código
Classe Application
- Construtor (__init__): Configura a janela principal da aplicação e cria os widgets necessários.
- Método create_widgets: Cria a interface gráfica com botões para diferentes funcionalidades e configura o canvas para gráficos.
- Método abrir_arquivo: Abre um arquivo Excel e carrega os dados em um DataFrame.
- Método abrir_janela_editar_dados: Cria uma nova janela para edição dos dados com várias opções de formatação.
- Métodos de Gráficos: Implementa métodos para abrir janelas para diferentes tipos de gráficos.
## Utilização
  1. Abrir Arquivo:
Clique em "Arquivo" no menu e selecione "Abrir".
Escolha um arquivo Excel (.xlsx) para carregar os dados.  
  2. Visualização e Edição de Dados:
Clique em "Editar Dados" para abrir a janela de edição.
Utilize a Treeview para visualizar e editar os dados.
  3. Criação de Gráficos:
Selecione o tipo de gráfico desejado na interface principal.
Personalize e visualize o gráfico.

## Dependências
tkinter (para a interface gráfica)

matplotlib (para criação de gráficos)

pandas (para manipulação de dados)

### Executando o Projeto
Para executar a aplicação, certifique-se de ter as bibliotecas necessárias instaladas e execute o script Python:
```bash
python nome_do_arquivo.py
```
Substitua nome_do_arquivo.py pelo nome do arquivo onde o código está salvo.
