# Base de Conhecimento - Rede


## Problema

Usuário está com problemas de conexão com a rede ou acesso à internet.


---

## Sintomas

- Sem acesso à internet
- Sites não carregam
- Sistemas online indisponíveis
- Wi-Fi conectado sem navegação


---

## Possíveis causas

- Computador sem endereço IP
- Problema no DHCP
- Falha no DNS
- Problema no roteador
- Configuração incorreta de rede


---

## Diagnóstico

Verificar informações de rede:

Comando:

ipconfig


Verificar comunicação com o gateway:

ping gateway


Verificar conexão externa:

ping google.com


Verificar resolução de nomes:

nslookup google.com


---

## Solução

Possíveis ações:

- Renovar endereço IP

Comando:

ipconfig /renew


- Reiniciar adaptador de rede
- Reconectar Wi-Fi
- Verificar cabo de rede
- Reiniciar equipamento de rede


---

## Escalonamento

Encaminhar para N2 caso:

- Vários usuários afetados
- Falha de infraestrutura
- Problema no roteador ou servidor