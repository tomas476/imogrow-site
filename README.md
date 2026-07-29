# Imogrow — Landing Page

Site da Imogrow: fundo verde pastel animado, logo IG em metal, animações de scroll.

## Como abrir

O site **tem de ser servido por HTTP** (não funciona a abrir o ficheiro
directamente, por causa dos imports de módulos).

```bash
python3 -m http.server 8000
```

Depois abre: http://localhost:8000/Imogrow.dc.html

## Ficheiros

| Ficheiro | Descrição |
|---|---|
| `Imogrow.dc.html` | O site — markup, estilos e lógica |
| `gradient-wave.jsx` | Fundo animado (ondas verdes pastel) |
| `image-slot.js` | Componente de imagens |
| `support.js` | Runtime auxiliar |
| `assets/` | Imagens e logo (`logo-metal.png`) |
