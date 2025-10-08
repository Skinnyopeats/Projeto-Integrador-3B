Sistema de Recomendação de Filmes com Grafos (Filtragem Colaborativa)

-- Descrição do Projeto --

Este projeto tem como objetivo implementar um sistema de recomendação de filmes baseado em filtragem colaborativa, utilizando modelagem em grafos bipartidos e projeção ponderada (método de Newman).

O sistema usará o dataset MovieLens (ml-latest-small ou ml-100k) para construir um grafo onde:

Usuários e filmes são nós;

Arestas representam avaliações (userId → movieId, com peso = nota dada);

O grafo é projetado sobre o conjunto de filmes para calcular similaridades entre eles;

A recomendação é feita a partir dos filmes avaliados positivamente por um usuário e dos filmes mais similares no grafo projetado.

-- Objetivos -- 

Modelar relações muitos-para-muitos usando grafos bipartidos.

Aplicar o conceito de projeção de grafos ponderada (colaboração de Newman).

Implementar uma lógica de recomendação baseada em grafos.

Avaliar resultados com métricas de precisão e ranking.

Explorar extensões com PageRank personalizado e embeddings de grafos.