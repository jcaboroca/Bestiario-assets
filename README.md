# Bestiario-assets

Recursos visuales descargables de Bestiario. Fotografías de criaturas ficticias,
generadas localmente y revisadas antes de publicar. Este repositorio no contiene
código de la app ni credenciales.

## Catálogo común

La release [Bestiario · Catálogo 1](https://github.com/jcaboroca/Bestiario-assets/releases/tag/catalogo-2026-10-29-v1)
reúne las siete imágenes aprobadas, incluida Lerafa. Las siguientes imágenes
aprobadas se añadirán a esta misma release, no a una release por sesión o lote.

Se conserva la etiqueta técnica `catalogo-2026-10-29-v1` para mantener estables
los enlaces. Cada PNG se descarga individualmente desde:

```text
https://github.com/jcaboroca/Bestiario-assets/releases/download/catalogo-2026-10-29-v1/<delantera>-<torso>-<trasera>.png
```

El adjunto [catalog.json](https://github.com/jcaboroca/Bestiario-assets/releases/download/catalogo-2026-10-29-v1/catalog.json)
registra los identificadores, partes, URLs, dimensiones, tamaños y SHA-256.
Los PNG actuales miden 512 × 384. La app descarga solo la fotografía solicitada
al pulsar **Ver ficha**, no un ZIP ni el catálogo completo. Publicar una imagen
no crea por sí solo su ficha local en la app.

## Incorporaciones siguientes

1. Revisar la anatomía y la correspondencia con las tres partes del dibujo.
2. Subir el PNG aprobado a **Catálogo 1** y comprobar su descarga anónima,
   dimensiones, tamaño y SHA-256.
3. Añadir su entrada a `catalog.json`, conservando las anteriores.
4. Incorporar la ficha y su URL al catálogo local de la app.

No retirar ni sobrescribir imágenes ya usadas por una versión de la app.
Una corrección debe recibir un nombre nuevo y su propia URL.

GitHub admite [hasta 1.000 adjuntos por release](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases#storage-and-bandwidth-quotas).
Con un `catalog.json`, caben 999 imágenes si no se añaden otros adjuntos.
Al alcanzar esa capacidad, continuar en **Catálogo 2** sin alterar los enlaces
del primero. Las condiciones del servicio siguen siendo aplicables.

## Compatibilidad del piloto

La release `lerafa-v1` y su imagen se conservan para las versiones ya instaladas.
El enlace actual de Lerafa pertenece a **Catálogo 1**:

```text
https://github.com/jcaboroca/Bestiario-assets/releases/download/catalogo-2026-10-29-v1/leon-jirafa-jirafa.png
```
