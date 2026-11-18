# Simulador do Megôhmetro Fluke 1550C/1555 — Motor 4,16 kV

Simulador interativo (Godot 4, exportado para HTML5/WebAssembly) para treinamento
de ensaio de resistência de isolação em motor trifásico de 4,16 kV, com modo instrução.

## Como jogar
Abra a página do GitHub Pages deste repositório e use o mouse:

- **Modo Instrução**: passo a passo com explicação do porquê de cada ação (ícone "?").
- **Modo Livre**: use o instrumento como no equipamento real.

## Publicar no GitHub Pages
1. Settings → Pages
2. Source: **Deploy from a branch** → Branch: `main` / pasta `/ (root)`
3. Aguarde 1–2 minutos e abra `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

O `index.html` fica na raiz e o arquivo `.nojekyll` evita que o GitHub processe os arquivos.

## Observação técnica
O motor do jogo (`index.wasm`, 43 MB) está compactado como `index.wasm.gz` (9,4 MB) para caber no
limite de 25 MB de upload pelo site do GitHub. O `index.html` descompacta o arquivo no navegador
ao carregar, então **não renomeie nem apague o `index.wasm.gz`**.
