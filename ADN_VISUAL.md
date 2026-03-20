# ADN_VISUAL.md

## Identidad visual general

El sistema debe sentirse:

- sobrio
- elegante
- oscuro
- firme
- limpio
- respirable
- noble
- personal
- serio
- editorial

No debe sentirse:

- genérico
- juvenil
- recargado
- brillante en exceso
- motivacional de app
- dashboard corporativo frío

## Naturaleza visual del monolito

El sistema vive en un solo HTML. Dentro de él coexisten dos modos visuales distintos que pertenecen a la misma familia estética, pero cumplen funciones diferentes.

### Modo Código

Debe sentirse:

- operativo
- ágil
- medible
- consultable
- directo
- útil para uso diario
- limpio

### Modo Constitución

Debe sentirse:

- canónico
- profundo
- editorial
- jerárquico
- respirable
- solemne
- no abrumador
- bien organizado por familias reales

## Navbar maestro (barra superior)

El sistema usa una única barra superior fija que alterna entre las dos vistas internas:

- `Código`
- `Constitución`

Reglas del navbar:

- limpio y fijo
- título o firma a la izquierda
- switch de vistas claro a la derecha o centrado
- sin saturación de links
- sin links genéricos visibles como navegación
- sin branding invasivo dentro de la barra
- sin firma expandida rara dentro del navbar
- `YAVL` no debe ir como ruido dentro del navbar

## Firma visual y naming

La firma o sello visible correcto es:

- `Yerikson Varela` — identidad principal dominante
- `YAVL` — sello secundario, discreto y editorial

Formas válidas de firma:

- `Yerikson Varela · YAVL`
- `YAVL · Yerikson Varela`

Formas no válidas:

- nombre largo expandido como firma dominante
- firma partida en esquina pequeña
- sello pegado al borde sin contexto
- `YAVL` protagonista por encima del nombre completo
- cualquier forma que invierta la jerarquía visual

## Búsqueda

La búsqueda dentro del sistema debe sentirse:

- clara
- útil
- rápida
- noble
- integrada con el lenguaje visual del monolito
- no una barra genérica sin jerarquía

Características esperadas:

- case-insensitive
- tolerante a acentos
- funcional con palabras sueltas o parciales
- funcional offline, sin dependencias externas
- resultados con tipo/categoría visible
- resultado lleva al bloque exacto en la vista correcta
- resaltado o indicación visual del match encontrado
- vacío limpio cuando no hay resultados
- limpieza de búsqueda accesible

## Botones y CTA

Los botones y CTA deben verse:

- nobles
- sobrios
- consistentes
- sin subrayado
- con borde o presencia elegante
- con altura suficiente para toque táctil
- con hover discreto
- no como links web genéricos

## Cards

Las cards deben ser:

- claras
- bien espaciadas
- con aire vertical
- con jerarquía visual real
- útiles, no decorativas

En la Constitución:

- las cards maestras representan categorías reales
- no deben tener todo expandido debajo sin jerarquía
- deben separar familia de contenido detallado

## Jerarquía visual

Debe existir orden claro entre:

- título principal
- subtítulo
- descripción
- categoría maestra
- subcard
- bloque de lectura
- CTA

La lectura debe sentirse progresiva, no plana.

## Espaciado y respiración

- Debe haber aire vertical suficiente.
- Hero y navbar no deben competir.
- Cards, subtítulos y títulos no deben quedar apretados.
- La sensación general debe ser respirable, no monstruosa.
- No scroll interno clásico dentro de paneles.

## YAVL

`YAVL` es un sello editorial secundario.

- Puede ir en hero, firma o footer discreto.
- No debe competir con el nombre completo.
- No debe saturar la cabecera.
- No debe convertirse en protagonista visual.

## Móvil (390px y similares)

- No debe haber overflow horizontal.
- Las cards deben apilar bien.
- Los botones deben seguir viéndose nobles y táctiles.
- La jerarquía debe mantenerse en pantallas pequeñas.
- El cambio de vistas `Código` / `Constitución` debe ser claro y accesible.
- Ningún panel debe generar scroll interno feo o inesperado.

## Prohibiciones visuales

- no navbar saturado
- no links genéricos visibles como navegación principal
- no todo expandido a la vez en la Constitución
- no mezclar `Código` y `Constitución` en una misma vista continua
- no CTA pobres tipo anchor sin tratamiento visual
- no branding exagerado de `YAVL`
- no rediseños que rompan la familia visual interna del monolito
- no volver a una arquitectura visual de dos HTML activos
- no duplicar navegación entre archivos
- no scroll interno clásico de Windows dentro de paneles
- no mezclar `Código` y `Constitución` en una lectura continua sin separación

## Regla final

La identidad visual ya no debe improvisarse. Cualquier cambio futuro debe respetar esta familia estética y reforzar la coherencia interna dentro del monolito. El sistema es un solo archivo; la coherencia visual debe ser también única y sostenida.
