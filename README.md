# Prueba IA Resuelve

Nos da gusto que quieras ser parte de nuestro equipo, si quieres saber un poco más sobre Resuelve Ingeniería y el equipo puedes ver [aquí](https://github.com/resuelve/nuestro-equipo).

Este ejercicio es una oportunidad para que escribas un poco de tu código más limpio que nos muestre cómo solucionas un caso básico de negocio.

* Escribe el código como si fuera a producción
* Asume que tu código pasará por un extenso proceso de _code review_
* Puedes apoyarte en cualquier referencia que desees 
* Puedes usar Python o R para escribir tu código
* Recuerda documentar adecuadamente tu código
* Asegurate de dejar instrucciones claras de cómo ejecutar tu código como si fuera a desplegarse en producción

## Problema 1

El conjunto de datos contienen ejemplos de lo que solemos utilizar para resolver problemas reales. Los DS que trabajan en equipos tienen la tarea de cuantificar la actividad de los usuarios. Cómo llevar a los equipos al éxito. Una de las áreas más grandes que nos preocupa es el compromiso que tienen los usuarios con la marca. Utilizando estos datos, tu conocimiento del negocio y potencialmente tus intereses, realiza lo siguiente

Para todos los usuarios que recibieron una notificación, ¿cuál es la diferencia en promedio en transacciones 7 días antes de que llegue la notificación vs. 7 días después de la notificación agrupado por país y grupo de edad.

Cómo ejecutar:
Ve a http://metabase.resuelve.io/ e inicie sesión con el
credenciales que te hemos enviado

1. Esto es Metabase, una herramienta de informes de código abierto. Es una alternativa gratuita a herramientas como Tableau, Looker, Microstrategy, PowerBI, etc.

2. Si te sientes confundido, puede leer su guía de inicio aquí:
https://metabase.com/docs/latest/getting-started.html.

ii. En la base de datos de `Data Warehouse`, tenemos tablas precargadas con datos inspirados en datos de la vida real que tomamos de nuestro día a día. Encontrarás el completo Descripción de los nombres y variables de la tabla al final del desafío.
También puede ver las tablas y el esquema de la base de datos en Metabase.

iii) Puedes usar la interfaz SQL de Metabase para probar SQL y generar diferentes
tipos de gráficos
iv. Crea una nueva "pregunta" y, una vez que estés satisfecho con tu consulta
y visualización, guarda tu pregunta como "ds_challenge-q1" en tu
Colección personal

v. Siéntete libre de guardar más preguntas y jugar con Metabase si
deseas, pero solo se considerará lo que se incluyas en "ds_challenge-q1"
para evaluación

## Problema 2

Con el data set en el archivo "datos_prestamo.csv" tiene información de una empresa que otorga créditos. Hasta ahora, hay un grupo de personas (el equipo de crédito) que estudia registro a registro y decide si prestarle o no. Las variables que tenemos son:

* Fecha_registro: El día y hora que el usuario se registró en nuestro sitio web.
* Fecha_contacto: El día y hora que un asesor se comunicó con el cliente. Debe ser posterior a la Fecha de registro.
* Id: Identificador que se le asigna al cliente. Debe ser único.
* Genero: Hombre o mujer.
* Casado: Si está casado.
* Dependientes: Número de personas que dependen de su ingreso.
* Educacion: Graduado si tiene un título universitario o superior. No graduado en otro caso.
* Trabaja_para_el: Si es dueño del negocio o empresa en donde trabaja.
* Salario: Salario neto anual en pesos.
* Salario_pareja: Salario neto anual de la pareja en pesos.
* Credito_pedido: Crédito que solicito en miles de pesos.
* Plazo_prestamo: Plazo al que pidió su crédito en días (en cuántos días va a pagar).
* Hitorial_crediticio: 1 si tiene historial crediticio, 0 si no tiene.
* Area_vivienda: En qué tipo de área esta situada su casa.
* Estatus_prestamo: Si le otorgaron el crédito.
* Asesor_asignado: El nombre del asesor que atenderá al cliente si se le otorgó el crédito.

En el último mes, han llegado muchos más registros de los que puede atender el equipo de crédito. Alguien sugirió crear un modelo para poder decidir a quien prestarle.

* ¿Crees que sea una buena idea? ¿ Por qué?
* Si la respuesta fue sí, ¿qué tipo de probema es según los datos que tienes? (Supervisado o No Supervisado)
* Haz las transformaciones que necesites a los datos y desarrolla algún modelo.
* ¿Cómo sabes que es un buen modelo?

## ¿Llegaste aquí por casualidad?
Si llegaste aquí por casualidad y ya tienes la prueba resuelta, ¡manda tus resultados a edsuarez@resuelve.mx para revisarla y agendar una llamada!


