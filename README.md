# CV - Jaime Loo

Este es un sitio web estático para mi currículum vitae, diseñado con un estilo futurista y creativo. Está alojado en GitHub Pages.

## Configuración de GitHub Pages

1. El repositorio ya está creado: `https://github.com/troll014/JaimeLoo.github.io.git`

2. Sube los archivos `index.html`, `styles.css` y `README.md` al repositorio.

   ```bash
   git init
   git add .
   git commit -m "Initial commit - Futuristic CV design"
   git remote add origin https://github.com/troll014/JaimeLoo.github.io.git
   git push -u origin main
   ```

3. Ve a la configuración del repositorio en GitHub (Settings > Pages).

4. Selecciona la rama `main` y la carpeta `/ (root)`.

5. Haz clic en "Save" para habilitar GitHub Pages.

6. El sitio estará disponible en `https://troll014.github.io/JaimeLoo.github.io/` (o tu dominio personalizado).

## Configuración de Dominio Personalizado

1. En la configuración de Pages, en "Custom domain", ingresa tu dominio (ej. `cv.jaimeloo.com`).

2. Configura los registros DNS en tu proveedor de dominio:
   - Añade un registro CNAME apuntando a `troll014.github.io`.
   - O registros A apuntando a las IPs de GitHub Pages: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153.

3. Espera a que se propague el DNS (puede tomar hasta 24 horas).

## Edición del Contenido

Edita `index.html` para actualizar tu información personal, experiencia, educación, etc.

## Tecnologías Usadas

- HTML5
- CSS3 con animaciones y efectos futuristas
- Font Awesome para íconos
- Google Fonts (Roboto)

## Vista Previa Local

Para ver el sitio localmente, abre `index.html` en tu navegador web.
