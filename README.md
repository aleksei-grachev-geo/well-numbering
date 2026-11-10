# Asignación de números de pozos

Aplicación de escritorio para preparar la numeración de nuevos pozos conforme a reglas definidas, teniendo en cuenta el inventario existente, la planificación de perforación y los números reservados anteriormente.

## Necesidad operativa

La asignación de números requiere comprobar información procedente de distintas fuentes y mantener la coherencia de la numeración dentro del yacimiento. La revisión manual implica tareas repetitivas y dificulta el seguimiento de los identificadores reservados durante la planificación.

## Datos de entrada

La aplicación trabaja con archivos Excel que contienen información sobre los pozos existentes y planificados, junto con un registro local de números reservados en usos anteriores.

El usuario selecciona el yacimiento y la plataforma multipozo, indica si se trata de una plataforma nueva o existente y define la cantidad de pozos por categoría: direccionales, horizontales, multilaterales y de captación de agua.

## Funcionalidades

- Asignación de números según las reglas y los sufijos correspondientes a cada tipo de pozo.
- Continuación de las series de una plataforma existente o inicio de la numeración de una nueva.
- Comprobación de disponibilidad frente al inventario, la planificación y las reservas anteriores.
- Validación de cantidades y avisos sobre coincidencias, discrepancias entre fuentes y antigüedad de los archivos.
- Reserva persistente de los números generados para tenerlos en cuenta en futuras solicitudes.
- Copia de los resultados y exportación a Excel.
- Registro de operaciones para facilitar la revisión del proceso.

## Resultados y valor aportado

En una gran empresa, la preparación y ejecución de un programa de perforación se distribuye entre varias áreas. El instituto de ingeniería elabora las propuestas, el equipo de geología revisa y coordina las soluciones y, posteriormente, la documentación se traslada a los especialistas en perforación, construcción y evaluación económica. El número asignado durante la planificación se convierte en el identificador común del pozo en la documentación y los sistemas de información utilizados a lo largo del proyecto.

En yacimientos con más de mil pozos y una larga historia de desarrollo, la comprobación de la numeración se complica por el volumen de información acumulada por distintos equipos. En la práctica, se detectaban coincidencias de números durante la construcción de pozos cuyos proyectos ya habían sido aprobados. Esto dificultaba el registro correcto de los nuevos pozos y de su producción en la base de datos y obligaba a modificar documentos relacionados, repetir aprobaciones y conciliar información entre departamentos.

La aplicación permite comprobar la disponibilidad de los números durante la preparación de las propuestas. Integra el inventario existente, los pozos planificados y los identificadores reservados, respetando la lógica del diseño: cantidad y tipos de pozos, características de la malla de desarrollo y reglas de numeración.

El usuario obtiene una propuesta de identificadores coherente con los datos cargados y preparada para su incorporación a la documentación del proyecto. El registro persistente de reservas reduce el riesgo de volver a asignar los mismos números en trabajos posteriores.

La herramienta agiliza la preparación de la numeración y reduce el riesgo de detectar coincidencias en fases avanzadas, de tener que realizar revisiones documentales laboriosas y de generar inconsistencias entre los distintos participantes del proyecto. La fiabilidad de la comprobación depende de la integridad y actualización de las fuentes cargadas.

## Mi contribución

Identifiqué la necesidad operativa, definí las reglas de numeración y los controles, desarrollé la herramienta y elaboré un manual de usuario para facilitar su utilización por otros profesionales.

## Demostración

Las imágenes muestran dos escenarios: ampliación de una plataforma multipozo existente e inicio de la numeración de una plataforma nueva.

La demostración utiliza datos ficticios y una interfaz simplificada en español sobre el motor de asignación original. Conserva los sufijos de la nomenclatura de origen, explicados en la interfaz. El código fuente y los datos internos de la empresa no forman parte del material publicado.
