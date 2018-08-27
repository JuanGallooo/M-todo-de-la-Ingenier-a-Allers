# Metodo-de-la-Ingenieria-Allers
Metodo de la Ingeneria
Paso 1. Identificación del problema

Se identifican de manera adecuada las necesidades que se presentan en el problema propuesto así como sus síntomas y condiciones por los que debe ser resuelto.
Identificación de sus síntomas y necesidades:

Datos recopilados desde hace 15 años que se encuentran en desorganizados y en deshuso.
Ingresos diarios de grandes cantidades de datos a la empresa (transacciones, facturación, cartera, etc.)
Se necesita lograr una evolución de beneficio a la empresa con los datos que se tiene en poder.
Se necesita informar a los clientes sobre insumos o productos que no conocen en base a la información en poder.
Se necesita poder predecir acciones posteriores, prinicipalmente dirigido a ventas ,de proveedores, clientes o productos.
 
Descripción del problema:
Una importante empresa como Allers requiere la estructuración de una solución que no solo le permita el beneficio de manejo de gran cantidad de datos y predicción de ventas en base a estos, sino también que estos sistematicen el manejo y flujo de información dentro de la empresa para que perduren los beneficios.

El sistema tiene los siguientes requerimientos:

Nombre: R1- Gestionar información de la empresa
Resumen: El requerimiento implica la utilización de información de clientes, proveedores, productos y demás información almacenada de las diferentes actividades que realiza la empresa para poder visualizarla tramitarla.  
Entradas: (Base de datos) Con la información de los diferentes proveedores, clientes, productos y demás datos que brinda la empresa.
Salidas:

Nombre: R2- Generar reportes de ventas
Resumen: El programa estará en la capacidad generar reportes de las transacciones, para realizar estadísticas de las ventas en el transcurso del tiempo. 
Entradas: (String) Nombre de cliente, (String) Código del cliente, (String) Código del producto 
Salidas: Un reporte con la información acertada con respecto a las ventas del determinado cliente o producto, utilizando gráficas y texto que permitan la mejor comprensión para el usuario.

Nombre: R3- Generar reportes de compras
Resumen: El programa estará en la capacidad generar reportes de las compras, para realizar estadísticas de las compras realizadas a los proveedores en el transcurso del tiempo.
Entradas: (String) Nombre del proveedor , (String) Código del proveedor, (String) Código del producto 
Salidas: Un reporte con la información acertada con respecto a las compras del determinado producto o proveedor, utilizando gráficas y texto que permitan la mejor comprensión para el usuario.

Nombre: R4- Generar reportes de productos
Resumen: El programa estará en la capacidad generar reportes de los productos, para realizar el seguimiento y control  de los productos que tiene la empresa. 
Entradas: (String) Nombre del producto, (String) Código del producto, (String) Precio del producto. 
Salidas: Un reporte con la información acertada con respecto a los productos utilizando gráficas y texto que permitan la mejor comprensión para el usuario.

Nombre: R5- Generar reporte con predicción de datos de ventas
Resumen: El programa estará en la capacidad generar reportes donde se predicen las posibles ventas de determinado producto o la posible compra de determinado cliente.
Entradas:(String) Nombre del producto , (String) Código del producto, (String) Precio del producto. 
Salidas: Un reporte con la información acertada con respecto a las posibles ventas de un cliente o producto utilizando gráficas y texto que permitan la mejor comprensión para el usuario.

Nombre: R6- Generar reporte con predicción de datos de compras
Resumen: El programa estará en la capacidad generar reportes donde se predicen las posibles compras de determinado producto o la posible compra ha determinado proveedor
Entradas: (String) Nombre del proveedor, (String) Código del proveedor, (String) Código del producto.
Salidas: Un reporte con la información acertada con respecto a las posibles compras ha un proveedor  o de determinado producto utilizando gráficas y texto que permitan la mejor comprensión para el usuario.

