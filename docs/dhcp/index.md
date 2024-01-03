# DHCP

## Instalação
fazendo os seguites comandos:

apt update

apt install dnsmasq

utilizando o windows como servidor 





## Configuração


Após a instalação, você precisará configurar o servidor DHCP editando o arquivo 

/etc/dnsmasq.conf

Com o editor nano

Logo apos configurei o /etc/resolv.conf 

[![dhcp](https://i.im.ge/2024/01/03/3MYvMS.dhcp.png)](https://im.ge/i/3MYvMS)


Incluir o(s) nome(s) e o conteúdo do(s) arquivo(s) de configuração.

- Distribuir um intervalo (*range* em inglês) de endereços IP; (15 pontos)
- Reservar 2 endereços (IP fixo) fora do intervalo do item anterior. (5 pontos)

## Teste

Service isc-dhcp-server status comando para verificar o funcionamento




