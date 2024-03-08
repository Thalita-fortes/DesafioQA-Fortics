## Report

---

**Bug:**
Um usuário pode criar uma conta para um e-mail associado a outro usuário.

**Detalhes:**
Durante o processo de criação de uma nova conta, não está sendo realizada uma verificação adequada para garantir que o endereço de e-mail inserido seja único. Isso pode resultar em uma situação na qual um usuário consegue criar uma conta com um endereço de e-mail que já está associado a outra conta existente no sistema.

**Passos para Reproduzir o Bug:**
1. Acesse a página de criação de conta no aplicativo.
2. Insira um endereço de e-mail que já esteja associado a uma conta existente.
3. Complete os demais campos necessários para a criação da conta.
4. clicar no botão Sign Up.

**Resultado Esperado:**
Deveria haver uma validação durante o processo de criação de conta para verificar se o endereço de e-mail já está em uso. Se o endereço de e-mail já estiver associado a uma conta existente, o sistema deveria exibir uma mensagem de erro indicando que o endereço de e-mail já está em uso e solicitar que o usuário insira um endereço de e-mail diferente.

**Sugestão de Correção:**
1. Adicionar uma validação no processo de criação de conta para verificar se o endereço de e-mail já está em uso.
2. Se o endereço de e-mail já estiver associado a uma conta existente, exibir uma mensagem de erro indicando que o endereço de e-mail já está em uso e solicitar que o usuário insira um endereço de e-mail diferente.
3. Garantir que a verificação seja realizada no lado do servidor para evitar possíveis manipulações no lado do cliente.

---

