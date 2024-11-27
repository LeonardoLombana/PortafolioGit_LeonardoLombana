<link rel="stylesheet" type="text/css" href="styles.css">

## Acerca de mí

Profesional titulado en ingeniería de software con una reciente transición al campo del aseguramiento de calidad (QA). He adquirido competencias en análisis de requisitos, diseño y ejecución de pruebas, seguimiento de errores, pruebas de aplicaciones web y móviles.

Además, tengo conocimientos en SQL, Python, Selenium, Jira, Postman. Estas competencias me permiten realizar pruebas manuales, automatizadas y de API de manera eficiente, enfocado en crear y mantener casos de prueba detallados y alineados con las necesidades del usuario y del negocio.


---


## Proyectos

### Pruebas de regresión Urban Routers

**Descripción del Proyecto**  
En este proyecto, se realizaron pruebas de regresión de una aplicación de transporte llamada Urban Routes, Urban Routes es una aplicación que crea rutas y calcula la duración y precio del viaje para diferentes tipos de transporte.

**Objetivos**  
- Evalué los requerimientos de la aplicación según la documentación entregada.
- Cree casos de prueba basado en el requisitos analizados basado en la funcion de solicitar un vehiculo entre un punto A y un punto B.
- Ejecute los casos de prueba definiendo un estado de aprobado, no aprobado u omitido.
- Genere los informes en jira en caso de que no se aprobara un caso de prueba.

**Metodología**  
Basé mi proyecto en realizar pruebas manuales iniciando en el campo "Desde" y "Hasta" aplicando listas de comprobación que me permitieron comprobar que los campos permitian el ingreso de datos correctos, tambien que no se pudiera agregar caracteres adicionales o que no correspondieran a las especificaciones de los requerimientos.

**Conclusiones**  
- Encontré que el aplicativo aún presenta fallos en algunos de los componentes principales como por ejemplo hacer zoom, hacer clic en los encabezados, no se señala correctamente luego de colocar las coordenadas de direccion ya sea desde o hasta, todo segun lo reportado en los informe de errores.
- Observé que la plataforma apesar de los fallos de funcionamiento basico logra tener buena funcionalidad al cambio de diseño de mapa terrestre y formato 3d.
- Siendo una aplicación de primera fase o primera entrega es muy amigable e intuitiva con el usuario, con potencial a futuro.

**Lenguajes y herramientas principales**  
<div style="display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px;">
  <img src="https://img.shields.io/badge/Manual test-6A6A6A?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/Web Testing-6A6A6A?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/Regression Test-6A6A6A?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/Funtional Test-6A6A6A?style=for-the-badge&logo=matplotlib&logoColor=white" />
</div>

**Visualizaciones**

A continuación, presento detalles de los casos de prueba 

   *Lista Casos de prueba*
   <div style="display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px;">
  <img src=".//assets/img/pruebasRegresion.png"/>  
   </div>

   Esta visualización muestra cómo se crearon y los pasos a seguir para efectar los distintos casos de prueba, se les da una valoración de aprobado, no aprobado u omitido

   *Informe de errores de la aplicación*
   <div style="display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px;">
  <img src="./assets/img/informeErrores.png"/>  
   </div>

   Este gráfico pertenece al informe de errores que se presentaron durante las pruebas de comportamiento de la aplicación.
 
**Explora más detalles del proyecto en el [repositorio completo](https://github.com/LeonardoLombana/Pruebas-de-regresion-Urban-Routers).**

---

### Diseño de casos de prueba

**Descripción del Proyecto**  
Para este proyecto, se elaboraron pruebas y documentación relacionada basándote en los requisitos para la función de compartir un automóvil de Urban Routes.
El ejercicio es analizar y descomponer estos requisitos, dividir clases de equivalencia y diseñar casos de prueba. Se tuvo en cuenta la siguiente parametrización en el proyecto, descomponer y visualizar los requisitos con un mapa mental, un diagrama de flujo y una tabla, definir los objetos de prueba y diseñar las pruebas 

**Objetivos**  
- Evalué los requerimientos de la aplicación según la documentación entregada.
- Diseñe un mapa mental descoponiendo la parte grafica y logica de la funcionalidad.
- Defini las clases de equivalencia y los valores limites.
- Diseñe un diagrama de flujo para calcular el precio y la duración de un servicio.
- Cree casos de prueba basado en el requisitos analizados basado en la funcion de solicitar un vehiculo entre un punto A y un punto B.
- Ejecute los casos de prueba definiendo un estado de aprobado, no aprobado u omitido.
- Genere los informes en jira en caso de que no se aprobara un caso de prueba.

**Metodología**  
Basé mi proyecto en el mapa mental que permitio descomponer los requerimientos en su parte mas pequeña para centrar las pruebas manuales segun las especificaciones de los requerimientos.

**Conclusiones**  
- Logre simplificar la cantidad de pruebas gracias a las clases de equivalencia.
- Diseñar un mapa mental acorde a la aplicación y los requisitos permite tener un mejor y centralizado enfoque al crear los casos de prueba. 
- Crear los casos de prueba se facilita al aplicar los metodos de diseño de diagramas o mapas, al descomponerlo de esta manera permite realizar pruebas mas exahustivas.

**Lenguajes y herramientas principales**  
<div style="display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px;">
  <img src="https://img.shields.io/badge/Manual test-6A6A6A?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/Web Testing-6A6A6A?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/Regression Test-6A6A6A?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/Funtional Test-6A6A6A?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/Equivalencia-6A6A6A?style=for-the-badge&logo=matplotlib&logoColor=white" />

</div>

**Visualizaciones**

A continuación, presento detalles de los casos de prueba 

   *Lista Casos de prueba*
   <div style="display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px;">
  <img src=".//assets/img/pruebasRegresion.png"/>  
   </div>

   Esta visualización muestra cómo se crearon y los pasos a seguir para efectar los distintos casos de prueba, se les da una valoración de aprobado, no aprobado u omitido

   *Informe de errores de la aplicación*
   <div style="display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px;">
  <img src="./assets/img/informeErrores.png"/>  
   </div>

   Este gráfico pertenece al informe de errores que se presentaron durante las pruebas de comportamiento de la aplicación.
 
**Explora más detalles del proyecto en el [repositorio completo](https://github.com/LeonardoLombana/Diseno_de_pruebas).**

---

- **Envíame un correo:** [leoanrdo.lc02@hotmail.com](mailto:leonardo.lc02@hotmail.com)
- **Contáctame en LinkedIn:** [linkedin.com/in/leonardo-lombana-contento](https://www.linkedin.com/in/leonardo-lombana-contento/)
- **Explora mis proyectos en GitHub:** [github.com/LeonardoLombana](https://github.com/LeonardoLombana)
