# English on Top — Landing Page

Landing page da mentoria de fluência **English on Top**, da Teacher Renata Bettarello. Site estático (HTML + CSS + JS puro, sem build step).

No ar em https://english-on-top.vercel.app (projeto `english-on-top` na Vercel, publica a cada push na `main`).

## Estrutura

```
.
├── index.html                  # página inteira (markup + estilos + script)
├── og.jpg                      # imagem de prévia ao compartilhar o link (1200×630)
└── assets/
    ├── logo.png                # logo English on Top
    ├── renata.jpg              # foto da Renata no topo
    ├── speak-go-logo.png       # logo do Speak & Go (cartão de embarque)
    └── renata-speak-go.png     # foto da Renata com a mala (cartão de embarque)
```

## Rodar localmente

```bash
python -m http.server 8765
```

Depois abra http://localhost:8765.

## Mudar de hospedagem

Basta copiar os arquivos deste repositório para o novo servidor. Se o endereço mudar, atualize `og:url` e `og:image` no `<head>` do `index.html`.
