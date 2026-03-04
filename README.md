# Samuelcessar.github.io

Treinando HTML - CSS.

## Rodando o projeto offline

O projeto agora funciona **100% offline**, usando apenas arquivos locais (HTML, CSS e imagens), sem dependências de CDN.

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

## Observação sobre framework
- O CSS principal local `style/style.css` é a base visual mínima do site.
- Como o uso de recursos do Materialize era mínimo, a dependência do framework foi removida para reduzir bloqueio de renderização e evitar falhas em ambiente sem internet.
