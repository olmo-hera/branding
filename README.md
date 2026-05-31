[README.md](https://github.com/user-attachments/files/28444637/README.md)
# Hera Zenter — Design System

Sistema de diseño de **Hera Zenter**, estudio boutique de bienestar en Guadalajara
(Pilates Reformer, Pilates Mat, Barre y Yoga).

Marca elegante, serena y cálida, enfocada en transformación física y mental,
comunidad y autenticidad. Organizada en torno a un método de cuatro elementos:
**Aire · Tierra · Fuego · Agua**.

## Estructura

```
hera-zenter-branding/
├── README.md              ← este archivo
├── style-guide.html       ← guía de estilo visual (ábrela en el navegador)
├── tokens/
│   ├── design-tokens.json ← tokens en formato estándar (color, tipografía, radios, espaciado)
│   └── colors.css         ← variables CSS listas para importar
├── logos/
│   ├── Hera Complete Logo     ← logotipo principal (wordmark + flor de loto)
│   └── H Logo Isotipo         ← isotipo / monograma H en óvalo
└── fonts/
    └── FONTS.md           ← guía de tipografías (Michelia + Questrial)
```

## Paleta de color

| Token        | Hex       | Uso                                  |
|--------------|-----------|--------------------------------------|
| charcoal     | `#424949` | Texto principal, fondos profundos    |
| slate        | `#788991` | Secundario, serenidad                |
| sage         | `#8D957E` | Color primario de marca              |
| terracotta   | `#9A4215` | Acento cálido, CTAs                  |
| ivory        | `#E4D6C6` | Fondos claros, respiración           |

Acentos adicionales en uso web: dorado `#B8A87A`, azul profundo `#185FA5`.

## Tipografía

- **Michelia** — títulos y display (serif elegante).
- **Questrial** — cuerpo y UI (sans ligera, gratis en Google Fonts).

## Uso rápido

```css
@import "tokens/colors.css";

.boton-primario {
  background: var(--accent);
  color: var(--bg-alt);
  font-family: var(--font-body);
  border-radius: var(--radius-pill);
}
```
