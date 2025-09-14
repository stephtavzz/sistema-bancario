# 🚗 Sistema de Estacionamento em C#

![C#](https://img.shields.io/badge/C%23-10.0%2B-purple)
![.NET](https://img.shields.io/badge/.NET-9.0-blue)

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio prático da **DIO (Digital Innovation One)** no módulo de **Fundamentos do .NET**.  
O objetivo é implementar um **sistema de estacionamento** que permita gerenciar veículos, incluindo operações de **cadastro**, **remoção** e **listagem**.

## ⚙️ Funcionalidades Implementadas

1. **Cadastrar veículo**
   - O usuário informa a placa do veículo;
   - O sistema armazena a placa em uma lista.

2. **Remover veículo**
   - O usuário informa a placa do veículo;
   - Caso o veículo esteja estacionado, o sistema solicita a quantidade de horas e calcula o valor total:
     ```
     valorTotal = precoInicial + (precoPorHora * horas)
     ```
   - O veículo é removido da lista e o valor é exibido.

3. **Listar veículos**
   - Exibe todas as placas atualmente cadastradas;
   - Caso não haja veículos, informa ao usuário.

4. **Menu interativo**
   - O usuário pode escolher entre:
     - Cadastrar veículo
     - Remover veículo
     - Listar veículos
     - Encerrar o programa

## 🖥️ Exemplo de Uso

Ao executar o programa, o usuário interage com o seguinte menu:

Digite a sua opção:
1 - Cadastrar veículo
2 - Remover veículo
3 - Listar veículos
4 - Encerrar


As operações são realizadas conforme a escolha do usuário, com mensagens claras de sucesso ou falha.

## ✅ Regras de Negócio

- O sistema armazena apenas a **placa do veículo**;
- Para remoção, é necessário informar a quantidade de horas estacionado;
- O cálculo do valor é feito a partir do preço inicial + preço por hora;
- Caso a placa não esteja cadastrada, o sistema exibe uma mensagem de erro.

## 🛠️ Tecnologias Utilizadas

- C# 10+
- .NET 6.0
- **Visual Studio Code** ou **Visual Studio** como ambiente de desenvolvimento

## 📂 Como Executar o Projeto

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/sistema-estacionamento-csharp.git
```

2. Navegue até o diretório do projeto:
```bash
cd sistema-estacionamento-csharp
```

3. Execute o projeto:
```bash
dotnet run
```
## 👩‍💻 Autora

**Stephanie Tavares dos Santos**  
🔗 [LinkedIn](https://www.linkedin.com/in/stephanie-t-santos/)  
💻 [GitHub](https://github.com/stephtavzz)  


Este projeto foi desenvolvido para fins educacionais, como parte de um desafio da plataforma DIO, visando a prática de sintaxe básica com C# e .NET.