Nombre: R7- Adicionar factor de empresa
Resumen: El programa estará en la capacidad adicionar un factor de empresa, tal como un nuevo producto,  cliente o un nuevo  proveedor.
Entradas: (String) Nombre del producto, (String) Nombre del cliente, (String)Nombre del proveedor, (String) Código del producto, (String) Código del cliente, (String) Código del proveedor, (String) Precio del producto. 
Salidas: Programa actualizado con la información adicional.

Nombre: R8- Eliminar factor de empresa
Resumen: El programa estará en la capacidad adicionar un factor de empresa así sea producto,  cliente o  proveedor.
Entradas: (String) Código del producto, (String) Código del cliente, (String) Código del proveedor
Salidas: Programa actualizado con la información eliminada.

Nombre: R9- Actualizar la información
Resumen: El programa estará en la capacidad actualizar un factor de empresa así sea producto,  cliente o  proveedor
Entradas: (String) Nombre del producto, (String) Nombre del cliente, (String)Nombre del proveedor, (String) Código del producto, (String) Código del cliente, (String) Código del proveedor, (String) Precio del producto
Salidas: Programa con la información actualizada.

Paso 2. Recopilación de información
   Con el propósito de tener claros todas las definiciones involucradas se hace una búsqueda de los términos relacionados con el problema planteado. Esta búsqueda se realiza en fuentes reconocidas y confiables para reconocer que conceptos hacen parte del problema y no.
 Fuentes:
https://es.wikipedia.org
http://www.alegsa.com.ar/Dic/texto_plano.php
https://docs.microsoft.com/es-es/dotnet/framework/winforms/windows-forms-overview
 https://searchdatacenter.techtarget.com/es/definicion/Big-data
 
https://www.gestiopolis.com/que-es-data-mining/
 VodafoneOne:
En Nueva York se ha propuesto el uso de Big Data para acabar con los atascos, según la investigadora del MIT en congestión de redes urbanas, Carolina Osorio, plantea que una gran solución para esta problemática en un futuro, la cual podría llegar hasta la agenda de las personas, debido a que una persona actualmente genera millones de datos en su vida diaria y el usar estos datos ayudará a tener una mayor organización tanto en las vías como en la misma persona.
 Data mining:
Data Mining (minería de datos) es el proceso de extracción de información significativa de grandes bases de datos, información que revela inteligencia del negocio, a través de factores ocultos, tendencias y correlaciones para permitir al usuario realizar predicciones que resuelven problemas del negocio proporcionando una ventaja competitiva.
 Big Data:
Big data (en español, grandes datos o grandes volúmenes de datos) es un término evolutivo que describe cualquier cantidad voluminosa de datos estructurados, semiestructurados y no estructurados que tienen el potencial de ser extraídos para obtener información.
 Archivos de texto plano:
Son aquellos formados exclusivamente por texto sin ningún formato, es decir, que no requieren ser interpretados para leerse. También son llamados archivos de texto llano, simple o sin formato.
 
 Windows Forms:
Las características principales de la programación de Windows Forms y cómo puede usar Windows Forms para compilar smart clients que satisfagan las necesidades actuales de las empresas y usuarios.
 
 C#
C# (pronunciado si sharp en inglés) es un lenguaje de programación orientado a objetos desarrollado y estandarizado por Microsoft como parte de su plataforma .NET, que después fue aprobado como un estándar por la ECMA (ECMA-334) e ISO (ISO/IEC 23270). C# es uno de los lenguajes de programación diseñados para la infraestructura de lenguaje común
 Microsoft .NET
 .NET es un framework de Microsoft que hace un énfasis en la transparencia de redes, con independencia de plataforma de hardware y que permite un rápido desarrollo de aplicaciones.
 Visual Studio
Microsoft Visual Studio es un entorno de desarrollo integrado (IDE, por sus siglas en inglés) para sistemas operativos Windows. Soporta múltiples lenguajes de programación, tales como C++, C#, Visual Basic .NET, F#, Java, Python, Ruby y PHP, al igual que entornos de desarrollo web, como ASP.NET MVC, Django, etc., a lo cual hay que sumarle las nuevas capacidades online bajo Windows Azure en forma del editor Monaco.

  






