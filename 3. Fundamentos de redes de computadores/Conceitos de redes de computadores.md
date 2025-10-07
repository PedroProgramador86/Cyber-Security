
# Introdução

Nesta aula vamos falar sobre redes de computadores, seus conceitos, protocolos e como funcionam.

# Redes de computadores

Redes de computadores refere-se a dispositivos de computação interconectados que podem trocar dados e compartilhar recursos entre si.

Estes dispositivos em rede usam um sistema de regras, os protocolos de comunicação, para transmitir informações por meio de tecnologias físicas ou sem fio.

# Termos e conceitos

- Nós
Equipamento conectado à rede (Computador, hub, switch, terminal, etc);

- Links
Meio de transmissão que conecta dois nós, podendo ser físico ou sem fio

- Arquitetura
Define as especificações para os componentes físicos da rede, organização funcional, protocolos, procedimentos, regras de acesso, portas abertas, , portas fechadas, mecanismo de autentificação, listas de controle de acesso.

- Endereço IP
Número exclusivo atribuído a cada dispositivo conectado à rede;

- Portas
Identifica uma conexão específica (Protocolos).

> 192.168.1.100:8080<br>
> Ip address : Port Number

# Tipos de arquiteturas de redes

O design de uma rede de computadores é enquadrado em duas grandes categorias:

- Cliente servidor;
- Ponto a ponto (P2P).

## 1. Arquitetura cliente servidor

Nesta arquitetura os nós podem ser servidores ou clientes. Os servidores fornecem recursos como memória, capacidade de processamento ou dados aos nós clientes.

## 2. Arquitetura ponto a ponto

Nesta arquitetura os computadores conectados têm capacidades e privilégios iguais, sem ser um servidor central para coordenação. Cada dispositivo na rede de computadores pode atuar como cliente ou servidor.

# Topologias de redes

A disposição de nós e links é chamada de topologia de rede, podendo ser configurados de maneiras diferentes para obter resultados distintos.

- Barramento
- Anel
- Estrela
- Malha

## 1. Topologia em barramento

Cada nó está vinculado a apenas um outro nó. A transmissão de dados pelas conexões de rede ocorre em uma direção.

## 2. Topologia em anel

cada nó está vinculado a dois outros nós, formando um anel. Os dados podem fluir bidirecionalmente. No entanto, a falha de um único nó pode desativar toda a rede.

## 3. Topologia em estrela

Um nó de servidor central está vinculado a vários dispositivos de rede do cliente. Essa topologia tem melhor performance, pois os dados não precisam passar por cada nó.

## 4. Topologia em malha

Cada nó conectado a muitos outros nós. Em uma topologia em malha completa, cada nó está conectado a todos os outros nós da rede.

# Tipos de redes

- **LAN (Local Area network):** conecta dispositivos próximos, em um mesmo ambiente;
- **MAN (Metropolitan Area Network):** para conectar redes locais dentro de distâncias maiores;
- **WAN (Wide Area Network):** Rede de longa distância que conecta dispositivos dentro de países ou continentes
- **SAN (Storage Area network):** Armazena dados da rede e faz a comunicação entre um servidor e os demais dispositivos;
- **VLAN (Virtual LAN):** Reúne diversas máquinas de forma lógica e não física