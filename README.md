# Contexto

El data set "datos_prestamo.csv" tiene información de una empresa que otorga créditos. Hasta ahora, hay un grupo de personas (el equipo de crédito) que estudia registro a registro y decide si prestarle o no. Las variables que tenemos son:

Fecha_registro: El día y hora que el usuario se registró en nuestro sitio web.

Fecha_contacto: El día y hora que un asesor se comunicó con el cliente. Debe ser posterior a la Fecha de registro.

Id: Identificador que se le asigna al cliente. Debe ser único.

Genero: Hombre o mujer.

Casado: Si está casado.

Dependientes: Número de personas que dependen de su ingreso.

Educacion: Graduado si tiene un título universitario o superior. No graduado en otro caso.

Trabaja_para_el: Si es dueño del negocio o empresa en donde trabaja.

Salario: Salario neto anual en pesos.

Salario_pareja: Salario neto anual de la pareja en pesos.

Credito_pedido: Crédito que solicito en miles de pesos.

Plazo_prestamo: Plazo al que pidió su crédito en días (en cuántos días va a pagar).

Hitorial_crediticio: 1 si tiene historial crediticio, 0 si no tiene.

Area_vivienda: En qué tipo de área esta situada su casa.

Estatus_prestamo: Si le otorgaron el crédito.

Asesor_asignado: El nombre del asesor que atenderá al cliente si se le otorgó el crédito.


En el último mes, han llegado muchos más registros de los que puede atender el equipo de crédito. Alguien sugirió crear un modelo para poder decidir a quien prestarle.

¿Crees que sea una buena idea? ¿ Por qué?

Si la respuesta fue sí, ¿qué tipo de probema es según los datos que tienes? (Supervisado o No Supervisado)

Haz las transformaciones que necesites a los datos y desarrolla algún modelo.

¿Cómo sabes que es un buen modelo?

Puedes usar Python o R para responder estas preguntas. Recuerda documentar adecuadamente tu código.