# Réplica del mapa de campo para Glide + GitHub Pages

Archivos incluidos:
- `index.html`: mapa completo en HTML/Leaflet con los puntos del CSV.
- `points.json`: datos de puntos extraídos del CSV, por si en el futuro se separan datos y HTML.

## Puntos incluidos
- H1-H18
- 2 puntos WC
- Campo de prácticas
- Casa Club

La fila `USER` del CSV no se ha usado como pin del campo, porque representa una ubicación de usuario/demo y no un punto fijo del mapa.

## URL recomendada en Glide

Cuando subas este `index.html` a un repositorio nuevo de GitHub Pages, usa una URL estable, por ejemplo:

`https://suumaprojects.github.io/mapa-campo-golf-nuevo/?lang=User_Language&v=estetico1`

En Glide:
- Template: `https://suumaprojects.github.io/mapa-campo-golf-nuevo/?lang=User_Language&v=estetico1`
- Replacement: `User_Language` → columna real del idioma del usuario
- Sin llaves: correcto `lang=User_Language`; incorrecto `lang={User_Language}`

## Demo con ubicación fija

Para una demo sin usar la posición viva de Glide:

`https://suumaprojects.github.io/mapa-campo-golf-nuevo/?loc=43.288200,-3.063052&lang=es&v=demo1`

No uses `loc=User_Location` en la pantalla real si quieres evitar parpadeo.
