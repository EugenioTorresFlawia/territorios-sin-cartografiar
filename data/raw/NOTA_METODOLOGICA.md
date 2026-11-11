# Nota metodológica — `data/raw/`

## Por qué este repositorio no incluye los textos completos del corpus

La muestra de la fase analítica de este proyecto está compuesta por cinco ficciones argentinas contemporáneas:

- «La casa de Adela», Mariana Enríquez, en *Las cosas que perdimos en el fuego* (Anagrama, 2016)
- «El patio del vecino», Mariana Enríquez, en *Las cosas que perdimos en el fuego* (Anagrama, 2016)
- *El conserje y la eternidad*, Ricardo Romero (Alfaguara, 2017)
- *La habitación del presidente*, Ricardo Romero (2015, [completar editorial])
- *Territorios sin cartografiar*, Kike Ferrari ([completar edición])

Las cinco obras se encuentran bajo derechos de autor vigentes. Publicar sus textos completos en un repositorio público equivaldría a una republicación no autorizada, con independencia de la finalidad académica del proyecto. Por esa razón, `data/raw/` contiene **fragmentos de muestra**: los pasajes iniciales de cada obra, por debajo del umbral de mil palabras del derecho de cita (art. 10, Ley 11.723 de Propiedad Intelectual), con atribución completa de autoría y fuente.

## Qué documentan los fragmentos

Los fragmentos permiten auditar el **formato, la procedencia y el estado efectivo** de los archivos de texto plano resultantes del proceso de digitalización (OCR) y curaduría manual. Se publican tal como quedaron tras ese proceso, incluido el ruido residual de OCR que persiste en algunos casos (visible, por ejemplo, en el inicio de *Territorios sin cartografiar*): ese ruido es parte del dato, no un defecto a ocultar, y su incidencia sobre el análisis se discute en la memoria.

## Dónde queda la reproducibilidad

El análisis computacional (exploración en Voyant Tools, procesamiento en R) se realizó sobre los textos íntegros, que permanecen en el entorno local de trabajo. La reproducibilidad pública se preserva mediante los datos derivados no consumibles alojados en `data/clean/`: el dataset normalizado con OpenRefine, su historial completo de operaciones (`historial_openrefine_corpus_weird.json`), los metadatos del corpus y la lista de stopwords aplicada (`stopwords_UmbralWeird_v2_completa.txt`). Estos derivados permiten auditar el proceso de datificación sin exponer las obras.

La tensión entre la apertura de datos que promueve la ciencia abierta y el régimen de propiedad intelectual del corpus literario contemporáneo se discute en la memoria del trabajo (sección «Registro de límites y crítica digital»).

---

*Redacción asistida con Claude (Anthropic, 2026); selección de criterios, revisión y edición final del autor.*
