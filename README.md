# Cristian Malón Javier · Portafolio profesional

Portafolio de una sola página de Cristian Malón Javier, Analista de Sistemas y Desarrollador .NET (Lima, Perú). Está hecho con HTML y CSS, sin frameworks, sin JavaScript y sin proceso de compilación.

Publicado en: https://cristianmalon.github.io/

## Contenido de la página

- **Portada:** nombre, titular, años de experiencia y un gráfico en HTML y CSS (procesos → requerimientos → desarrollo → datos).
- **Perfil:** resumen profesional y tres especialidades.
- **Experiencia:** cronología de cargos, de la más reciente a la más antigua.
- **Proyectos y aportes:** tres casos con contexto, aporte y las tecnologías asociadas a cada uno.
- **Tecnologías:** tecnologías destacadas y el resto agrupadas por tipo.
- **Formación:** título universitario y formación complementaria.
- **Contacto:** correo, GitHub y LinkedIn.

El contenido profesional proviene únicamente de los datos verificados del CV. La página no muestra teléfono, dirección, referencias ni el CV en PDF.

## Archivos

| Archivo | Contenido |
| --- | --- |
| `index.html` | Estructura y textos |
| `styles.css` | Diseño adaptable a celular y escritorio; los colores están como variables al inicio (`--accent` es el verde petróleo) |
| `capturas/portafolio/antes/` y `capturas/portafolio/despues/` | Página personal anterior y portafolio actual, a 1440 px y 390 px |
| `capturas/portafolio/comparativa.png` | Comparación lado a lado |
| `capturas/antes/`, `capturas/despues/` | Capturas de versiones anteriores (cambio de color de acento) |

## Accesibilidad

- Enlace «Saltar al contenido» al inicio.
- Navegación completa con teclado y foco visible en todos los enlaces.
- Contraste de texto que cumple WCAG AA.
- Avisos para lectores de pantalla en los enlaces que se abren en otra pestaña.
- Respeto por la preferencia de movimiento reducido.

## Abrir la página en tu computadora

Haz doble clic en `index.html`. No hace falta instalar nada ni levantar un servidor.

## Publicar cambios en GitHub Pages

El repositorio `cristianmalon.github.io` publica automáticamente la rama `main`. Para actualizar la página:

```bash
git add .
git commit -m "Describe el cambio"
git push
```

La página se actualiza en uno o dos minutos en https://cristianmalon.github.io/.

### Si se publica en un repositorio nuevo

1. Crea el repositorio en GitHub y sube los archivos.
2. En **Settings → Pages**, elige **Deploy from a branch**, la rama **main** y la carpeta **/ (root)**.
3. La página quedará en `https://USUARIO.github.io/NOMBRE-DEL-REPO/`.
