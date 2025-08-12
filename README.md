# Sistema Básico de Login

## Descrição
Este é um programa simples em Python que solicita ao usuário digitar um nome de usuário e senha. Se as credenciais estiverem corretas, o programa exibe uma mensagem de boas-vindas. Caso contrário, informa que o usuário não foi encontrado e pede para tentar novamente.

## Como usar
1. Execute o programa.
2. Digite o nome de usuário quando solicitado.
3. Digite a senha quando solicitado.
4. Veja a resposta do sistema:
   - Se o usuário for `"Guilherme"` e a senha `"1234"`, será exibida a mensagem de boas-vindas.
   - Caso contrário, aparecerá uma mensagem de erro.

## Código

```python
usuario = input("digite o usuario: ")
senha = input("digite a senha: ")

if usuario == "Guilherme" and senha == "1234":
    print("Bem-vindo Guilherme 🔓")
else:
    print("Usuario n encontrado 🔐. Tesnte Novamente")
