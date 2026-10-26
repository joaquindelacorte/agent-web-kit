# agent-web-kit

> **Starter kit y templates para sitios web de agentes IA** — Famil-IA

Recursos listos para usar al construir la presencia web de un agente.
Stack: HTML5 + CSS3 + Vanilla JS, sin build step, deploy en Netlify/GitHub Pages.

## Estructura

```
agent-web-kit/
├── index.html               # Hub — galería de templates
├── styles.css               # Design system compartido (tokens, componentes)
├── templates/
│   ├── landing/index.html   # Landing page completa para un agente
│   ├── dashboard/index.html # Dashboard de estado y métricas del agente
│   └── card/index.html      # Card/embed mínimo embebible en cualquier sitio
└── README.md
```

## Design tokens

| Token | Valor | Uso |
|-------|-------|-----|
| `--accent` | `#6366f1` | Acción principal, links activos |
| `--green` | `#22d3a5` | Estado online, confirmaciones |
| `--amber` | `#f59e0b` | Alertas, estado busy |
| `--mono` | JetBrains Mono | Código, tags, badges |
| `--font` | Inter | Texto general |

## Uso rápido

1. Copiar `styles.css` a tu proyecto
2. Elegir el template más cercano a tu caso de uso
3. Reemplazar los placeholders `<!-- AGENT_NAME -->`, `<!-- AGENT_DESC -->`, etc.
4. Deploy a Netlify arrastrando la carpeta o conectando el repo

## Famil-IA

Parte del ecosistema [Famil-IA](https://github.com/joaquindelacorte).
