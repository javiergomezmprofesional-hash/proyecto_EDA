# proyecto_EDA
Proyecto realizado por Francisco Javier Gómez Moya

Caracteristicas del Dataset: Es un Dataset formado por 371528 filas y 20 columnas en las que se registran las características de vehículos usados. Dichas características nos permiten analizar el mercado de vehículos de segunda mano mediante los datos de los que tiene cada vehículo registrado: marca, modelo, tipo de vehiculo, combustible, kilometraje que lleva, precio, año...

Mediante el estudio de los datos, hemos podido conococer el dominio de las marcas alemanas ya que su participación era mayoritaria en el Top 10 Marcas mas vendidas, ocupando una gran posición en el mercado. En cuanto al precio de los vehículos, la mediana situa el precio en 3500€, con un 75% de los vehículos por debajo de los 8000€. Lo que nos hace pensar que los vehículos son económicos. La mayoría de los vehículos se compraron en la década de los 2000. Sabiendo que el Dataset es de 2016, esto quiere decir que en aquella época, los vehículos tenían 10 o más años su mayoría.

Cambios realizados:

  - Hemos eliminado las filas duplicadas para que no se nos vicien los datos. Aunque en nuestro caso eran 4 filas, en otros Datasets puede darse el caso de que sean cientas o miles.
  - Hemos cambiado las columnas con fechas de tipo objeto a tipo date para poder extraer y filtrar por mes/año o rango de fechas de una manera más sencilla.
  - Hemos tratado los datos 'Nan' como 'Desconocidos' porque si hubieramos eliminado las filas en las que habia valores nulos se nos habría reducido el Dataset de manera considerable, haciendo que ya no fuera lo mas 'realista' posible y pudiendo quedar inservible.
  - Hemos pasado a minusculas toda la información para que no se vieran commo categorias diferentes información que sabemos de primera mano que quiere decir lo mismo, por ejemplo: 'Suv' y 'suv'.
  - Hemos traducido del aleman aquellas palabras que nos podrian dificultar mas la comprensión de las tablas para que nos cueste menos el tratamiento de los datos.
