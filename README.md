# Tarea 2 - Análisis de sentimientos usando aprendizaje supervisado

**Semestre:** 2018, primer semestre

**Entrega:** 22 de junio, 23:59.

---

En este repositorio se te entregará:

* `.gitignore`

Recuerda que deberás entregar:

* código e informe en un Jupyter Notebook

**Cuando el momento de la entrega llegue, se almacenará el último *commit* (en la branch `master`) y este se considerará la entrega final del alumno. En caso de entregar con atraso, se revisará el último *commit* y la hora en que este aparece en GitHub para revisar y aplicar el descuento.**



## :warning: Algunos alcances para quien corrija esta tarea

- En primer lugar, incluí un archivo `requirements.txt` con **todas las librerías que es necesario instalar para ejecutar el *notebook* entregado**. Este archivo puede utilizarse de la siguiente manera:

  ```shell
  pip install -r requirements.txt
  ```

- La versión de GloVe utilizada corresponde a: Common Crawl (42B tokens, 1.9M vocab, uncased, 300d vectors, 1.75 GB download): [glove.42B.300d.zip](http://nlp.stanford.edu/data/glove.42B.300d.zip)

- **Utilicé algunos recursos adicionales**. En particular, frases en inglés con su polaridad e información sobre países y gentilicios. Las fuentes de estos recursos y sus razones de uso fueron incluidas en el informe. Al ser estos de un tamaño *adecuado* para git, se incluyen junto a esta tarea.