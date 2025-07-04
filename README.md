# Simulador de Multibanco em Java

Projeto académico desenvolvido no âmbito da unidade curricular **Fundamentos de Programação** do curso de **Engenharia Informática e Telecomunicações** da **Escola Superior de Tecnologia e Gestão de Lamego**.

## 📌 Descrição

Este projeto consiste num **simulador de Multibanco** implementado em Java. O sistema permite a criação, gestão e utilização de contas bancárias (Conta à Ordem e Conta Estudante), incluindo funcionalidades como:

- Verificação de saldo
- Levantamentos e depósitos
- Transferências entre contas
- Registo de logs de operações
- Funcionalidades administrativas restritas

## 🧱 Estrutura do Projeto

O sistema é dividido em várias classes, com responsabilidades distintas:

- `Administrador` – Acesso e funcionalidades de administração
- `Conta` – Gestão de dados e operações bancárias
- `ContaEstudante` – Subclasse de `Conta`
- `Utilizador` – Dados e identificação de utilizadores
- `App` – Classe principal para execução do programa

## 🖥️ Ambiente de Desenvolvimento

- **Editor:** [Visual Studio Code](https://code.visualstudio.com/)
- **Linguagem:** Java
- **Requisitos:** JDK 19+
