# Análisis estadistico empresa Megaline

## Descripción
Trabajas como analista para el operador de telecomunicaciones Megaline. La empresa ofrece a sus clientes dos tarifas de prepago, Surf y Ultimate. El departamento comercial quiere saber cuál de las tarifas genera más ingresos para poder ajustar el presupuesto de publicidad.

## Objetivo
Realizar un análisis preliminar de las tarifas basado en una selección de clientes relativamente pequeña. Tendrás los datos de 500 clientes de Megaline: quiénes son los clientes, de dónde son, qué tarifa usan, así como la cantidad de llamadas que hicieron y los mensajes de texto que enviaron en 2018. Tu trabajo es analizar el comportamiento de los clientes y determinar qué tarifa de prepago genera más ingresos.

## Tecnologias
- Python
- Vs code
- pandas
- numpy
- math
- matplotlib
- scipy


## Estudio de comportamiento

### llamadas
- La media para los 2 planes son parecidas el plan surf tiene una media aproximada de 404.76 y el plan ultimate 406.19 esto indica que consumen casi los mismos minutos por llama mensualmente pero las personas del plan ultimate tienden a usar mas minutos.
- La mediana como se puede apreciar son casi iguales para el plan surf es 401.76 aproximadamente y para el plan ultimate 398.58 por lo que el promedio de personas que hablan 400 o mas es mayor a las personas que hablan menos de 400 minutos
- La varianza es mucho mayor a la media en ambos casos por lo que los datos estan mayormente dispersos de esta siendo mayor la varianza del plan ultimate por lo que se puede concluir que tiene una mayor cantidad de minutos mayor a la media

### Mensajes
- La media del plan ultimate es mayor con 38 mensajes promedio a comparacion de la del plan surf que son de 31 mensajes esto quiere decir la las personas del plan ultimate tienden a mandar una mayor cantidad de mensajes
- La mediana para el plan ultimate es de 30 y para surf de 24 al ser mayor la media que la mediana tienen una asimetria positiva en ambos planes
- La varianza es mayor a la media en ambos planes por lo que los datos estan dispersos de esta. Como se puede apreciar el grafico las personas del plan ultimate tienden a enviar mas mensajes 
- Varia muy poco la cantidad de mensajes  entre los 2 planes

### Internet
- La media como se ha estado repitiendo es mayor para el plan ultimate 
- En este caso la mediana es casi identica entre los 2 planes
- La varianza es mayor a la media en los planes, el plan surf tiene una varianza mayor lo que quiere decir que cuenta con datos mas dispersos
- Varia muy poco el consumo que tiene entre los 2 planes

### Ingreso
- La media difiere bastante en comparacion con los datos de los minutos, mensajes e internet ya que la media del plan surf es mucho mayor que la del plan ultimate esto quiere decir que las personas tienden a pagar mas en el plan surf mensualmente
- En ambos casos la media es superior a la mediana como se venia analizando con demas datos pero la diferencia entre los planes es bastante grande 
- La varianza es mucho mayor a la media en ambos casos por lo que los datos estan dispersos de esta, pero la varianza del plan surf es mucho mayor lo que indica que tiene una mayor dipersion en comparacion que el plan ultimate 
- Con esto podemos ver que las personas del plan surf pagan mas mensualmente, teniendo en consideracion las caracteristicas de cada plan y la cantidad de personas que tienen, por lo que se podria argumentar que las personas del plan surf sobrepasan ya sea los minutos, cantidad de mensajes o internet llevando a pagar por exceder estos y las personas del ultimate tienden a no pasar el limite del plan haciendo que estos solo paguen la mensualidad y no los excedentes

## Hipótesis
 ### son diferentes los ingresos promedio procedentes de los usuarios de los planes de llamada Ultimate y Surf
- La hipótesis nula se rechazo por lo cual los ingreses de los usuarios ultimate y surf son diferentes

### el ingreso promedio de los usuarios del área NY-NJ es diferente al de los usuarios de otras regiones
- La hipótesis nula se rechazo lo que quiere decir que el ingreso promedio de los usuarios de las regiones NY-NJ difieren de las demas

# Conclusiones

- Con respecto a las medias analizadas la mayor siempre fue con respecto al plan ultimate pero se tiene que considerar que las personas del plan surf eran practicamente el doble que las del ultimate 

- se puede ver que las personas del plan ultimate no usan la totalidad de los recursos que posee el plan 

- Por lo contrario las personas del plan surf tienden a sobrepasar los limites del plan 

- Al redondear las llamadas como era requerido se encontraron llamadas con duracion 0 lo cual se remplazo con duracion de 1 ya que independientemente si fue error del sistema o una llamada que se corto al momento de marcar por el usuario se tiene un registro de esta

- Ya que la primera hipotesis con respecto a la media de ingresos de los 2 planes se rechazo la hipotesis nula lo que significa que los ingresos son diferentes

- Con respecto a la segunda hipotesis de media de ingreso en el NY-NJ se rechaza la hipostisis nula lo que significa que los ingresos son diferentes para el area NY-NJ con lo demas

