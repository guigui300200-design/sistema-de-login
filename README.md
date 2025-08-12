# sistema-de-login

Sistema de Login Simples
Este script Python solicita ao usuário um nome de usuário e senha e verifica se as credenciais correspondem a um usuário autorizado.
===================================================================================================================================
Como usar
Execute o script.

Quando solicitado, digite o nome do usuário.

Digite a senha.

Se as credenciais forem "Guilherme" e "1234", uma mensagem de boas-vindas será exibida.

Caso contrário, será exibida uma mensagem informando que o usuário não foi encontrado.
===================================================================================================================================
Código
python
Copiar
Editar
usuario = input("digite o usuario: ")
senha = input("digite a senha: ")

if usuario == "Guilherme" and senha == "1234":
    print("Bem-vindo Guilherme 🔓")
else:
    print("Usuario n encontrado 🔐. Tesnte Novamente")
Possíveis melhorias
Permitir múltiplas tentativas de login.

Implementar verificação para mais usuários.

Melhorar mensagens de erro.

Usar armazenamento seguro para senhas.
