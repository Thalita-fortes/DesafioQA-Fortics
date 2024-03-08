# Casos de Teste

## Caso de Teste 1: Login no Aplicativo

Passos:
1. Abra o aplicativo.
2. Toque no botão "Login".
3. Insira o nome de usuário e senha corretos.
4. Toque no botão "Log In".

Resultado Esperado:
- O usuário é redirecionado para a página inicial do aplicativo.

## Caso de Teste 2: Redefinir Senha

Passos:
1. Abra o aplicativo.
2. Toque no botão "Esqueceu sua senha?".
3. Insira o endereço de e-mail associado à conta.
4. Toque no botão "Enviar".

Resultado Esperado:
- O usuário recebe um e-mail com instruções para redefinir a senha.

## Caso de Teste 3: Criar Nova Conta

Passos:
1. Abra o aplicativo.
2. Toque no botão "Criar Nova Conta".
3. Preencha os campos obrigatórios (name, email, password e date of birth) com informações válidas.
4. Toque no botão "Sign up".

Resultado Esperado:
- O usuário recebe uma confirmação por e-mail após criar a conta.

# BDD - Casos de Teste

## Caso de Teste 1: Login no Aplicativo
Dado que o usuário acesse o aplicativo  
Quando clicar no botão "Login"  
E Insira o nome de usuário e senha corretos  
E clicar no botão "Log In"  
Então o sistema deverá redirecionar o usuário para a tela inicial  

## Caso de Teste 2: Redefinir Senha

Dado que o usuário acesse o aplicativo  
Quando clicar no botão "Esqueceu sua senha?"  
E inserir o endereço de e-mail associado à conta  
E clicar no botão "Enviar"  
Então o sistema deverá enviar um email para redefinir a senha  

## Caso de Teste 3: Criar Nova Conta

Dado que o usuário acesse o aplicativo  
Quando clicar no botão "Criar Nova Conta"  
E preencher os campos obrigatórios (name, email, password e date of birth) com informações válidas  
E clicar no botão "Sign up"  
Então o usuário deverá receber um email de confirmação da criação da conta  