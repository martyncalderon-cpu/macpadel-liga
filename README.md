
# MAC PADEL — Gestor de liga (estático)
Sitio ligero para publicar jornadas, resultados y patrocinadores en GitHub Pages.

## Estructura
- `index.html` — portada
- `jornadas.html` — jornadas y resultados (edítalo pegando tus marcadores)
- `patrocinadores.html` — logos y enlaces de patrocinadores
- `contacto.html` — botón de WhatsApp y correo
- `styles.css` — estilos compartidos
- `/assets` — imágenes, logos, flyers

## Cómo publicarlo en un nuevo repositorio
1. Crea un repo nuevo en GitHub (ej. `macpadel-liga`).
2. Sube todos estos archivos (o arrastra el ZIP).
3. Ve a Settings → Pages → Source: `Deploy from a branch` → Branch: `main` y `/ (root)`.
4. Abre `https://<tuusuario>.github.io/macpadel-liga/`.

## Editar jornadas
- Abre `jornadas.html` y pega tus enfrentamientos en las tablas.
- Puedes duplicar la sección de plantilla tantas veces como necesites.

## Cambiar WhatsApp o correo
- `contacto.html`, función `openWhats()`, y links `mailto:`.
