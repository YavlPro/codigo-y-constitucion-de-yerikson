# AGENTS.md

## Identidad del proyecto

Este repo contiene el sistema personal de Yerikson Varela.

La arquitectura canónica y oficial del sistema es un único archivo HTML monolítico:

- `Codigo y Constitucion de Yerikson Varela.html`

Este archivo contiene internamente dos mundos separados:

- `Código de Yerikson Varela` — sistema operativo diario
- `Constitución de Yerikson Varela` — documento canónico de identidad

La separación entre ellos es **interna y navegacional**, no estructural entre archivos.

## Arquitectura canónica

### Monolito oficial: `Codigo y Constitucion de Yerikson Varela.html`

Este archivo es el único punto de entrada del sistema. Contiene:

#### Vista Código

Función:

- sistema operativo vivo
- uso diario
- lectura diaria
- checklist diario
- preguntas de reflexión
- revisión semanal
- estadísticas y seguimiento
- accesos internos al canon

#### Vista Constitución

Función:

- documento canónico
- lectura identitaria
- núcleo constitucional
- juramento
- Mi Norte
- Psicología y Estrategia
- Filosofía Profunda
- Perfil Maestro
- Guías de Vida

## Regla de separación

La separación entre `Código` y `Constitución` sigue siendo obligatoria, pero ahora es **interna al monolito**:

- No mezclar `Código` y `Constitución` en una misma vista continua.
- No volver a convertir la Constitución en una masa expandida sin jerarquía.
- No saturar la barra maestra de navegación.
- No romper la lógica de familias/categorías de la Constitución.
- No reintroducir dos archivos separados como arquitectura activa principal.
- No crear fuentes activas duplicadas del mismo sistema.
- No reintroducir múltiples HTML activos que dupliquen el sistema bajo ninguna forma.

Los archivos `Codigo de Yerikson.html` y `Constitucion de Yerikson.html` fueron **eliminados definitivamente**. Razón: inadecuados para uso real en móvil (Android + Chrome + `content://...`) y para PC offline. El monolito resolvió mejor todas las necesidades reales. No existen en el repo, no están archivados.

## Regla de navegación

- Un solo HTML es la fuente canónica.
- El cambio entre vistas es interno.
- El sistema funciona offline/local-first en móvil y PC.
- No depende de enlaces entre archivos.
- No depende de rutas relativas cruzadas ni de servidores.
- Un solo archivo = un solo punto de entrada = cero dependencias de navegación externa.

## Regla de intervención

Las intervenciones futuras deben ser quirúrgicas.

- Primero preservar el monolito como fuente canónica.
- Luego pulir o corregir.
- No rehacer por capricho.
- No introducir rediseños grandes sin una orden explícita del usuario.
- No reintroducir la arquitectura separada sin orden explícita.
- No crear nuevos HTML que dupliquen contenido ya activo en el monolito.
- Antes de cambiar estructura, validar si el cambio realmente mejora algo esencial.

## Regla de naming

El naming canónico visible es:

- `Yerikson Varela` — identidad principal dominante
- `YAVL` — sello secundario, firma editorial discreta, marca complementaria

Formas válidas de firma:

- `Yerikson Varela · YAVL`
- `YAVL · Yerikson Varela`

`YAVL` no debe:

- ir por encima de `Yerikson Varela`
- competir con el nombre principal
- protagonizar visualmente la interfaz
- aparecer más grande que el nombre completo

## Restricciones técnicas

- HTML, CSS y JS simples.
- Sin frameworks pesados.
- Sin dependencias externas innecesarias.
- Uso offline prioritario para móvil y PC.
- Un solo scroll natural del documento, sin scrolls internos de panel.
- Sin `content://`-fragility por arquitectura de archivos cruzados.
- Evitar CDNs, librerías remotas o recursos que rompan el uso local.
- Evitar `iframe` anidados que creen doble scroll o problemas de tamaño.
- Búsqueda debe funcionar sin red y sin dependencias externas.

## Regla editorial

- No simplificar el contenido canónico por comodidad.
- No reescribir el texto con tono genérico o motivacional barato.
- No convertir el sistema en una app de hábitos genérica.
- El sistema debe sentirse personal, serio, sobrio y con identidad real.
- La voz debe conservar dignidad, claridad, peso y utilidad real.

## QA mínimo obligatorio

Antes de cerrar cualquier intervención futura, verificar:

- [ ] cambio limpio entre vista `Código` y vista `Constitución`
- [ ] sin overflow horizontal en móvil (390px)
- [ ] sin scroll interno feo dentro de paneles
- [ ] scroll natural del documento funciona bien
- [ ] naming visible correcto (`Yerikson Varela`)
- [ ] `YAVL` en posición secundaria y discreta
- [ ] búsqueda funcionando y llevando al bloque correcto
- [ ] sin errores de consola
- [ ] sigue siendo un solo HTML
- [ ] funcionamiento local/offline intacto
- [ ] la Constitución sigue organizada por familias reales
- [ ] el Código sigue funcionando como sistema operativo
- [ ] no quedan nombres viejos ni residuos de arquitectura anterior
- [ ] archivos secundarios están en `others/` y no en raíz

## Organización del repo

### Raíz (sistema canónico activo)

Solo deben existir en la raíz:

- `Codigo y Constitucion de Yerikson Varela.html` — monolito canónico
- `AGENTS.md` — documentación de arquitectura y reglas
- `ADN_VISUAL.md` — documentación de identidad visual
- `screenshots/` — capturas de QA
- `.vscode/` — configuración de entorno

**Regla:** la raíz solo contiene el sistema canónico activo y su documentación directa. Ningún archivo secundario, histórico o experimental debe vivir en la raíz.

### `others/` (archivos secundarios e históricos)

Archivos que no forman parte del sistema activo:

- `documento master.html`
- `me importa tu futuro.html`
- `musica.mp3`
- `Propuesta.html`
- `Verdad`

Estos archivos no se tocan, no se editan, no se vinculan al sistema activo.

## Estado de congelación

La arquitectura oficial es el monolito `Codigo y Constitucion de Yerikson Varela.html`.

Esta arquitectura queda **congelada** salvo orden explícita del usuario.

No reabrir debates sobre separar en dos archivos sin una razón concreta y verificable que no existía antes.
