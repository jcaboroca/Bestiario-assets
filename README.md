# Bestiario-assets

Recursos visuales descargables de Bestiario, generados localmente a partir de
los dibujos del taller. Este repositorio no contiene
código de la app ni credenciales.

## Catálogo común

La release [Bestiario · Catálogo 1](https://github.com/jcaboroca/Bestiario-assets/releases/tag/catalogo-2026-10-29-v1)
reúne 343 imágenes: las siete revisadas, incluida Lerafa, y 336 candidatas
pendientes de revisión visual, publicadas para probarlas desde la app.
Las siguientes imágenes se añadirán a esta misma release, no a una release
por sesión o lote.

Se conserva la etiqueta técnica `catalogo-2026-10-29-v1` para mantener estables
los enlaces. Cada PNG se descarga individualmente desde:

```text
https://github.com/jcaboroca/Bestiario-assets/releases/download/catalogo-2026-10-29-v1/<delantera>-<torso>-<trasera>.png
```

El adjunto [catalog.json](https://github.com/jcaboroca/Bestiario-assets/releases/download/catalogo-2026-10-29-v1/catalog.json)
registra los identificadores, partes, URLs, dimensiones, tamaños y SHA-256.
Las 336 incorporaciones incluyen `reviewStatus: candidate`; su integridad,
dimensiones y descarga se han comprobado, pero eso no valida su anatomía
ni las transiciones del pelaje. Los PNG actuales miden 512 × 384.
La app descarga solo la fotografía solicitada
al pulsar **Ver ficha**, no un ZIP ni el catálogo completo. Publicar una imagen
no crea por sí solo su ficha local en la app.

## Incorporaciones siguientes

1. Comprobar el PNG y su correspondencia con el triple que lo identifica.
2. Subirlo a **Catálogo 1** y comprobar su descarga anónima,
   dimensiones, tamaño y SHA-256.
3. Añadir su entrada a `catalog.json`, conservando las anteriores y marcándola
   como candidata mientras no se haya revisado visualmente.
4. Incorporar la ficha provisional y su URL al catálogo local de la app.
5. Revisar anatomía, pelaje y encuadre antes de considerarla aprobada y redactar
   su ficha definitiva.

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
