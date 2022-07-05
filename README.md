![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

## Propuesta - E-Commerce Public Dataset by Olist

Una empresa de E-Commerce de Argentina, esta evaluando la posibilidad de expandirse al Brasil, y para ello necesita entender como es el mercado de E-Commerce de alla.
Para ello, se consiguio data de 100k de ordenes desde el 2016 hasta el 2018, de distintos puntos de venta en BRasil.
Esto se puede ver desde distintas dimensiones, status de las ordenes, precios, pagos y perfomance de envios hacia los usuarios, productos e incluso reviws de los mismos escritos por diversos clientes.
Asi mismo, se podra encontrar un archivo de geolocalizacion con todos los codigos postales de Brasil, junto con tu lat y long

El proceso es el siguiente, una vez que el cliente realiza una compra en Olist, un vendedor es notificado para comenzar a armar la orden
Luego, cuando el cliente recibe el producto o se agoto el tiempo en el cual debia recibirlo, el cliente recibe una encuesta de satisfaccion por mail, donde puede hacer una review sobre su experiencia


Consideraciones
Una order puede tener mas de un producto.
Cada producto puede ser despachado por distintos puestos de venta.
Todos los nombres de las tiendas y empleados fueron remplazados por nombres de Games of Thrones


Data Schema
Los datos estan divididos en distintos datasets para ser comprendidos de una manera mas eficiente

La informacion clasificada fue removida

Que esperamos ¿?  algunos fuentes de inspiracion 

* Ventas:<br>
En base a la data que tenemos podemos hacer una pequeña prediccion de como podrian ser las ventas a futuro. 
El gerente del equipo de productos requiere lo siguiente para escribir el informe del cliente lo más claro posible.
Tendencia de compra de los clientes año a año, mes a mes
El equipo de marketing necesita los siguientes datos para establecer la estrategia de marketing para cada estado

* Delivery:<br>
Si queremos entrar de lleno en este mercado, el tema de logistica seria un punto importante a considerar y seria optimo tener referencias sobre las principales metricas de logistica

* Productos:<br>
En base a las reviews, podemos ver cuales son considerados los productos con mejor o peor calidad? 
Las 10 principales y las 10 últimas categorías de productos según los ingresos.
Los miembros del equipo de productos solicitan los datos de la tasa de crecimiento de la categoría del producto para ver la tendencia de qué categoría está creciendo o disminuyendo.

* Por ubicacion geografica:<br>
Agregación de ingresos por 'estado'
Las 5 principales categorías de productos por 'estado'
Número de clientes y vendedores por 'estado'

* La satisfacción del cliente:<br>
Tendencia de compra

* Pago:<br>
Agregación del método de pago del cliente

* Vendedores:<br>
El equipo de ventas y el equipo de productos están planificando la ceremonia de premiación para entregar los premios al vendedor a los 10 mejores vendedores que tienen un gran desempeño dentro de las categorías. 


## Para pensar y debatir
- ¿Debería Olist eliminar solo a los vendedores de bajo rendimiento?
- ¿Olist debería eliminar por completo los productos/categorías de peor rendimiento de su mercado?
- ¿Olist debería restringir los pares (vendedor, cliente) entre distintos Estados (provincia) para evitar retrasos?
- ¿Debería Olist adquirir nuevos vendedores, sugiriendo algunos supuestos de costos?
