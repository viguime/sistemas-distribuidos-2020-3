# Síntese dos conceitos e caracterização de sistemas distribuídos

## O que é um sistema distribuído?

É o contrário do mais tradicional sistema centralizado, possui natureza modular.
Várias máquinas com responsabilidades diferentes no mesmo sistema.

Características:

- Mais robusto (pode tolerar falhas)
- Mais escalável (aumento da base de usuários)
- Mais complexo
- Mais confiável (isolamento de falhas)

## Metas de Sistemas Distribuídos

- Compartilhamento de recursos
- Transparência
    *Esconde do usuário características e funcionamento dos dados/sistema, como localização geográfica, concorrência, migração, falhas, persistência, latência etc.
- Abertura
    *Padronização de sintax e semântica dos serviços, o que pode permitr que o sistema seja expandido utilizando essa padronização como fundação
- Iteroperabilidade
    *Comunicação entre implementações distintas, por conta da abertura
- Portabilidade
    *Compatibilidade de aplicações entre sistemas distribuídos
- Extensibilidade
    *Capacidade expandir o sistema com a adição de novos componentes sem afetar os antigos
- Escalabilidade
    *Aumento da capacidade de atendimento, por tamanho e geograficamente (replicação de servidores em países diferentes).

## Exemplos de Sistemas Distribuídos:

* Domain Name Systems (DNS)
* Servidores de Email (SMTP)
* Redes telefônicas
* Microsserviços
* Armazenamento remoto (GDrive, OneDrive)

