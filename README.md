# Sistema Bancário 🏦

Este é um projeto simples e funcional de um **Sistema Bancário** desenvolvido em Python, que oferece recursos básicos para gerenciar transações financeiras por meio de uma interface no terminal. Esta é a **primeira versão** do sistema.

---

## 📋 Funcionalidades

O sistema oferece as seguintes operações:

- **[1] Depositar:** Permite adicionar um valor à conta.
- **[2] Sacar:** Permite realizar saques, considerando restrições como limite por operação e número máximo de saques diários.
- **[3] Extrato:** Exibe um resumo das movimentações realizadas e o saldo atual.
- **[0] Sair:** Encerra a execução do programa.

---

## ⚙️ Regras de Funcionamento

### Depósitos:
- Apenas valores positivos são aceitos.
- Valores inválidos serão rejeitados com uma mensagem de erro.

### Saques:
- O valor do saque não pode ultrapassar:
  - O saldo disponível.
  - O limite de R$ 500,00 por operação.
- O número máximo de saques diários é **3**.
- Apenas valores positivos são permitidos.

### Extrato:
- Exibe todas as transações realizadas (depósitos e saques).
- Caso não haja movimentações, será exibida a mensagem: *"Não foram realizadas movimentações."*
- Mostra o saldo atualizado ao final.

---

## 🛠️ Pré-requisitos

Certifique-se de ter o seguinte antes de executar o programa:

- **Python 3.11** instalado no sistema.

---

## 🚀 Como Executar

1. Clone este repositório para o seu sistema:
   ```bash
   git clone https://github.com/DiogoQa/Sistema-bancario.git
