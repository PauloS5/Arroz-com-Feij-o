# Requisistos funcionais


## Geral:
### Usuário se cadastrar:
    - Decrição: O usuário pode se cadastrar no site
    - Restrição: O usuário precisa de um email/telefone para cadastro e não ter uma conta criada com base neste email/telefone
    - Ação: 
        1. Informar:
            - Nome Completo
            - Data de nascimento
            - Email
            - Telefone
            - Endereço:
                - Bairro
                - Rua
                - Número
        2. Criar uma senha
        3. Confirmar senha
    - Resultado: 
        - Sucesso: As informações do usuário serão adicionadas a base de dados do sistema
        - Fracasso: Usuário não será cadastrado e retornará a página com as informações pessoais
### Usuário entrar no sistema:
    - Descrição: Usuário conseguir ter acesso a sua conta
    - Restrição: Usuário deve possuir uma conta
    - Ação: 
        1. Informar:
            - Email ou Telefone
            - Senha
    - Resultado:
        - Sucesso: Usuário entrou no sistema e terá acesso a sua conta
        - Fracasso: Usuário não entrará no sistema e não terá acesso a sua conta
### Usuário sair do sistema:
    - Descrição: Usuário pode sair do sistema
    - Restrição: Usuário deve estar logado no sistema
    - Ação: 
        1. Sair do sistema
    - Resultado: Usuário saiu do sistema
### Usuário alterar senha da conta:
    - Descrição: Usuário alterar senha da sua conta
    - Restrição: Usuário deve possuir uma conta
    - Ação: 
        1. Informar Email ou Telefone
        2. Receber email/sms com um código de verificação
        3. Informar o código de verificação
    - Resultado:
        - Sucesso: Usuário terá alterado a senha da sua conta
        - Fracasso: Usuário não terá alterado a senha da sua conta
### Excluir conta:
    - Descrição: O Usuário pode excluir sua conta
    - Restrição: O usuário de ter uma conta e estar logado no sistema
    - Ação: 
        1. Confirmar email/telefone
        2. Receber email/sms com um código de verificação
        3. Informar o código de verificação
        4. Confirmar senha
        5. Confirmar exclusão da conta
    - Resultado: Conta do usuário excluida do banco de dados
### Altera informações pessoais da conta
    - Descrição: O usuário altera informações da conta do mesmo
    - Restrição: O usuário deve estar logado 
    - Ação:
        - Alterar telefone/email
        - Alterar nome completo
        - Alterar endereço
        -Altera data de nascimento
    - Resultado: Dados da conta alterados