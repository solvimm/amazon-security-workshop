1 - IAM Hands-on
==

**Instruções:**

1.  No painel principal, entre no `IAM`
    -   
2.  Clique em `Activate MFA on your root account` e siga os passos parar ativar o MFA na conta root
3.  No menu da esquerda, clique em Groups
4.  Clique no botão azul “Create New Group”
    -   De o nome ao grupo chamado **Operacional** e clique Next Step no canto inferior direito
    -   Na página de Attach Policy, busque por **PowerUserAccess** e marque o checkbox e clique Next Step no canto inferior direito
    -   clique Create Group no canto inferior direito para criar o grupo **Operacional**
5.  No menu da esquerda, clique em `Users`
    -   Clique no botão azul `Add user`
    -   na aba de `Set user details`, Add o nome do usuario `nome.sobrenome`, ex: abian.laginestra
    -   na aba `select AWS access type`, marque o checkbox `AWS Management Console access`
    -   em Console password, clique em Autogenerate password
    -   clique no Next Permission no `Next:Permissions`
    -   Mantenha o checkbox de require password reset selecionado
    -   Na aba de `Set permissions` clique em `Add user to group
    -   Na aba de `Add user to group`, marque o grupo `Operacional`, criado anteriormente
    -   clique em Next:Tags
    -   clique em Next:Review
    -   clique em Create User
    -   aparecerá um mensagem verde de sucesso, com o nome do usuário e o password. Clique em `show` para descobrir o password gerado, esse será o password que o novo usuário deverá usar para acessar a conta, portanto, anote o password e o nome do usuário escolhido.
    -   clique no nome da conta e deslogue
6.  Logar com a nova conta
    -   Criar uma nova senha 
    -   Clicar na aba Services
    -   Entrar no IAM
    -   Tentar criar um novo usuario

