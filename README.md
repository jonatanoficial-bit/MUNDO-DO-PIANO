# Mundo do Piano - Pack de PDFs pronto para GitHub

Este pacote foi organizado para ser copiado diretamente para o projeto do app.

## Como usar

1. Copie a pasta `lessons/` para a raiz do projeto.
2. Copie `data/curriculum_pdfs_ready.json` para a pasta `data/`.
3. No app, use os caminhos do campo `pdf`.
4. Ao hospedar no GitHub/Vercel, mantenha a estrutura de pastas.

## Estrutura

- `lessons/00_teoria_musical/`
- `lessons/01_iniciante/`
- `lessons/02_elementar_tecnica/`
- `lessons/03_intermediario/`
- `lessons/04_avancado/`
- `lessons/05_virtuose/`
- `data/curriculum_pdfs_ready.json`
- `data/pdf_manifest.json`

## Regra de nomes

Os arquivos foram renomeados para padrão web seguro:
- sem acentos
- sem espaços
- minúsculas
- separados por hífen

## Duplicatas removidas

Alguns PDFs estavam repetidos. Eles foram removidos do pacote final e listados em `data/pdf_manifest.json`.
