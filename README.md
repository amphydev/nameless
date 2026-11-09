# Arcana Studio — Prototipo TCG

Prototipo responsive de alta fidelidad para crear plantillas reutilizables y generar cartas de juegos tipo TCG.

## Estructura del proyecto

```text
arcana-studio/
├── index.html          # Estructura y contenido de la web
├── css/
│   └── styles.css      # Estilos y diseño responsive
├── js/
│   └── script.js       # Navegación e interacciones
└── README.md           # Instrucciones del proyecto
```

## Ejecutar localmente

Abre `index.html` en un navegador. No requiere instalación, dependencias ni servidor. Mantén las carpetas `css` y `js` junto al HTML para que se carguen correctamente.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub.
2. Sube todos los archivos y carpetas respetando la estructura anterior.
3. Entra en **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`, guarda y espera la publicación.

## Recorrido principal

- **Plantillas:** explora los diseños y crea una nueva plantilla.
- **Crear plantilla:** define identidad, componentes, variables y reglas.
- **Editor de cartas:** selecciona una plantilla, edita variables y observa la vista previa en directo.
- **Mis cartas:** consulta las cartas añadidas a la colección.

## Alcance

Es un prototipo front-end. Los datos se mantienen solo durante la sesión; no incluye autenticación, base de datos ni exportación real de imágenes.
