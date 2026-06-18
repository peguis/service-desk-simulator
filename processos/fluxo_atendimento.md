# Fluxo de Atendimento - Service Desk


## Objetivo

O fluxo de atendimento define as etapas que um chamado deve seguir desde sua abertura até o encerramento.

O objetivo é garantir organização, rastreabilidade e qualidade no suporte aos usuários.


---

# Visão Geral do Processo


Usuário abre chamado

↓

Registro do chamado

↓

Classificação

↓

Priorização

↓

Diagnóstico inicial (N1)

↓

Resolução?

↓

Sim → Encerramento

Não → Escalonamento N2/N3

↓

Documentação da solução

↓

Fechamento do chamado


---

# 1. Abertura do Chamado

O usuário informa o problema ou solicita um serviço.


Informações necessárias:

- Nome do usuário
- Data e horário
- Descrição do problema
- Sistema afetado
- Impacto percebido


Exemplo:

Usuário informa:

"Não consigo acessar a internet."


---

# 2. Registro do Chamado

O analista cria o ticket contendo:

- ID do chamado
- Usuário
- Categoria
- Tipo
- Descrição
- Prioridade inicial


Exemplo:

ID:

INC-001


Categoria:

Rede


Tipo:

Incidente


---

# 3. Classificação

O chamado é categorizado para facilitar o atendimento.


Categorias comuns:

## Hardware

Exemplos:

- Computador
- Monitor
- Impressora


## Software

Exemplos:

- Aplicativos
- Sistemas
- Erros de programa


## Rede

Exemplos:

- Internet
- Wi-Fi
- Conectividade


## Segurança

Exemplos:

- Vírus
- Phishing
- Conta comprometida


## Acesso

Exemplos:

- Senha
- Permissões
- Usuário bloqueado


---

# 4. Priorização

O analista avalia:

Impacto:

Quantas pessoas ou serviços foram afetados.


Urgência:

Qual a necessidade de resolver.


Com base nisso é definida a prioridade:

- P1
- P2
- P3
- P4


---

# 5. Diagnóstico N1

O primeiro nível realiza a análise inicial.


Atividades:

- Fazer perguntas ao usuário
- Reproduzir o problema
- Executar testes
- Verificar configurações
- Consultar base de conhecimento


Ferramentas comuns:

- ping
- ipconfig
- tracert
- logs
- configurações do sistema


---

# 6. Resolução

Se o N1 encontrar a solução:

O chamado é corrigido.


Exemplos:

- Reset de senha
- Renovação de IP
- Instalação de software
- Ajuste de configuração


---

# 7. Escalonamento

Caso o problema não seja resolvido, o chamado é encaminhado.


N2:

Problemas técnicos mais avançados.


N3:

Problemas especializados.


O escalonamento deve conter:

- Diagnóstico realizado
- Testes executados
- Evidências
- Motivo do envio


---

# 8. Encerramento

Antes de fechar o chamado:

Confirmar com o usuário:

- Problema resolvido
- Serviço funcionando
- Usuário satisfeito


Registrar:

- Solução aplicada
- Data de encerramento
- Observações


---

# Exemplo de Fluxo Completo


Usuário:

"Meu computador não acessa a internet."


↓

N1 registra chamado.


↓

Analista verifica:

- IP
- Gateway
- DNS


↓

Identifica problema de configuração.


↓

Executa:

ipconfig /renew


↓

Internet restaurada.


↓

Chamado encerrado com documentação da solução.


---

# Boas Práticas

Sempre:

- Documentar ações realizadas
- Seguir SLA
- Atualizar o usuário
- Registrar solução
- Evitar encerrar chamados sem validação