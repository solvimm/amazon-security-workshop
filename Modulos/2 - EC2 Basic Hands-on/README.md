2 - EC2 Basic Hands-on
==

**Instruções:**

- Criar todos os recursos em **N.Virginia (us-east-1)** 

1.  Logue ou crie um usuario com a politica de permissão de **AdministratorAccess** seguindo as instruções do Lab 1
2.  No painel principal entre em `CloudFormation`
3.  Clique no botão “Crate Stack”
    -   Escolha a opção `Upload a template file`
    -   Clique no botão `Choose file`
    -   Faça upload do arquivo `lab2.yml` que esta dentro da pastas Modulos/2 - EC2 Basic Hands-on e clique em `Next`
    -   Em `Stack name` digite um nome para stack
    -   Em `InstanceName` digite um nome para a instancia EC2 ou deixe a padrão
    -   Em `LatestAmiId` manter o valor padrão e clique em `Next`
    -   Na tela `Configure stack options` clique em `Next`
    -   Em `Capabilities` marque a opção *I acknowledge that AWS CloudFormation might create IAM resources.* e clique em `Next`
    -   Em `Events` atualize a pagina periodicamente para acompanhar os recursos sendo criados pelo Cloudformation
    -   O CloudFormation muda para o status CREATE_COMPLETE quando finalizar a execução
4.  No painel principal entre em `EC2`
5.  Clique no link `Running Instances`
6.  Espere o Status Checks mude de `Initializing` para `2/2 checks passed`
7.  No painel principal entre em `System Manager`
8.  Na aba de opções clique em ``Session Manager`
9. Clique em `Start Session`
10. Marque a instancia e clique em `Start session`
11. Execute algum comando no terminal

**OBS** Utilize o navegador Chrome para o Hands-on para maior compatibilidade com os serviços
