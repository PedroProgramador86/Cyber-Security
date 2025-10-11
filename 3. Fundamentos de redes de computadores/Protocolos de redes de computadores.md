
# Introdução

Protocolos de rede são um conjunto de normas que permitem que máquinas conectadas em redes possam se comunicar entre si.

> Funciona como um idioma na comunicação<br>
> Assim, não sendo relevante o fabricante, modelos e etc

# Protocolos de redes

Funcionam como uma linguagem universal para que dispositivos distribuídos ao redor do mundo possam se comunicar de forma padronizada.

# Modelos de camadas

Os modelos de camadas definem regras e orientações para que haja a intercomunicação entre os dispositivos de redes independente dos modelos ou fabricantes.

Na transmissão, cada camada realiza seu trabalho e o entregue para a camada inferior.

O agrupamento em camadas facilita a análise do processo de comunicação por:

- Delimitar as funções das regras de comunicação (protocolos), dos serviços e das interfaces;
- Servir como referência de comparação entre protocolos e serviços de pilhas diferentes.

Existem dois modelos de camadas utilizados atualmente, os modelos OSI e TCP/IP

| Modelo TCP/IP | Modelo OSI   |
| ------------- | ------------ |
|               | Aplicação    |
| Aplicação     | Apresentação |
|               | Seção        |
| Transporte    | Transporte   |
| Internet      | Rede         |
| Acesso a Rede | Enlace       |
|               | Fisica       |

## Modelo OSI

Divide as funções em 7 camadas:

- Aplicação
- Apresentação
- Sessão
- Transporte
- Rede
- Enlace
- Física

Nesse modelo temos:

- A decomposição dos componentes da rede em partes menores.
- Padronização dos componentes presentes na rede.
- Comunicação entre diversos tipos de hardware e software
- Evita que alterações em uma camada afete as configurações da próxima


## Modelo TCP/IP

O modelo TCP/IP possui quatro camadas:

- Aplicação
- Transporte
- Internet
- Acesso a rede

No início, o modelo OSI foi o primeiro a ser utilizado, sendo base para nomenclaturas e para as redes, atualmente o modelo TCP/IP tem sido mais utilizado em todo o mundo, tanto nas redes internas como também nas externas.

## Comparação entre Modelo OSI e TCP/IP

- OSI: 7 camadas - TCP/IP: 4 camadas;
- O TCP/IP mesclou as camadas 1 e 2 do OSI para a camada de Aplicação
- Há uma camada de Internet em TCP/IP enquanto a mesma é chamada de Redes no OSI.

# Principais protocolos de redes

A rede é dividida em camadas, cada uma com uma função específica. Os diversos tipos de protocolos de rede variam de acordo com o tipo de serviço utilizado e a camada correspondente.

- Camada de Aplicação:

WWW, HTTP, SMTP, Telnet, FTP, SSH, NNTP, RDP, IRC, SNMP, POP3, IMAP, SIP, DNS, PING;

- Camada de Transporte:

TCP, UDP, RTP, DCCP, SCTP;

- camada de Internet:

IPv4, IPv6, IPsec, ICMP;

- Camada de acesso à rede:

Ethernet, Modem, PPP

## Portas e protocolos

Ao realizar a comunicação entre dispositivos, por meio de protocolos, são utilizadas portas numeradas.

| Aplicação      | Protocolo | Numero da Porta |
| -------------- | --------- | --------------- |
| FTP (Cliente)  | TCP       | 20              |
| FTP (Servidor) | TCP       | 21              |
| SSH            | TCP       | 22              |
| Telnet         | TCP       | 23              |
| SMTP           | TCP       | 25              |
| DNS            | UDP/TCP   | 53              |
| DHCP           | UDP       | 67, 68          |
| TFTP           | UDP       | 69              |
| HTTP           | TCP       | 80              |
| POP3           | TCP       | 110             |
| SNMP           | UDP       | 161             |
| HTTPS          | TCP       | 443             |

# Conclusão

Visto fundamentos de redes de computadores que serão muito úteis e relembrados ao longo do curso.