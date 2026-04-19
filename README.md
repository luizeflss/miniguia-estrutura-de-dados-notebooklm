# Caderno Temático: Estruturas de Dados e Algoritmos

## Contexto e Objetivos
Este repositório contém um Caderno Temático focado em **Estrutura de Dados**, englobando conceitos de alocação de memória, recursão, listas e pilhas. O objetivo deste guia é consolidar o aprendizado do 3º semestre do curso de Análise e Desenvolvimento de Sistemas (ADS), facilitando a revisão de lógica algorítmica para a construção de sistemas mais eficientes no back-end. 

A Inteligência Artificial (NotebookLM) foi utilizada como ferramenta de tutoria ativa para extrair resumos, gerar analogias e testar conhecimentos técnicos.

## Curadoria de Fontes
Os seguintes materiais acadêmicos foram selecionados e carregados no NotebookLM para embasar este estudo:
1. `AS008TSN2 - PLANO DE ENSINO E APRENDIZAGEM – Estrutura de Dados.pdf` (Visão geral e ementa)
2. `AS008TSN2 - AULA01-03 - ALOCACAO DE MEMÓRIA.pdf` (Conceitos de Malloc e limpeza de memória)
3. `AS008TSN2 - AULA02 - Recursão.pdf` (Lógica recursiva e problema da Torre de Hanói)
4. `AS008TSN2 - AULA03 - Listas Array e Pilhas.pdf` (Implementações LIFO e métodos Java)

## Engenharia de Prompts e "Cicatrizes"
**Teste 1: Compreensão de Conceitos Abstratos**
* **Prompt:** *"Explique o conceito de recursão utilizando o exemplo da Torre de Hanói presente nos documentos. Use uma linguagem simples."*
* **Resposta da IA:** A IA explicou que a recursão é como resolver um problema grande dividindo-o em problemas menores idênticos, citando os passos de mover os discos para pinos auxiliares até atingir o caso base.
* **Cicatrizes (Troubleshooting):** Inicialmente, a IA deu uma resposta muito matemática. Precisei refinar o prompt pedindo para *"usar uma linguagem simples e focar no passo a passo lógico dos discos"* para obter uma resposta que ajudasse na visualização do algoritmo.

**Teste 2: Aplicação Prática**
* **Prompt:** *"Com base na Aula 03, crie um pequeno exercício prático em Java sobre Pilhas (Stacks) verificando se uma palavra é um palíndromo, e mostre a resolução passo a passo."*
* **Resposta da IA:** Gerou um código utilizando os métodos `.push()` e `.pop()` para inverter a String e comparar com a original, validando a regra LIFO (Last In, First Out).

## Miniguia de Estudo (Entrega Final)
### Resumo Estruturado
* **Alocação de Memória:** Em linguagens como C, o programador gerencia a memória manualmente (ex: `malloc`). Em linguagens de alto nível, o processo costuma ser automatizado (Garbage Collector), mas entender o consumo de memória é vital para a performance.
* **Recursividade:** Uma função que chama a si mesma até atingir uma condição de parada (caso base). Essencial para percorrer árvores e resolver problemas complexos com menos linhas de código.
* **Pilhas (Stacks):** Estrutura linear baseada no princípio LIFO (o último a entrar é o primeiro a sair). Muito usada em funções de "Desfazer" de softwares e validação de expressões.

### Glossário
* **LIFO (Last In, First Out):** Princípio onde o último elemento adicionado à estrutura é o primeiro a ser removido.
* **Caso Base:** A condição de parada dentro de uma função recursiva que impede um loop infinito (Stack Overflow).
* **Array:** Estrutura de dados estática que armazena elementos do mesmo tipo em posições de memória contíguas.
* **Ponteiro:** Uma variável que armazena o endereço de memória de outra variável.

### Prompts Reutilizáveis para Revisão
Para futuras revisões no NotebookLM ou ChatGPT, utilize os prompts abaixo:
1. *"Atue como um professor de algoritmos. Me faça 3 perguntas de múltipla escolha sobre Pilhas e Filas com base nos meus documentos. Só me dê a resposta após eu tentar responder."*
2. *"Resuma o processo de alocação dinâmica de memória em tópicos curtos e cite um exemplo prático de onde isso pode causar um vazamento de memória (memory leak)."*
3. *"Gere um mapa mental em formato de texto relacionando Listas, Arrays e Pilhas."*
