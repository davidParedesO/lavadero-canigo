# Lavadero Canigo

Vista previa de la web de Lavadero Canigo (lavadero de coches en Cartagena).

Página estática: `index.html` + `img/`. Las fotos son de stock de Unsplash (licencia Unsplash, cargadas desde images.unsplash.com); el "antes" de las comparativas es una simulación con filtro. Se cambiarán por fotos reales del lavadero y los precios son orientativos, pendientes de confirmar con el cliente.
Lleva `noindex` mientras es una vista previa; quitarlo al publicar en el dominio definitivo.

Sin cookies (las únicas peticiones externas son las fotos de Unsplash de la vista previa): las fuentes (Unbounded y Figtree, licencia OFL) se sirven desde `fonts/`, así que no hace falta banner de cookies. Si se añade Google Analytics o un mapa de Google incrustado, habrá que poner banner.

Al pasar al dominio definitivo, actualizar las URL de `og:url` y `og:image` en `index.html`. El mapa es un iframe de OpenStreetMap.
