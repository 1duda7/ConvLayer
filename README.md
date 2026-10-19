# Atividade Prática 3

Módulo de Convolução 2D

## Grupo 
 - 05235A-Grupo-C
 - Alunos: 
    Maria Eduarda Correa Peres (24100814) | Joao Gabriel Castilho da Silva (24100817) | João Vitor Sousa Soeiro (24200513) | Priscila do Nascimento Pinto (25100709) | Marcos Vinicius Silva Brandao (26103604)	
 

## Descrição

1. Tópico:
Um módulo de Convolução se trata de um hardware dedicado o qual se baseia na passagem de um filtro (uma matriz numérica com pesos pré- definidos) sobre uma matriz de dados, visando a detecção de padrões. Para tal, os pesos são multiplicados pelos valores dos respectivos pixels e, por fim, os resultados são somados. Esse processo se repete até que o filtro perpasse toda a imagem.

2. Problema e Justificativa:
Em algoritimos de processamento digital de sinais e imagens, bem como em arquiteturas de Redes Neurais Convolucionais (CNNs), é necessário extrair características visuais em prol de analisar as relações espaciais entre os pixels vizinhos. Tal processo poderia ser realizado, de fato, utilizando a CPU de forma direta, no entanto, como processadores tradicionais executam tarefas de modo sequencial, calcular a convolução de uma imagem exigiria um grande conjunto de loopings aninhados, resultando em um elevado gasto energetico e temporal. Tal premissa justifica a necessidade de um módulo de hardware dedicado, o qual permite o explorar do paralelismo de dados, acelerando significativamente a filtragem em tempo real.

