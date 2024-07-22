# base-repo

[![link-repo-base](https://img.shields.io/badge/Repo-Base-blue)](./)

[![GIT](https://img.shields.io/badge/GIT-orange)](./)
[![MD](https://img.shields.io/badge/MD-darkblue)](./)
[![YML](https://img.shields.io/badge/YML-darkblue)](./)

[![link-readme-inglês](https://img.shields.io/badge/README-English/Inglês-red)](./README.md#english)
[![link-readme-Portugês](https://img.shields.io/badge/README-Portuguese/Portugês-green)](./README.md#português)

## English

Bifrost is a PHP framework with a basis for web development

## Description

This repository contains a `tasks.json` file inside the `.vscode` folder, which defines tasks to pull repositories with `API`, `APP`, `Banco` scripts and others.

## Requirements

* Git
*Docker
* Docker Compose
* Visual Studio Code (VS Code)

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/Felipe-Cavalca/BifrostPHP.git
    cd BifrostPHP
    ```

2. Open the project in Visual Studio Code:

    ```sh
    code .
    ```

3. In VS Code, open the built-in terminal and run the tasks defined in `tasks.json` to pull the scripts from the required repositories:
    * In the menu, go to **Terminal > Run Task...**
    * Select the desired task to perform.

4. Build and start Docker containers:

    ```sh
    docker-compose up --build -d
    ```

## Contributions

Contributions are welcome! Please follow the steps below to contribute:

1. Fork the project.
2. Create a new branch:

    ```sh
    git checkout -b my-feature
    ```

3. Make your changes and commit:

    ```sh
    git commit -m 'My new feature'
    ```

4. Upload to remote repository:

    ```sh
    git push origin my-feature
    ```

5. Open a Pull Request.

## português

Bifrost é um framework em PHP com uma base para o desenvolvimento web

## Descrição

Este repositório contém um arquivo `tasks.json` dentro da pasta `.vscode`, que define tarefas para puxar os repositórios com os scripts de `API`, `APP`, `Banco` entre outros.

## Requisitos

* Git
* Docker
* Docker Compose
* Visual Studio Code (VS Code)

## Instalação

1. Clone o repositório:

    ```sh
    git clone https://github.com/Felipe-Cavalca/BifrostPHP.git
    cd BifrostPHP
    ```

2. Abra o projeto no Visual Studio Code:

    ```sh
    code .
    ```

3. No VS Code, abra o terminal integrado e execute as tarefas definidas no `tasks.json` para puxar os scripts dos repositórios necessários:
    * No menu, vá para **Terminal > Run Task...**
    * Selecione a tarefa desejada para executar.

4. Construa e inicie os containers Docker:

    ```sh
    docker-compose up --build -d
    ```

## Contribuições

Contribuições são bem-vindas! Por favor, siga os passos abaixo para contribuir:

1. Faça um fork do projeto.
2. Crie uma nova branch:

    ```sh
    git checkout -b minha-feature
    ```

3. Faça suas modificações e commit:

    ```sh
    git commit -m 'Minha nova feature'
    ```

4. Envie para o repositório remoto:

    ```sh
    git push origin minha-feature
    ```

5. Abra um Pull Request.
