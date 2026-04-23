# BitSimples — Fila de Posts Instagram

## Como usar

1. Coloque a imagem em `pendente/` com nome sequencial: `001.jpg`, `002.jpg`...
2. Crie um arquivo `.txt` com o mesmo nome contendo a legenda: `001.txt`
3. Faça `git push` — o n8n detecta automaticamente e publica no Instagram

## Formato da legenda (`001.txt`)

```
Texto do post aqui.

Pode ter múltiplas linhas.

#bitsimples #tecnologia #cloud #ti
```

## Pastas

- `pendente/` — imagens aguardando publicação
- `publicado/` — imagens já publicadas (movidas automaticamente)
