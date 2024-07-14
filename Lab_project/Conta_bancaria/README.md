# Desafio Plataforma DIO: Simulando uma Conta Bancária através do Terminal/Console

## Introdução
Desafio do curso Trilha Java Básico da DIO ministrado pelo instrutor Gleyson Sampaio.

## Sintaxe - Desafio
Vamos praticar todo o conteúdo apresentado no módulo de Sintaxe codificando o seguinte cenário.

## Descrição do Projeto
Crie o projeto `ContaBanco` que receberá dados via terminal contendo as características de conta em banco conforme atributos abaixo:

### Atributos da Conta Bancária
| Atributo      | Tipo    | Exemplo      |
|---------------|---------|--------------|
| Numero        | Inteiro | 1021         |
| Agencia       | Texto   | 067-8        |
| Nome Cliente  | Texto   | MARIO ANDRADE|
| Saldo         | Decimal | 237.48       |

### Passos para Realização do Desafio
1. Crie um projeto Java chamado `ContaBanco`.
2. Dentro do projeto, crie uma classe `ContaTerminal.java` para realizar toda a programação do nosso programa.

### Regras de Declaração de Variáveis
Revise sobre regras de declaração de variáveis:

- Numero: Inteiro
- Agencia: Texto
- Nome Cliente: Texto
- Saldo: Decimal

### Entrada de Dados via Terminal
Permita que os dados sejam inseridos via terminal. O usuário receberá uma mensagem indicando quais informações serão solicitadas. Por exemplo:

- Programa: "Por favor, digite o número da Agência !"
- Usuário: 1021 (depois ENTER para o próximo campo)

### Concatenar e Exibir a Mensagem Final
Revise sobre concatenação e classe String com método `concat`. Depois de todas as informações terem sido inseridas, o sistema deverá exibir a seguinte mensagem:

"Olá [Nome Cliente], obrigado por criar uma conta em nosso banco, sua agência é [Agencia], conta [Numero] e seu saldo [Saldo] já está disponível para saque".