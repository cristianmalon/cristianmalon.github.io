# Cristian Malon · Página personal

Página personal estática de una sola página, hecha con HTML y CSS, sin frameworks ni proceso de compilación.

## Archivos

| Archivo | Contenido |
| --- | --- |
| `index.html` | Estructura y contenido: encabezado, Sobre mí, Habilidades y Contacto |
| `styles.css` | Diseño adaptable a celular y escritorio |
| `capturas/` | Capturas de la página en escritorio y en celular |

## Abrir la página en tu computadora

1. Descarga o clona esta carpeta.
2. Haz doble clic en `index.html` y se abrirá en tu navegador.

No hace falta instalar nada ni levantar un servidor.

## Publicar en GitHub Pages

1. En GitHub, crea un repositorio nuevo (por ejemplo `cristianmalon.github.io` o `pagina-personal`).
2. Sube los archivos desde la terminal, dentro de esta carpeta:

   ```bash
   git init
   git add index.html styles.css README.md capturas
   git commit -m "Página personal"
   git branch -M main
   git remote add origin https://github.com/cristianmalon/NOMBRE-DEL-REPO.git
   git push -u origin main
   ```

   También puedes usar el botón **Add file → Upload files** en la web de GitHub.
3. En el repositorio, entra a **Settings → Pages**.
4. En **Build and deployment**, elige **Source: Deploy from a branch**, la rama **main** y la carpeta **/ (root)**. Pulsa **Save**.
5. Después de uno o dos minutos, la página estará en:
   - `https://cristianmalon.github.io/` si el repositorio se llama `cristianmalon.github.io`.
   - `https://cristianmalon.github.io/NOMBRE-DEL-REPO/` en cualquier otro caso.

## Editar el contenido

- Los textos están en `index.html`.
- Los colores están definidos como variables al inicio de `styles.css` (`--accent` es el color de acento, un terracota).
