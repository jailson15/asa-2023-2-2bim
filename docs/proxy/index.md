# PROXY

## Instalação
Comandos executados dentro do conteiner lxc no proprio terminal da maquina real.
  
  apt update

  apt install squid  

## Configuração
Entrando no arquivo
$ nano /etc/squid/squid.conf

editei esse arquivo e configurei essas 4 ACLs 

##ACLS
acl yo dst www.youtube.com

acl uo dst www.uol.com.br

acl gp dst chat.openai.com

acl in dst www.instagram.com  

onde dei siglas para subistituir os nomes e dos saites e ficar mas facil de permitir ou negar o acesso.

#negar ou pemitir

http_acess deny yo

http acess deny uo 

http acess deny gp

http_acess deny in

ficou no nano assim.

[![acls](https://i.im.ge/2023/12/29/xxnnRh.acls.png)](https://im.ge/i/xxnnRh)

Deny(negar). sendo assim negando o acesso a cada saite.
configurei o firefox com o proxy e coloquei o porta 80


## Teste
Agora depois de ter configurado todos as acls e ter configurado o firefox tentei abrir os sites 
e todos foram bloqueados.

[![youtube](https://i.im.ge/2023/12/29/xx4d40.youtube.png)](https://im.ge/i/xx4d40)
[![chatgpt](https://i.im.ge/2023/12/29/xx4S3W.chatgpt.png)](https://im.ge/i/xx4S3W)
[![google](https://i.im.ge/2023/12/29/xx42Ur.google.png)](https://im.ge/i/xx42Ur)
[![instagran](https://i.im.ge/2023/12/29/xx41Tm.instagran.png)](https://im.ge/i/xx41Tm)

