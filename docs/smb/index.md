# SMB


O Samba é um software que tem como principal finalidade o compartilhamento de arquivos de servidores Linux para consumo em computadores Windows.
## Instalação

apk add samba

verificar se o samba esta funcionando 

rc-service samba status

depos editei esse arquivo 

nano /etc/samba/smb.comf



## Configuração

depos editei esse arquivo 

nano /etc/samba/smb.comf

[![samba](https://i.im.ge/2024/01/03/3MlGCY.samba.png)](https://im.ge/i/3MlGCY)

logo apos eu reiniciei o samba rc-service restart

ferifiquei se o compartilhamento esta funcionando com rc-service status

Logo apos fui no windous, me conectei a uma cononta administrator atravez
do ip e do dominio pernambuco.lab.

[![win1](https://i.im.ge/2024/01/03/3MFohP.win1.png)](https://im.ge/i/3MFohP)

[![adm](https://i.im.ge/2024/01/03/3MF7bx.adm.png)](https://im.ge/i/3MF7bx)

[![grupo w](https://i.im.ge/2024/01/03/3MOeQp.grupo-w.png)](https://im.ge/i/3MOeQp)

criei os grupos pela tela grafica do windous .



## Teste

e testei pelo xarope para ver se estavam se comunicando.


[![menbros](https://i.im.ge/2024/01/03/3MOI5q.menbros.png)](https://im.ge/i/3MOI5q)


