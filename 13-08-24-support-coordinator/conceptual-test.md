# Interview for Support Coordinator

## Introduction interview
Se realiza un dialogo libre y fluido con el candidato para conocer su experiencia y habilidades en el área de soporte técnico y coordinación de equipos de trabajo. Se busca conocer su experiencia en el manejo de proyectos de desarrollo de software, su experiencia en el manejo de productos de software y su experiencia en el manejo de equipos de trabajo.

## Conceptual test
1. Una empresa multinacional en el sector financiero está planificando la modernización de su infraestructura tecnológica. Actualmente, la empresa opera con varios sistemas legados que manejan funciones críticas como pagos, gestión de inventarios y atención al cliente. Estos sistemas comparten una base de datos común para garantizar la consistencia de los datos. Sin embargo, la empresa necesita integrar estos sistemas en un nuevo portal corporativo unificado, con la capacidad de agregar nuevas funcionalidades y servicios en el futuro. Es crucial que la solución permita una gobernanza y seguridad centralizadas, y que mantenga la consistencia de datos sin introducir una complejidad significativa. El equipo de TI debe decidir entre una arquitectura SOA y microservicios. ¿Qué arquitectura recomendarías para esta empresa, considerando la necesidad de mantener una base de datos compartida, asegurar la gobernanza y seguridad centralizadas, y permitir futuras expansiones?

2. Como Coordinador de Soporte, manejas un equipo que trabaja en la resolución de incidentes y la implementación de parches en un sistema crítico en producción. Debes asegurarte de que los cambios en el código se gestionen de manera eficiente, sin interrumpir el servicio a los usuarios. ¿Qué estrategia de gestión de ramas en Git implementarías para manejar los parches en producción y al mismo tiempo permitir el desarrollo de nuevas funcionalidades? Explica cómo organizarías las ramas y el flujo de trabajo para asegurar la estabilidad del sistema.

3. Estás liderando el equipo de soporte técnico de una empresa que utiliza Odoo como su sistema ERP principal. Un cliente reporta que las operaciones de inventario están siendo lentas y el sistema ocasionalmente arroja errores al procesar grandes volúmenes de datos. Como Coordinador de Soporte, ¿cómo abordarías la identificación y resolución del problema? ¿Qué herramientas de Odoo y procedimientos aplicarías para diagnosticar y solucionar este tipo de problemas?

4. En tu equipo de trabajo, se detecto que por acccidente un desarrollador realizó un commit erróneo en en la rama de producción de un proyecto crítico. ¿Cómo manejarías esta situación? ¿Qué medidas tomarías para revertir el commit y evitar que situaciones similares ocurran en el futuro? ¿Qué procedimientos y controles implementarías para garantizar la calidad y la integridad del código en el futuro?

5. Estas encargado del soporte de un proyecto que trabaja con con Azure DevOps y notaste en un commit reciente que un desarrollador hardcodeó una contraseña en un archivo de configuración. ¿Cuál sería tu enfoque para abordar este problema? ¿Qué medidas tomarías para garantizar la seguridad de las credenciales y evitar que se repita en el futuro?	

6. Un cliente ha reportado que Odoo no puede conectarse a la base de datos, aunque la conexión de red parece estar funcionando correctamente. Realizas un ping desde la máquina donde se ejecuta Odoo a la base de datos y obtienes una respuesta, lo que confirma que hay conectividad. Sin embargo, Odoo sigue mostrando un error de conexión a la base de datos. Como Coordinador de Soporte, ¿qué pasos seguirías para diagnosticar y resolver este problema? ¿Qué podrías revisar relacionado con los puertos TCP y la configuración de red?

## Technical test

La prueba técnica a continuación debe publicarse en un repositorio de código abierto (por ejemplo, GitHub) y enviarse a <desarrollo3@experis.co> y <paola.carrasco@experis.co> como un enlace al repositorio. Debe estar acompañado de un archivo README que explique detalladamente cómo instalar y ejecutar la aplicación. Se cuenta con una hora para completar la prueba desde el momento que ue se comparte este documento.

7. Crear un módulo básico de Odoo que gestione una lista de tareas. El módulo debe permitir:
    * Crear, editar y eliminar tareas.
    * Marcar una tarea como completada.
    * Filtrar tareas por estado (completadas, pendientes).

8. Crear un script de python que cree una tarea ejecutando SQL directamente a la tabla del módulo de Odoo creado en la pregunta anterior. El script debe aceptar los siguientes parámetros:
    * Título de la tarea.
    * Descripción de la tarea.
    * Estado de la tarea (completada o pendiente).

9. Crear un script de php que lea todas las tareas ejecutando SQL directamente a la tabla del módulo de Odoo creado en la pregunta 7 y las muestre en una tabla HTML. 

## Criteria for evaluation

