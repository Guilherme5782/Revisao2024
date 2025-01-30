# Revisao2024 Gerador de Senha

Este é um programa simples em C# que gera senhas seguras com base nas preferências do usuário. O programa permite que o usuário escolha a quantidade de dígitos, bem como incluir ou excluir números, símbolos, letras maiúsculas e minúsculas na senha gerada.

## Funcionalidades

- O usuário pode definir o **tamanho da senha** (quantidade de dígitos).
- O programa pergunta se o usuário deseja incluir:
  - **Números** (0-9)
  - **Símbolos** (como `!@#$%^&*`)
  - **Letras maiúsculas** (A-Z)
  - **Letras minúsculas** (a-z)
- A senha gerada será salva em um arquivo de backup chamado `bkp.txt`.

## Requisitos

- .NET (qualquer versão que suporte C# 9.0 ou superior).

## Como usar

1. Compile o programa usando o comando adequado do C#.
2. Execute o programa e siga as instruções interativas no console.
3. O programa irá pedir a quantidade de dígitos desejada para a senha.
4. Em seguida, ele perguntará se você deseja incluir números, símbolos, letras maiúsculas ou minúsculas na senha.
5. Após a entrada, a senha será gerada e exibida no console.
6. A senha gerada será salva no arquivo `bkp.txt` no diretório do programa.

### Exemplo de execução:

```bash
GERADOR DE SENHA

Qual a quantidade de dígitos que você deseja?
8

Incluir números S/N?
S

Incluir símbolos S/N?
S

Incluir letras maiúsculas S/N?
S

Incluir letras minúsculas S/N?
S

Senha gerada: B1g@aB2c
