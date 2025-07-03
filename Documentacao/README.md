# **Documentação do Projeto: Jogo "Fuga do Labirinto"**

## **1. Introdução**
### **1.1. Contexto**
"Fuga de Teseu" é um jogo 2D inspirado na mitologia grega, onde o jogador controla Teseu, que deve escapar de um labirinto enquanto é perseguido por um Minotauro. O jogo combina estratégia, velocidade e coleta de itens para aumentar o desafio e engajar os jogadores.

Este projeto foi desenvolvido com o objetivo de demonstrar habilidades em design de jogos, programação e inteligência artificial, enquanto proporciona entretenimento e promove o aprendizado de conceitos mitológicos.

### **1.2. Objetivos**
#### **Objetivo Geral**
Criar um jogo dinâmico e interativo que desafie a capacidade do jogador de planejar e reagir rapidamente.

#### **Objetivos Específicos**
1. Implementar mecânicas de fuga e perseguição utilizando algoritmos de pathfinding.
2. Desenvolver o sistema de geração de itens dinâmico.

---

## **2. Desenvolvimento do Projeto**
### **2.1. Metodologia**
- **Planejamento e Design:** Definição da temática, personagens e mecânicas principais.
- **Ferramentas Utilizadas:** Unity 2D, C#, A* Pathfinding Project.
- **Desenvolvimento Iterativo:** Cada funcionalidade foi implementada e testada antes de avançar para o próximo estágio.
- **Testes de Jogabilidade:** Usuários testaram o jogo em diferentes fases de desenvolvimento.

### **2.2. Estrutura do Jogo**
#### **Personagens**
- **Teseu:** Controlado pelo jogador, deve escapar do labirinto.
- **Minotauro:** Controlado por IA, persegue Teseu continuamente.

#### **Itens**
- **Itens Coletáveis:** Auxiliam o jogador a fugir do labirinto.
- **Saída:** Objetivo final que marca a vitória do jogador.

#### **IA e Mecânicas**
- **Algoritmo A\*** foi implementado para que o Minotauro encontre o caminho mais curto até Teseu e a Lã do Caminho mostre o menor caminho até a saída.
- **Sistema de Colisão:** Determina vitória ou derrota dependendo das condições de jogo e a coleta de itens.


## **3. Resultados e Conclusões**
### **3.1. Resultados Obtidos**
- **Jogabilidade Funcional:** Movimentação fluida, perseguição e coleta de itens funcionaram conforme planejado.

### **3.2. Conclusões**
O projeto foi bem-sucedido em criar uma experiência de jogo divertida e desafiadora, com potencial educativo. O uso de algoritmos de pathfinding demonstrou a eficácia de técnicas avançadas de programação em jogos.

---

## **4. Próximos Passos**
1. Implementar novos níveis com diferentes layouts de labirinto.
2. Adicionar mais opções de itens para o jogador.
3. Criar uma versão para dispositivos móveis para aumentar o alcance.
4. Criar um sistema de pontuação.

