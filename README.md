# pulso.continum4.com

Sitio público de **Pulso**, la aplicación Android para anotar cada día qué
padecimientos has tenido y cómo ha estado tu ánimo. Todo vive en el dispositivo:
sin cuentas, sin servidores y sin permiso de internet.

Aquí solo está el sitio. El código de la aplicación vive en otro repositorio.

## Qué hay

| Archivo | Qué es |
|---|---|
| `index.html` | La landing: qué hace la aplicación, capturas y la promesa de privacidad. |
| `privacidad.html` | La política de privacidad. Es el documento que enlaza la ficha de Google Play, así que su texto no se toca sin motivo. |
| `assets/fonts/` | Instrument Serif y DM Sans, las mismas tipografías de la aplicación (SIL Open Font License 1.1). |
| `assets/img/` | Icono y capturas de pantalla. |

## Cómo está hecho

HTML y CSS a mano, sin JavaScript, sin dependencias y sin proceso de compilación.
Las tipografías se sirven desde este mismo dominio: el sitio no hace ni una sola
petición a terceros, que es lo coherente con lo que la página dice de la
aplicación.

Para verlo en local basta con abrir `index.html` en el navegador, o servir la
carpeta:

```bash
python -m http.server 8000
```

## Publicación

Se despliega el contenido de la carpeta tal cual, como sitio estático en
`pulso.continum4.com`. No hay paso de construcción.

## Licencia

El contenido, los textos y las imágenes son de continum4. Las tipografías
incluidas en `assets/fonts/` mantienen su propia licencia (OFL 1.1).
