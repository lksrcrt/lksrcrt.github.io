---
title: "Avances MotorSynth y obra asociada"
date: 2026-10-22 09:00:00 -0300
categories: [Ideas, Avances]
tags: [orquesta, motores, samples]
---

<!--
PLANTILLA DE ENTRADA (post) para un blog Chirpy.
- Guárdala en la carpeta _posts/ de TU repositorio (USUARIO.github.io).
- El nombre del archivo debe ser AAAA-MM-DD-titulo.md (ej: 2026-09-24-mi-idea.md).
- La fecha de arriba no puede estar en el futuro, o la entrada no aparece.
- Borra las secciones que no uses (y este comentario).
-->

### El desafío de JavaScript offline.
Ya hemos recibido los Macbooks oficiales para la orquesta. La forma en que están configurados actualmente solo otorga acceso a una red local, no a internet.
Esto plantea el desafío de que todos los instrumentos programados deben ser autocontenidos y funcionar de manera local. Personalmente estoy de acuerdo con esta medida pues no se debe depender de internet para que un instrumento funcione al momento de presentar.
He identificado dos formas de solucionar este pequeño problema. La primera y más evidente radica en que cada archivo HTML y su JavaScript sea completamente autocontenido y que no requiera de ningún archivo externo para su ejecución. Esto es lo más sencillo a corto plazo y eficiente para proyectos pequeños. No obstante, tiene ciertas limitaciones a la hora de incluir archivos de audio, dependencias externas, etc.
La segunda solución es incluir todos los archivos en una carpeta, de tal manera que al clonarse a las laptops desde github, uno pueda ejecutar el código sin mayores problemas. Esto plantea un desafío en el testeo de compatibilidad sin tener el acceso a los Macs.

### Derechos de autor para samples
Fue un desafío notorio manejar los derechos de autor al descargar samples. Muchas páginas directamente no dejan descargar los archivos, e incluso si se pudiera, no tienen licencias que permitan su uso.
Esto podría llegar a ser un problema, por ejemplo, si se descarga el audio "a la mala" y luego se utiliza audio con copyright en una obra final. Esto no es deseable.
Afortunadamente pude encontrar un sitio que posee derechos de autor sumamente libres, que nisiquiera requieren atribución directa y permite uso completo, al menos eso fue lo que entendí (no soy abogado).
El sitio en cuestión es [Pixbay](https://pixabay.com/sound-effects/search/electric%20motor/?pagi=1). 


<!-- Escribe aquí el texto de tu entrada. Puedes usar **negrita**, *cursiva* y [enlaces](https://orquestalaptopsuc.github.io/).-->

### Un video de YouTube
<!-- En YouTube: Compartir → Insertar, copia el src del iframe -->
<iframe width="100%" height="315" src="https://www.youtube.com/embed/ID_DEL_VIDEO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Samples de motores eléctricos
<!-- Sube el audio a tu carpeta en el repo de la orquesta: portafolios/Nombre_Apellido/Samples/ -->
<audio controls preload="none" style="width:100%">
  <source src="https://orquestalaptopsuc.github.io/2026/portafolios/Lukas_Recart/Samples/edr-rear-window-wiper-8189.mp3" type="audio/mpeg">
  Tu navegador no puede reproducir este audio. <a href="https://orquestalaptopsuc.github.io/2026/portafolios/Lukas_Recart/Samples/edr-rear-window-wiper-8189.mp3">Descargar</a>.
</audio>

<audio controls preload="none" style="width:100%">
  <source src="https://orquestalaptopsuc.github.io/2026/portafolios/Lukas_Recart/Samples/freesound_community-generator-synthetic-63166.mp3" type="audio/mpeg">
  Tu navegador no puede reproducir este audio. <a href="https://orquestalaptopsuc.github.io/2026/portafolios/Lukas_Recart/Samples/freesound_community-generator-synthetic-63166.mp3">Descargar</a>.
</audio>

### El estado actual de MotorSynth
<!-- Sube la imagen a assets/img/ de tu repositorio -->
![Screenshot de MotorSynth en su estado actual](/assets/MotorSynthv002_screenshot.png)
Actualmente, MotorSynth solo ejecuta el sintetizado de sonido que se describió en la entrada anterior del portafolio. Los desafíos mayores radican en permitir que se pueda ejecutar de manera local y offline en las (¿los') Macs, y mejorar la interfaz de usuario.
El método de creación musical usando este instrumento es similar al live coding. La idea es que cada persona pueda ir modificando los parámetros de los motores sobre la marcha, y que tengan unas "partituras" que expliciten qué parámnetros sugeridos pueden utilizar para cada sección de la pieza; así, quien quiera regirse a una estructura definida lo puede hacer, y por otro lado, también se puede improvisar o tener mucha flexibilidad artística.

Tengo el dilema de si seguir ampliando masivamente la funcionalidad de MotorSynth: añadir más formas de simular motores, añadir samples, síntesis de otros tipos de sonidos, etc; o si simplemente hacer instrumentos pequeños, simples y altamente especializados para cada textura sonora de la obra.
Se introduce la siguiente idea:
### ResoDance


### Conclusión:
Cierra con lo que aprendiste o lo que propones para la orquesta.
