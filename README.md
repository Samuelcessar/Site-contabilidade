# Samuelcessar.github.io

Treinando HTML - CSS.

## Rodando o projeto offline

O projeto foi ajustado para usar o CSS local (`style/style.css`) como base visual principal, reduzindo a dependência do Materialize para melhorar a resiliência em modo offline.

### Opção 1: abrir direto no navegador
1. Faça o download/clone deste repositório.
2. Abra `index.html` no navegador (duplo clique ou `Arquivo > Abrir arquivo`).
3. Navegue pelos links internos (`Links úteis` e `Contato`).

### Opção 2: servir localmente (recomendado)
Com Python instalado:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Observação sobre dependências
- O layout principal funciona com o CSS local.
- O JavaScript do Materialize foi movido para o final do `body` com `defer`, reduzindo bloqueio de renderização.
- Se desejar operação 100% offline (sem CDN), o próximo passo é versionar localmente o arquivo JS do Materialize ou removê-lo completamente caso não seja necessário.
