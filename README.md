# To Do APP (🐍 Python & 🎲 SQLite)

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
[![GitHub license](https://img.shields.io/github/license/devscie/PythonConnectDb)](https://github.com/devscie/PythonConnectDb/blob/master/LICENSE)

## 💻 Sobre o projeto

Este projeto consiste em criar uma aplicação CRUD (create, read, update and delete) com python e sqlite.
A aplicação será um app lista de tarefas (To Do APP) em que poderemos adicionar, remover e alterar as tarefas de rotina que devem ser priorizadas.
A interface da aplicação será o próprio terminal de linha de comando.


Tabela tarefa 
___

Campo     | Tipo       | Requerido
--------- | ---------- | ----------
cd_tarefa | inteiro    | sim
tarefa    | texto      | sim
concluido | inteiro    | sim

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Python](https://www.python.org/)
- [SQLite](https://www.sqlite.org/)

Índice de conteúdos
=================
<!--ts-->
   * [Implementação]
      * [Conexão com o banco de dados e comandos sql](https://github.com/devscie/PythonConnectSQLite_ToDoAPP/blob/master/db.py)
      * [Interface de linha de comando e interação com o usuário](https://github.com/devscie/PythonConnectSQLite_ToDoAPP/blob/master/mensagens.py)
      * [Controle o fluxo do programa](https://github.com/devscie/PythonConnectSQLite_ToDoAPP/blob/master/app.py)
   * [Comandos]
      * [Create - cria a tabela 'tarefa' caso ela não exista]
      * [Insert - adiciona uma nova tarefa]
      * [SELECT - retorna a lista de tarefas cadastras]
      * [Update - marca a tarefa como concluida]
      * [Delete - remove a tarefa da tabela]
   * [License](https://github.com/devscie/PythonConnectSQLite_ToDoAPP/blob/master/LICENSE)
<!--te-->

### Features

- [x] Adicionar tarefa
- [x] Marcar tarefa
- [x] Remove tarefa

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Python](https://www.python.org/). 
Além disso um bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 💻 Rodando

```bash
# Clone este repositório
$ git clone <https://github.com/devscie/PythonConnectSQLite_ToDoAPP>

# Crie o virtualenv com o nome python-sqlite
$ virtualenv PythonConnectSQLite_ToDoAPP

# Habilite o python3
$ $ virtualenv -p /usr/bin/python3 PythonConnectSQLite_ToDoAPP

# Acesse a pasta do projeto
$ cd PythonConnectSQLite_ToDoAPP

# Ative o ambiente
$ source bin/activate

# Instale as dependências
$ pip install -r requirements.txt

# Executar To Do APP
$ python3 app.py

# "tecle 99 volta para o menu inicial, [CTRL+C] sai"

# "O que deseja fazer? 1 = Nova tarefa, 2 = Concluir tarefa, 3 = Remover tarefa => "
$
```

###	🚧 To Do APP - Lista de Tarefas - Em construção 🚧

### Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
>> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions)


## Licença

Este projeto esta sobe a licença MIT.

## Autor

<img src="https://avatars3.githubusercontent.com/u/78492236" width="100px;" alt="Avatar" style="border-radius: 50%;">
<b>Vinicius George dos Santos</b>
<br /><br />

👋🏽 Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-Vinicius-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/vinicius-george-dos-santos-932b29167/)](https://www.linkedin.com/in/vinicius-george-dos-santos-932b29167/) 
[![Gmail Badge](https://img.shields.io/badge/-devscient@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:devscient@gmail.com)](mailto:devscient@gmail.com)
