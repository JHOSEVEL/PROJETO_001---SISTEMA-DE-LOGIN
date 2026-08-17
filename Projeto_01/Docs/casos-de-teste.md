## Casos de Testes

---
          **ID - Título do Caso de Teste - Pré-condição - Resultado Esperado**

TC-LOGIN-001 - Login com credenciais válidas - Usuário cadastrado no banco - Autenticação com sucesso e redirecionamento para a Home
TC-LOGIN-002 - Login com senha incorreta - Usuário cadastrado - "Exibir mensagem: ""E-mail ou senha inválidos"""
TC-LOGIN-003 - Login com usuário inexistente - Nenhuma "Exibir mensagem: ""E-mail ou senha inválidos"""
TC-LOGIN-004 - Login com e-mail vazio - Nenhuma "Exibir mensagem de validação: ""Campo e-mail é obrigatório"""
TC-LOGIN-005 - Login com senha vazia - Nenhuma "Exibir mensagem de validação: ""Campo senha é obrigatório"""
TC-LOGIN-006 - Login com ambos os campos vazios - Nenhuma,Exibir mensagens de validação em ambos os campos
TC-LOGIN-007 - Login com formato de e-mail inválido - Nenhuma,"Exibir mensagem: ""Por favor, insira um e-mail válido"""

---

---
## TC-LOGIN-001 - "estrutura do caso de teste"

    *Título:* Login com credenciais válidas

    *Pré-condição:* Usuário ativo e cadastrado no sistema.

    *Massa de Dados:*

    E-mail: usuario@email.com

    Senha: Senha123

    *Passos:*

        Acessar a página principal de login (/login).

        Informar o e-mail usuario@email.com no campo correspondente.

        Informar a senha Senha123 no campo correspondente.

        Clicar no botão Login.

    *Resultado Esperado:* O sistema deve autenticar o usuário com sucesso e redirecioná-lo para o dashboard/página principal da aplicação.

---
