# Introdução

Nesta aula vamos falar sobre IP, o identificador único de cada dispositivo conectado à rede.

# Endereços de IP

Endereço IP é um endereço exclusivo que identifica um dispositivo na Internet ou uma rede local.

IP vem do inglês **_"Internet Protocol"_** que consiste em um conjunto de regras que regem o formato de dados enviados pela Internet ou por uma rede local.

# O que é IP ?

Um endereço IP é uma sequência de números separados por pontos, representado por um conjunto de quatro números conhecidos como octetos, como por exemplo 192.158.1.38

> Octetos simbolizam 8 bits<br>
> Se cada octeto tem 8 bits, e o endereço IP é constituído por 4 números, logo, ele se limita em uma combinação começando de 0 á 255.

# Máscara de rede

Um endereço IP de uma rede local é dividido internamente em duas partes:

> Uma parte que simboliza a Rede<br>
> E a outra que identifica o Host dentro da Rede

A máscara de rede tem 32 bits, assim como o endereço IP, tendo como finalidade mascarar uma parte do endereço IP, assim, todo endereço IP tem uma máscara correspondente, servindo para identificar qual parte do endereço é da rede e qual é a do host.

| Hosts | Redes | CIDR | Máscara de sub-rede |
| ----- | ----- | ---- | ------------------- |
| 1     | 256   | /32  | 255.255.255.255     |
| 2     | 128   | /31  | 255.255.255.254     |
| 4     | 64    | /30  | 255.255.255.252     |
| 8     | 32    | /29  | 255.255.255.248     |
| 16    | 16    | /28  | 255.255.255.240     |
| 32    | 8     | /27  | 255.255.255.224     |
| 64    | 4     | /26  | 255.255.255.192     |
| 128   | 2     | /25  | 255.255.255.128     |
| 256   | 1     | /24  | 255.255.255.0       |
# Classe de IP

As pricipais são a classes A, classe B, classe C.

Com base nos primeiros bits (prefixo) de um endereço IP, podemos determinar a qual a classe pertence um endereço IP.

- Classe de endereçamento A: 255.0.0.0
- Classe de endereçamento B: 255.255.0.0
- Classe de endereçamento C: 255.255.255.0

Originalmente, o espaço de endereçamento IP foi dividido estruturas de tamanho fixo designadas de **"Classes de endereços"**.

# IPv4 e IPv6

- IPv4 pe um endereço IP de 32 bits, já o IPv6 tem um endereço IP de 128 bits
- O IPv4 consegue no maximo 4.3 bilhões de endereços, já o IPv6  uma escala de 7.9x10 elevado a 28
- O IPv4 utiliza anotação em alfa numérica, enquanto o IPv6 em Hexadecimal 
- O IPv4 necessita de do protocolo DHCP para fazer a atribuição de IP, Já o IPv6 é feito automaticamente

# Ataques contra IP's

- Engenharia social
- Ciberstalking
- Download de conteúdo ilegal usando seu endereço IP
- Rastrear sua localização
- Ataque direto à sua rede
- Ataques em seu dispositivo
# Conclusão

Foi explorado os endereços de IP, nas aulas seguintes será um conceito muito utilizado para conexão com computadores alvos nos testes.