# 🛠️ Sistema de Gerenciamento de Oficina Mecânica
Este repositório contém o modelo EER (Entidade-Relacionamento Estendido) para um sistema de controle e execução de Ordens de Serviço (OS) em uma oficina mecânica.

# 📋 Sobre o Projeto

O objetivo do sistema é automatizar o fluxo de trabalho de uma oficina, desde a entrada do veículo pelo cliente até a execução do serviço por equipes especializadas.

Fluxo de Funcionamento:
- Clientes cadastram seus Veículos.
- Cada veículo é direcionado a uma Equipe de Mecânicos.
- A equipe identifica os serviços e gera uma OS (Ordem de Serviço).
- O valor da OS é calculado com base em uma Tabela de Referência de Mão-de-Obra e no valor das Peças utilizadas.
- A mesma equipe que avalia é responsável pela execução após autorização do cliente.

# 🗄️ Estrutura do Banco de Dados

O modelo é composto pelas seguintes entidades principais:
- Oficina Mecânica: Entidade central que gerencia equipes e mecânicos.
- Clientes & Veículos: Registro dos proprietários e seus respectivos automóveis.
- Mecânicos: Profissionais com código, nome, endereço e especialidade.
- Equipe de Mecânicos: Agrupamento de profissionais responsáveis pela execução das OS.
- OS (Ordem de Serviço): Contém número, data de emissão, valor total, status e previsão de entrega.
- Peças & Tabela de Mão-de-Obra: Catálogos de preços para composição do valor total da OS.
