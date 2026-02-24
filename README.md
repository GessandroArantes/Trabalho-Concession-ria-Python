# 🚗 Sistema de Concessionária - Dreams Master

Este é um sistema interativo em Python desenvolvido para gerenciar operações de compra, venda e aluguel de veículos. O projeto foca na manipulação de estruturas de dados complexas e lógica de negócio aplicada.

## 🛠️ Funcionalidades

O sistema simula o atendimento real de uma loja de veículos:

* **Cadastro de Cliente:** Captura nome, contato e saldo inicial.
* **Venda de Veículo (Cliente → Loja):** O sistema avalia o veículo com base na Tabela FIPE e aplica um desconto de 12% para a proposta de compra da empresa.
* **Aluguel de Veículos:** Permite locação por diárias (R$ 77,00/dia) com verificação automática de saldo e disponibilidade de estoque.
* **Compra de Veículos (Cliente ← Loja):** O cliente pode adquirir carros do estoque com acréscimo de 25% sobre a FIPE.
* **Gestão de Saldo:** Atualização em tempo real do saldo do cliente após cada transação bem-sucedida.

## 💻 Conceitos Técnicos Aplicados

* **Dicionários e Listas:** Armazenamento de dados do cliente, estoque e tabela de preços.
* **Funções Modulares:** Código organizado em funções específicas para cada operação (`vender()`, `alugar()`, `comprar()`).
* **Estruturas de Repetição e Decisão:** Uso de `while True` para o menu principal e `match-case` para seleção de opções.
* **Tratamento de Strings:** Padronização de entradas com `.strip()`, `.title()` e `.lower()`.

## 📈 Exemplo de Uso

1. O usuário informa um saldo inicial de R$ 100.000,00.
2. Ao escolher comprar um **Corolla** (FIPE R$ 125.000,00), o sistema calcula o valor de venda (FIPE + 25%).
3. O sistema valida se o saldo é suficiente e realiza a transação ou cancela por falta de fundos.

---
🚀 *Desenvolvido para consolidar conhecimentos em lógica de programação e estruturas de dados em Python.*
