
# Modelo de Comunição em camadas

## Modelo TCP/IP

Aplicação -> Transporte -> Internet -> Acesso a rede

## Modelo OSI
| Aplicação | Apresentação | Sessão | Transporte | Rede | Enlace de Dados | Fisico |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| Dados | Dados | Dados | Segmento | Pacotes | Quadros | Bits |
Aplicação -> Apresentação -> Sessão -> Transporte -> Rede -> Enlace de Dados -> Físico
Dados -> Dados -> Dados -> Segmento -> Pacotes -> Quadros -> Bits


![[Camadas de rede.png]]

## Tipos de comunicação entre dispositivos

- Unicast : 1 -> 1
- Anycast: 1 -> n (mesma região IPv6)
- Broadcast: 1 -> n (IPv4)
- Multicast: 1 -> n (Alguns IPv6)

### Tipos de endereços IPv6 na pratica

- Global Unicast Add : 200::/3 (~ public ip)
- Unique local add : fc00::/7 (~ private ip)
- Link Local: FE80::/3
- Loopback: ::1 (auto test ~127.0.0.1)

### Abreviação de endereço

