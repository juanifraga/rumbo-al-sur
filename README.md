# Rumbo al Sur 2027

Propuesta de un viaje en auto con amigos, de Montevideo a la Patagonia argentina, en la segunda quincena de enero de 2027. La armamos para presentarla en una juntada y decidir juntos fecha, recorrido y presupuesto.

**Web:** [sur.juanifraga.com](https://sur.juanifraga.com)

## Qué hay en la web

- **El recorrido día por día**, con un mapa que acompaña el scroll y una van que maneja de Montevideo a Bariloche, Villa Traful, Pichi Traful y el lago Falkner, y la vuelta.
- **Los lagos** donde nos metemos al agua, dibujados a la misma escala, con fotos en el mapa.
- **El presupuesto estimado por persona** y la comparación con ir en avión.
- **La valija**: lo que hay que llevar.
- **Lo que decidimos en la juntada**: elegir entre las dos fechas posibles y una lista de pendientes para tildar.

Tiene tema claro y oscuro, y funciona en el celular y en la compu.

## Cómo está hecho

Es un sitio estático, sin framework: HTML, CSS y JavaScript, con [GSAP](https://gsap.com) para las animaciones y [Lenis](https://lenis.darkroom.engineering) para el scroll. El mapa es un SVG dibujado a mano a partir de coordenadas reales.

```
public/
├── index.html      la página, ya armada
├── assets/         app.css y app.js, compilados con esbuild
├── img/            fotos de los lugares y sus miniaturas
└── favicon…        la van, en SVG y PNG
```

## Publicación

La web se publica en [Vercel](https://vercel.com) desde la rama `main`, sirviendo la carpeta `public/`. Cada cambio entra por pull request y lo aprueba el dueño del repo; Vercel arma una vista previa de cada pull request antes de publicarlo.

## Fotos

Las fotos son de referencia, para ver a dónde vamos, y pertenecen a sus autores.
