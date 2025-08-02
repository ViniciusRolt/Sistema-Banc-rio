# Sistema Bancário em Python

Simulador simples de um sistema bancário feito em Python que permite:

- Cadastro de clientes com validação de nome, CPF.
- Depósito de valores
- Saque com limite diário e limite por operação
- Visualização de extrato com histórico das operações

---

## Como usar:

1. Clone este repositório:

git clone https://github.com/ViniciusRolt/Sistema-Banc-rio.git
cd Sistema-Banc-rio

Execute o programa:
python3 sistema.py

No menu, escolha as opções:

[c] Cadastrar cliente (exige nome completo, CPF e data de nascimento)

[d] Depositar valores

[s] Sacar valores (máximo 3 saques por dia, limite de R$ 500 por saque)

[e] Ver extrato (lista operações e saldo atual)

[q] Sair do programa

---
## Requisitos:
Python 3.x
