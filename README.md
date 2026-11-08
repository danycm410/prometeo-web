# Web de PROMETEO

Web de PROMETEO, estudio de digitalización para pequeños y medianos negocios: https://prometeoproyect.com

Es una web estática: 6 páginas HTML sin dependencias, con los estilos, el código y las imágenes dentro de cada archivo.

| Archivo | Página |
| --- | --- |
| `index.html` | Inicio (portada) |
| `proyectos.html` | Proyectos |
| `proyecto-asador-marchena.html` | Caso de estudio: Asador Marchena |
| `servicios.html` | Servicios |
| `nosotros.html` | Nosotros |
| `contacto.html` | Contacto (formulario con Netlify Forms) |

## Publicar

La web está alojada en Netlify. Para publicar una versión nueva:

1. En Netlify, abre el sitio y ve a **Deploys**.
2. Arrastra la carpeta con los 6 archivos al recuadro de subida.

Los archivos tienen que estar juntos en la misma carpeta y conservar su nombre, porque las páginas se enlazan entre sí.

## Formulario de contacto

`contacto.html` usa Netlify Forms. Para recibir los mensajes:

1. En Netlify, activa **Forms → Enable form detection** antes de subir la web.
2. Activa el aviso por correo en **Forms → Form notifications** hacia prometeo.proyect.team@gmail.com.

Fuera de Netlify, el formulario muestra un enlace para enviar el mensaje por email.
