# Modelo numérico de interior estelar

Código en Python que construye un modelo de estructura estelar integrando las
ecuaciones fundamentales del interior de una estrella mediante un método
**predictor-corrector** con **integración mixta**.

Basado en Novotny (1973), *Introduction to Stellar Atmospheres and Interiors*.

## Características

- Integración mixta y ajuste en la frontera radiativa-convectiva.
- Optimización de radio, luminosidad y temperatura central mediante mallas con refinamiento sucesivo.
- Variación de masa y composición química, comparada con las relaciones de homología.
- Localización en el diagrama HR con datos reales (`astroquery`) y comprobación del teorema del virial.
- Modelo de evolución temporal en secuencia principal.


## Librerías

Python 3.9+, con NumPy, SciPy, pandas, Matplotlib y astroquery.


## Autor

Alexandre Rivela Jelliti — TFG, Grado en Física, Universidad Complutense de
Madrid. Tutores: Sergio Pascual Ramírez y Nicolás Cardiel López.
