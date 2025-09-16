# G-meo_Digital_TE2
Projeto de gêmeo digital para aula de Tópicos Especiais em Engenharia de Controle e Automação

# 🤖 Gêmeo Digital para Otimização de Célula Robotizada

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📄 Descrição

Este projeto é um protótipo funcional de um **Gêmeo Digital (Digital Twin)** desenvolvido como trabalho final para a disciplina de Tópicos Especiais II em Controle e Automação. Ele simula uma célula de montagem robotizada, comum no Polo Industrial de Manaus (PIM), permitindo a validação e otimização de processos de automação em um ambiente virtual antes da implementação física.

## 🎯 Objetivo do Projeto

O principal objetivo é demonstrar como os princípios da Indústria 4.0 podem ser aplicados de forma acessível e de baixo custo para solucionar desafios da indústria, como:
* Reduzir o tempo de comissionamento de novas linhas de produção.
* Minimizar riscos de colisão e danos a equipamentos.
* Eliminar o desperdício de matéria-prima durante a fase de testes.
* Servir como uma plataforma segura para treinamento de operadores e programadores.

## ✨ Características Inovadoras

* **Arquitetura de Baixo Custo:** Utiliza exclusivamente softwares gratuitos e de código aberto.
* **Modularidade:** O controle (Python) é desacoplado da simulação (CoppeliaSim) via protocolo MQTT, permitindo flexibilidade e escalabilidade.
* **Comissionamento Virtual:** Permite que 100% da lógica de controle seja testada e validada offline.

## 📸 Demonstração em Vídeo

*Em andamento*

![GIF da Simulação em Funcionamento](Em andamento)

## 🚀 Tecnologias Utilizadas

* **Simulação:** CoppeliaSim (V-REP)
* **Linguagem de Controle:** Python 3
* **Comunicação:** Protocolo MQTT (com a biblioteca Paho-MQTT)
* **Scripting Embarcado:** LUA (dentro do CoppeliaSim)
* **Hardware (Prova de Conceito):** ESP32

## 🔧 Como Executar o Projeto

Siga os passos abaixo para executar a simulação em sua máquina.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
* [CoppeliaSim EDU]()
* [Python 3.9+]()
* Um Broker MQTT (como o [Mosquitto]())
* Git

### Passo a Passo

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
    ```
2.  Instale as dependências do Python:
    ```bash
    pip install paho-mqtt
    ```
3.  Inicie seu Broker MQTT local.
4.  Abra o arquivo de simulação `nome_da_cena.ttt` no CoppeliaSim e inicie a simulação (clicando no botão "Play").
5.  Execute o script de controle principal:
    ```bash
    python main_controller.py
    ```

## 👨‍💻 Autor

Desenvolvido por **[Yuri Macedo Michele]**.

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/yuri-m-michele)

## 📜 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
