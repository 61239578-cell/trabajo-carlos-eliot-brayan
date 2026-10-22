# ZUMO — versión preparada para GitHub Pages

## Publicación
1. Descomprime este ZIP en tu computadora.
2. En GitHub, crea un repositorio nuevo (por ejemplo `zumo-tienda`).
3. Abre el repositorio y pulsa **Add file → Upload files**.
4. Selecciona y arrastra TODO el contenido descomprimido, incluida la carpeta `assets` y las carpetas `tienda`, `producto`, `como-jugar`, `nosotros`, `blog`, `contacto` y `preguntas-frecuentes`. `index.html` debe quedar directamente en la raíz del repositorio, no dentro de otra carpeta.
5. Pulsa **Commit changes**.
6. Ve a **Settings → Pages**. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/(root)`, y guarda.
7. Espera a que GitHub muestre la URL publicada en esa misma sección.

## Importante
- La tienda es estática. La bolsa se conserva en el navegador y los pedidos se envían por WhatsApp; no hay base de datos ni pasarela de pago integrada.
- Revisa `assets/config.js` y confirma el número de WhatsApp antes de publicar. El archivo actual tiene un número que podría requerir verificación.
- Se incluye `.nojekyll` para que GitHub Pages publique los archivos estáticos sin procesamiento de Jekyll.
