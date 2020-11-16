# Programação Avançada

Atividade padrão de projeto - **State**.

## Conteúdos

1. [Classificação](https://github.com/igorgodoy/cco-programacao-avancada-state#classifica%C3%A7%C3%A3o)
2. [Intenção](https://github.com/igorgodoy/cco-programacao-avancada-state#inten%C3%A7%C3%A3o)
3. [Motivação](https://github.com/igorgodoy/cco-programacao-avancada-state#motiva%C3%A7%C3%A3o)
4. [Aplicação](https://github.com/igorgodoy/cco-programacao-avancada-state#aplica%C3%A7%C3%A3o)
5. [Estrutura](https://github.com/igorgodoy/cco-programacao-avancada-state#estrutura)
6. [Participantes](https://github.com/igorgodoy/cco-programacao-avancada-state#participantes)
7. [Implementação](https://github.com/igorgodoy/cco-programacao-avancada-state#implementa%C3%A7%C3%A3o)

## State

### Classificação

- O **State** é um padrão de projeto que permite a alteração de comportamente de um determinado objeto de acordo com seu estado atual.

### Intenção

- Tornar o código menos verboso, evitando o uso dos métodos if/else de forma excessiva dentro do código, dentre outras.

### Motivação

- Tornar o código mais legível, facilitar manutenção, etc.

### Aplicação

- Comumente utilizado em interfaces, como por exemplo os frameworks React e React Native.

### Estrutura

- Este [diagrama](https://refactoring.guru/images/patterns/diagrams/state/structure-pt-br-2x.png) representa uma estrutura elaborada baseada nos padrões do **State**.

### Participantes

- *Context*: define a interface com o cliente e mantém a instância de estado concreto o qual define o estado atual do objeto;
- *State*: interface que engloba as responsabilidades de cada estado de cada contexto;
- *ConcreteState*: um ou mais estados que compõem a interface estado.

### Implementação

[Implementação](https://github.com/igorgodoy/cco-programacao-avancada-state/tree/main/example) onde o padrão State foi para construir um player de mídias que se comporta de forma diferente de acordo com o estado de reprodução.