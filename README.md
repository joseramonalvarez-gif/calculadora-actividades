# Calculadora de Actividades

Herramienta para poner precio a salidas, competiciones y excursiones, y para
llevar el histórico de lo que deja cada una.

**Acceso:** https://joseramonalvarez-gif.github.io/calculadora-actividades/

Nevada & Amurai · referencia `NA-BENDHORA-GUIA-2026-09-14`

## Qué hace

- Separa **costes fijos** (el autocar, el conductor, el equipo técnico) de
  **costes variables** (hotel, comidas, dorsal), que es donde se equivoca casi
  todo el mundo. Los fijos se reparten entre los que van; los variables se
  multiplican por cada persona.
- Calcula el **precio por participante** desde el margen que quieras, o al
  revés: pones el precio y te dice qué margen queda.
- Da el **mínimo de inscripciones** por debajo del cual la salida pierde dinero,
  y qué pasa si viene menos gente de la prevista.
- Admite **varios paquetes** con precios distintos (habitación individual,
  doble, con comidas o sin ellas).
- Trata el **IVA** aparte del resultado, como memorándum de tesorería.
- Genera el **paquete comercial** listo para copiar y enviar.
- Guarda un **registro de actividades** que se puede cerrar con los
  participantes reales y descargar como listado.

## Cómo se usa

Todo está explicado dentro de la propia página: hay un bloque de instrucciones
arriba y una nota bajo cada apartado diciendo qué va en cada casilla.

Lo único que conviene tener claro antes de empezar es la diferencia entre coste
fijo y coste variable. La pregunta que lo resuelve siempre: **si se cae una
persona de la lista, ¿desaparece ese coste?** Si no desaparece es fijo; si
desaparece con ella es variable.

## El registro y sus límites

Las actividades se guardan **en el navegador de cada uno**. No van a ningún
servidor. Eso tiene tres consecuencias que conviene saber:

1. **No se comparte solo.** La lista de una persona no es la de otra. Para
   trabajar sobre la misma, una exporta la copia y la otra la importa.
2. **Se pierde si se borran los datos de navegación.** Conviene descargar el
   listado de vez en cuando.
3. **Es por dispositivo.** Lo guardado en el ordenador no aparece en el móvil.

Guardar la página en marcadores para volver siempre a la misma dirección.

## Notas

- Se ve bien en móvil, pero para trabajar es más cómodo en ordenador.
- Los datos que se escriben **no salen del navegador**: no se envían a ningún
  sitio ni los ve nadie más.
- El listado se descarga en CSV separado por punto y coma, que es lo que abre
  Excel en español directamente.
