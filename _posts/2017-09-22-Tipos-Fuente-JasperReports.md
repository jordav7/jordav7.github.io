---
layout: home
title: Agregar fuentes a Jasperreports
description: Se van a añadir varias fuentes 
date: 2017-09-22 15:24:00 -0005
category: Java
tags: java, jasperreports
---
## Agregar varias fuentes a jasperreports 6.x

Muchas veces cuando se esta diseñando un reporte el usuario final o cliente nos pidan que cierta "x" o "y" tipo de letra o fuente, en jasperreports se puede añadir la fuente que uno desee, anteriormente cuando se trabajaba con ireport se podía añadir la fuente que necesitabas siempre que exista en el sistema operativo y si usabas una fuente por Ej: Arial, Calibri, etc que son Windows y ejecutabas el reporte en Linux donde saltaban los errores.

Ahora para que no tengas este tipo de inconvenientes, jasperreports no toma ningun tipo de fuente a menos que se la añadas como dependencia al proyecto en donde estas ejecutando los reportes.

### Exportando el/los tipo de fuente

Para poder usar las fuentes que deseemos una vez las descarguemos o las obtengamos de donde sea **ejemplo:** *para Times New Roman serán las siguientes (times.tff, timesbd.tff, timesbi.tff, timesi.tff) que son la letra normal, negrita, negrita cursiva y cursiva*, colocarlas dentro una carpeta y seguir los siguientes pasos dentro de jaspersoft studio:

  1. Menu Window -> Preferences -> Jaspersoft Studio -> Fonts.
  2. Presionar el botón **Add From Path** y buscar la carpeta en donde se colocó los fuentes.
  3. Para añadir más fuentes seguir el mismo procedimiento.
  4. Una vez termines selecciona todas o solo las fuentes que necesites y presionar el botón **Export** escoges la ruta donde se va a exportar y presionas OK.
   
Con esto puedes llevar tus fuentes como librería a cualquier proyecto que necesites!!!


Espero te sirva!!!
