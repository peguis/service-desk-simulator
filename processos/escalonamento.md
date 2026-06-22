# Processo de Escalonamento - Service Desk


## Objetivo

Definir quando um chamado deve ser resolvido pelo primeiro nível de atendimento (N1) ou encaminhado para equipes especializadas (N2/N3).


---

# Nível 1 — N1 (Service Desk)

## Responsabilidades

O N1 realiza o primeiro atendimento ao usuário.

Atividades:

- Registrar chamado
- Classificar incidente
- Identificar impacto e urgência
- Realizar diagnóstico inicial
- Aplicar procedimentos conhecidos
- Documentar solução


---

## Chamados resolvidos pelo N1

### Rede

Exemplos:

- Sem internet
- Problema de Wi-Fi
- Renovação de IP

Ferramentas:

- ipconfig
- ping
- nslookup


---

### Acesso

Exemplos:

- Desbloqueio de conta
- Redefinição de senha
- Problemas simples de login


---

### Windows

Exemplos:

- Computador lento
- Limpeza básica
- Ajustes de inicialização


---

# Nível 2 — N2 (Suporte Especializado)


## Quando escalar para N2

Quando:

- N1 não possui permissão
- Problema exige conhecimento avançado
- Solução não está na documentação
- Existe impacto maior


---

## Responsabilidades N2

Atividades:

- Analisar problemas complexos
- Acessar configurações avançadas
- Investigar causa raiz
- Apoiar N1


---

## Exemplos de chamados N2


### Rede avançada

- Problema em servidor
- Configuração de equipamentos
- Falha para vários usuários


---

### Sistemas

- Erro de aplicação
- Problemas de permissão avançada


---

### Segurança

- Malware confirmado
- Conta comprometida
- Investigação de incidente


---

# Nível 3 — N3 (Especialistas)


## Quando escalar para N3

Quando:

- Problema envolve desenvolvimento
- Necessita alteração estrutural
- Exige conhecimento especializado


---

## Responsabilidades N3

Atividades:

- Resolver problemas complexos
- Corrigir falhas de sistema
- Alterar código ou arquitetura


---

## Exemplos de chamados N3


### Desenvolvimento

- Erro no sistema
- Falha no código


---

### Banco de Dados

- Corrupção de dados
- Problemas de desempenho


---

### Infraestrutura

- Arquitetura de servidores
- Grandes mudanças de ambiente


---

# Fluxo de Escalonamento


Usuário abre chamado

↓

N1 analisa

↓

Existe solução conhecida?

↓

SIM → Resolver e documentar

↓

NÃO → Escalar N2

↓

N2 resolve?

↓

SIM → Encerrar

↓

NÃO → Escalar N3


---

# Exemplos do Projeto


## INC-001 - Sem Internet

Nível:

N1

Motivo:

Problema solucionado com diagnóstico básico de rede.


---

## INC-003 - Sem acesso ao sistema

Nível:

N1

Motivo:

Bloqueio de conta resolvido com desbloqueio.


---

## INC-005 - Suspeita de Malware

Nível:

N2

Motivo:

Necessita investigação de segurança.


---

# Boas práticas

- Nunca escalar sem diagnóstico inicial
- Registrar tudo no chamado
- Informar ações realizadas
- Enviar evidências para próxima equipe