### **1. Conocimiento de Arquitectura de Software:**
   - **5:** Demuestra un conocimiento profundo y aplica correctamente conceptos como SOA, microservicios, y la integración de sistemas legados.
   - **4:** Buen conocimiento, pero con pequeñas áreas de mejora en la aplicación práctica.
   - **3:** Entiende los conceptos básicos, pero tiene dificultades para aplicarlos en escenarios complejos.
   - **2:** Conocimiento limitado y respuestas incorrectas o insuficientes.
   - **1:** No comprende los conceptos o no puede aplicarlos adecuadamente.

### **2. Estrategia de Gestión de Ramas en Git:**
   - **5:** Propone y justifica una estrategia avanzada y efectiva para la gestión de ramas en proyectos críticos.
   - **4:** Proporciona una buena estrategia, con ligeras áreas de mejora.
   - **3:** Conocimiento básico de estrategias, pero falta profundidad en su aplicación.
   - **2:** Estrategia limitada, con posibles fallos en su implementación.
   - **1:** Desconoce o sugiere estrategias inadecuadas para la gestión de ramas.

### **3. Manejo y Resolución de Problemas en Odoo:**
   - **5:** Identifica y resuelve problemas de manera eficiente utilizando herramientas y procedimientos adecuados.
   - **4:** Resuelve problemas comunes, con algunas áreas de mejora en el uso de herramientas avanzadas.
   - **3:** Soluciona problemas básicos, pero con limitaciones en la aplicación de técnicas más complejas.
   - **2:** Conoce Odoo, pero tiene dificultades significativas en la resolución de problemas.
   - **1:** No tiene suficiente experiencia o capacidad para resolver problemas técnicos en Odoo.

### **4. Seguridad y Buenas Prácticas:**
   - **5:** Identifica riesgos y propone soluciones robustas, demostrando un fuerte enfoque en la seguridad y buenas prácticas.
   - **4:** Proporciona soluciones adecuadas, con margen para mejorar en la prevención.
   - **3:** Reconoce el problema y sugiere soluciones básicas, pero falta profundidad.
   - **2:** Entiende la importancia, pero carece de implementación efectiva.
   - **1:** No identifica adecuadamente los riesgos o propone soluciones ineficaces.

### **5. Conocimiento de Redes para Infraestructura Cloud:**
   - **5:** Domina conceptos avanzados de redes, como segmentación, seguridad, y conectividad en entornos cloud, y los aplica de manera efectiva.
   - **4:** Buen conocimiento, pero podría mejorar en la implementación de configuraciones avanzadas.
   - **3:** Conocimiento funcional, pero con limitaciones en escenarios más complejos.
   - **2:** Conocimiento básico, insuficiente para gestionar redes en entornos cloud.
   - **1:** Desconoce o tiene un conocimiento muy limitado sobre redes y su aplicación en la nube.

### **6. Conocimiento de Consultas SQL:**
   - **5:** Domina la ejecución de consultas SQL desde Python y PHP, utilizando prácticas seguras como el uso de consultas preparadas para prevenir inyecciones SQL. Demuestra capacidad para manejar bases de datos complejas como PostgreSQL, MySQL, etc.
   - **4:** Buen conocimiento y aplicación de consultas SQL desde Python y PHP, con comprensión de buenas prácticas, aunque con pequeñas áreas de mejora.
   - **3:** Conocimiento básico y funcional, capaz de realizar consultas simples, pero con limitaciones en la implementación de prácticas avanzadas de seguridad y eficiencia.
   - **2:** Conocimiento limitado, con dificultades en la ejecución de consultas SQL desde Python o PHP, especialmente en escenarios más complejos.
   - **1:** Desconoce o tiene un conocimiento muy básico de cómo ejecutar consultas SQL desde Python y PHP, con poca o ninguna comprensión de las buenas prácticas.

### **7. Prueba Técnica:**
   - **5:** El código es claro, bien estructurado y sigue las mejores prácticas. El repositorio está muy bien organizado, con un archivo README detallado que explica cómo instalar, configurar y ejecutar la aplicación. Los comentarios en el código son claros y útiles, facilitando la comprensión y el mantenimiento. La solución es completa y cumple con todos los requisitos planteados en la prueba.
   - **4:** El código es de buena calidad y está bien documentado. El archivo README es claro pero podría ser más detallado en algunas áreas. Los comentarios en el código son adecuados, pero podrían mejorarse en términos de profundidad o claridad.
   - **3:** El código es funcional y cumple con los requisitos, pero tiene deficiencias en la estructura o la documentación. El archivo README cubre lo básico, pero le falta detalle, y los comentarios en el código son escasos o superficiales.
   - **2:** El código cumple parcialmente con los requisitos y está mal estructurado o documentado. El archivo README es insuficiente, y los comentarios en el código son limitados o inexistentes, lo que dificulta la comprensión y el mantenimiento.
   - **1:** El código no cumple con los requisitos, está mal estructurado y carece de documentación adecuada. El archivo README está ausente o es muy básico, lo que hace difícil instalar y ejecutar la aplicación. No hay comentarios en el código, lo que lo hace difícil de entender y mantener.