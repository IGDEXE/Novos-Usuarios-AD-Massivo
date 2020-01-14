# Novos Usuarios AD Massivo
 Script para criar varios usuarios no AD com base num arquivo CSV


## Como usar?
* Antes de utilizar, instale o [RSAT](https://support.microsoft.com/pt-br/help/2693643/remote-server-administration-tools-rsat-for-windows-operating-systems)
* Crie um arquivo CSV com duas colunas, na primeira coloque os nomes e na segunda os sobrenomes, separados por virgulas
* Os usuarios vão ser criados no padrão: nome.sobrenome


## Para funcionar, é preciso algumas alterações no codigo: 
No script "NovosUsuarios-Padrao", altere as variaveis considerando o seu ambiente: 
* **$DominioOffice365** -> Dominio padrao do Office 365
* **$Password** -> Senha padrão para as contas
