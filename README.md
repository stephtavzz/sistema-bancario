# 🏦 Sistema Bancário em Python

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio prático da **DIO (Digital Innovation One)** com o objetivo de implementar um **sistema bancário básico** utilizando a linguagem Python. O sistema simula operações comuns de uma conta bancária, como **depósitos**, **saques** e **emissão de extrato**, respeitando algumas regras de negócio predefinidas.

## ⚙️ Funcionalidades Implementadas

1. **Depósito**
   - Aceita apenas valores positivos.
   - Registra o valor na conta e no extrato.

2. **Saque**
   - Limite de até **3 saques por dia**.
   - Cada saque não pode ultrapassar **R$ 500,00**.
   - Verifica se o saldo é suficiente antes de permitir a operação.
   - Registra o valor sacado no extrato.

3. **Extrato**
   - Exibe todas as movimentações (depósitos e saques) com formatação de moeda.
   - Mostra o saldo atual da conta.
   - Caso não haja movimentações, informa ao usuário.

## 🖥️ Exemplo de Uso

Ao executar o script, o usuário verá um menu interativo:
   - [d] Depositar
   - [s] Sacar
   - [e] Extrato
   - [q] Sair


As operações são realizadas conforme a escolha do usuário, com mensagens claras de sucesso ou falha conforme as regras do sistema.

## ✅ Regras de Negócio

- Apenas valores positivos são aceitos para depósito e saque.
- O limite de saque é de R$ 500,00 por operação.
- O número máximo de saques diários é 3.
- O sistema não possui autenticação ou múltiplos usuários (versão simplificada).
- Todos os registros de movimentações são armazenados em memória.

## 🛠️ Tecnologias Utilizadas

- Python 3.10+
- **Visual Studio Code (VS Code)** como ambiente de desenvolvimento

## 📂 Como Executar o Projeto

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/sistema-bancario-python.git
```

2. Navegue até o diretório do projeto:
```bash
cd sistema-bancario-python
```

3. Execute o script:
```bash
python sistema_bancario.py
```
## 👩‍💻 Autora

**Stephanie Tavares dos Santos**  
🔗 [LinkedIn](https://www.linkedin.com/in/stephanie-t-santos/)  
💻 [GitHub](https://github.com/stephtavzz)  


Este projeto foi desenvolvido para fins educacionais, como parte de um desafio da plataforma DIO, visando a prática de conceitos básicos de programação com Python.
