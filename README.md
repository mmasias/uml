# UML

## ¿Por qué?

El desarrollo de software se enfrenta a un problema fundamental de comunicación que genera costos significativos y errores frecuentes. Cuando se crean diagramas y documentación técnica sin seguir estándares, surge una ambigüedad interpretativa que afecta tanto la consistencia temporal como la comprensión entre equipos.

||||
|-|-|-|
La misma persona que diseña un sistema puede interpretar de manera diferente sus propios diagramas después de semanas o meses, especialmente cuando estos se basan en garabatos informales o representaciones ad-hoc dibujadas en servilletas o pizarras. Esta inconsistencia temporal genera pérdida de conocimiento y decisiones de diseño que no pueden recuperarse fácilmente.|El problema se agrava cuando diferentes personas deben interpretar la misma documentación técnica. Presentaciones visualmente atractivas y diagramas elaborados carecen de valor si cada revisor extrae conclusiones distintas sobre la arquitectura, los requisitos o el comportamiento del sistema. Esta falta de consenso interpretativo conduce a implementaciones divergentes, defectos de integración y conflictos en los equipos de desarrollo.|La ausencia de un vocabulario común y reglas de representación estandarizadas convierte la documentación técnica en una fuente de confusión más que en una herramienta de clarificación, especialmente en proyectos complejos donde la precisión comunicativa resulta crítica para el éxito.|

## ¿Qué?

UML (Unified Modeling Language o Lenguaje Unificado de Modelado) es un lenguaje estándar de modelado diseñado para visualizar, especificar, construir y documentar artefactos de sistemas software. Se trata de una notación gráfica formal que proporciona un vocabulario común y reglas sintácticas para representar conceptos y relaciones en el desarrollo de software.

Como lenguaje formal, UML define tres componentes esenciales: 

|Léxico|Sintaxis|Semántica|
|-|-|-|
|**Símbolos estandarizados**, equivalente a las palabras correctas de un idioma.|**Reglas** que determinan cómo estos símbolos se relacionan en diagramas, similar a la gramática que estructura las oraciones.|**Significados específicos y no ambiguos** que se asignan a cada construcción válida del lenguaje.|

Este estándar fue propuesto originalmente por la metodología RUP (Rational Unified Process) y actualmente es dirigido por el Object Management Group (OMG), lo que garantiza su evolución controlada y adopción amplia en la industria del software.

## ¿Para qué?

UML resuelve directamente cada uno de los problemas de ambigüedad comunicativa identificados:

|Frente a...|UML...|
|-|-|
|**Inconsistencia temporal**|Garantiza que la misma persona pueda interpretar correctamente sus propios diagramas meses o años después, ya que los símbolos y reglas mantienen significados constantes independientemente del tiempo transcurrido. Los garabatos en servilletas se reemplazan por notaciones formales que preservan las decisiones de diseño de manera recuperable.
|**Falta de consenso interpretativo**|Elimina las interpretaciones subjetivas entre diferentes personas. Cuando un diagrama UML representa una arquitectura de sistema, todos los desarrolladores, analistas e involucrados extraen exactamente la misma información técnica, eliminando las implementaciones divergentes y conflictos de integración que surgen de documentación ambigua.
|**Ausencia de vocabulario común**|Proporciona precisamente ese vocabulario estandarizado y reglas de representación que convierten la documentación técnica en una herramienta de clarificación efectiva, especialmente crítica en proyectos complejos.

Este lenguaje permite crear propuestas claras y documentación precisa para requisitos y arquitectura de software, funcionando como los planos estandarizados en la construcción civil. UML puede describir tanto conceptos abstractos (como procesos de negocio y funciones de sistemas), como elementos concretos (incluyendo sentencias de código, esquemas de bases de datos y componentes reutilizables).

La aplicación práctica incluye la comunicación efectiva con clientes no técnicos, la coordinación entre equipos distribuidos, y la integración con herramientas de generación automática de código y documentación. UML funciona como un medio que facilita estos objetivos, estableciendo las bases para procesos de desarrollo más eficientes y productos de mayor calidad.

## ¿Cómo?

<div align=center>

|![](/images/plantUMLModels/umlDiagrams.svg)
|:-:
|[*Código fuente*](/plantUMLModels/umlDiagrams.puml)

</div>

### Estructurales

<div align=center>

|Objetos|Clases|
|-|-|
|"Foto" de entidades de la "realidad"|"Foto" (estática) de clases de entidades de la "realidad"|
|Instancias concretas en un momento específico|Tipos generales, plantillas o moldes
|Objetos con valores de atributos|Clases, interfaces, …​
|Enlaces entre objetos paralelo a las relaciones entre sus clases|Relaciones de herencia, composición, agregación, dependencia, …​
|![](/images/plantUMLModels/objectDiagram.svg)|![](/images/plantUMLModels/classDiagram.svg)
|Ejemplos|Ejemplos|

</div>