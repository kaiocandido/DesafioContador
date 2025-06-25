# Validação de Parâmetros em Java

Este projeto demonstra como criar e utilizar uma exceção personalizada em Java chamada `ParametrosInvalidosException`. Ele é ideal para fins educativos, mostrando como validar entrada de dados e lançar exceções de forma adequada.

## 📌 Descrição

O programa solicita dois números inteiros do usuário. Se o primeiro número for maior que o segundo, uma exceção personalizada (`ParametrosInvalidosException`) é lançada. Caso contrário, o programa realiza uma contagem simples entre os dois números informados.

## 📂 Estrutura do Projeto

- `Main.java`  
  Contém a lógica principal da aplicação, onde ocorre a leitura dos parâmetros e a chamada da função de contagem.

- `ParametrosInvalidosException.java`  
  Classe da exceção personalizada que estende `Exception`, usada para validar os parâmetros de entrada.

## 🛠️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/kaiocandido/DesafioContador
