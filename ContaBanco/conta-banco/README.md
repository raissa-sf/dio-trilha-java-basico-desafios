# Conta Terminal - Sistema de Cadastro Bancário

## Descrição do Projeto

O projeto **Conta Terminal** é um sistema simples de cadastro bancário em Java. O programa solicita que o usuário insira informações como nome, sobrenome, número da agência, número da conta e saldo, e, em seguida, exibe essas informações formatadas em uma mensagem de boas-vindas ao cliente.

O principal objetivo deste projeto é aprender a trabalhar com entradas e saídas de dados no Java, utilizando a classe **Scanner** para capturar informações do usuário e exibindo esses dados de forma clara e formatada.

## Funcionalidades

- **Leitura de Dados**: O programa solicita ao usuário para inserir seu nome, sobrenome, número da agência, número da conta e saldo.
- **Exibição de Dados**: Após a inserção dos dados, o programa exibe uma mensagem de boas-vindas com as informações do cliente.

## Como Executar

1. Clone este repositório para a sua máquina local.
2. Abra o projeto em um ambiente de desenvolvimento integrado (IDE) como VsCode, Eclipse ou outro de sua preferência.
3. Compile e execute o arquivo `ContaTerminal.java`.
4. Siga as instruções na tela para inserir os dados.

## Exemplo de Execução

**Entrada**:
- Digite seu nome: Raissa 
- Digite seu sobrenome: Feitosa 
- Digite o número da sua agência: 1234 
- Digite o número da sua conta: 12345 
- Digite o valor do saldo da sua conta: 1000


**Saída**:
Olá Raissa Feitosa, obrigado por criar uma conta em nosso banco. Sua agência é 1234, conta 12345.0 e seu saldo 1000.0 já está disponível para saque.


## O que Eu Aprendi

Durante o desenvolvimento deste projeto, aprendi e pratiquei os seguintes conceitos em Java:

1. **Manipulação de Entradas com Scanner**:
   - Aprendi a utilizar o `Scanner` para capturar entradas do usuário e como lidar com diferentes tipos de dados, como `String`, `int` e `double`.

2. **Exibição de Resultados Formatados**:
   - Aprendi a exibir informações de maneira clara e bem formatada para o usuário, criando uma mensagem personalizada que combina o nome completo do cliente com os dados da conta bancária.

3. **Concatenação de Strings**:
   - Usei concatenação de strings para unir o nome e sobrenome do usuário em uma variável `nomeCompleto`, além de integrar os dados da agência, número da conta e saldo na mensagem final.

4. **Trabalhando com Tipos de Dados**:
   - Aprendi a manipular e armazenar dados em variáveis dos tipos apropriados, como `String` para o nome e número da conta, e `double` para o saldo.

## Melhorias Futuras

- **Validação de Entrada**: O sistema pode ser melhorado com validações para garantir que o usuário insira dados no formato correto (como garantir que o saldo não seja negativo ou que o número da conta tenha o formato adequado).
- **Armazenamento de Dados**: Em um projeto mais complexo, seria interessante integrar um banco de dados para armazenar as informações do cliente de maneira persistente.

