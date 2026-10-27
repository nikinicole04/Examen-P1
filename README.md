# Find a Dealer — Cat Lift Trucks

## Cómo correrlo

1. Abrir la carpeta en VS Code.
2. Terminal: `sass --watch sass:css`
3. Clic derecho en `index.html` → Open with Live Server.

## Estructura

```
find-a-dealer/
├── index.html
├── img/
├── css/styles.css        ← lo genera Sass
└── sass/
    ├── styles.scss       ← junta todo con @use
    ├── _variables.scss   ← colores, fuentes, breakpoint
    ├── _mixins.scss      ← mixin mv (media query)
    ├── _base.scss        ← reset
    └── components/
        ├── _button.scss
        ├── _contact-item.scss
        ├── _header.scss
        ├── _masthead.scss
        ├── _finder.scss
        ├── _dealer-card.scss
        ├── _contact-form.scss
        └── _footer.scss
```

## Requisitos de la actividad

| Requisito | Dónde |
|---|---|
| Flexbox | header, botones de la tarjeta, contact-item, parte de abajo del footer |
| Grid | cuerpo de la tarjeta (3 col), formulario (2 col), footer (4 col) |
| Media queries | `@include mv` en cada componente (1024px) |
| BEM | `bloque__elemento--modificador` en todas las clases |
| Variables | `_variables.scss` |
| Nesting | `&__`, `&--`, `&:hover` en todos los componentes |
| Componentes | carpeta `components/` |
| Mixin | `mv` en `_mixins.scss` |
