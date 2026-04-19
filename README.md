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
