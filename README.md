# Mi Tienda Online

Proyecto de e-commerce desarrollado con HTML y CSS. La página presenta una tienda online con su catálogo de productos, reseñas de clientes, servicios y un formulario de contacto para que los visitantes envíen consultas.

## Contenido

- **Inicio / Nosotros:** presentación de la tienda.
- **Multimedia:** imagen destacada y video con subtítulos en español.
- **Productos:** cards responsivas (Flexbox).
- **Reseñas:** opiniones de clientes (CSS Grid).
- **Servicios:** lista de lo que ofrece la tienda.
- **Contacto:** formulario (nombre, correo y mensaje) enviado con [Formspree](https://formspree.io), adaptado a distintas pantallas con Media Queries.
- **Mensajes recibidos:** tabla de ejemplo con el estado de cada consulta.

## Archivos

| Archivo | Descripción |
|---|---|
| `index.html` | Estructura semántica (`header`, `nav`, `main`, `section`, `footer`) |
| `styles.css` | Estilos, Google Fonts (Sora y Source Sans 3), Flexbox, Grid y Media Queries |
| `logo.png`, `producto-destacado.png`, `video.mp4`, `subtitulos.vtt` | Recursos multimedia (colocar en la misma carpeta) |

## Configurar el formulario

1. Crear una cuenta gratuita en [formspree.io](https://formspree.io) y un nuevo formulario.
2. Copiar su ID y reemplazar `tu-id-de-formspree` en el atributo `action` de `index.html`.

## Cómo ver el proyecto

Abrir `index.html` en el navegador.
