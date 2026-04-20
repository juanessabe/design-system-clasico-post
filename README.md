# Clásico Post · Design System

Sistema de diseño visual de **Clásico Post** — paleta, tipografía, componentes de UI, liquid glass, iconos de servicios, isotipo, imagotipo y patrones de animación.

Documento único y autocontenido en `CLASICO-POST_DESIGN-SYSTEM.html`, pensado para consulta humana y para que agentes de diseño (Claude Design) lo lean como fuente de verdad.

---

## Estructura

```
.
├── CLASICO-POST_DESIGN-SYSTEM.html   # Documento principal
└── design-system_assets/
    ├── iconos/          # Iconos de servicios (Edit, Color, Audio, VFX, Coordinación)
    ├── isotipo/         # Variantes de isotipo
    ├── imagotipo/       # Imagotipo (isotipo + logotipo)
    └── logotipo/        # Solo texto
```

El HTML referencia los assets por **ruta relativa**, así que la carpeta `design-system_assets/` debe mantenerse al lado del HTML.

---

## Ver online

Publicado vía GitHub Pages:

```
https://<usuario>.github.io/<repo>/CLASICO-POST_DESIGN-SYSTEM.html
```

---

## Tokens de marca

**Primarios:** Verde Clásico `#C6F135` · Negro `#111111` · Crema `#F0EDE4`

**Secundarios:** Naranja `#E85C1A` · Verde Bosque `#2A6856` · Azul Marino `#1C3F87` · Amarillo `#F0C54A` · Negro · Crema

**Tipografía:** Bebas Neue (display) · Inter (body/UI) · JetBrains Mono (código/tokens) · Dela Gothic One + Anton (impacto editorial)

---

## Cómo usarlo con Claude Design

1. Dale al agente la URL de GitHub Pages del HTML (no la de `raw.githubusercontent.com`, porque ahí las rutas relativas a imágenes se rompen).
2. Si necesita un asset suelto, enlázaselo directo:
   ```
   https://raw.githubusercontent.com/<usuario>/<repo>/main/design-system_assets/isotipo/ISOTIPO_CLASICO-POST_VERDE.svg
   ```
3. El HTML incluye especímenes para cada componente — pídele que replique o extienda cualquiera de ellos.

---

## Licencia

Uso interno Clásico Post. No redistribuir sin autorización.

Cali, Colombia · 2026
