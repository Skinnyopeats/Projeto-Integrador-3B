# Sistema de Recomendação de Filmes com Grafos (Filtragem Colaborativa)

## Descrição do Projeto

Este projeto implementa um sistema de recomendação de filmes baseado em filtragem colaborativa, utilizando:

- **Grafos bipartidos** (usuários ↔ filmes)
- **Projeção ponderada por Newman** para similaridade filme–filme
- **Dataset MovieLens** (ml-latest-small ou ml-100k)

A lógica central consiste em:

- Criar um grafo bipartido onde:
  - Usuários e filmes são nós  
  - Arestas representam avaliações, com peso = nota dada
- Projetar o grafo no conjunto de filmes para calcular similaridades
- Gerar recomendações com base nos filmes avaliados positivamente pelo usuário + filmes similares no grafo projetado


---

## Como Executar o Projeto

### **1. Clonar o repositório**

git clone https://github.com/Skinnyopeats/Projeto-Integrador-3B.git

cd Projeto-Integrador-3B

### **2. Criar e ativar um ambiente virtual (opcional, mas recomendado)**

python -m venv venv
venv\Scripts\activate

### **3. Instalar dependências**

pip install -r requirements.txt

### **4. Executar via Jupyter Notebook**

jupyter notebook
