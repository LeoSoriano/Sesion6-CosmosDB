## Azure Cosmos DB

![Cosmos DB](Imagenes/descarga.png)

Esta es una  base es rapida.

- **Modelo de servicio:** PaaS.
- **Que es:** Base de datos no estructurada  y NoSQL.
- **Caracteristicas:** Guardado de datos rapido.
- **Caracteristicas:** Soporta MongoDB, Cassandra, Gemlin.
- **Caracteristicas:** Puede hacer consultas con SQL.
- **Cuando usar:** Para hacer consultas e insersiones muy rapidas.

---------------------------------------------------------------------------------------------------------------------------

### Pasos para crear un Cosmos DB

1.- Abrimos el [Portal Azure](portal.azure.com)

![Portal Azure](Imagenes/PortalAzure.PNG)

2.- Buscamos Cosmos DB.

![Cosmo DB](Imagenes/AzureCosmos.PNG)

3.- Creamos un Cosmo DB.

![Creamos Cosmos](Imagenes/CreamoselCosmo.PNG)

4.- Nos dara varias opciones ara crear la base, vamos a crear la que dice **Nucleo SQL**.

![Nucleo SQL](Imagenes/NucleoSQL.PNG)

5.- Ahora,le daremos en explorador de datos abiertos.

![Explorador Datos](Imagenes/exploradordatos.PNG)

6.- Del lado izquierdo podremos observa que esta el archivo y estan los items, 
no aparece nada por que no le hemos agregado nada.

![Data](Imagenes/data.PNG)

11.- Para agregarle un item, le daremos donde dice **New item** 

12.- Y vamos escribiendo la variable y lo que contiene cada variable (osea vamos creando los items), una ves que acabemos, debemos darle en **save**.

![Creando items](Imagenes/agregandotems.PNG)

13.- Al darle save, no crea algo que es solo de uso interno de **cosmos**.

![uso Interno](Imagenes/usointernocosmos.PNG)

14.- Para crear otro, debemos darle de nuevo en **Nuevo item** y copiamos lo que ya habiamos puesto, modificando que sea el item numero 2 y agregando otro dato mas.

15.- Le damos Save y podemos ver del lado izquiero que donde dice **id** ya aparece el 1 y el 2.

![Item 2](Imagenes/Item2.PNG)

16.- Ahora nos iremos a New SQL Query (Consulta)  y le diremos que nos muestre la numero 1.

![Save Quary](Imagenes/saveQuery.PNG)

17.- Pondremos el comando **SELECT*FROM c WHERE c.id="1"**, despues le daremos a que se guarde el Query por lo que nos cobrara.
![Comando Quary](Imagenes/comandoquary.PNG)
18.- Una ves que se guarde, le daremos en **Execute Query** y podremos ver lo que pusimos en el item 1.
![Visualizacion Quary](Imagenes/vizualizacionquery.PNG)
19.- Y esto es **COSMOS DB**.

-----------------------------------------------------------------------------------------------------------------------------------
