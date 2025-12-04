# Burger Kitchen

Projeto para a disciplina Computação Gráfica que consiste no desenvolvimento de um jogo digital ambientado em uma lanchonete. O jogo é inteiramente implementado em WebGL puro, utilizando diferentes texturas, formas e visões da câmera.

## Narrativa

O jogador, na função de chefe, deve montar lanches conforme os pedidos que surgem individualmente no canto esquerdo da tela, apresentando graficamente os ingredientes necessários para cada preparo. Os ingredientes ficam organizados em uma bancada e o desempenho do jogador é influenciado pelo tempo e pela precisão. Há alternância de câmera, interação com um garçom responsável pela entrega dos pedidos e exibição da pontuação ao final de cinco minutos.

## Controles
### Chef
- W - Move para frente
- A - Move para esquerda
- S - Move para trás
- D - Move para direita
- Space - Anima braço direito

### Câmera
- Seta ↑ - Move câmera para cima
- Seta ↓ - Move câmera para baixo
- Seta ← - Rotaciona câmera para esquerda
- Seta → - Rotaciona câmera para direita

## Como Executar
- Opção 1: Servidor HTTP Python
```bash
# No diretório do projeto
python -m http.server 8000

# Acesse no navegador
http://localhost:8000
```

- Opção 2: Servidor HTTP Node.js
```bash
# Instale o http-server globalmente
npm install -g http-server

# Execute no diretório do projeto
http-server -p 8000

# Acesse no navegador
http://localhost:8000
```

- Opção 3: Live Server (VS Code)
1. Instale a extensão "Live Server" no VS Code
2. Clique com botão direito em index.html
3. Selecione "Open with Live Server"

## Tecnologias Utilizadas

- WebGL 1.0 - API de renderização 3D
- GLSL - Linguagem de shaders
- JavaScript ES6 - Lógica da aplicação
- gl-matrix - Matemática 3D (matrizes e vetores)
- Async.js - Carregamento assíncrono de recursos

## Autores
- Letícia Vieira França
- Pedro Henrique Bento Bocalon
- Thomas Benjamin Vieira de Oliveira
- Victor Yo Yin Oliveira
- Yago Peixoto Koki
