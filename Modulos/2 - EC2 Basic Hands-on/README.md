2 - EC2 Basic Hands-on
==

**Instruções:**

1.  Logue ou crie um usuario com a politica de permissão de **AdministratorAccess** seguindo as instruções do Lab 1
2.  No painel principal entre em `CloudFormation`
3.  Mude para a região de *US East (N. Virginia)* no canto superior esquerdo do painel caso esteja em outra região
4.  Clique no botão “Crate Stack”
    -   Escolha a opção `Upload a template file`
    -   Clique no botão `Choose file`
    -   Faça upload do arquivo `lab2.yml` que esta dentro da pastas Modulos/2 - EC2 Basic Hands-on e clique em `Next`
    -   Em `Stack name` digite um nome para stack
    -   Em `InstanceName` digite um nome para a instancia EC2 ou deixe a padrão e clique em `Next`
    -   Na tela `Configure stack options` clique em `Next`
    -   Em `Capabilities` marque a opção *I acknowledge that AWS CloudFormation might create IAM resources.* e clique em `Next`
    -   Em `Events` atualize a pagina periodicamente para acompanhar os recursos sendo criados pelo Cloudformation
    -   O CloudFormation muda para o status CREATE_COMPLETE quando finalizar a execução
5.  No painel principal entre em `EC2`
6.  Clique no link `Running Instances`
7.  Espere o Status Checks mude de `Initializing` para `2/2 checks passed`
8.  No painel principal entre em `System Manager`
9.  Na aba de opções clique em ``Session Manager`
10. Clique em `Start Session`
11. Marque a instancia e clique em `Start session`
12. Execute algum comando no terminal
