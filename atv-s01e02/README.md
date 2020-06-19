# Classificação de Hardware com Várias CPUs

De acordo com a taxonomia de Flynn, Hardwares com várias CPUs são considerados MIMD (multiple instruction, multiple data) , ou seja, possuem múltiplo fluxo de instruções e múltiplo fluxo de dados, esses sitemas são classificados da maneira a seguir:

## Multicomputadores

Vários computadores interligados por uma rede, cada um possui sua memória e se comunicam por mensagens roteadas pela rede que os interconecta

### Multicomputador Homogêneo

Como o nome indica são computadores produzidos desta maneira, matrizes de computadores iguais dispostos com a computação paralela em mente, podem possuir disposições de grade e cubo. Exemplos:

* MPPs (Massively Parallel Processors),supercomputadores muito caros;

* COW (Cluster of Workstations), como Beowulf

### Multicomputador Heterogêneo

Tipo mais comum de sistema distribuído, computadores com arquiteturas diferentes e características diferentes unidos no mesmo sistema de computação paralela.

## Multiprocessadores

### Compartilhamento de memória

* Privado

Cada processador possui a própria memória

* Compartilhado

A memória inteira e livre para ser acessada por qualquer processador no sistema

### Multiprocessador em Barramento

Todos os processadores(e unidades de memória) estão ligados direto ao barramento e precisam esperar que este esteja desocupado para utilizá-lo

### Multiprocessador com Chaveamento

Cada processador está ligado a um switch que gerencia o acesso dos processadores aos recursos



