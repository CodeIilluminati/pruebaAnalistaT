# Prueba Técnica
## Analista de Transformación - Riesgo de Crédito


### Información general sobre la prueba:

- Puedes realizar la prueba en SQL, Python, PySpark o Jupiter Notebook.
- Si tienes conocimientos en AWS, te sugerimos que hagas uso de la capa gratuita de Aws para construir tu solución para el problema propuesto. 
- Debes entregar el código que desarrolles, si lo elaboraste en Aws comparte el enlace público de tu proyecto, en caso contrario, comparte tu código en un repositorio publico de github. 
- Si no usaste ninguna de las dos plataformas mencionadas, comparte los archivos de los códigos que realizaste, de ser posible compartelos desde github para facilitar el envio y descarga.
- El tiempo estimado para la realización de la prueba es de:  **60 a 90 minutos**

## Problema a resolver

La gerencia quiere conocer aspectos relacionados con las tasas de intermediación del sector bancario, para trabajar en su estrategia de fondeo y costo de crédito. Para esto, la gerencia nos entregó la siguiente información la cual esta conformada por las siguientes tablas:

- Detalle_tasas
- Tipo_entidad
- Entidades
- Tipo_credito
- Plazos

Los datos los encuentras en la carpeta Data: [Data](https://github.com/CodeIilluminati/pruebaAnalistaT/tree/main/Data)

La gerencia nos comentó que no ha realizado ningún analisis o exploración de la información, asi como tampoco la limpieza de los datos contenidos en las tablas.

**Con la información recibida nos han pedido generar los siguientes datos para que la gerencia pueda desarrollar sus estrategias de negocio:** 

1.	Obtener las 5 entidades financieras que tengan las mayores tasa de intermediación. Se debe mostrar en un resumen que contenga los campos: entidad financiera, tipo de entidad, subtipo de crédito, nombre de la entidad financiera, descripción del tipo de entidad, descripción del subtipo y valor de la tasa de intermediación obtenido.

2.	Obtener el promedio mensual de la tasa de intermediación para todas las entidades, clasificando la información por: tipo de entidad financiera y tipo de crédito. Adicionalmente, obtener el monto total desembolsado y la cantidad total de desembolsos.  El resumen debe contener la descripción del tipo de crédito y la descripción del tipo de entidad financiera.

3.	Con el periodo **octubre 2022** se deben generar los siguientes reportes: 

	a.	Obtener el monto total de desembolsos y promedio de la tasa y mostrar un resumen agrupando por tamaño de la empresa.
	
	b.	Obtener el monto total de desembolsos y el promedio de la tasa para persona natural para mostrar un resumen por Producto de Crédito y el promedio de la tasa para cada producto.
	
	c.	Mostrar un resumen del promedio de la tasa clasificado por el plazos.
	
	d.	Obtener la cantidad de desembolsos realizados durante el mes y valor del monto total, mostrando un resumen distribuido por sexo, tipo de garantía y mes.

4.	Generar un reporte que muestre datos consolidados de acuerdo con los siguientes campos:

		- Fecha: Consolidado YYYYMM
		- Tipo de Entidad
		- Nombre Tipo Entidad
		- Id entidad financiera
		- Entidad financiera
		- Tipo de persona
		- Tamaño de empresa
		- Código Plazo
		- Plazo crédito
		- Promedio de tasa mensual
		- Margen Máximo
		- Margen Mínimo
		- Tasa máxima
		- Tasa mínima
		- Valor desembolsos
		- Monto mínimo desembolsado
		- Monto máximo desembolsado
		- Cantidad desembolsos

**Te sugerimos realizar la exploración de los datos y realizar la limpieza donde lo consideres crítico**
